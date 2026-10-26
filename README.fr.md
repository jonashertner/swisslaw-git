# Droit suisse

[Deutsch](README.md) · **Français** · [Italiano](README.it.md) · [English](README.en.md)

Le droit de la Confédération et des cantons en dépôt Git : chaque acte un fichier par langue, chaque version un commit, daté du jour où elle s’applique – depuis le 1er janvier 2021.

> **Non officiel.** Seule fait foi la publication au Recueil officiel du droit fédéral (art. 15 LPubl, RS 170.512) et dans les recueils officiels des cantons. Les versions anglaises sont des traductions sans force juridique.

|  | Actes | Versions depuis 2021 |
|:---|---:|---:|
| [Droit fédéral](ch/README.md) · droit interne et traités | 5 338 | 11 674 |
| [Droit cantonal](cantons/README.md) · 24 cantons | 16 440 | 30 877 |
| [Adopté, pas encore en vigueur](adopted/README.md) · RO et projets soumis au référendum | 145 | |
| [Consultations](consultations/README.md) · projets de la Confédération, 22 ouvertes | 609 | |

État au 27 octobre 2026. La carte qui l’accompagne – comment les actes reposent les uns sur les autres et comment les tribunaux les citent : [Atlas du droit suisse](https://jonashertner.github.io/swiss-law-graph/).

**Souvent consultés** : [Cst.](ch/1/101/fr.md) · [CC](ch/2/210/fr.md) · [CO](ch/2/220/fr.md) · [CP](ch/3/311.0/fr.md) · [LP](ch/2/281.1/fr.md) · [CPC](ch/2/272/fr.md) · [CPP](ch/3/312.0/fr.md) · [LTF](ch/1/173.110/fr.md) · [PA](ch/1/172.021/fr.md) · [LPD](ch/2/235.1/fr.md) · [LPGA](ch/8/830.1/fr.md) · [LEI](ch/1/142.20/fr.md) · [CEDH](ch/0.1/0.101/fr.md)

## Utiliser

```sh
# le Code des obligations, aujourd’hui
cat ch/2/220/fr.md

# chaque version depuis 2021, avec les modifications
git log --follow -p -- ch/2/220/fr.md

# le CO au 1er juillet 2023 (une étiquette par premier du mois)
git show stand/2023-07-01:ch/2/220/fr.md

# à n’importe quel jour : le dernier commit jusque-là, midi heure de Zurich
git show "$(git rev-list -1 --before='2023-06-30 12:00 +0200' main)":ch/2/220/fr.md

# ce qui a changé en 2025 à Zurich et en droit des assurances sociales
git log --since=2025-01-01 --until=2026-01-01 --stat -- cantons/zh ch/8

# quelle version a écrit chaque ligne
git blame ch/2/220/fr.md

# chercher
git grep -n "bonne foi" -- 'ch/*/fr.md'

# chaque fichier avec numéro, titre, version et source
grep ',220,' index.csv

# avec les versions qui ne s’appliquent que plus tard
git checkout future
```

Chaque article est un titre, donc un lien : [`ch/2/220/fr.md#art-41`](ch/2/220/fr.md#art-41). [AGENTS.md](AGENTS.md) décrit la structure et chaque champ pour les programmes et les agents d’IA.

## Structure

| Chemin | Contenu |
|:---|:---|
| `ch/<1–9 \| 0.1–0.9>/<SR>/<lang>.md` | droit fédéral en vigueur ; domaine = premier chiffre du numéro RS, traités 0.1 – 0.9 |
| `cantons/<ct>/<x>/<nr>/<lang>.md` | droit cantonal ; dossiers selon le premier caractère du numéro du recueil cantonal |
| `adopted/as/…`, `adopted/bbl/…` | publié au RO, pas encore en vigueur (jusqu’à l’entrée en vigueur) ; projets soumis au référendum (FF) jusqu’au RO, à l’échéance du délai ou au rejet |
| `consultations/<year>/<nr>/` | projets mis en consultation par la Confédération, dès l’ouverture ; « clos » après le délai |
| `index.csv`, `index.jsonl` | chaque fichier avec numéro, titre, version et source |

`main` vaut jusqu’à aujourd’hui et s’enrichit deux fois par semaine, sans jamais être réécrite ; `future` contient en plus les versions futures déjà publiées et est reconstruite à chaque mise à jour ; les tags `stand/AAAA-MM-01` l’état au premier de chaque mois. Date d’auteur d’un commit = jour dès lequel la version s’applique ; date de commit = jour dès lequel ce dépôt la montre (une version publiée plus tard suit avec la mise à jour suivante).

**Un fichier** : en-tête (YAML) : numéro, titre, titre abrégé, langue, version (dès le), adoption, entrée en vigueur, source ; titre, préambule, structure en titres, chaque article `#### Art. N` ; chaque alinéa sur une ligne (`<sup>1</sup> …`), pour des diffs et un `blame` exacts ; notes (modifications avec leur référence) juste après leur article ; tableaux en HTML.

## Sources et contrôle

- Confédération : les versions consolidées sur [Fedlex](https://www.fedlex.admin.ch) en XML (Akoma Ntoso), chaque version depuis le 1er janvier 2021 ; RO, FF et consultations également de Fedlex.
- Cantons : les recueils systématiques – 19 sur LexWork, Vaud (BLV) et Zurich (zh.ch) avec chaque version depuis le 1er janvier 2021 ; Genève et Neuchâtel (SIL) et le Jura (RSJU) avec le texte en vigueur. Les actes abrogés depuis le 1er janvier 2021 y figurent jusqu’à leur abrogation.
- Chaque fichier est contrôlé : chaque mot de la source doit figurer dans le Markdown.

| Source | Fichiers | Mots de la source | manquent |
|:---|---:|---:|---:|
| Confédération (Fedlex, XML) | 37 274 | 333 497 234 | 703 |
| Cantons, LexWork (structuré) | 27 851 | 68 803 393 | 343 |
| Cantons, LexWork (lu dans le PDF) | 5 883 | 14 192 665 | 113 |
| Vaud (BLV) | 3 452 | 5 910 511 | 22 |
| Genève, Neuchâtel (SIL) | 1 687 | 4 374 185 | 13 |
| Zurich (lu dans le PDF) | 1 786 | 5 275 451 | 17 |
| Jura (lu dans le PDF) | 855 | 1 653 093 | 467 |
| RO et FF (XML) | 7 695 | 13 006 466 | 189 |
| Consultations (lu dans le PDF) | 3 079 | 8 641 030 | 263 |

Les textes lus dans le PDF portent `text: pdf` dans l’en-tête : leurs mots sont contrôlés, leur structure est déduite de la mise en page et non contrôlée. En cas de doute, le PDF indiqué fait foi.

## Limites

- Les versions antérieures à 2021 (Fedlex ne les offre qu’en PDF et Word) et les actes abrogés avant 2021.
- Les versions antérieures à Genève, Neuchâtel et dans le Jura (les cantons ne publient que le texte en vigueur) ; les cantons du Tessin et de Schwyz.
- Les actes du RO et projets soumis au référendum que Fedlex n’offre qu’en PDF (1 258 et 79, presque tous 2020–2022).
- Des consultations, seuls les projets, pas les rapports explicatifs.

## Licence et citation

Les actes et leurs traductions ne sont pas protégés par le droit d’auteur (art. 5, al. 1, let. a LDA). La mise en forme – en-têtes, répertoires, structure – est sous [CC0](LICENSE). Le droit se cite d’après la publication officielle ; ce dépôt d’après [CITATION.cff](CITATION.cff). Produit avec les scripts de [`jonashertner/swiss-law-graph`](https://github.com/jonashertner/swiss-law-graph) (`pipeline/lawgit/`). Un projet de [Jonas Hertner](https://jonashertner.com).
