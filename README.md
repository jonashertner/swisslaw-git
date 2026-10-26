# Schweizer Recht

**Deutsch** · [Français](README.fr.md) · [Italiano](README.it.md) · [English](README.en.md)

Das Recht des Bundes und der Kantone als Git-Repository: jeder Erlass eine Datei je Sprache, jede Fassung ein Commit, datiert auf den Tag, an dem sie gilt – seit dem 1. Januar 2021.

> **Nicht amtlich.** Massgebend ist die Veröffentlichung in der Amtlichen Sammlung des Bundesrechts (Art. 15 PublG, SR 170.512) und in den amtlichen Sammlungen der Kantone. Englische Fassungen sind Übersetzungen ohne Rechtskraft.

|  | Erlasse | Fassungen seit 2021 |
|:---|---:|---:|
| [Bundesrecht](ch/README.md) · Landesrecht und Staatsverträge | 5'338 | 11'674 |
| [Kantonales Recht](cantons/README.md) · 24 Kantone | 16'440 | 30'877 |
| [Beschlossen, noch nicht in Kraft](adopted/README.md) · AS und Referendumsvorlagen | 145 | |
| [Vernehmlassungen](consultations/README.md) · Entwürfe des Bundes, 22 offen | 609 | |

Stand 27. Oktober 2026. Die Karte dazu – wie die Erlasse aufeinander aufbauen und wie Gerichte sie zitieren: [Atlas des Schweizer Rechts](https://jonashertner.github.io/swiss-law-graph/).

**Häufig gebraucht**: [BV](ch/1/101/de.md) · [ZGB](ch/2/210/de.md) · [OR](ch/2/220/de.md) · [StGB](ch/3/311.0/de.md) · [SchKG](ch/2/281.1/de.md) · [ZPO](ch/2/272/de.md) · [StPO](ch/3/312.0/de.md) · [BGG](ch/1/173.110/de.md) · [VwVG](ch/1/172.021/de.md) · [DSG](ch/2/235.1/de.md) · [ATSG](ch/8/830.1/de.md) · [AIG](ch/1/142.20/de.md) · [EMRK](ch/0.1/0.101/de.md)

## Benutzen

```sh
# das Obligationenrecht, heute
cat ch/2/220/de.md

# jede Fassung seit 2021, mit den Änderungen
git log --follow -p -- ch/2/220/de.md

# das OR am 1. Juli 2023 (ein Git-Tag für jeden Monatsersten)
git show stand/2023-07-01:ch/2/220/de.md

# an einem beliebigen Tag: der letzte Commit bis dahin, Mittag Zürcher Zeit
git show "$(git rev-list -1 --before='2023-06-30 12:00 +0200' main)":ch/2/220/de.md

# was sich 2025 in Zürich und im Sozialversicherungsrecht änderte
git log --since=2025-01-01 --until=2026-01-01 --stat -- cantons/zh ch/8

# welche Fassung jede Zeile geschrieben hat
git blame ch/2/220/de.md

# suchen
git grep -n "Treu und Glauben" -- 'ch/*/de.md'

# jede Datei mit Nummer, Titel, Fassung und Quelle
grep ',220,' index.csv

# mit den Fassungen, die erst später gelten
git checkout future
```

Jeder Artikel ist eine Überschrift und damit verlinkbar: [`ch/2/220/de.md#art-41`](ch/2/220/de.md#art-41). [AGENTS.md](AGENTS.md) beschreibt Aufbau und jedes Feld für Programme und KI-Agenten.

## Aufbau

| Pfad | Inhalt |
|:---|:---|
| `ch/<1–9 \| 0.1–0.9>/<SR>/<lang>.md` | Bundesrecht in Kraft; Bereich = erste Ziffer der SR-Nummer, Staatsverträge 0.1 – 0.9 |
| `cantons/<ct>/<x>/<nr>/<lang>.md` | kantonales Recht; Ordner nach dem ersten Zeichen der Nummer der kantonalen Sammlung |
| `adopted/as/…`, `adopted/bbl/…` | in der AS veröffentlicht, noch nicht in Kraft (bis zum Inkrafttreten); Referendumsvorlagen aus dem BBl (bis zur AS, zum Ablauf der Frist oder zur Ablehnung) |
| `consultations/<year>/<nr>/` | Vernehmlassungsvorlagen des Bundes, ab Eröffnung; nach dem Ende der Frist «abgeschlossen» |
| `index.csv`, `index.jsonl` | jede Datei mit Nummer, Titel, Fassung und Quelle |

`main` gilt bis heute und wird zweimal pro Woche ergänzt, nie umgeschrieben; `future` enthält zusätzlich die bereits veröffentlichten künftigen Fassungen und wird bei jedem Lauf neu aufgebaut; Tags `stand/JJJJ-MM-01` den Stand jedes Monatsersten. Autor-Datum eines Commits = Tag, ab dem die Fassung gilt; Commit-Datum = Tag, ab dem dieses Repository sie zeigt (eine erst danach veröffentlichte Fassung folgt mit dem nächsten Lauf).

**Eine Datei**: Kopf (YAML): Nummer, Titel, Kurztitel, Sprache, Fassung (gilt ab), Beschluss, Inkrafttreten, Quelle; Titel, Ingress, Gliederung als Überschriften, jeder Artikel `#### Art. N`; jeder Absatz eine Zeile (`<sup>1</sup> …`), damit Diffs und `blame` genau sind; Fussnoten (Änderungen mit Fundstelle) gleich nach ihrem Artikel; Tabellen als HTML.

## Quellen und Prüfung

- Bund: die konsolidierten Fassungen auf [Fedlex](https://www.fedlex.admin.ch) als XML (Akoma Ntoso), jede Fassung seit 1. Januar 2021; AS, BBl und Vernehmlassungen ebenfalls von Fedlex.
- Kantone: die systematischen Sammlungen – 19 auf LexWork, die Waadt (BLV) und Zürich (zh.ch) mit jeder Fassung seit 1. Januar 2021; Genf und Neuenburg (SIL) und der Jura (RSJU) mit dem geltenden Text. Erlasse, die seit 1. Januar 2021 aufgehoben wurden, stehen bis zu ihrer Aufhebung im Repository.
- Geprüft wird jede Datei: Jedes Wort der Quelle muss im Markdown stehen.

| Quelle | Dateien | Wörter der Quelle | fehlen |
|:---|---:|---:|---:|
| Bund (Fedlex, XML) | 37'274 | 333'497'234 | 703 |
| Kantone, LexWork (strukturiert) | 27'851 | 68'803'393 | 343 |
| Kantone, LexWork (aus dem PDF gelesen) | 5'883 | 14'192'665 | 113 |
| Waadt (BLV) | 3'452 | 5'910'511 | 22 |
| Genf, Neuenburg (SIL) | 1'687 | 4'374'185 | 13 |
| Zürich (aus dem PDF gelesen) | 1'786 | 5'275'451 | 17 |
| Jura (aus dem PDF gelesen) | 855 | 1'653'093 | 467 |
| AS und BBl (XML) | 7'695 | 13'006'466 | 189 |
| Vernehmlassungen (aus dem PDF gelesen) | 3'079 | 8'641'030 | 263 |

Aus dem PDF gelesene Texte tragen `text: pdf` im Kopf: Ihre Wörter sind geprüft, ihre Gliederung ist aus dem Satzbild erschlossen und nicht geprüft. Im Zweifel gilt das PDF, das der Kopf nennt.

## Grenzen

- Fassungen vor 2021 (Fedlex führt sie nur als PDF und Word) und Erlasse, die vor 2021 aufgehoben wurden.
- Frühere Fassungen in Genf, Neuenburg und im Jura (die Kantone veröffentlichen nur den geltenden Text); die Kantone Tessin und Schwyz.
- Erlasse der AS und Referendumsvorlagen, die Fedlex nur als PDF führt (1'258 bzw. 79, fast alle 2020–2022).
- Von den Vernehmlassungen nur die Vorlagen, nicht die erläuternden Berichte.

## Lizenz und Zitieren

Erlasse und ihre Übersetzungen sind urheberrechtlich nicht geschützt (Art. 5 Abs. 1 Bst. a URG). Die Aufbereitung – Kopfdaten, Verzeichnisse, Gliederung – steht unter [CC0](LICENSE). Zitiert wird das Recht nach der amtlichen Veröffentlichung; dieses Repository nach [CITATION.cff](CITATION.cff). Erzeugt mit den Skripten in [`jonashertner/swiss-law-graph`](https://github.com/jonashertner/swiss-law-graph) (`pipeline/lawgit/`). Ein Projekt von [Jonas Hertner](https://jonashertner.com).
