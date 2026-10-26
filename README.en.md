# Swiss law

[Deutsch](README.md) · [Français](README.fr.md) · [Italiano](README.it.md) · **English**

The law of the Confederation and the cantons as a git repository: one file per act and language, one commit per version, dated on the day it applies – since 1 January 2021.

> **Not official.** Only the publication in the Official Compilation of Federal Legislation (Art. 15 PublA, SR 170.512) and in the cantons' official collections is authoritative. English versions are translations without legal force.

|  | Acts | Versions since 2021 |
|:---|---:|---:|
| [Federal law](ch/README.md) · domestic law and treaties | 5,338 | 11,674 |
| [Cantonal law](cantons/README.md) · 24 cantons | 16,437 | 30,874 |
| [Adopted, not yet in force](adopted/README.md) · Official Compilation and bills subject to referendum | 145 | |
| [Consultations](consultations/README.md) · federal drafts, 22 open | 609 | |

As of 27 October 2026. The map that goes with it – how the acts rest on one another and how courts cite them: [Atlas of Swiss Law](https://jonashertner.github.io/swiss-law-graph/).

**Often used**: [Cst.](ch/1/101/en.md) · [CC](ch/2/210/en.md) · [OR](ch/2/220/de.md) · [SCC](ch/3/311.0/en.md) · [DEBA](ch/2/281.1/en.md) · [CPC](ch/2/272/en.md) · [CrimPC](ch/3/312.0/en.md) · [BGG](ch/1/173.110/de.md) · [APA](ch/1/172.021/en.md) · [FADP](ch/2/235.1/en.md) · [ATSG](ch/8/830.1/de.md) · [FNA](ch/1/142.20/en.md) · [EMRK](ch/0.1/0.101/de.md)

## Use

```sh
# the Code of Obligations, today
cat ch/2/220/en.md

# every version since 2021, with what changed
git log --follow -p -- ch/2/220/en.md

# the CO on 1 July 2023 (a tag for the first of every month)
git show stand/2023-07-01:ch/2/220/en.md

# on any day: the last commit up to it, noon Zurich time
git show "$(git rev-list -1 --before='2023-06-30 12:00 +0200' main)":ch/2/220/en.md

# what changed in 2025 in Zurich and in social insurance law
git log --since=2025-01-01 --until=2026-01-01 --stat -- cantons/zh ch/8

# which version wrote each line
git blame ch/2/220/en.md

# search
git grep -n "good faith" -- 'ch/*/en.md'

# every file with number, title, version and source
grep ',220,' index.csv

# with the versions that apply only later
git checkout future
```

Every article is a heading, so it can be linked: [`ch/2/220/en.md#art-41`](ch/2/220/en.md#art-41). [AGENTS.md](AGENTS.md) documents the layout and every field for programs and AI agents.

## Layout

| Path | Content |
|:---|:---|
| `ch/<1–9 \| 0.1–0.9>/<SR>/<lang>.md` | federal law in force; area = first digit of the SR number, treaties 0.1 – 0.9 |
| `cantons/<ct>/<x>/<nr>/<lang>.md` | cantonal law; folders by the first character of the number in the cantonal collection |
| `adopted/as/…`, `adopted/bbl/…` | published in the Official Compilation, not yet in force (until it enters into force); bills subject to referendum (Federal Gazette) until the Official Compilation, the deadline or a rejection |
| `consultations/<year>/<nr>/` | federal consultation drafts, from their opening; “closed” after the deadline |
| `index.csv`, `index.jsonl` | every file with number, title, version and source |

`main` applies up to today; `future` adds the versions already published for a later day; tags `stand/YYYY-MM-01` the state on the first of every month.

**A file**: front matter (YAML): number, title, short title, language, version (applies from), adoption, entry into force, source; title, preamble, the structure as headings, each article `#### Art. N`; each paragraph on one line (`<sup>1</sup> …`), so diffs and `blame` are exact; footnotes (amendments with their reference) right after their article; tables as HTML.

## Sources and checks

- Confederation: the consolidated versions on [Fedlex](https://www.fedlex.admin.ch) as XML (Akoma Ntoso), every version since 1 January 2021; the Official Compilation, the Federal Gazette and consultations from Fedlex too.
- Cantons: the classified collections – 19 on LexWork, Vaud (BLV) and Zurich (zh.ch) with every version since 1 January 2021; Geneva and Neuchâtel (SIL) and Jura (RSJU) with the text in force. Acts repealed since 1 January 2021 are included up to their repeal.
- Every file is checked: every word of the source must be in the Markdown.

| Source | Files | Words of the source | missing |
|:---|---:|---:|---:|
| Confederation (Fedlex, XML) | 37,274 | 333,497,234 | 703 |
| Cantons, LexWork (structured) | 27,846 | 68,800,929 | 343 |
| Cantons, LexWork (read from the PDF) | 5,883 | 14,192,665 | 113 |
| Vaud (BLV) | 3,452 | 5,910,511 | 22 |
| Geneva, Neuchâtel (SIL) | 1,687 | 4,374,100 | 13 |
| Zurich (read from the PDF) | 1,786 | 5,275,451 | 17 |
| Jura (read from the PDF) | 855 | 1,653,093 | 467 |
| Official Compilation and Gazette (XML) | 7,695 | 13,006,466 | 189 |
| Consultations (read from the PDF) | 3,079 | 8,641,030 | 263 |

Texts read from a PDF carry `text: pdf` in their front matter: their words are checked, their structure is inferred from the layout and not checked. When in doubt, the PDF named there is authoritative.

## Limits

- Versions before 2021 (Fedlex offers them as PDF and Word only) and acts repealed before 2021.
- Earlier versions in Geneva, Neuchâtel and Jura (the cantons publish only the text in force); the cantons of Ticino and Schwyz.
- Acts of the Official Compilation and bills subject to referendum that Fedlex offers as PDF only (1,258 and 79, nearly all 2020–2022).
- Of the consultations, the drafts only, not the explanatory reports.

## Licence and citation

Acts and their translations are not protected by copyright (Art. 5 para. 1 let. a CopA). The preparation – front matter, indexes, structure – is [CC0](LICENSE). Cite the law by its official publication; this repository by [CITATION.cff](CITATION.cff). Made with the scripts in [`jonashertner/swiss-law-graph`](https://github.com/jonashertner/swiss-law-graph) (`pipeline/lawgit/`). A project by [Jonas Hertner](https://jonashertner.com).
