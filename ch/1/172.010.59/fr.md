---
sr: "172.010.59"
title: "Ordonnance du 19 octobre 2016 sur les systèmes de gestion des données d'identification et les services d'annuaires de la Confédération (OIAM)"
short: OIAM
eli: "https://fedlex.data.admin.ch/eli/cc/2016/610"
language: fr
version: 2024-01-01
adopted: 2016-10-19
in_force: 2017-01-01
source: "https://fedlex.data.admin.ch/filestore/fedlex.data.admin.ch/eli/cc/2016/610/20240101/fr/xml/fedlex-data-admin-ch-eli-cc-2016-610-20240101-fr-xml-2.xml"
url: "https://www.fedlex.admin.ch/eli/cc/2016/610/20240101/fr"
---

> Reproduction non officielle de la version consolidée (Fedlex). Seule la publication au Recueil officiel fait foi (art. 15 LPubl, RS 170.512).

# Ordonnance sur les systèmes de gestion des données d’identification et les services d’annuaires de la Confédération

(OIAM)

du 19 octobre 2016 (État le 1<sup>er</sup> janvier 2024)

Le Conseil fédéral suisse,

vu les art. 26 et 84, al. 1, de la loi du 18 décembre 2020 sur la sécurité de l’information (LSI)[^ingress-1], vu la loi fédérale du 17 mars 2023 sur l’utilisation de moyens électroniques pour l’exécution des tâches des autorités (LMETA)[^ingress-2], vu la loi du 21 mars 1997 sur l’organisation du gouvernement et de l’administration (LOGA)[^ingress-3], vu l’art. 27, al. 5 et 6, de la loi du 24 mars 2000 sur le personnel de la Confédération[^ingress-4], vu l’art. 186 de la loi fédérale du 3 octobre 2008 sur les systèmes d’information de l’armée et du DDPS[^ingress-5],[^ingress-6]

arrête:

