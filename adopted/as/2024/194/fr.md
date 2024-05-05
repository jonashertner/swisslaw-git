---
status: "beschlossen, noch nicht in Kraft"
reference: AS 2024 194
title: Ordonnance du DFI sur le dossier électronique du patient (ODEP-DFI)
language: fr
adopted: 2024-04-24
published: 2024-05-06
in_force: ["2024-06-01"]
url: "https://www.fedlex.admin.ch/eli/oc/2024/194/fr"
---

> Reproduction non officielle du Recueil officiel (RO). L’acte est publié mais n’est pas encore en vigueur ; seule la publication au RO fait foi (art. 15 LPubl, RS 170.512).

# Ordonnance du DFI sur le dossier électronique du patient

(ODEP-DFI)

Modification du 24 avril 2024

Le Département fédéral de l’intérieur (DFI)

arrête:

## I

L’ordonnance du DFI du 22 mars 2017 sur le dossier électronique du patient[^lvlI-1] est modifiée comme suit:

***Art. 8d* Disposition transitoire relative à la modification du 24 avril 2024**

Les communautés et communautés de référence ne sont pas tenues de mettre en œuvre la modification du 24 avril 2024 avant le 31 mai 2025.

[^lvlI-1]: [RS 816.111](https://fedlex.data.admin.ch/eli/cc/2017/205)

## II

<sup>1</sup> Les annexes 2 à 4 et 8[^lvlII-1] sont modifiées.

<sup>2</sup> Les annexes 5 et 6 sont remplacées par les versions ci-jointes.

[^lvlII-1]: Le contenu des présentes annexes est publié dans le RO et le RS uniquement sous forme de renvoi. Il peut être consulté à l’adresse suivante: [https://fedlex.data.admin.ch/eli/oc/2024/194](https://fedlex.data.admin.ch/eli/oc/2024/194) &gt; Informations générales &gt; Étendue de la publication &gt; Publication d’une partie d’un texte sous la forme d’un renvoi.

## III

La présente ordonnance entre en vigueur le 1<sup>er</sup> juin 2024.

<table>
<tr><td>24 avril 2024</td><td>Département fédéral de l’intérieur: Elisabeth Baume-Schneider</td></tr>
</table>

Annexe 5

(art. 5)

## Profils d’intégration

### 1 Profils d’intégration IHE

[^annex5-lvlu1-lvl1-1]

[^annex5-lvlu1-lvl1-1]: *Integrating the Healthcare Enterprise.*

<table>
<tr><th>Profil d’intégration</th><th>Document technique</th><th>Acteurs</th><th>Transactions</th><th>Adaptations nationales</th></tr>
<tr><td>ATNA</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Secure Application Secure Node Audit Record Repository</td><td>Authenticate Node [ITI‑19] Record Audit Event [ITI‑20]</td><td>Complément 1[^annex5-lvlu1-lvl1-2] à l’annexe 5 de l’ODEP‑DFI, édition 7</td></tr>
<tr><td></td><td>IHE IT Infrastructure Technical Framework Supplement, Add RESTful ATNA (Query and Feed), Revision 3.3, July 2, 2021</td><td>Audit Consumer Audit Record Repository</td><td>Retrieve ATNA Audit Event [ITI‑81]</td><td>Complément 2.2[^annex5-lvlu1-lvl1-3] à l’annexe 5 de l’ODEP‑DFI, profil d’intégration de l’Audit Trail Consumption (CH:ATC), édition 5</td></tr>
<tr><td>CT</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Time Client Time Server</td><td>Maintain Time [ITI‑1]</td><td>Non</td></tr>
<tr><td>HPD</td><td>IHE IT Infrastructure Technical Framework, Supplement Healthcare Provider Directory (HPD), Revision 1.8, August 28, 2020</td><td>Provider Information Source Provider Information Consumer Provider Information Directory</td><td>Provider Information Query [ITI‑58] Provider Information Feed [ITI‑59] Provider Information Delta Download (CH:PIDD)</td><td>Complément 1 à l’annexe 5 de l’ODEP‑DFI, édition 7</td></tr>
<tr><td>IUA</td><td>IHE IT Infrastructure Technical Framework, Supplement Internet User Authorization (IUA), Revision 2.2, June 17, 2022</td><td>Authorization Client Resource Server</td><td>Incorporate Authorization Token [ITI‑72]</td><td>Non</td></tr>
<tr><td>PCC</td><td>IHE Patient Care Coordination (PCC) Technical Framework, Volume 2, Revision 11.1, April 14, 2021</td><td>Content Creator Content Consumer</td><td></td><td>Non</td></tr>
<tr><td>PDQV3</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Patient Demographics Consumer Patient Demographics Supplier</td><td>Patient Demographics Query HL7 V3 [ITI‑47]</td><td>Complément 1 à l’annexe 5 de l’ODEP‑DFI, édition 7</td></tr>
<tr><td>PIXV3</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Patient Identity Source Patient Identifier Cross-reference Consumer Patient Identifier Cross-reference Manager</td><td>Patient Identity Feed HL7 V3 [ITI‑44] PIXV3 Query [ITI‑45] PIXV3 Update Notification [ITI‑46]</td><td>Complément 1 à l’annexe 5 de l’ODEP‑DFI, édition 7</td></tr>
<tr><td>RMU</td><td>IHE IT Infrastructure Technical Framework, Supplement Restricted Metadata Update (RMU), Revision 1.3, July 2, 2021</td><td>Update Initiator Update Responder</td><td>Restricted Update Document Set [ITI‑92]</td><td>Complément 1 à l’annexe 5 de l’ODEP‑DFI, édition 7</td></tr>
<tr><td>SVS</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Value Set Consumer Value Set Repository</td><td>Retrieve Value Set [ITI‑48]</td><td>Non</td></tr>
<tr><td>XCA</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Initiating Gateway Responding Gateway</td><td>Cross Gateway Query [ITI‑38] Cross Gateway Retrieve [ITI‑39]</td><td>Complément 1 à l’annexe 5 de l’ODEP‑DFI, édition 7</td></tr>
<tr><td>XCA-I</td><td>IHE Radiology Technical Framework, Volume 3 (RAD‑TF‑3), Cross-Transaction Specifications and Content Specifications, Revision 20.0, March 10, 2022</td><td>Initiating Imaging Gateway Responding Imaging Gateway</td><td>Cross Gateway Retrieve Image Document Set [RAD‑75]</td><td>Non</td></tr>
<tr><td>XCPD</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Initiating Gateway Responding Gateway</td><td>Cross Gateway Patient Discovery [ITI‑55]</td><td>Complément 1 à l’annexe 5 de l’ODEP‑DFI, édition 7</td></tr>
<tr><td>XDM</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Portable Media Creator Portable Media Importer</td><td>Distribute Document Set on Media [ITI‑32]</td><td>Non</td></tr>
<tr><td>XDS</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Document Consumer Document Source Document Repository Document Registry Patient Identity Source</td><td>Registry Stored Query [ITI‑18] Provide and Register Document Set‑b [ITI‑41] Register Document Set‑b [ITI‑42] Retrieve Document Set [ITI‑43] Patient Identity Feed HL7v3 [ITI‑44]</td><td>Complément 1 à l’annexe 5 de l’ODEP‑DFI, édition 7</td></tr>
<tr><td>XDS-I.b</td><td>IHE Radiology Technical Framework, Volume 3 (RAD‑TF‑3), Cross-Transaction Specifications and Content Specifications, Revision 20.0, March 10, 2022</td><td>Imaging Document Source Imaging Document Consumer</td><td>Provide & Register Imaging Document Set – MTOM/XOP [RAD‑68] Retrieve Imaging Document Set [RAD‑69]</td><td>Complément 1 à l’annexe 5 de l’ODEP‑DFI, édition 7</td></tr>
<tr><td>XDS Metadata Update</td><td>IHE IT Infrastructure Technical Framework, Supplement XDS Metadata Update, Revision 1.13, June 17, 2022</td><td>Document Administrator Document Registry</td><td>Update Document Set [ITI‑57]</td><td>Complément 1 à l’annexe 5 de l’ODEP‑DFI, édition 7</td></tr>
<tr><td>XUA</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>X-Service User X-Service Provider X-Assertion Provider User Authentication Provider</td><td>Authenticate User Get X-User Assertion Provide X-User Assertion [ITI‑40]</td><td>Complément 1 à l’annexe 5 de l’ODEP‑DFI, édition 7</td></tr>
</table>

[^annex5-lvlu1-lvl1-2]: Le contenu du complément 1 à l’annexe 5 peut être consulté à l’adresse suivante: [https://fedlex.data.admin.ch/eli/oc/2024/194](https://fedlex.data.admin.ch/eli/oc/2024/194) &gt; Informations générales &gt; Étendue de la publication &gt; Publication d’une partie d’un texte sous la forme d’un renvoi.
[^annex5-lvlu1-lvl1-3]: Le contenu du complément 2.2 à l’annexe 5 peut être consulté à l’adresse suivante: [https://fedlex.data.admin.ch/eli/oc/2024/194](https://fedlex.data.admin.ch/eli/oc/2024/194) &gt; Informations générales &gt; Étendue de la publication &gt; Publication d’une partie d’un texte sous la forme d’un renvoi.

### 2 Profils d’intégration nationaux

<table>
<tr><th>Profil d’intégration</th><th>Document technique</th><th>Acteurs</th><th>Transactions</th></tr>
<tr><td>CH:ADR</td><td>Complément 2.1[^annex5-lvlu1-lvl2-1] à l’annexe 5 de l’ODEP‑DFI, profil d’intégration de l’Authorization Decision Request (CH:ADR), édition 6</td><td>Authorization Decision Provider Authorization Decision Consumer</td><td>Authorization Decision Request (CH:ADR)</td></tr>
<tr><td>CH:ATC</td><td>Complément 2.2 à l’annexe 5 de l’ODEP‑DFI, profil d’intégration de l’Audit Trail Consumption (CH:ATC), édition 5</td><td>Patient Audit Consumer Patient Audit Record Repository</td><td>Retrieve ATNA Audit Event [ITI‑81]</td></tr>
<tr><td>CH:CPI</td><td>Complément 2.3[^annex5-lvlu1-lvl2-2] à l’annexe 5 de l’ODEP‑DFI, profil d’intégration du Community Portal Index (CH:CPI), édition 6</td><td>CH:CPI Consumer CH:CPI Provider</td><td>Community Information Query (CH:CIQ) Community Information Delta Download (CH:CIDD)</td></tr>
<tr><td>CH:PPQ</td><td>Complément 2.1 à l’annexe 5 de l’ODEP‑DFI, profil d’intégration du Privacy Policy Query (CH:PPQ), édition 6</td><td>Policy Source Policy Repository Policy Consumer</td><td>Privacy Policy Feed (CH:PPQ‑1) Privacy Policy Retrieve (CH:PPQ‑2)</td></tr>
</table>

[^annex5-lvlu1-lvl2-1]: Le contenu du complément 2.1 à l’annexe 5 peut être consulté à l’adresse suivante: [https://fedlex.data.admin.ch/eli/oc/2024/194](https://fedlex.data.admin.ch/eli/oc/2024/194) &gt; Informations générales &gt; Étendue de la publication &gt; Publication d’une partie d’un texte sous la forme d’un renvoi.
[^annex5-lvlu1-lvl2-2]: Le contenu du complément 2.3 à l’annexe 5 peut être consulté à l’adresse suivante: [https://fedlex.data.admin.ch/eli/oc/2024/194](https://fedlex.data.admin.ch/eli/oc/2024/194) &gt; Informations générales &gt; Étendue de la publication &gt; Publication d’une partie d’un texte sous la forme d’un renvoi.

Annexe 6

(art. 6)

## Évaluation et recherche

### 1 Critères généraux

- 1\.1

  Les métadonnées visées à l’annexe 3 doivent être utilisées pour:

  - a. le type organisationnel de l’établissement de santé (ch. 2.3);
  - b. la classe de document (ch. 2.5);
  - c. le type de document (ch. 2.6);
  - d. le rôle de la personne détentrice initiale (ch. 2.14).

- 1\.2 Des classes d’âge de cinq ans s’appliquent (0 à 4; 5 à 9; 10 à 14 … 95 à 99; 100 ans et plus).

### 2 Données à collecter par les communautés

- 2\.1

  Le nombre de documents élaborés au moyen du dossier électronique du patient, répertoriés par:

  - a. type organisationnel de l’établissement de santé;
  - b. classe de document;
  - c. type de document;
  - d. rôle de la personne détentrice initiale.

- 2\.2 Le nombre de documents enregistrés dans un format d’échange normalisé conformément à l’annexe 4, répertoriés par type d’établissement de santé.
- 2\.3

  Le nombre de documents par niveau de confidentialité au sens de l’art. 1 ODEP, répertoriés par:

  - a. type organisationnel de l’établissement de santé;
  - b. classe de documents;
  - c. type de document;
  - d. rôle de la personne détentrice initiale.

- 2\.4

  Le nombre de consultations de documents mis à disposition, répertoriées par:

  - a. nombre d’accès dans des situations d’urgence médicale;
  - b. type d’organisation de l’organisation de santé accédant aux documents;
  - c. rôle de la personne détentrice initiale accédant aux documents.

### 3 Données supplémentaires à collecter par les communautés de référence

- 3\.1

  Le nombre de personnes possédant un dossier électronique du patient, répertoriées par:

  - a. canton;
  - b. sexe et classe d’âge.

- 3\.2

  Le nombre de révocations du consentement de la tenue d’un dossier électronique du patient, répertoriées par:

  - a. canton;
  - b. sexe et classe d’âge.

- 3\.3

  Le nombre de modifications apportées aux droits d’accès, répertoriées par sexe et classe d’âge des patients concernant:

  - a. la définition des niveaux de confidentialité attribués aux nouvelles données médicales au sens de l’art. 4, let. a, ODEP;
  - b. le refus du patient d’accorder tout accès à son dossier électronique à certains professionnels de la santé au sens de l’art. 4, let. b, ODEP;
  - c. l’information de l’entrée de professionnels de la santé dans des groupes au sens de l’art. 4, let. c, ODEP;
  - d. la limitation de la durée des droits d’accès au sens de l’art. 4, let. c, ODEP;
  - e. l’extension du droit d’accès au niveau de confidentialité «restreint» en cas d’urgence médicale au sens de l’art. 4, let. e, ODEP;
  - f. le refus du patient de tout accès à son dossier électronique en cas d’urgence médicale au sens de l’art. 4, let. e, ODEP;
  - g. l’autorisation accordée par un patient à un professionnel de la santé affilié à sa communauté de référence de déléguer à d’autres professionnels de la santé ou groupes de professionnels de la santé les droits d’accès lui ayant été attribués au sens de l’art. 4, let. g, ODEP.

- 3\.4 Le nombre de patients n’ayant pas modifié leurs droits d’accès, répertoriés par sexe et classe d’âge.
- 3\.5 Le nombre de professionnels de la santé et de groupes de professionnels de la santé possédant des droits d’accès, répertoriés par dossier électronique du patient.
- 3\.6 Le nombre de personnes ayant désigné un représentant au sens de l’art. 4, let. f, ODEP, répertoriées par sexe et classe d’âge.
