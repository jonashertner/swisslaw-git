---
sr: "211.432.11"
title: Ordonnance technique du DFJP et du DDPS du 28 décembre 2012 concernant le registre foncier (OTRF)
short: OTRF
eli: "https://fedlex.data.admin.ch/eli/cc/2013/3"
language: fr
version: 2013-02-01
adopted: 2012-12-28
in_force: 2013-02-01
source: "https://fedlex.data.admin.ch/filestore/fedlex.data.admin.ch/eli/cc/2013/3/20130201/fr/xml/fedlex-data-admin-ch-eli-cc-2013-3-20130201-fr-xml-1.xml"
url: "https://www.fedlex.admin.ch/eli/cc/2013/3/20130201/fr"
---

> Reproduction non officielle de la version consolidée (Fedlex). Seule la publication au Recueil officiel fait foi (art. 15 LPubl, RS 170.512).

# Ordonnance technique du DFJP et du DDPS concernant le registre foncier

(OTRF)

du 28 décembre 2012 (Etat le 1<sup>er</sup> février 2013)

Le Département fédéral de justice et police (DFJP) et le Département fédéral de la défense, de la protection de la population et des sports (DDPS),

vu l’art. 949*a*, al. 3, du code civil (CC)[^ingress-1], vu les art. 19, al. 4, 40, al. 2, et 41, al. 1, de l’ordonnance du 23 septembre 2011 sur le registre foncier (ORF)[^ingress-2], vu l’art. 6*a*, al. 2, de l’ordonnance du 18 novembre 1992 sur la mensuration officielle (OMO)[^ingress-3],

arrêtent:

