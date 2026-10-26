# Diritto svizzero

[Deutsch](README.md) · [Français](README.fr.md) · **Italiano** · [English](README.en.md)

Il diritto della Confederazione e dei Cantoni come repository Git: ogni atto un file per lingua, ogni versione un commit, datato al giorno in cui si applica – dal 1° gennaio 2021.

> **Non ufficiale.** Fa stato la pubblicazione nella Raccolta ufficiale del diritto federale (art. 15 LPubb, RS 170.512) e nelle raccolte ufficiali dei Cantoni. Le versioni inglesi sono traduzioni senza forza giuridica.

|  | Atti | Versioni dal 2021 |
|:---|---:|---:|
| [Diritto federale](ch/README.md) · diritto interno e trattati | 5'338 | 11'674 |
| [Diritto cantonale](cantons/README.md) · 24 Cantoni | 16'437 | 30'874 |
| [Adottato, non ancora in vigore](adopted/README.md) · RU e progetti soggetti a referendum | 145 | |
| [Consultazioni](consultations/README.md) · progetti della Confederazione, 22 aperte | 609 | |

Stato al 27 ottobre 2026. La carta che lo accompagna – come gli atti poggiano gli uni sugli altri e come i tribunali li citano: [Atlante del diritto svizzero](https://jonashertner.github.io/swiss-law-graph/).

**Spesso consultati**: [Cost.](ch/1/101/it.md) · [CC](ch/2/210/it.md) · [CO](ch/2/220/it.md) · [CP](ch/3/311.0/it.md) · [LEF](ch/2/281.1/it.md) · [CPC](ch/2/272/it.md) · [CPP](ch/3/312.0/it.md) · [LTF](ch/1/173.110/it.md) · [PA](ch/1/172.021/it.md) · [LPD](ch/2/235.1/it.md) · [LPGA](ch/8/830.1/it.md) · [LStrI](ch/1/142.20/it.md) · [CEDU](ch/0.1/0.101/it.md)

## Usare

```sh
# il Codice delle obbligazioni, oggi
cat ch/2/220/it.md

# ogni versione dal 2021, con le modifiche
git log --follow -p -- ch/2/220/it.md

# il CO al 1° luglio 2023 (un tag per ogni primo del mese)
git show stand/2023-07-01:ch/2/220/it.md

# a un giorno qualsiasi: l’ultimo commit fino ad allora, mezzogiorno ora di Zurigo
git show "$(git rev-list -1 --before='2023-06-30 12:00 +0200' main)":ch/2/220/it.md

# che cosa è cambiato nel 2025 a Zurigo e nelle assicurazioni sociali
git log --since=2025-01-01 --until=2026-01-01 --stat -- cantons/zh ch/8

# quale versione ha scritto ogni riga
git blame ch/2/220/it.md

# cercare
git grep -n "buona fede" -- 'ch/*/it.md'

# ogni file con numero, titolo, versione e fonte
grep ',220,' index.csv

# con le versioni che si applicano solo più tardi
git checkout future
```

Ogni articolo è un titolo, quindi un link: [`ch/2/220/it.md#art-41`](ch/2/220/it.md#art-41). [AGENTS.md](AGENTS.md) descrive la struttura e ogni campo per programmi e agenti di IA.

## Struttura

| Percorso | Contenuto |
|:---|:---|
| `ch/<1–9 \| 0.1–0.9>/<SR>/<lang>.md` | diritto federale in vigore; settore = prima cifra del numero RS, trattati 0.1 – 0.9 |
| `cantons/<ct>/<x>/<nr>/<lang>.md` | diritto cantonale; cartelle secondo il primo carattere del numero della raccolta cantonale |
| `adopted/as/…`, `adopted/bbl/…` | pubblicato nella RU, non ancora in vigore (fino all’entrata in vigore); progetti soggetti a referendum (FF) fino alla RU, alla scadenza del termine o al rifiuto |
| `consultations/<year>/<nr>/` | progetti posti in consultazione dalla Confederazione, dall’apertura; «chiusa» dopo il termine |
| `index.csv`, `index.jsonl` | ogni file con numero, titolo, versione e fonte |

`main` vale fino a oggi; `future` contiene in più le versioni future già pubblicate; i tag `stand/AAAA-MM-01` lo stato al primo di ogni mese.

**Un file**: intestazione (YAML): numero, titolo, titolo breve, lingua, versione (dal), adozione, entrata in vigore, fonte; titolo, ingresso, struttura in titoli, ogni articolo `#### Art. N`; ogni capoverso su una riga (`<sup>1</sup> …`), per diff e `blame` esatti; note (modifiche con riferimento) subito dopo il loro articolo; tabelle in HTML.

## Fonti e controllo

- Confederazione: le versioni consolidate su [Fedlex](https://www.fedlex.admin.ch) in XML (Akoma Ntoso), ogni versione dal 1° gennaio 2021; RU, FF e consultazioni pure da Fedlex.
- Cantoni: le raccolte sistematiche – 19 su LexWork, Vaud (BLV) e Zurigo (zh.ch) con ogni versione dal 1° gennaio 2021; Ginevra e Neuchâtel (SIL) e il Giura (RSJU) con il testo in vigore. Gli atti abrogati dal 1° gennaio 2021 vi figurano fino alla loro abrogazione.
- Ogni file è controllato: ogni parola della fonte deve figurare nel Markdown.

| Fonte | File | Parole della fonte | mancano |
|:---|---:|---:|---:|
| Confederazione (Fedlex, XML) | 37'274 | 333'497'234 | 703 |
| Cantoni, LexWork (strutturato) | 27'846 | 68'800'929 | 343 |
| Cantoni, LexWork (letto dal PDF) | 5'883 | 14'192'665 | 113 |
| Vaud (BLV) | 3'452 | 5'910'511 | 22 |
| Ginevra, Neuchâtel (SIL) | 1'687 | 4'374'100 | 13 |
| Zurigo (letto dal PDF) | 1'786 | 5'275'451 | 17 |
| Giura (letto dal PDF) | 855 | 1'653'093 | 467 |
| RU e FF (XML) | 7'695 | 13'006'466 | 189 |
| Consultazioni (letto dal PDF) | 3'079 | 8'641'030 | 263 |

I testi letti dal PDF recano `text: pdf` nell’intestazione: le loro parole sono controllate, la struttura è dedotta dall’impaginazione e non controllata. In caso di dubbio fa stato il PDF indicato.

## Limiti

- Le versioni anteriori al 2021 (Fedlex le offre solo in PDF e Word) e gli atti abrogati prima del 2021.
- Le versioni anteriori a Ginevra, Neuchâtel e nel Giura (i Cantoni pubblicano solo il testo in vigore); i Cantoni Ticino e Svitto.
- Gli atti della RU e i progetti soggetti a referendum che Fedlex offre solo in PDF (1'258 e 79, quasi tutti 2020–2022).
- Delle consultazioni, solo i progetti, non i rapporti esplicativi.

## Licenza e citazione

Gli atti e le loro traduzioni non sono protetti dal diritto d’autore (art. 5 cpv. 1 lett. a LDA). La preparazione – intestazioni, indici, struttura – è sotto [CC0](LICENSE). Il diritto si cita secondo la pubblicazione ufficiale; questo repository secondo [CITATION.cff](CITATION.cff). Prodotto con gli script di [`jonashertner/swiss-law-graph`](https://github.com/jonashertner/swiss-law-graph) (`pipeline/lawgit/`). Un progetto di [Jonas Hertner](https://jonashertner.com).
