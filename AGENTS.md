# Using this repository from scripts and agents

Swiss federal law and the law of the cantons, as Markdown: one file per act and language, one commit per version, each
commit dated 00:00 Europe/Zurich on the day its version applies (2021-01-01 to 2026-10-27). Not official: the official
publication (AS/BBl for the Confederation, the canton's collection) is authoritative. 39,330 files, 22,529 acts and
drafts in the last tree of `main`.

## Find a file without opening it: `index.csv`, `index.jsonl`

One row per file of the last tree of `main` (the same rows in both files; `future` adds the versions it holds).

| column | meaning |
|---|---|
| `file` | path of the file, e.g. `ch/2/220/de.md` |
| `act` | its directory: one act, all languages (`ch/2/220`) |
| `jurisdiction` | `CH` or the canton (`ZH`, `VD`, …) |
| `kind` | `federal`, `treaty` (SR 0.…), `cantonal`, `adopted` (published in the AS, not yet in force), `referendum` (BBl, referendum period), `consultation` (draft) |
| `number` | SR number, the canton's collection number, the AS/BBl reference, or the consultation's ELI |
| `language` | `de`, `fr`, `it`, `rm`, `en` (English: a translation without legal force) |
| `title`, `short` | title and abbreviation in that language |
| `version` | the day this version applies from (consultation: opened; AS/BBl: published) |
| `valid_until` | last day of this version if the source states it (consultation: deadline; BBl: referendum deadline) |
| `adopted`, `in_force` | adoption and first entry into force of the act (AS acts in force in stages: several dates) |
| `status` | `in force`, or the status of an adopted act, referendum bill or draft |
| `text` | where the words come from: `xml` (Fedlex), `html` (the canton's structured text), `pdf` (read from the canton's or Fedlex's PDF: words checked, structure inferred) |
| `url`, `source` | the page of this version; the file it was read from (XML or PDF) |

## Layout

| path | content |
|---|---|
| `ch/<area>/<SR>/<lang>.md` | federal acts in force, area = first digit (treaties: `0.1` … `0.9`) |
| `cantons/<ct>/<first char>/<number>/<lang>.md` | cantonal acts (`cantons/zh/7/700.1/de.md`; characters outside `[A-Za-z0-9._-]` become `_`) |
| `adopted/as/<year>/<nr>/` | acts published in the AS whose entry into force is later; removed on the day they enter into force (they then appear consolidated under `ch/`) |
| `adopted/bbl/<year>/<nr>/` | bills subject to referendum, until their AS publication, the referendum deadline or a rejection at the ballot |
| `consultations/<year>/<nr>/` | federal consultation drafts from their opening; `status: Vernehmlassung abgeschlossen` once closed |
| `README.md` in each directory | human-readable lists |

Branches and tags: `main` = the law as it applied each day up to 2026-10-27; `future` = `main` plus versions already
published for a later day; `stand/YYYY-MM-01` = the law on the first of every month (the law only: README and indexes
are in the last commit).

## Inside a file

- YAML front matter (the fields above, plus per source: federal `sr`, `eli`, `source`; cantonal `canton`, `number`,
  `corrected` (a correction without formal procedure), `version_adopted` (adoption of the amendment that made this
  version), `pdf`; ZH `nachtrag`; consultations `document`, `opened`, `closes`, `affects` (SR numbers), `consultation`).
  Lists are YAML flow sequences.
- A one-line notice (`> …`) that the text is not official.
- `# Title`, then preamble, then the structure: `##`/`###` headings for parts, titles, chapters, sections;
  `#### Art. 41` (cantons: `#### § 3`, `#### Article 12`) for each article, so `ch/2/220/de.md#art-41` links to it.
- Each paragraph on one line, starting `<sup>1</sup>`; lists as `- a. …`; tables as HTML.
- Footnotes `[^<article>-<k>]`, defined right after the article that calls them (amendment notes with their AS/collection reference).
- Amending acts (`adopted/as/`): the amended element in bold (`**Art. 6 Abs. 2bis**`) followed by its new text.

## Recipes

```sh
# the law on the first of a month
git show stand/2023-07-01:ch/2/220/de.md;  git worktree add /tmp/law-2023-07 stand/2023-07-01
# the file as it applied on any day: the last commit at or before noon of that day, Zurich time (any machine time zone)
git show "$(git rev-list -1 --before='2023-06-30 12:00 +0200' main)":ch/2/220/de.md
# every version of an act, with what changed
git log --follow -p -- ch/2/220/de.md
# what changed in a canton or an area between two days
git log --since='2025-01-01 12:00 +0100' --until='2025-12-31 12:00 +0100' --name-status -- cantons/zh ch/8
# find an act by number or title words
grep -i ',220,' index.csv;  grep -i 'Raumplanung' index.csv | grep ',cantonal,'
```

Commit messages: first line `<label>: Stand <day>` (or `aufgehoben per`, `formlos berichtigt`, `veröffentlicht, tritt am …
in Kraft`, `Vernehmlassung eröffnet/abgeschlossen`); the body lists the AS references new in this version (federal) or the rows
of the canton's change table that took effect that day, then `Fedlex:`/`Quelle:` with the URL.

## Limits

- Federal versions before 2021 are not here (Fedlex publishes them as PDF/Word only); versions start on 2021-01-01.
- Geneva and Neuchâtel publish only the text in force; it enters on the day its version took effect (or 2021-01-01).
  Jura: likewise, from its PDF. Ticino and Schwyz are not included.
- `text: pdf` files: every word of the PDF is in the file (checked), but headings, paragraphs, lists and footnotes are
  inferred from the layout. When in doubt, the PDF in `source` is authoritative.
- AS acts of 2020–2022 published only as PDF are missing under `adopted/as/`; consultations: drafts only, not the
  explanatory reports.

Made by [Jonas Hertner](https://jonashertner.com) with the scripts in `jonashertner/swiss-law-graph` (`pipeline/lawgit/`).
Texts of acts: not protected by copyright (Art. 5 URG). Front matter, indexes: CC0.