[^ingress-1]: [RS 128](https://fedlex.data.admin.ch/eli/cc/2022/232)
[^ingress-2]: [RS 172.019](https://fedlex.data.admin.ch/eli/cc/2023/682)
[^ingress-3]: [RS 172.010](https://fedlex.data.admin.ch/eli/cc/1997/2022_2022_2022)
[^ingress-4]: [RS 172.220.1](https://fedlex.data.admin.ch/eli/cc/2001/123)
[^ingress-5]: [RS 510.91](https://fedlex.data.admin.ch/eli/cc/2009/823)
[^ingress-6]: Nouvelle teneur selon le ch. I de l’O du 8 nov. 2023, en vigueur depuis le 1<sup>er</sup> janv. 2024 ([RO 2023 738](https://fedlex.data.admin.ch/eli/oc/2023/738)).

## Section 1 Dispositions générales

#### Art. 1

**Objet**

La présente ordonnance régit les compétences, le traitement et la publication de données personnelles ainsi que les exigences concernant la sécurité de l’information pour les systèmes de gestion des données d’identification (systèmes IAM[^1-1]), les services d’annuaires et la base centralisée des identités de la Confédération.

[^1-1]: IAM = *Identity and Access Management* (gestion des identités et des accès)

#### Art. 2

**Champ d’application**[^2-1]

<sup>1</sup>

Les art. 24 et 25 LSI ainsi que la présente ordonnance s’appliquent:

- a. aux unités de l’administration fédérale centrale au sens de l’art. 7 de l’ordonnance du 25 novembre 1998 sur l’organisation du gouvernement et de l’administration (OLOGA)[^2-2];
- b. à l’armée.

<sup>2</sup> L’application de la présente ordonnance aux unités de l’administration fédérale décentralisée visées à l’art. 2, al. 3, LOGA et aux organisations visées à l’art. 2, al. 4, LOGA est régie par l’art. 2, al. 2, let. b, et al. 3, de l’ordonnance du 8 novembre 2023 sur la sécurité de l’information (OSI)[^2-3].

[^2-1]: Nouvelle teneur selon le ch. I de l’O du 8 nov. 2023, en vigueur depuis le 1<sup>er</sup> janv. 2024 ([RO 2023 738](https://fedlex.data.admin.ch/eli/oc/2023/738)).
[^2-2]: [RS 172.010.1](https://fedlex.data.admin.ch/eli/cc/1999/170)
[^2-3]: [RS 128.1](https://fedlex.data.admin.ch/eli/cc/2023/735)

## Section 2 But et fonction principale des systèmes

#### Art. 3

**Systèmes IAM**

<sup>1</sup> Un système IAM sert à gérer conjointement des données sur l’identité et les autorisations de personnes, de machines et de systèmes pour les mettre, sur demande, à la disposition des systèmes en aval et d’autres systèmes IAM.

<sup>2</sup> Les systèmes en aval sont des applications techniques ou des dispositifs permettant d’accéder à des informations, des moyens informatiques, des locaux et d’autres infrastructures.

<sup>3</sup> Placé en amont, le système IAM vérifie l’identité et certains critères d’accès des personnes, des machines et des systèmes qui souhaitent accéder à un système en aval; il transmet à ce dernier les résultats de la vérification afin que celui-ci puisse délivrer les autorisations.

#### Art. 4

**Services d’annuaires**

Un service d’annuaires sert à gérer des informations sur les utilisateurs des infrastructures de la Confédération pour pouvoir identifier les personnes et administrer les appareils, les raccordements, les coordonnées et les éléments similaires qui leur ont été attribués.

## Section 3 Organes responsables

#### Art. 5

**Systèmes IAM**[^5-1]

<sup>1</sup>

Les organes de la Confédération suivants sont responsables des systèmes IAM de l’administration fédérale centrale ci-après:

- a.

  le secteur Transformation numérique et gouvernance de l’informatique de la Chancellerie fédérale (secteur TNI de la ChF), pour:

  - 1\. tous les systèmes IAM proposés comme services standard et tous les systèmes IAM relevant explicitement du secteur TNI de la ChF, y compris leur mise à la disposition des cantons et des communes ainsi que d’organisations et de personnes de droit public ou de droit privé conformément à l’art. 11, al. 3, LMETA,
  - 2\. le système IAM des processus de soutien en matière de finances, d’acquisition, de gestion immobilière et de logistique, y compris le raccordement aux services d’informatique en nuage *(**cloud**)*;

- b. la Direction des ressources du Département fédéral des affaires étrangères (DFAE), pour le système IAM exploité par l’unité Informatique DFAE;
- c. le Secrétariat général du Département fédéral de la défense, de la protection de la population et des sports, pour les systèmes IAM exploités par le Groupement Défense (Groupement D);
- d. l’Administration fédérale des finances, pour le système IAM de gestion des systèmes d’assurances sociales du premier pilier et de soutien à leurs processus exploité par la Centrale de compensation;
- e. le Secrétariat général du Département fédéral de l’économie, de la formation et de la recherche (DEFR), pour le système IAM exploité par le Centre de services informatiques du DEFR (ISCeco);
- f. l’Office fédéral des routes, pour son système IAM de gestion des équipements d’exploitation et de sécurité des routes nationales.

<sup>2</sup> Ils veillent à ce que le traitement des données personnelles figurant dans les systèmes IAM dont ils sont responsables soit contrôlé au moins tous les quatre ans par un organe externe.

<sup>3</sup>

Les organes suivants sont responsables des systèmes IAM ci-après:

- a. le Groupement D, pour les systèmes IAM de l’armée;
- b. les unités administratives concernées, pour les systèmes IAM des unités de l’administration fédérale décentralisée;
- c. les organisations concernées, pour les systèmes IAM des organisations visées à l’art. 2, al. 4, LOGA.

<sup>4</sup> Les autorités visées à l’art. 2, al. 1, let. a et c à e, LSI auxquelles la présente ordonnance s’applique en vertu de l’art. 84, al. 3, LSI déterminent quels organes de la Confédération sont responsables dans leur domaine.

<sup>5</sup> La responsabilité du système en aval, et en particulier de l’accès à celui-ci, continue d’incomber au service technique responsable du système.

[^5-1]: Nouvelle teneur selon le ch. I de l’O du 8 nov. 2023, en vigueur depuis le 1<sup>er</sup> janv. 2024 ([RO 2023 738](https://fedlex.data.admin.ch/eli/oc/2023/738)).

#### Art. 6

**Services d’annuaires**

Les organes de la Confédération responsables des services d’annuaires extérieurs aux systèmes IAM sont:

- a. pour les services standard, le secteur TNI de la ChF[^6-1];
- b.

  pour les autres annuaires, les fournisseurs de prestations informatiques qui exploitent ces systèmes, à savoir:

  - 1\. l’unité Informatique DFAE de la Direction des ressources du DFAE,
  - 2\. le Centre de services informatiques (CSI) du Département fédéral de justice et police (DFJP),
  - 3\.[^6-2] le Groupement D,
  - 4\. l’Office fédéral de l’informatique et de la télécommunication (OFIT),
  - 5\. l’ISCeco.

[^6-1]: Nouvelle expression selon l’annexe ch. 8 de l’O du 25 nov. 2020 sur la transformation numérique et l’informatique, en vigueur depuis le 1<sup>er</sup> janv. 2021 ([RO 2020 5871](https://fedlex.data.admin.ch/eli/oc/2020/988)). Il a été tenu compte de cette mod. dans tout le texte.
[^6-2]: Nouvelle teneur selon le ch. I de l’O du 8 nov. 2023, en vigueur depuis le 1<sup>er</sup> janv. 2024 ([RO 2023 738](https://fedlex.data.admin.ch/eli/oc/2023/738)).

#### Art. 7

**Exercice des droits**

Les personnes concernées font valoir leurs droits relatifs aux systèmes IAM et aux services d’annuaires auprès des organes suivants:

- a. droit d’accès: auprès des organes responsables;
- b.[^7-1]

  droit de rectification et de suppression:

  - 1\. auprès du service du personnel de leur unité administrative ou de leur organisation ou auprès du service chargé de gérer leurs données,
  - 2\. dans le cas de l’art. 9, let. b: auprès des organes responsables.

[^7-1]: Nouvelle teneur selon le ch. I de l’O du 8 nov. 2023, en vigueur depuis le 1<sup>er</sup> janv. 2024 ([RO 2023 738](https://fedlex.data.admin.ch/eli/oc/2023/738)).

## Section 4 Données traitées, collecte des données et délai de conservation

#### Art. 8

**Personnes gérées dans les systèmes IAM et les services d’annuaires**

<sup>1</sup>

Les données concernant les personnes suivantes peuvent être traitées dans les systèmes IAM et les services d’annuaires:

- a. membres de l’administration fédérale centrale au sens de l’art. 7 OLOGA[^8-1];
- b. membres de l’administration fédérale décentralisée au sens de l’art. 7*a* OLOGA;
- c. membres de l’Assemblée fédérale et des Services du Parlement au sens du titre 4, chap. 7, de la loi du 13 décembre 2002 sur le Parlement[^8-2];
- d. personnes élues par l’Assemblée fédérale au sens de l’art. 168 de la Constitution[^8-3];
- e. membres du Tribunal fédéral, du Tribunal administratif fédéral, du Tribunal pénal fédéral et du Tribunal fédéral des brevets, sauf disposition contraire de la législation;
- f. membres du Ministère public de la Confédération au sens des art. 7 à 22 de la loi du 19 mars 2010 sur l’organisation des autorités pénales (LOAP)[^8-4];
- g. membres du Secrétariat de l’Autorité de surveillance du Ministère public de la Confédération au sens de l’art. 27, al. 2, LOAP;
- h.[^8-5] les militaires et les membres de la protection civile.

<sup>2</sup>

Peuvent en outre être traitées les données concernant les membres des entreprises suivantes, pour autant que ceux-ci soient régulièrement en contact avec des organes au sens de l’al. 1:

- a. Chemins de fer fédéraux;
- b. La Poste Suisse;
- c. RUAG;
- d. Caisse nationale suisse d’assurance en cas d’accidents.

<sup>3</sup>

Par ailleurs, les données concernant les personnes suivantes peuvent être traitées dans les systèmes IAM et les services d’annuaires:

- a. personnes externes exerçant une activité pour des organes au sens des al. 1 ou 2;
- b. personnes externes qui, pour d’autres motifs, ont accès à des informations, des moyens informatiques, des locaux et d’autres infrastructures de l’administration fédérale.

[^8-1]: [RS 172.010.1](https://fedlex.data.admin.ch/eli/cc/1999/170)
[^8-2]: [RS 171.10](https://fedlex.data.admin.ch/eli/cc/2003/510)
[^8-3]: [RS 101](https://fedlex.data.admin.ch/eli/cc/1999/404)
[^8-4]: [RS 173.71](https://fedlex.data.admin.ch/eli/cc/2010/444)
[^8-5]: Introduite par le ch. I de l’O du 14 nov. 2018, en vigueur depuis le 1<sup>er</sup> janv. 2019 ([RO 2018 4739](https://fedlex.data.admin.ch/eli/oc/2018/752)).

#### Art. 9

**Personnes gérées dans les systèmes IAM**

Les données concernant les personnes suivantes peuvent être traitées dans les systèmes IAM en plus des données au sens de l’art. 8:

- a. membres d’autorités cantonales ou communales, si ces personnes utilisent des systèmes d’information mis à disposition par la Confédération;
- b.[^9-1] particuliers et représentants d’organisations qui accèdent à des systèmes d’information mis à disposition par la Confédération ou, pour l’exécution du droit cantonal, par les cantons et les communes ainsi que par des organisations et personnes de droit public ou de droit privé, tels que les applications de cyberadministration.

[^9-1]: Nouvelle teneur selon le ch. I de l’O du 8 nov. 2023, en vigueur depuis le 1<sup>er</sup> janv. 2024 ([RO 2023 738](https://fedlex.data.admin.ch/eli/oc/2023/738)).

#### Art. 10

**Personnes gérées dans les services d’annuaires**

Les données des membres d’autorités cantonales ou communales et d’autres entreprises liées à la Confédération que celles mentionnées à l’art. 8, al. 2, qui utilisent un certificat numérique de la Confédération peuvent être traitées dans les services d’annuaires en plus des données au sens de l’art. 8.

#### Art. 11

**Catégories de données personnelles**

<sup>1</sup> Les données personnelles énumérées dans l’annexe peuvent être traitées dans les systèmes IAM, les services d’annuaires et la base centralisée des identités visée à l’art. 13.

<sup>2</sup> Aucun profilage au sens de l’art. 5, let. f et g, de la loi fédérale du 25 septembre 2020 sur la protection des données[^11-1] ne peut être effectué dans ces systèmes.[^11-2]

<sup>3</sup> En l’absence d’une base légale particulière en la matière, aucune donnée sensible ne peut être traitée dans ces systèmes. Fait exception le traitement de données biométriques par les systèmes IAM à des fins d’identification des personnes visées aux art. 8 et 9, let. a, en fonction du risque (art. 20, al. 2, LSI).[^11-3]

<sup>4</sup> Les données assorties d’un astérisque dans l’annexe concernant des personnes mentionnées à l’art. 8 peuvent être publiées dans un service d’annuaires qui est accessible à toutes les personnes y figurant.

[^11-1]: [RS 235.1](https://fedlex.data.admin.ch/eli/cc/2022/491)
[^11-2]: Nouvelle teneur selon le ch. I de l’O du 8 nov. 2023, en vigueur depuis le 1<sup>er</sup> janv. 2024 ([RO 2023 738](https://fedlex.data.admin.ch/eli/oc/2023/738)).
[^11-3]: Nouvelle teneur selon le ch. I de l’O du 8 nov. 2023, en vigueur depuis le 1<sup>er</sup> janv. 2024 ([RO 2023 738](https://fedlex.data.admin.ch/eli/oc/2023/738)).

#### Art. 12

**Obtention de données personnelles**

<sup>1</sup> Les systèmes IAM et les services d’annuaires peuvent obtenir automatiquement les données relatives aux personnes gérées dans le système d’information pour la gestion des données du personnel (IGDP) au sens de l’art. 34 de l’ordonnance du 22 novembre 2017 concernant la protection des données personnelles du personnel de la Confédération[^12-1].[^12-2]

<sup>2</sup> Ils peuvent obtenir automatiquement auprès des organes concernés au sens de l’art. 8 les données des personnes ne figurant pas dans IGDP[^12-3], dans la mesure où ces groupes de personnes ont besoin d’accéder à des systèmes d’information ou à d’autres ressources de la Confédération.

<sup>3</sup> Ils peuvent obtenir automatiquement auprès des systèmes d’information concernés les données des personnes externes qui accèdent régulièrement aux ressources de la Confédération.

<sup>4</sup> Ils peuvent obtenir automatiquement les données de personnes externes auprès des systèmes IAM externes raccordés aux systèmes IAM de la Confédération conformément aux art. 21 à 24.[^12-4]

[^12-1]: [RS 172.220.111.4](https://fedlex.data.admin.ch/eli/cc/2017/793)
[^12-2]: Nouvelle teneur selon l’annexe 8 ch. II 1 de l’O du 22 nov. 2017 concernant la protection des données personnelles du personnel de la Confédération, en vigueur depuis le 1<sup>er</sup> janv. 2018 ([RO 2017 7271](https://fedlex.data.admin.ch/eli/oc/2017/793)).
[^12-3]: Nouvelle expression selon l’annexe 8 ch. II 1 de l’O du 22 nov. 2017 concernant la protection des données personnelles du personnel de la Confédération, en vigueur depuis le 1<sup>er</sup> janv. 2018 ([RO 2017 7271](https://fedlex.data.admin.ch/eli/oc/2017/793)). Il a été tenu compte de cette mod. dans tout le texte.
[^12-4]: Introduit par le ch. I de l’O du 8 nov. 2023, en vigueur depuis le 1<sup>er</sup> janv. 2024 ([RO 2023 738](https://fedlex.data.admin.ch/eli/oc/2023/738)).

#### Art. 13

**Base centralisée des identités pour la distribution des données**

<sup>1</sup> L’OFIT exploite une base centralisée des identités pour distribuer les données des utilisateurs aux différents systèmes IAM et services d’annuaires. Toutes les données personnelles mentionnées dans l’annexe peuvent être traitées dans cette base. Le secteur TNI de la ChF est l’organe responsable au sein de la Confédération.

<sup>2</sup> IGDP transmet régulièrement à la base centralisée des identités les données mentionnées dans l’annexe, pour autant que ces dernières soient disponibles. Toute obtention automatique de données personnelles depuis IGDP est réalisée grâce à ce distributeur, à l’exception de l’obtention directe des données de base du personnel dans l’environnement SAP pour les systèmes SAP autorisés.

<sup>3</sup> Les données personnelles au sens de l’art. 8, al. 1, let. c, et 3, sont transmises aux Services du Parlement pour y être reprises et harmonisées.

<sup>4</sup>

Les données peuvent être transmises de manière automatisée à d’autres systèmes d’information internes à l’administration fédérale, dans lesquels elles sont reprises et harmonisées, à condition que le système concerné:

- a.[^13-1] dispose d’une base légale prévoyant le traitement des données à transmettre et d’un règlement de traitement au sens de l’art. 6 de l’ordonnance du 31 août 2022 sur la protection des données (OPDo)[^13-2], et
- b. ait été annoncé au Préposé fédéral à la protection des données et à la transparence conformément à l’art. 12, al. 4, de loi fédérale du 25 septembre 2020 sur la protection des données[^13-3].[^13-4]

<sup>4bis</sup> Le numéro AVS n’est transmis que si son utilisation est annoncée à la Centrale de compensation conformément à l’art. 134<sup>ter</sup> du règlement du 31 octobre 1947 sur l’assurance-vieillesse et survivants[^13-5].[^13-6]

<sup>5</sup> Les données nécessaires à la publication de l’Annuaire fédéral au sens de l’art. 5 de l’ordonnance du 29 octobre 2008 sur l’organisation de la Chancellerie fédérale[^13-7] sont transmises régulièrement à cette dernière.

[^13-1]: Nouvelle teneur selon le ch. I de l’O du 8 nov. 2023, en vigueur depuis le 1<sup>er</sup> janv. 2024 ([RO 2023 738](https://fedlex.data.admin.ch/eli/oc/2023/738)).
[^13-2]: [RS 235.11](https://fedlex.data.admin.ch/eli/cc/2022/568)
[^13-3]: [RS 235.1](https://fedlex.data.admin.ch/eli/cc/2022/491)
[^13-4]: Nouvelle teneur selon l’annexe 2 ch. II 18 de l’O du 31 août 2022 sur la protection des données, en vigueur depuis le 1<sup>er</sup> sept. 2023 ([RO 2022 568](https://fedlex.data.admin.ch/eli/oc/2022/568)).
[^13-5]: [RS 831.101](https://fedlex.data.admin.ch/eli/cc/63/1185_1183_1185)
[^13-6]: Introduit par le ch. I de l’O du 4 mai 2022, en vigueur depuis le 1<sup>er</sup> juin 2022 ([RO 2022 282](https://fedlex.data.admin.ch/eli/oc/2022/282)).
[^13-7]: [RS 172.210.10](https://fedlex.data.admin.ch/eli/cc/2008/719)

#### Art. 14

**Délai de conservation des données personnelles**

<sup>1</sup> Lorsqu’une personne n’est plus soumise à la présente ordonnance, ses données figurant dans les systèmes IAM et les services d’annuaires sont détruites au plus tard après deux ans.

<sup>2</sup> Les dispositions de l’art. 20, al. 2, LSI relatives à la destruction des données biométriques sont réservées.[^14-1]

[^14-1]: Introduit par le ch. I de l’O du 14 nov. 2018 ([RO 2018 4739](https://fedlex.data.admin.ch/eli/oc/2018/752)). Nouvelle teneur selon le ch. I de l’O du 8 nov. 2023, en vigueur depuis le 1<sup>er</sup> janv. 2024 ([RO 2023 738](https://fedlex.data.admin.ch/eli/oc/2023/738)).

## Section 5 Communication de données inhérente aux systèmes IAM

#### Art. 15

**Communication de données en cas de raccordement d’un système d’information à un système IAM**

<sup>1</sup> Si un système d’information auparavant autonome est raccordé à un système IAM et si la vérification de l’identité et de certains critères d’accès des personnes est confiée à ce dernier, les données personnelles correspondantes peuvent être importées dans le système IAM.

<sup>2</sup> Il faut gérer dans le système IAM, pour chaque système d’information en aval, une liste des données personnelles pouvant être communiquées à ce dernier en vertu de la présente ordonnance et des bases légales du système en aval.

#### Art. 16

**Communication de données en cas d’accès individuel**

Le système IAM authentifie les personnes, les machines ou les systèmes qui demandent l’accès à un système d’information en aval; il vérifie les données d’identification requises ainsi que d’autres caractéristiques et attestations nécessaires et transmet au système en aval le résultat de la vérification, avec les données d’identification, les caractéristiques et les attestations déterminées.

#### Art. 17

**Communication de données personnelles à un exploitant externe**

<sup>1</sup> Si un système d’information de la Confédération est géré par un exploitant externe sur mandat de celle-ci ou si les personnes visées à l’art. 8, al. 1 ou 3, let. a, doivent accéder à des systèmes d’information tiers, les données personnelles requises à cet effet peuvent être communiquées de manière automatisée à l’exploitant externe à partir des systèmes d’information concernant le personnel, de la base centralisée des identités ou des systèmes IAM.

<sup>2</sup> Pour ce faire, le service qui est responsable du système d’information confié à un exploitant externe ou qui a besoin d’accéder à un système d’information tiers établit une demande écrite précisant les personnes concernées et la transmet, par l’intermédiaire du conseiller à la protection des données compétent, à l’organe de la Confédération responsable du système d’information fournissant les données requises.

<sup>3</sup> Dans la demande, le service responsable au sens de l’al. 2 s’engage par écrit à respecter la législation fédérale sur la protection des données, à utiliser ces dernières exclusivement dans le but prévu et à les protéger conformément à l’état de la technique. Un droit d’inspection doit être accordé à l’organe de la Confédération responsable du système d’information fournissant les données requises.

<sup>4</sup> Les personnes concernées doivent être informées au préalable.

## Section 6 Mesures de protection des systèmes IAM et des services d’annuaires

[^sec6-1]

[^sec6-1]: Nouvelle teneur selon le ch. I de l’O du 8 nov. 2023, en vigueur depuis le 1<sup>er</sup> janv. 2024 ([RO 2023 738](https://fedlex.data.admin.ch/eli/oc/2023/738)).

#### Art. 18

**Exigences concernant la sécurité de l’information**

<sup>1</sup> Les exploitants internes et externes d’éléments d’un système IAM ou d’un service d’annuaires doivent avoir des instructions écrites sur la sécurité de l’information et la gestion des risques. En particulier, chaque organe responsable d’un système ou d’un service d’annuaires en vertu de la présente ordonnance établit un règlement de traitement conformément à l’art. 6 OPDo[^18-1].[^18-2]

<sup>2</sup> Les systèmes IAM et les services d’annuaires qui ne sont pas gérés par des organes visés à l’art. 2 ou sur mandat de ces derniers peuvent être raccordés à des systèmes IAM ou des services d’annuaires internes à l’administration fédérale uniquement s’ils respectent les exigences minimales concernant la sécurité de l’information.[^18-3]

<sup>3</sup> L’organe compétent ou le secteur TNI de la ChF peut demander le respect d’exigences plus élevées et des certifications précises afin d’accorder l’accès à certains systèmes d’information.

<sup>4</sup> Le secteur TNI de la ChF fixe dans des directives les exigences en matière de sécurité et les procédures à respecter.

[^18-1]: [RS 235.11](https://fedlex.data.admin.ch/eli/cc/2022/568)
[^18-2]: Nouvelle teneur selon le ch. I de l’O du 8 nov. 2023, en vigueur depuis le 1<sup>er</sup> janv. 2024 ([RO 2023 738](https://fedlex.data.admin.ch/eli/oc/2023/738)).
[^18-3]: Nouvelle teneur selon le ch. I de l’O du 8 nov. 2023, en vigueur depuis le 1<sup>er</sup> janv. 2024 ([RO 2023 738](https://fedlex.data.admin.ch/eli/oc/2023/738)).

#### Art. 19

**Traitement des données pour émettre des moyens d’identification électroniques**

<sup>1</sup> Pour vérifier l’identité de la personne demandeuse, l’émetteur d’un moyen d’identification peut exiger la présentation d’un passeport, d’une carte d’identité suisse ou d’une pièce d’identité reconnue pour entrer en Suisse.

<sup>2</sup> Il peut enregistrer une photo ou la signature de la personne ou utiliser des photos ou signatures figurant déjà dans le système pour les comparer avec la pièce d’identité.

<sup>3</sup> Les données utilisées pour l’identification sont enregistrées avec celles du moyen d’identification. Si les exigences en matière de sécurité propres au moyen d’identification l’exigent, une copie des pièces d’identité ayant servi à l’identification peut également être sauvegardée.

## Section 7 Interconnexion de systèmes IAM

#### Art. 20

**Système global IAM**[^20-1]

Les systèmes IAM de la Confédération peuvent être reliés entre eux et aux systèmes IAM externes visés à l’art. 21 pour former un système global.

[^20-1]: Nouvelle teneur selon le ch. I de l’O du 8 nov. 2023, en vigueur depuis le 1<sup>er</sup> janv. 2024 ([RO 2023 738](https://fedlex.data.admin.ch/eli/oc/2023/738)).

#### Art. 21

**Conditions pour le raccordement de systèmes IAM externes**

Les systèmes IAM externes ci-après peuvent être raccordés aux systèmes IAM de la Confédération afin que les personnes gérées dans ces systèmes externes puissent accéder aux ressources de celle-ci, pour autant que les conditions et les procédures énoncées aux art. 22 et 23 soient respectées et que leurs exploitants s’engagent à respecter la présente ordonnance et les prescriptions qui en découlent ou, dans le cas des cantons, que ces derniers garantissent une sécurité de l’information au moins équivalente:[^21-1]

- a.[^21-2] systèmes IAM comprenant des collaborateurs cantonaux et communaux au sens de l’art. 9, let. a, et systèmes IAM de la Principauté de Liechtenstein;
- b. systèmes IAM reconnus par le secteur TNI de la ChF qui sont destinés à la fédération d’identités dans le cadre de la cyberadministration;
- c. fédérations d’identités ou systèmes IAM étrangers dont le raccordement mutuel est prévu dans un traité international, ou
- d. registres des attributs qui mettent à disposition des données relatives à des fonctions professionnelles selon l’annexe, let. b.

[^21-1]: Nouvelle teneur selon le ch. I de l’O du 8 nov. 2023, en vigueur depuis le 1<sup>er</sup> janv. 2024 ([RO 2023 738](https://fedlex.data.admin.ch/eli/oc/2023/738)).
[^21-2]: Nouvelle teneur selon le ch. I de l’O du 8 nov. 2023, en vigueur depuis le 1<sup>er</sup> janv. 2024 ([RO 2023 738](https://fedlex.data.admin.ch/eli/oc/2023/738)).

#### Art. 22

**Demande de raccordement de systèmes IAM externes**

<sup>1</sup> Le service compétent adresse à l’organe de la Confédération responsable en vertu de l’art. 5 une demande de raccordement d’un système IAM externe à un système IAM de la Confédération.

<sup>2</sup>

La demande comprend notamment:

- a. le but du raccordement;
- b. les bases légales et les autres réglementations relatives au système à raccorder;
- c. une description technique du système à raccorder;
- d. les preuves du respect des exigences concernant la sécurité de l’information au sens de l’art. 18, al. 2 ou 3;
- e. l’avis favorable du département compétent;
- f. l’avis favorable d’au moins un service responsable d’un système en aval auquel le système IAM à raccorder permettra d’accéder.

#### Art. 23

**Décision concernant la demande de raccordement de systèmes IAM externes**

<sup>1</sup> L’organe de la Confédération responsable d’un système IAM de la Confédération est chargé de statuer sur la demande.

<sup>2</sup> Si le système IAM externe est relié aussi à d’autres systèmes IAM de la Confédération par le système auquel il est directement raccordé, l’approbation de la demande requiert l’accord de le secteur TNI de la ChF.

<sup>3</sup> L’organe de la Confédération responsable conclut la convention avec le service demandeur, informe le secteur TNI de la ChF et mandate le fournisseur de prestations concerné en vue du raccordement.

<sup>4</sup> Les demandes de modification ou de déconnexion sont traitées de manière analogue aux demandes de raccordement.

#### Art. 24

**Raccordement de systèmes IAM de la Confédération à des systèmes IAM externes**

<sup>1</sup>

Les systèmes IAM de la Confédération peuvent être raccordés en qualité de fournisseurs de données d’identification et d’authentification à un système IAM externe ou à une fédération d’identités externe aux conditions suivantes:

- a.[^24-1]

  le raccordement sert à octroyer aux personnes visées aux art. 8 ou 9 un accès:

  - 1\. à des systèmes d’information qui sont gérés par un exploitant externe sur mandat de la Confédération ou à des systèmes d’information tiers dont elles ont besoin pour exécuter leurs tâches légales, ou
  - 2\. à des systèmes d’information qui sont mis à disposition, pour l’exécution du droit cantonal, par les cantons et les communes ainsi que par des organisations et personnes de droit public ou de droit privé, tels que les applications de cyberadministration;

- b. la Confédération et l’exploitant du système d’information bénéficiaire concluent une convention régissant les relations sur le plan juridique, organisationnel et technique;
- c. la connexion est configurée de façon à permettre uniquement un accès aux systèmes d’information prédéfinis.

<sup>2</sup> Le secteur TNI de la ChF fixe dans des directives les exigences à respecter en matière de sécurité, en accord avec l’organe responsable du système IAM correspondant, et vérifie régulièrement si ces exigences sont satisfaites.

<sup>3</sup> Il est également possible de participer à une fédération internationale d’identités sur la base d’un traité international, à condition que le respect des exigences concernant la sécurité de l’information soit garanti.

[^24-1]: Nouvelle teneur selon le ch. I de l’O du 8 nov. 2023, en vigueur depuis le 1<sup>er</sup> janv. 2024 ([RO 2023 738](https://fedlex.data.admin.ch/eli/oc/2023/738)).

## Section 8 Établissement de procès-verbaux, de statistiques et d’une documentation

#### Art. 25

**Établissement de procès-verbaux par les systèmes IAM**

<sup>1</sup> Le système IAM consigne les authentifications et la publication de données d’identification dans un procès-verbal uniquement pour la durée et dans la mesure nécessaires à une exploitation sûre et ordonnée de ses propres systèmes et de ceux en aval.

<sup>2</sup> Les données des procès-verbaux de journalisation sont conservées séparément du système dans lequel les données personnelles sont traitées et sont détruites au plus tard après deux ans. Elles ne sont pas archivées.[^25-1]

<sup>3</sup> Demeurent réservés l’établissement d’un procès-verbal plus détaillé, une conservation plus longue ou un archivage des procès-verbaux concernant les accès à un système d’information précis en raison d’une base légale particulière.

[^25-1]: Nouvelle teneur selon l’annexe 2 ch. II 18 de l’O du 31 août 2022 sur la protection des données, en vigueur depuis le 1<sup>er</sup> sept. 2023 ([RO 2022 568](https://fedlex.data.admin.ch/eli/oc/2022/568)).

#### Art. 26

**Transmission des données des procès-verbaux établis par les systèmes IAM**

<sup>1</sup> Les exploitants des systèmes IAM de la Confédération peuvent communiquer au service responsable du système en aval concerné les données des procès-verbaux concernant les authentifications et la publication de données d’identification.

<sup>2</sup> À cet effet, une demande écrite mentionnant le but et les bases légales doit être adressée à l’organe responsable du système IAM par l’intermédiaire du conseiller à la protection des données compétent. La livraison des données peut faire l’objet d’une convention mentionnant les mêmes informations entre l’organe responsable du système en aval et l’exploitant du système IAM.

<sup>3</sup> En vertu des principes en vigueur pour l’acquisition de prestations informatiques au sein de la Confédération, la livraison des données peut être payante.

#### Art. 27

**Statistiques des systèmes IAM**

Des statistiques d’accès peuvent être établies pour les besoins du service responsable du système IAM ou du système d’information en aval. Les données personnelles doivent être anonymisées.

#### Art. 28

**Inventaire et documentation**

<sup>1</sup>

Tout organe responsable d’un système IAM, d’un service d’annuaires ou d’un autre système d’information en vertu de la présente ordonnance tient un inventaire:

- a. de ses systèmes IAM et services d’annuaires;
- b. des systèmes d’information à partir desquels des données sont obtenues automatiquement;
- c. des systèmes d’information auxquels des données sont transmises automatiquement;
- d. de tous les systèmes IAM auxquels est relié son propre système IAM.

<sup>2</sup> Les preuves et les documents importants, en particulier les demandes établies en vertu de la présente ordonnance, doivent être conservés au moins jusqu’à l’expiration de leur durée de validité.

## Section 9 Dispositions finales

#### Art. 29

**Exécution**

Le secteur TNI de la ChF édicte les directives administratives et techniques concernant la mise en place et l’exploitation des systèmes IAM de la Confédération.

#### Art. 30

**Abrogation d’un autre acte**

L’ordonnance du 6 décembre 2013 sur les services d’annuaires de la Confédération exploités par l’OFIT[^30-1] est abrogée.

[^30-1]: [[RO 2013 4553](https://fedlex.data.admin.ch/eli/oc/2013/811)]

#### Art. 31

**Entrée en vigueur**

La présente ordonnance entre en vigueur le 1<sup>er</sup> janvier 2017

Annexe[^t-1]

(art. 11 et 13, al. 1 et 2)

## Catégories de données

[^t-1]: Nouvelle teneur selon le ch. II de l’O du 8 nov. 2023, en vigueur depuis le 1<sup>er</sup> janv. 2024 ([RO 2023 738](https://fedlex.data.admin.ch/eli/oc/2023/738)).

Remarque préliminaire: pour la signification des astérisques (\*), voir l’art. 11, al. 4.

<table>
<tr><th></th><th>Services d’annuaires</th><th>Systèmes IAM avec des personnes au sens des art. 8 et 9, let. a</th><th>Systèmes IAM avec des personnes au sens de l’art. 9, let. b</th></tr>
<tr><td>a. Données relatives à la personne</td><td></td><td></td><td></td></tr>
<tr><td>1. Nom\*</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>2. Prénoms\*</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>3. Date de naissance</td><td></td><td>x</td><td>x</td></tr>
<tr><td>4. Lieu de naissance</td><td></td><td></td><td>x</td></tr>
<tr><td>5. Nationalité</td><td></td><td></td><td>x</td></tr>
<tr><td>6. Sexe</td><td></td><td>x</td><td>x</td></tr>
<tr><td>7. Civilité\*</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>8. Titre\*</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>9. Initiales\*</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>10. Identificateurs personnels locaux</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>11. Profession\*</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>12. Langue de correspondance\*</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>13. Caractéristiques biométriques personnelles particulières, en particulier scan de l’iris, rétine, scan des veines, empreinte digitale, empreinte palmaire, caractéristiques de la forme du visage et profil de la voix</td><td></td><td>x</td><td></td></tr>
<tr><td>14. Photo du visage</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>15. Numéro AVS</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>b. Données relatives au rapport avec l’employeur / le mandant</td><td></td><td></td><td></td></tr>
<tr><td>1. Rapports de travail (interne/externe)\*</td><td>x</td><td>x</td><td></td></tr>
<tr><td>2. Informations relatives à l’unité d’organisation et aux postes de travail\*</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>3. Futur rattachement à une unité d’organisation</td><td>x</td><td>x</td><td></td></tr>
<tr><td>4. Catégorie de personnel</td><td></td><td>x</td><td></td></tr>
<tr><td>5. Numéro personnel (y c. cantonal)</td><td>x</td><td>x</td><td></td></tr>
<tr><td>6. Fonction\*</td><td>x</td><td>x</td><td></td></tr>
<tr><td>7. Poste\*</td><td>x</td><td>x</td><td></td></tr>
<tr><td>8. Identification du système d’information du personnel (source)</td><td>x</td><td>x</td><td></td></tr>
<tr><td>9. Date d’entrée et date de départ</td><td>x</td><td>x</td><td></td></tr>
<tr><td>10. Numéro de pièce d’identité et/ou de badge</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>c. Données de contact</td><td></td><td></td><td></td></tr>
<tr><td>1. Lieu de travail et adresse postale professionnelle\*</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>2. Adresse postale privée</td><td></td><td></td><td>x</td></tr>
<tr><td>3. Numéro du bureau\*</td><td>x</td><td>x</td><td></td></tr>
<tr><td>4. Composantes de l’adresse professionnelle\* telles qu’adresse électronique\*, numéro de téléphone\*, numéro de fax\*, adresse VoIP\*</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>5. Composantes de l’adresse externe\* (pour les collaborateurs et les mandataires\*) ou de l’adresse privée</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>d. Données concernant les fonctions professionnelles</td><td></td><td></td><td></td></tr>
<tr><td>1. Indications issues des registres professionnels officiels (médecin, personne habilitée à dresser des actes authentiques, avocat, etc.)</td><td></td><td>x</td><td>x</td></tr>
<tr><td>2. Fonction selon le registre du commerce et d’autres registres des représentations</td><td></td><td>x</td><td>x</td></tr>
<tr><td>e. Données techniques</td><td></td><td></td><td></td></tr>
<tr><td>1. Appareils, raccordements, systèmes, applications, etc.</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>2. Composantes de l’adresse, numéros d’identification, etc.</td><td>x</td><td></td><td></td></tr>
<tr><td>3. Langue du système des appareils, des raccordements, etc.</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>4. Clés publiques des certificats numériques\*</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>5. Groupes d’autorisations</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>6. Noms pour la connexion aux systèmes informatiques</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>7. Mots de passe (sécurisés cryptographiquement)</td><td></td><td>x</td><td>x</td></tr>
<tr><td>8. Dernière ouverture de session</td><td></td><td>x</td><td>x</td></tr>
<tr><td>9. Échecs lors d’ouvertures de session</td><td></td><td>x</td><td>x</td></tr>
<tr><td>10. Statut (actif/passif)</td><td></td><td>x</td><td>x</td></tr>
<tr><td>11. Qualité de l’authentification</td><td></td><td>x</td><td>x</td></tr>
<tr><td>f. Données relatives au contrôle de sécurité relatif aux personnes, si celui-ci a abouti à une déclaration de sécurité sans réserve ou si l’autorité décisionnelle a rendu une décision positive</td><td></td><td></td><td></td></tr>
<tr><td>1. Degré de contrôle</td><td></td><td>x</td><td></td></tr>
<tr><td>2. Durée de validité de la déclaration de sécurité</td><td></td><td>x</td><td></td></tr>
</table>
