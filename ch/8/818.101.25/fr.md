---
sr: "818.101.25"
title: Ordonnance du 24 juin 2020 sur le système de traçage de proximité pour le coronavirus SARS-CoV-2 (OSTP)
eli: "https://fedlex.data.admin.ch/eli/cc/2020/468"
language: fr
version: 2020-11-19
adopted: 2020-06-24
in_force: 2020-06-25
source: "https://fedlex.data.admin.ch/filestore/fedlex.data.admin.ch/eli/cc/2020/468/20201119/fr/xml/fedlex-data-admin-ch-eli-cc-2020-468-20201119-fr-xml-1.xml"
url: "https://www.fedlex.admin.ch/eli/cc/2020/468/20201119/fr"
---

> Reproduction non officielle de la version consolidée (Fedlex). Seule la publication au Recueil officiel fait foi (art. 15 LPubl, RS 170.512).

# Ordonnance sur le système de traçage de proximité pour le coronavirus SARS-CoV-2

(OSTP)

du 24 juin 2020 (Etat le 19 novembre 2020)

Le Conseil fédéral suisse,

vu l’art. 60*a*, al. 7, de la loi du 28 septembre 2012 sur les épidémies (LEp)[^ingress-1],

arrête:

[^ingress-1]: [RS 818.101](https://fedlex.data.admin.ch/eli/cc/2015/297)

#### Art. 1

**Objet**

La présente ordonnance règle les modalités de l’organisation, de l’exploitation et du traitement des données du système de traçage de proximité pour le coronavirus SARS-CoV-2 au sens de l’art 60*a* LEp (système TP).

#### Art. 2

**Structure**

<sup>1</sup>

Le système TP est composé des éléments suivants:

- a. un système de gestion de données relatives aux situations de rapprochement (système GR), composé d’un logiciel que les participants installent sur leur téléphone portable (application SwissCovid) et d’un *back-end* (*back-end* GR);
- b. un système permettant de gérer les codes pour autoriser l’information (système de gestion des codes), composé d’un *front-end* en ligne et d’un *back-end*.

<sup>2</sup> Le *back-end* GR et le système de gestion des codes sont administrés comme des serveurs centraux par l’Office fédéral de la santé publique (OFSP).

#### Art. 3

**Caractère volontaire**

<sup>1</sup> L’installation et l’utilisation de l’application SwissCovid s’effectuent sur une base volontaire.

<sup>2</sup> Les participants sont informés qu’ils ont potentiellement été exposés au coronavirus uniquement si la personne infectée y a expressément consenti.

#### Art. 4

**Organe fédéral responsable**

L’OFSP est l’organe fédéral responsable du respect de la législation sur la protection des données pour tous les composants du système TP.

#### Art. 5

**Fonctionnement de base**

<sup>1</sup>

Dans le fonctionnement de base, le *back-end* GR donne aux applications SwissCovid un accès en ligne à son contenu. Le contenu consiste en une liste des données suivantes:

- a. les clés privées des participants infectés qui étaient actuelles au moment où d’autres personnes ont potentiellement été exposées au coronavirus (période pertinente);
- b. la date de chaque clé.

<sup>2</sup>

L’application SwissCovid remplit les fonctions suivantes à l’aide d’une interface avec le système d’exploitation du téléphone portable:

- a. elle génère au moins chaque jour une nouvelle clé privée qui ne permet pas d’identifier l’application SwissCovid, le téléphone portable ou le participant;
- b. elle échange un code d’identification, modifié au moins toutes les demi-heures, avec toutes les applications compatibles et à portée de Bluetooth; le code d’identification est généré à partir de la clé privée actuelle, mais ne permet ni de remonter à la clé, ni d’identifier l’application SwissCovid, le téléphone portable ou le participant;
- c. l’application SwissCovid enregistre les codes d’identification reçus, la force du signal, la date et la durée approximative du rapprochement;
- d. depuis le *back-end* GR, elle extrait à intervalles réguliers la liste des clés privées des participants infectés et vérifie si les codes d’identification qu’elle a enregistrés localement ont été générés avec une clé privée de la liste;
- e.[^5-1] si elle constate qu’au moins un code d’identification enregistré localement a été généré avec une clé privée de la liste et que les conditions relatives au rapprochement énumérées au ch. 1 de l’annexe sont remplies, elle émet une information; la distance du rapprochement est estimée à l’aide de la force des signaux reçus.

<sup>3</sup> Les fonctions des systèmes d’exploitation utilisées via l’interface doivent satisfaire aux prescriptions de l’art. 60*a* LEp et de la présente ordonnance; font exception la réglementation concernant le code source visé à l’art. 60*a*, al. 5, let. e, LEp. L’OFSP s’assure que ces prescriptions sont respectées, en particulier en se procurant les garanties appropriées.

<sup>4</sup> ...[^5-2]

[^5-1]: Nouvelle teneur selon le ch. I de l’O du 18 nov. 2020, en vigueur depuis le 19 nov. 2020 ([RO 2020 4733](https://fedlex.data.admin.ch/eli/oc/2020/852)).
[^5-2]: Abrogé par le ch. I de l’O du 18 nov. 2020, avec effet au 19 nov. 2020 ([RO 2020 4733](https://fedlex.data.admin.ch/eli/oc/2020/852)).

#### Art. 6

**Fonctionnement après une infection**

<sup>1</sup> Si une infection est avérée, un service autorisé peut, avec le consentement de la personne infectée, demander un code d’autorisation unique et temporaire au système de gestion des codes; il transmet à ce système la date où les premiers symptômes sont apparus ou, si la personne infectée ne présente aucun symptôme, la date du test.[^6-1]

<sup>2</sup> Le service autorisé communique le code d’autorisation à la personne infectée.[^6-2] Celle-ci peut saisir le code d’autorisation dans son application SwissCovid.

<sup>3</sup> Le *back-end* de gestion des codes confirme à l’application SwissCovid la validité du code saisi. Il retranche de la date saisie le nombre de jours prévus au ch. 2 de l’annexe.[^6-3] La date qui en résulte est considérée comme le début de la période pertinente. Le *back-end* de gestion des codes communique cette date à l’application SwissCovid de la personne infectée.

<sup>4</sup> L’application SwissCovid de la personne infectée transmet au *back-end* GR les clés privées qui étaient actuelles durant la période pertinente ainsi que les dates correspondantes.

<sup>5</sup> Le *back-end* GR inscrit les clés privées reçues et les dates correspondantes dans sa liste.

<sup>6</sup> Après la transmission des clés privées, l’application SwissCovid génère une nouvelle clé privée. Celle-ci ne permet pas de remonter à d’anciennes clés privées.

[^6-1]: Nouvelle teneur selon le ch. I de l’O du 18 nov. 2020, en vigueur depuis le 19 nov. 2020 ([RO 2020 4733](https://fedlex.data.admin.ch/eli/oc/2020/852)).
[^6-2]: Nouvelle teneur selon le ch. I de l’O du 18 nov. 2020, en vigueur depuis le 19 nov. 2020 ([RO 2020 4733](https://fedlex.data.admin.ch/eli/oc/2020/852)).
[^6-3]: Nouvelle teneur de la phrase selon le ch. I de l’O du 18 nov. 2020, en vigueur depuis le 19 nov. 2020 ([RO 2020 4733](https://fedlex.data.admin.ch/eli/oc/2020/852)).

#### Art. 7

**Contenu de l’information**

<sup>1</sup>

L’information comprend:

- a. une information selon laquelle le participant a potentiellement été exposé au coronavirus;
- b.[^7-1] une indication des jours où cela s’est produit;
- c. une mention que l’OFSP gère une ligne d’information offrant des conseils sans frais;
- d. les règles de conduite recommandées par l’OFSP.

<sup>2</sup> Le système TP ne donne aucune consigne aux participants.

[^7-1]: Nouvelle teneur selon le ch. I de l’O du 18 nov. 2020, en vigueur depuis le 19 nov. 2020 ([RO 2020 4733](https://fedlex.data.admin.ch/eli/oc/2020/852)).

#### Art. 8

**Contenu du système de gestion des codes**

<sup>1</sup>

Le système de gestion des codes contient les données suivantes:

- a. les codes d’autorisation;
- b. la date à laquelle les premiers symptômes sont apparus ou, si la personne infectée ne présente aucun symptôme, la date du test;
- c. la date de la destruction des données visées aux let. a et b.

<sup>2</sup> Ces données ne permettent pas de remonter aux participants.^

#### Art. 8a

**Mode d’accès au système de gestion des codes**[^8a-1]

L’accès au système de gestion des codes peut s’effectuer au moyen:

- a. du *front-end*, utilisé par un professionnel du service autorisé, ou
- b. d’une interface entre le système de gestion des codes et un système employé par le service autorisé.

[^8a-1]: Introduit par le ch. I de l’O du 18 nov. 2020, en vigueur depuis le 19 nov. 2020 ([RO 2020 4733](https://fedlex.data.admin.ch/eli/oc/2020/852)).

#### Art. 9

**Accès au système de gestion des codes au moyen du *front-end*[^9-1]**

<sup>1</sup>

Les personnes suivantes, agissant pour le service autorisé concerné, peuvent demander un code d’autorisation au moyen du *front-end*:[^9-2]

- a. les médecins cantonaux;
- b. le médecin en chef de l’armée;
- c. les autres collaborateurs des services des médecins cantonaux ou du service médico-militaire de l’armée;
- d. les tiers mandatés par les services des médecins cantonaux ou par le service médico-militaire de l’armée;
- e.[^9-3] les collaborateurs des cabinets médicaux;
- f.[^9-4] les collaborateurs des laboratoires titulaires de l’autorisation prévue à l’art. 16 LEp;
- g.[^9-5] les collaborateurs des établissements visés à l’art. 24, al. 1, let. b, de l’ordonnance 3 COVID-19 du 19 juin 2020[^9-6];
- h.[^9-7] les collaborateurs de la ligne d’information visée à l’art. 7, al. 1, let. c.

<sup>2</sup> L’inscription dans le système de gestion des codes passe par le système central de gestion des accès et des autorisations de l’administration fédérale pour les applications Web. Les dispositions de l’ordonnance du 19 octobre 2016 sur les systèmes de gestion des données d’identification et les services d’annuaires de la Confédération[^9-8] s’appliquent.

<sup>3</sup> L’OFSP attribue et gère les droits d’accès au système de gestion des codes. Il peut autoriser les médecins cantonaux, le médecin en chef de l’armée et certains membres de leur personnel assistant à attribuer des droits d’accès à du personnel assistant.

[^9-1]: Nouvelle teneur selon le ch. I de l’O du 18 nov. 2020, en vigueur depuis le 19 nov. 2020 ([RO 2020 4733](https://fedlex.data.admin.ch/eli/oc/2020/852)).
[^9-2]: Nouvelle teneur selon le ch. I de l’O du 18 nov. 2020, en vigueur depuis le 19 nov. 2020 ([RO 2020 4733](https://fedlex.data.admin.ch/eli/oc/2020/852)).
[^9-3]: Nouvelle teneur selon le ch. I de l’O du 18 nov. 2020, en vigueur depuis le 19 nov. 2020 ([RO 2020 4733](https://fedlex.data.admin.ch/eli/oc/2020/852)).
[^9-4]: Introduite par le ch. I de l’O du 18 nov. 2020, en vigueur depuis le 19 nov. 2020 ([RO 2020 4733](https://fedlex.data.admin.ch/eli/oc/2020/852)).
[^9-5]: Introduite par le ch. I de l’O du 18 nov. 2020, en vigueur depuis le 19 nov. 2020 ([RO 2020 4733](https://fedlex.data.admin.ch/eli/oc/2020/852)).
[^9-6]: [RS 818.101.24](https://fedlex.data.admin.ch/eli/cc/2020/438)
[^9-7]: Introduite par le ch. I de l’O du 18 nov. 2020, en vigueur depuis le 19 nov. 2020 ([RO 2020 4733](https://fedlex.data.admin.ch/eli/oc/2020/852)).
[^9-8]: [RS 172.010.59](https://fedlex.data.admin.ch/eli/cc/2016/610)

#### Art. 9a

**Accès au système de gestion des codes au moyen de l’interface**[^9a-1]

L’OFSP permet aux services autorisés visés à l’art. 9, al. 1, de raccorder leur système au système de gestion des codes au moyen de l’interface, pour autant que le système concerné présente un niveau de sécurité adéquat.

[^9a-1]: Introduit par le ch. I de l’O du 18 nov. 2020, en vigueur depuis le 19 nov. 2020 ([RO 2020 4733](https://fedlex.data.admin.ch/eli/oc/2020/852)).

#### Art. 10

**Prestations de tiers**

<sup>1</sup> L’OFSP peut charger des tiers de donner aux applications SwissCovid un accès en ligne à la liste des données nécessaires aux informations.

<sup>2</sup> Il peut déléguer à des tiers l’attribution des droits d’accès au système de gestion des codes. Le tiers désigné doit garantir la vérification fiable et juridiquement correcte des droits accordés aux professionnels.

<sup>3</sup> Les tiers doivent être contractuellement tenus de respecter les prescriptions de l’art. 60*a* LEp et de la présente ordonnance; font exception la réglementation concernant le code source visé à l’art. 60*a*, al. 5, let. e, LEp. L’OFSP contrôle le respect des prescriptions.

#### Art. 11

**Journaux des accès**

<sup>1</sup> Les art. 57*i* à 57*q* de la loi du 21 mars 1997 sur l’organisation du gouvernement et de l’administration[^11-1] et l’ordonnance du 22 février 2012 sur le traitement des données personnelles liées à l’utilisation de l’infrastructure électronique de la Confédération[^11-2] sont applicables à l’enregistrement et à l’analyse des journaux des accès au *back-end* GR, au système de gestion des codes et à la liste visée à l’art. 10, al. 1.

<sup>2</sup> Hormis les journaux des accès et l’enregistrement des rapprochements, le système TP n’enregistre aucun journal des activités des *front-ends* du système de gestion des codes et des applications SwissCovid.

[^11-1]: [RS 172.010](https://fedlex.data.admin.ch/eli/cc/1997/2022_2022_2022)
[^11-2]: [RS 172.010.442](https://fedlex.data.admin.ch/eli/cc/2012/160)

#### Art. 12

**Communication à des fins statistiques**

L’OFSP met régulièrement à la disposition de l’Office fédéral de la statistique (OFS) les données actuelles disponibles dans les deux *back-ends*, sous forme entièrement anonymisée, à des fins statistiques.

#### Art. 13

**Destruction des données**

<sup>1</sup> Les données du système GR sont détruites à la fois sur les téléphones portables et dans le *back-end* GR 14 jours après leur saisie.

<sup>2</sup> Les données du système de gestion des codes sont détruites 24 heures après leur saisie.

<sup>3</sup> Les données journalisées par des tiers mandatés au sens de l’art. 10, al. 1, sont détruites 7 jours après leur saisie.

<sup>4</sup> Pour le reste, les données journalisées sont détruites conformément à l’art. 4, al. 1, let. b, de l’ordonnance du 22 février 2012 sur le traitement des données personnelles liées à l’utilisation de l’infrastructure électronique de la Confédération[^13-1].

<sup>5</sup> Les données mises à la disposition de l’OFS sont également détruites conformément au présent article.

[^13-1]: [RS 172.010.442](https://fedlex.data.admin.ch/eli/cc/2012/160)

#### Art. 14

**Vérification du code source**

<sup>1</sup> L’OFSP publie les données qui servent à vérifier si, pour tous les éléments du système TP, les programmes lisibles par une machine ont été créés à partir du code source publié.

<sup>2</sup> Il effectue lui-même la vérification.

#### Art. 15

**Désactivation de l’application SwissCovid et rapport**

<sup>1</sup> Lors de l’abrogation de la présente ordonnance, l’OFSP désactive l’application SwissCovid et invite les participants à la désinstaller de leur téléphone portable.

<sup>2</sup> Il fait rapport au Conseil fédéral au plus tard six mois après l’abrogation.

#### Art. 16

**Abrogation d’un autre acte**

L’ordonnance COVID-19 du 13 mai 2020 essai pilote traçage de proximité[^16-1] est abrogée.

[^16-1]: [[RO 2020 1589](https://fedlex.data.admin.ch/eli/oc/2020/324)]

#### Art. 16a

**Actualisation de l’annexe**[^16a-1]

Le Département fédéral de l’intérieur (DFI) actualise l’annexe à la présente ordonnance en fonction de l’état actuel des connaissances scientifiques.

[^16a-1]: Introduit par le ch. I de l’O du 18 nov. 2020, en vigueur depuis le 19 nov. 2020 ([RO 2020 4733](https://fedlex.data.admin.ch/eli/oc/2020/852)).

#### Art. 17

**Entrée en vigueur et durée de validité**

La présente ordonnance entre en vigueur le 25 juin 2020 à 0 h 00 et a effet jusqu’au 30 juin 2022.

Annexe*[^t-1]*

(art. 5, al. 2, let. e, et 6, al. 3)

## Conditions épidémiologiques relatives au rapprochement et période pertinente

[^t-1]: Nouvelle teneur selon le ch. II de l’O du 18 nov. 2020, en vigueur depuis le 19 nov. 2020 ([RO 2020 4733](https://fedlex.data.admin.ch/eli/oc/2020/852)).

### 1. Conditions épidémiologiques relatives au rapprochement

Les conditions épidémiologiques relatives au rapprochement sont remplies si les conditions suivantes sont remplies:

- a. il y a eu un rapprochement spatial de 1,5 mètre ou moins avec un téléphone portable au moins d’un participant infecté;
- b. la durée totale de tous les rapprochements au sens de la let. a atteint ou dépasse 15 minutes au cours de la même journée.

### 2. Début de la période pertinente sur le plan épidémiologique

- [tab] Nombre de jours à retrancher: deux.