[^ingress-1]: [RS 210](https://fedlex.data.admin.ch/eli/cc/24/233_245_233)
[^ingress-2]: [RS 211.432.1](https://fedlex.data.admin.ch/eli/cc/2011/667)
[^ingress-3]: [RS 211.432.2](https://fedlex.data.admin.ch/eli/cc/1992/2446_2446_2446)

## Section 1 Objet

#### Art. 1

La présente ordonnance règle:

- a. le modèle de données pour le registre foncier (MD-eGRIS; annexe 1);
- b. le modèle de données pour l’échange des données entre le registre foncier et la mensuration officielle (MD-IMO-RF; annexe 2);
- c. l’interface permettant le prélèvement et l’échange des données du registre foncier (IPD-RF; annexe 3);
- d. l’interface pour l’échange des données entre la mensuration officielle et le registre foncier (IMO-RF);
- e. l’identification fédérale des immeubles (E-GRID);
- f. les formats de données des documents pour les communications et les transactions électroniques avec les offices du registre foncier;
- g. les procédures alternatives de transmission pour les communications et les transactions électroniques (annexe 4);
- h. La sauvegarde à long terme des données.

## Section 2 Attributions

#### Art. 2

**DFJP**

<sup>1</sup>

Le DFJP définit pour le registre foncier:

- a. le MD-eGRIS et les exigences auxquelles les données qu’il contient doivent satisfaire, ainsi que la date d’entrée en vigueur de chaque nouvelle version;
- b. le langage de description des données;
- c. l’IPD-RF et la date d’entrée en vigueur de chaque nouvelle version, ainsi que l’échéance des versions précédentes;
- d. le catalogue des critères applicables à la reconnaissance de plateformes alternatives pour les communications et les transactions électroniques avec l’office du registre foncier.

<sup>2</sup> Il reconnaît les plateformes alternatives pour les communications et les transactions électroniques avec l’office du registre foncier.

#### Art. 3

**DFJP et DDPS**

<sup>1</sup>

Le DFJP et le DDPS définissent pour l’échange des données entre la mensuration officielle et le registre foncier:

- a. le MD-IMO-RF ainsi que la date d’entrée en vigueur de chaque nouvelle version;
- b. le langage de description des données;
- c. l’IMO-RF.

<sup>2</sup> Ils définissent l’E-GRID.

#### Art. 4

**Office fédéral chargé du droit du registre foncier et du droit foncier**

<sup>1</sup> L’Office fédéral chargé du droit du registre foncier et du droit foncier (OFRF) veille à la diffusion du MD-eGRIS et de l’IPD-RF, ainsi qu’à celle de la documentation correspondante.

<sup>2</sup> Il élabore, avec la participation des cantons, des fabricants de systèmes et d’autres participants, une planification pour le développement continu du registre foncier informatisé ainsi que de son interconnexion avec d’autres systèmes. Il adapte annuellement cette planification.

#### Art. 5

**OFRF et Direction fédérale des mensurations cadastrales**

<sup>1</sup> L’OFRF et la Direction fédérale des mensurations cadastrales (D+M) veillent à la diffusion du MD-IMO-RF et de l’IMO-RF, ainsi qu’à celle de la documentation correspondante.

<sup>2</sup> Ils assurent, avec la participation des cantons et des fabricants de systèmes, le développement continu du MD-IMO-RF.

#### Art. 6

**Cantons**

<sup>1</sup> Les cantons intègrent dans leurs systèmes du registre foncier les éléments du MD‑eGRIS spécifiés dans l’annexe 1 comme étant obligatoires.

<sup>2</sup> Ils réalisent dans leurs systèmes du registre foncier les éléments de l’IPD-RF spécifiés comme étant obligatoires dans l’annexe 3.

<sup>3</sup> Ils garantissent l’échange des données entre le registre foncier et la mensuration officielle dans la dimension du MD-IMO-RF.

## Section 3 Langages de description des données

#### Art. 7

<sup>1</sup> Le MD-eGRIS ainsi que le MD-IMO-RF sont décrits dans le langage de description des données INTERLIS conformément à la norme suisse SN 612031[^7-1], édition 2006‑05.

<sup>2</sup> L’IPD-RF est décrit en XML.

[^7-1]: Cette norme peut être consultée gratuitement ou obtenue contre paiement auprès de l’Association suisse de normalisation (SNV), Sulzerallee 70, 8404 Winterthour; www.snv.ch.

## Section 4 Le modèle de données du registre foncier

#### Art. 8

<sup>1</sup> Le MD-eGRIS décrit les types et le degré de précision des données du registre foncier ainsi que leurs relations. Il sert de base à l’IPD-RF.

<sup>2</sup> Le degré de précision des éléments déclarés obligatoires dans l’annexe 1 du MD‑eGRIS ne peut être diminué et les extensions ne peuvent remplacer les éléments obligatoires existants.

<sup>3</sup>

Le MD-eGRIS se compose des modèles partiels suivants:

- a.

  modèles partiels obligatoires:

  - 1\. grand livre et tableaux de codes qui en font partie,
  - 2\. journal et tableaux de codes qui en font partie;

- b.

  modèles partiels facultatifs:

  - 1\. données de base des personnes,
  - 2\. notes;

<sup>4</sup> Les modèles partiels obligatoires du MD-eGRIS doivent être introduits et mis à disposition dans leur dernière version dans tous les registres fonciers dans un délai de 24 mois à compter de leur entrée en vigueur.

## Section 5 Modèle de données pour l’échange des données entre le registre foncier et la mensuration officielle

#### Art. 9

<sup>1</sup> Le MD-IMO-RF décrit les données qui doivent être échangées entre le registre foncier et la mensuration officielle.

<sup>2</sup> Le degré de précision du MD-IMO-RF ne peut être diminué. Les extensions ne peuvent pas remplacer les éléments existants.

<sup>3</sup> Les extensions ne peuvent contrevenir ni au modèle de données de la mensuration officielle (art. 6 OMO) ni au MD-eGRIS.

<sup>4</sup>

Le MD-IMO-RF est composé des modèles partiels suivants:

- a. relations de propriété;
- b. description de l’immeuble;
- c. tableau de mutation;
- d. objets liés à l’exécution.

<sup>5</sup> Il identifie les immeubles au moyen de l’E-GRID.

<sup>6</sup> Le MD-IMO-RF doit être introduit et mis à disposition dans sa dernière version dans tous les registres fonciers et dans la mensuration officielle dans un délai de 24 mois à compter de son entrée en vigueur.

## Section 6 L’interface pour le prélèvement et l’échange des données du registre foncier

#### Art. 10

<sup>1</sup>

L’IPD-RF permet:

- a. la livraison des données qui ont des effets juridiques ainsi que celles qui sont radiées du grand livre, du journal et des pièces justificatives, sous une forme structurée et lisible par une machine;
- b. l’établissement de l’index national des immeubles, conformément à l’art. 27, al. 3, ORF;
- c. l’exportation, en vue de leur sauvegarde à long terme par la Confédération, des données du grand livre qui ont des effets juridiques ainsi que de celles qui sont radiées;
- d. les communications et les transactions électroniques avec les offices du registre foncier.

<sup>2</sup> S’agissant de leur contenu et de leur degré de précision, les structures des données obéissent au MD-eGRIS.

<sup>3</sup> L’OFRF ou un organisme externe à l’administration qu’il a désigné peut poursuivre le développement de l’IPD-RF avec la participation des cantons. A cette fin, il peut constituer un groupe d’accompagnement composé de représentants des cantons, de la mensuration officielle, des fabricants des systèmes concernés et d’autres cercles spécialisés.

<sup>4</sup> Les fabricants de systèmes recueillent les propositions de modifications et établissent une liste épurée de celles-ci, qu’ils soumettent pour adoption au groupe d’accompagnement. Une fois les propositions adoptées installées et la nouvelle version de l’interface testée en pratique et reçue par le groupe d’accompagnement, la nouvelle version est soumise au DFJP pour approbation.

<sup>5</sup> L’IPD-RF doit être introduit et mis à disposition dans sa dernière version dans tous les systèmes de registre foncier dans un délai de 24 mois à compter de son entrée en vigueur.

## Section 7 L’interface pour l’échange de données entre la mensuration officielle et le registre foncier

#### Art. 11

**Définition**

L’IMO-RF est défini par le MD-IMO-RF et par le format de transfert résultant du MD-IMO-RF et de la SN 612031, édition 2006-05[^11-1].

[^11-1]: Cette norme peut être consultée gratuitement ou obtenue contre paiement auprès de l’Association suisse de normalisation (SNV), Sulzerallee 70, 8404 Winterthour, www.snv.ch.

#### Art. 12

**Utilisation**

<sup>1</sup> L’IMO-RF doit être introduit et mis à disposition dans sa dernière version dans tous les systèmes de registre foncier et dans la mensuration officielle dans un délai de 24 mois à compter de son entrée en vigueur.

<sup>2</sup> En lieu et place de l’introduction de l’IMO-RF, les cantons peuvent faire en sorte d’une autre manière que les données de la mensuration officielle définies dans le MD-IMO-RF soient intégralement transférées dans le registre foncier dans le cadre de l’exploitation régulière.

## Section 8 Exigences posées aux systèmes informatiques

#### Art. 13

**Exigences pour la tenue du registre foncier**

Les systèmes informatiques utilisés pour la tenue du registre foncier doivent être en mesure:

- a. de livrer les données au moyen de l’IMO-RF;
- b. de livrer, dans un fichier IPD-RF, les données du grand livre qui ont des effets juridiques et celles qui sont radiées afin de permettre leur sauvegarde à long terme;
- c. de produire et d’attribuer les identifiants obligatoires du MD-eGRIS.

#### Art. 14

**Tenue des données des systèmes du registre foncier**

<sup>1</sup> L’eGRISMD régit la tenue des données du registre foncier s’agissant de leur contenu, du degré de leur précision et de leur intégralité.

<sup>2</sup> Lors du passage du registre foncier sur papier au registre foncier informatisé, toutes les données ayant des effets juridiques des diverses rubriques doivent être reprises. Il n’est pas nécessaire de saisir les données radiées ainsi que les renvois aux pièces justificatives correspondantes.

#### Art. 15

**Exigences posées à la tenue du registre foncier et à la mensuration officielle**

Les systèmes informatiques utilisés pour la tenue du registre foncier et la mensuration officielle doivent être en mesure de prélever et de livrer les données dans la dimension et le degré de précision du MD-IMO-RF.

## Section 9 Identification fédérale des immeubles

#### Art. 16

**Principes**

<sup>1</sup> L’E-GRID est uniforme pour l’ensemble du pays, ne contient pas d’éléments classifiants et n’est attribué qu’une seule fois.

<sup>2</sup> Elle est l’identifiant des immeubles dans le modèle de données de la mensuration officielle, dans le MD-eGRIS et dans le MD-IMO-RF.

<sup>3</sup> Elle constitue la base de l’échange de données relatives aux immeubles.

<sup>4</sup> Elle doit pouvoir être utilisée en tant que clé de recherche dans les systèmes d’informations relatifs à des immeubles.

#### Art. 17

**Attribution aux immeubles**

<sup>1</sup> La mensuration officielle met en place l’E-GRID et l’attribue aux biens-fonds ainsi qu’aux droits distincts et permanents et aux mines différenciés par la surface. L’office du registre foncier le met en place et l’attribue aux autres immeubles. Les cantons peuvent édicter des dispositions différentes.

<sup>2</sup> En cas de modification à l’état ou au territoire des communes, tous les immeubles concernés conservent leur E-GRID.

<sup>3</sup> En cas de division d’un immeuble, une partie de celui-ci conserve, en règle générale, l’E-GRID existant. En cas de réunion de plusieurs immeubles, l’E-GRID de l’un des immeubles est, en règle générale, réutilisé pour le nouvel immeuble.

## Section 10 Formats de données des documents pour les communications et les transactions électroniques avec les offices du registre foncier

#### Art. 18

**Requêtes à l’office du registre foncier**

Les formats de données autorisés pour les requêtes à l’office du registre foncier sont:

- a. pour les réquisitions au registre foncier qui ne sont pas déjà contenues dans le justificatif relatif au titre: PDF munies de la signature électronique qualifiée conformément à l’art. 14, al. 2<sup>bis</sup>, du code des obligations (CO)[^18-1]; les données contenues dans la réquisition peuvent en outre être ajoutées en format XML;
- b. pour les justificatifs relatifs au titre passés en la forme authentique: les formats prévus par l’ordonnance du DFJP du 2 décembre 2011 relative aux formats reconnus dans le domaine des actes authentiques électroniques[^18-2];
- c. pour les justificatifs relatifs au titre en la forme écrite, y compris les annexes: PDF/A munis d’une signature électronique qualifiée conformément à l’art. 14, al. 2<sup>bis</sup>, CO;
- d. pour les demandes de délivrance d’un extrait du registre foncier ou d’un certificat d’inscription: PDF munies de la signature électronique qualifiée conformément à l’art. 14, al. 2<sup>bis</sup>, CO; demeurent réservées les requêtes émanant de participants authentifiés dans le cadre de procédures de transmission alternatives et de systèmes cantonaux d’informations du registre foncier.

[^18-1]: [RS 220](https://fedlex.data.admin.ch/eli/cc/27/317_321_377)
[^18-2]: [[RO 2011 6265](https://fedlex.data.admin.ch/eli/oc/2011/882). [RO 2013 2347](https://fedlex.data.admin.ch/eli/oc/2013/495)art. 20]. Voir actuellement l’O du DFJP du 8 déc. 2017 sur l’établissement d’actes authentiques électroniques et la légalisation électronique ([RS 211.435.11](https://fedlex.data.admin.ch/eli/cc/2018/30)).

#### Art. 19

**Notifications par l’office du registre foncier**

Les formats pour les notifications aux parties par l’office du registre foncier sont:

- a. pour les certificats d’inscription et pour les avis relatifs à une écriture du registre foncier: PDF/A ou XML; sur demande du destinataire, le document PDF/A peut être muni d’une signature électronique qualifiée conformément à l’art. 14, al. 2<sup>bis</sup>, CO[^19-1]; des données en format XML peuvent y être ajoutées;
- b. pour les fixations de délais ou les décisions de rejet: PDF/A munies d’une signature électronique qualifiée conformément à l’art. 14, al. 2<sup>bis</sup>, CO;
- c. pour les extraits du registre foncier: PDF/A ou XML; sur demande du destinataire, l’extrait peut être muni d’une signature électronique qualifiée conformément à l’art. 14, al. 2<sup>bis</sup>, CO; des données en format XML peuvent y être ajoutées.

[^19-1]: [RS 220](https://fedlex.data.admin.ch/eli/cc/27/317_321_377)

#### Art. 20

**Formats de données admis**

<sup>1</sup> Les versions admises du format de données PDF/A figurent dans l’annexe de l’ordonnance du DFJP du 2 décembre 2011 relative aux formats reconnus dans le domaine des actes authentiques électroniques[^20-1].

<sup>2</sup> Les formats PDF et XML peuvent être utilisés dans n’importe laquelle de leurs versions courantes.

[^20-1]: [[RO 2011 6265](https://fedlex.data.admin.ch/eli/oc/2011/882). [RO 2013 2347](https://fedlex.data.admin.ch/eli/oc/2013/495)art. 20]. Voir actuellement l’O du DFJP du 8 déc. 2017 sur l’établissement d’actes authentiques électroniques et la légalisation électronique ([RS 211.435.11](https://fedlex.data.admin.ch/eli/cc/2018/30)).

## Section 11 Procédures de transmission alternatives

#### Art. 21

**Reconnaissance de plateformes de messagerie alternatives**

Le DFJP reconnaît une plateforme de messagerie alternative pour les communications et les transactions avec l’office du registre foncier lorsque celle-ci:

- a. utilise pour la signature et le cryptage des certificats de machine (certificats SSL) émanant d’un fournisseur reconnu de services de certification (fournisseur reconnu) au sens de la loi du 19 décembre 2003 sur la signature électronique[^21-1];
- b. est en mesure de prouver quels documents ont été transmis ou utilisés pour la tâche spécifiée;
- c. protège les requêtes et les notifications de manière appropriée contre des accès non autorisés de tiers;
- d. est en mesure de communiquer conformément aux règles reconnues en matière de transmission sûre; dans ce cadre, l’état de la technique tel qu’il ressort en particulier des Standards eCH[^21-2] est pris en compte;
- e dispose de moyens ou de garantie financiers suffisants.

[^21-1]: [[RO 2004 5085](https://fedlex.data.admin.ch/eli/oc/2004/788), [2008 3437](https://fedlex.data.admin.ch/eli/oc/2008/447)ch. II 55. [RO 2016 4651](https://fedlex.data.admin.ch/eli/oc/2016/752)annexe ch. I]. Voir actuellement la LF du 18 mars 2016 ([RS 943.03](https://fedlex.data.admin.ch/eli/cc/2016/752)).
[^21-2]: www.eCH.ch

#### Art. 22

**Procédure de reconnaissance**

<sup>1</sup> Les demandes de reconnaissance doivent être adressées à l’OFRF.

<sup>2</sup>

La demande contient des informations concernant:

- a. le respect du catalogue de critères, soit en particulier les mesures techniques et d’organisation pour garantir l’intégrité des données, la protection des données et la sécurité des données durant la transmission et sur la plateforme;
- b. la traçabilité de la transmission;
- c. la disponibilité du système.

<sup>3</sup>

La demande doit être accompagnée:

- a. d’une description de la configuration du système;
- b. des résultats des tests effectués et des contrôles.

<sup>4</sup> L’OFRF peut faire appel à des experts externes à l’administration pour examiner si les conditions de la reconnaissance sont remplies. Les coûts sont mis à la charge du demandeur.

<sup>5</sup> Le DFJP retire la reconnaissance lorsqu’il constate que les conditions de reconnaissance ne sont plus remplies.

<sup>6</sup> L’émolument pour la décision est calculé en fonction du temps consacré; le tarif horaire est de 250 francs. Les dispositions de l’ordonnance générale du 8 septembre 2004 sur les émoluments[^22-1] sont applicables pour le surplus.

[^22-1]: [RS 172.041.1](https://fedlex.data.admin.ch/eli/cc/2004/677)

## Section 12 Sauvegarde à long terme

#### Art. 23

<sup>1</sup> Pour la sauvegarde à long terme, les cantons livrent à l’Office fédéral de la justice (OFJ) au moins une fois par année civile, à un moment qu’ils choisissent librement, l’intégralité du lot de données du grand livre qui ont des effets juridiques et de celles qui sont radiées, structurées conformément aux exigences de l’IPD-RF.

<sup>2</sup> La livraison comprend soit un seul fichier pour tout le canton, soit plusieurs fichiers relatifs, pour chacun d’entre eux, à une partie du canton (par ex. arrondissement du registre foncier).

<sup>3</sup> La transmission des fichiers a lieu au moyen d’une liaison sécurisée par un programme informatique mis à disposition par la Confédération, par un certificat de signature conforme à la loi du 19 décembre 2003 sur la signature électronique[^23-1] ainsi que par un certificat d’authentification du même fournisseur.

<sup>4</sup> Pour chacune des unités de son territoire, chaque canton désigne et annonce à l’OFJ une personne chargée de la sauvegarde à long terme des données, qui transmet à la Confédération le fichier qu’elle a signé et qui, par sa signature, confirme qu’il s’agit du lot de données du système du registre foncier à sauvegarder.

[^23-1]: [[RO 2004 5085](https://fedlex.data.admin.ch/eli/oc/2004/788), [2008 3437](https://fedlex.data.admin.ch/eli/oc/2008/447)ch. II 55. [RO 2016 4651](https://fedlex.data.admin.ch/eli/oc/2016/752)annexe ch. I]. Voir actuellement la LF du 18 mars 2016 ([RS 943.03](https://fedlex.data.admin.ch/eli/cc/2016/752)).

## Section 13 Exigences minimales relatives à la sécurité d’exploitation des systèmes du registre foncier

#### Art. 24

<sup>1</sup> En collaboration avec des représentants des cantons, le DFJP élabore, sur la base d’une évaluation méthodique du risque, un catalogue de critères contenant des mesures adéquates, efficaces et vérifiables sur le plan formel pour l’exploitation sûre d’un système du registre foncier.

<sup>2</sup> Le catalogue contient des exigences relatives aux personnes chargées de l’audit, à la fréquence de l’examen et à la procédure à suivre pour celui-ci.

<sup>3</sup> Il est mis à disposition des cantons à titre de recommandation.

## Section 14 Dispositions finales

#### Art. 25

**Abrogation du droit en vigueur**

L’ordonnance technique du DFJP et du DDPS du 6 juin 2007 concernant le registre foncier[^25-1] est abrogée.

[^25-1]: [[RO 2007 3353](https://fedlex.data.admin.ch/eli/oc/2007/408)]

#### Art. 26

**Disposition transitoire**

<sup>1</sup>

Les cantons mettent à disposition dans leurs systèmes informatiques au plus tard le 1<sup>er</sup> janvier 2014:

- a. pour le registre foncier et pour la mensuration officielle: l’IMO-RF ou une méthode équivalente de transfert des données et l’E-GRID;
- b. pour le registre foncier: les éléments obligatoires du MD-eGRIS et les parties renseignements/prélèvement des données et sauvegarde à long terme des données de l’IPD-RF.

<sup>2</sup> Le DFJP peut prolonger les délais dans des cas motivés.

#### Art. 27

**Entrée en vigueur**

La présente ordonnance entre en vigueur le 1<sup>er</sup> février 2013.

Annexe 1*[^t-1]*

(art. 1, let. a, 2, al. 1, let. a, et art. 8)

## Modèle de données pour le registre foncier MD-eGRIS, décrit en INTERLIS

[^t-1]: Cette annexe contient le modèle de données dans sa version MD-eGRIS11. Elle n’est pas publiée au RO. Conslutation: www.bj.admin.ch &gt; Thèmes &gt; Economie &gt; Registre foncier & registre des bateaux.

Annexe 2*[^t-2]*

(art. 1, let. b, 3, al. 1, let. a, et art. 9)

## Modèle de données pour la mensuration officielle et pour le registre foncier MD-IMO-RF, décrit en INTERLIS

[^t-2]: Cette annexe contient le modèle de données dans sa version MD-IMO-RF05. Elle n’est pas publié au RO. Consultation: www.bj.admin.ch &gt; Thèmes &gt; Economie &gt; Registre foncier & registre des bateaux.

Annexe 3*[^t-3]*

(art. 1, let. c, 2, al. 1, let. c, et art. 10)

## Interface pour le prélèvement et l’échange des données du registre foncier IPD-RF, décrit en XML

[^t-3]: Cette annexe contient l’interface dans sa version 2.0.5. Elle n’est pas publié au RO. Consultation: www.bj.admin.ch &gt; Thèmes &gt; Economie &gt; Registre foncier & registre des bateaux.

Annexe 4*[^t-4]*

(art. 1, let. g, et 2, al. 1, let. d)

## Catalogue de critères pour la reconnaissance de plateformes alternatives

[^t-4]: Cette annexe n’est pas publiée au RO. Consultation: www.bj.admin.ch &gt; Thèmes &gt; Economie &gt; Registre foncier & registre des bateaux.
