---
status: "beschlossen, noch nicht in Kraft"
reference: AS 2025 309
title: Ordonnance du DFI sur le dossier électronique du patient (ODEP-DFI)
language: fr
adopted: 2025-04-30
published: 2025-05-14
in_force: ["2025-06-01"]
url: "https://www.fedlex.admin.ch/eli/oc/2025/309/fr"
---

> Reproduction non officielle du Recueil officiel (RO). L’acte est publié mais n’est pas encore en vigueur ; seule la publication au RO fait foi (art. 15 LPubl, RS 170.512).

# Ordonnance du DFI sur le dossier électronique du patient

(ODEP-DFI)

Modification du 30 avril 2025

Le Département fédéral de l’intérieur (DFI)

arrête:

## I

L’ordonnance du DFI du 22 mars 2017 sur le dossier électronique du patient[^lvlI-1] est modifiée comme suit:

***Art. 8e* Disposition transitoire relative à la modification du 30 avril 2025**

Les éditeurs de moyens d’identification, les communautés et les communautés de référence ne sont pas tenus de mettre en œuvre la modification du 30 avril 2025 avant le 31 mai 2027.

[^lvlI-1]: [RS 816.111](https://fedlex.data.admin.ch/eli/cc/2017/205)

## II

<sup>1</sup> Les annexes 2 à 4 et 8[^lvlII-1] sont modifiées.

<sup>2</sup> L’annexe 5 est remplacée par la version ci-jointe.

[^lvlII-1]: Le contenu des présentes annexes est publié dans le RO et le RS uniquement sous forme de renvoi. Il peut être consulté à l’adresse suivante: [https://fedlex.data.admin.ch/eli/oc/2025/309](https://fedlex.data.admin.ch/eli/oc/2025/309) &gt; Informations générales &gt; Étendue de la publication &gt; Publication d’une partie d’un texte sous la forme d’un renvoi.

## III

La présente ordonnance entre en vigueur le 1<sup>er</sup> juin 2025.

<table>
<tr><td>30 avril 2025</td><td>Département fédéral de l’intérieur: Elisabeth Baume-Schneider</td></tr>
</table>

Annexe 5

(art. 5)

## Profils d’intégration

### 1 Profils d’intégration IHE

[^annex5-lvlu1-lvl1-1]

[^annex5-lvlu1-lvl1-1]: *Integrating the Healthcare Enterprise*.

<table>
<tr><th>Profil d’intégration</th><th>Document technique</th><th>Acteurs</th><th>Transactions</th><th>Adaptations nationales</th></tr>
<tr><td>ATNA</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Secure Application Secure Node Audit Record Repository</td><td>Authenticate Node [ITI‑19] Record Audit Event [ITI‑20]</td><td>Complément 1[^annex5-lvlu1-lvl1-2] à l’annexe 5 de l’ODEP‑DFI, édition 8 RESTful ATNA, CH EPR FHIR (R4), RESTful ATNA, Implementation Guide Version 4.0.1, 2024‑12‑18</td></tr>
<tr><td>CT</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Time Client Time Server</td><td>Maintain Time [ITI‑1]</td><td>Non</td></tr>
<tr><td>HPD</td><td>IHE IT Infrastructure Technical Framework, Supplement Healthcare Provider Directory (HPD), Revision 1.8, August 28, 2020</td><td>Provider Information Source Provider Information Consumer Provider Information Directory</td><td>Provider Information Query [ITI‑58] Provider Information Feed [ITI‑59] Provider Information Delta Download (CH:PIDD)</td><td>Complément 1 à l’annexe 5 de l’ODEP‑DFI, édition 8</td></tr>
<tr><td>IUA</td><td>IHE IT Infrastructure Technical Framework, Supplement Internet User Authorization (IUA), Revision 2.2, June 17, 2022</td><td>Authorization Server Authorization Client Resource Server</td><td>Get Access Token [ITI‑71] Incorporate Authorization Token [ITI‑72] Get Authorization Server Metadata [ITI‑103]</td><td>Internet User Authorization (IUA), CH EPR FHIR (R4), IUA, Implementation Guide Version 4.0.1, 2024‑12‑18</td></tr>
<tr><td>mCSD</td><td>IHE IT Infrastructure Technical Framework, Mobile Care Services Discovery (mCSD), Implementation Guide Version 3.8.0, 2022‑08‑12</td><td>Care Services Selective Consumer Care Services Selective SupplierCare Services SourceCare Services Directory</td><td>Find Matching Care Services [ITI‑90] Care Services Feed [CH:mCSD‑1]</td><td>Mobile Care Services Discovery (mCSD), CH EPR FHIR (R4), mCSD, Implementation Guide Version 4.0.1, 2024‑12‑18</td></tr>
<tr><td>MHD</td><td>IHE IT Infrastructure Technical Framework, Mobile access to Health Documents (MHD), Implementation Guide Version 4.2.2, 2024‑05‑18</td><td>Document Source Document Recipient Document Consumer Document Responder</td><td>Provide Document Bundle [ITI‑65] Find Document References [ITI‑67] Retrieve Document [ITI‑68] Update Document Metadata [CH:MHD‑1]</td><td>Mobile Access to Health Documents (MHD) with XDS on FHIR, CH EPR FHIR (R4), MHD, Implementation Guide Version 4.0.1, 2024‑12‑18</td></tr>
<tr><td>PCC</td><td>IHE Patient Care Coordination (PCC) Technical Framework, Volume 2, Revision 11.1, April 14, 2021</td><td>Content Creator Content Consumer</td><td></td><td>Complément 1 à l’annexe 5 de l’ODEP‑DFI, édition 8</td></tr>
<tr><td>PDQV3</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Patient Demographics Consumer Patient Demographics Supplier</td><td>Patient Demographics Query HL7 V3 [ITI‑47]</td><td>Complément 1 à l’annexe 5 de l’ODEP‑DFI, édition 8</td></tr>
<tr><td>PDQm</td><td>IHE IT Infrastructure Technical Framework, Patient Demographics Query for Mobile (PDQm), Implementation Guide Version 3.0.0, 2024‑02‑23</td><td>Patient Demographics Consumer Patient Demographics Supplier</td><td>Patient Demographics Match [ITI‑119]</td><td>Patient Demographics Query for Mobile (PDQm), CH EPR FHIR (R4), PDQm, Implementation Guide Version 4.0.1, 2024‑12‑18</td></tr>
<tr><td>PIXV3</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Patient Identity Source Patient Identifier Cross-reference Consumer Patient Identifier Cross-reference Manager</td><td>Patient Identity Feed HL7 V3 [ITI‑44] PIXV3 Query [ITI‑45]</td><td>Complément 1 à l’annexe 5 de l’ODEP‑DFI, édition 8</td></tr>
<tr><td>PIXm</td><td>IHE IT Infrastructure Technical Framework, Patient Identifier Cross-referencing for Mobile (PIXm), Implementation Guide Version 3.0.4, 2024-02-23</td><td>Patient Identity Source Patient Identifier Cross-reference Consumer Patient Identifier Cross-reference Manager</td><td>Mobile Patient Identifier Cross-reference Query [ITI‑83] Patient Identity Feed FHIR [ITI‑104]</td><td>Patient Identifier Cross-referencing for mobile (PIXm), CH EPR FHIR (R4), PIXm, Implementation Guide Version 4.0.1, 2024‑12‑18</td></tr>
<tr><td>RMU</td><td>IHE IT Infrastructure Technical Framework, Supplement Restricted Metadata Update (RMU), Revision 1.3, July 2, 2021</td><td>Update Initiator Update Responder</td><td>Restricted Update Document Set [ITI‑92]</td><td>Complément 1 à l’annexe 5 de l’ODEP‑DFI, édition 8</td></tr>
<tr><td>SVS</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Value Set Consumer Value Set Repository</td><td>Retrieve Value Set [ITI‑48]</td><td>Non</td></tr>
<tr><td>XCA</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Initiating Gateway Responding Gateway</td><td>Cross Gateway Query [ITI‑38] Cross Gateway Retrieve [ITI‑39]</td><td>Complément 1 à l’annexe 5 de l’ODEP‑DFI, édition 8</td></tr>
<tr><td>XCA-I</td><td>IHE Radiology Technical Framework, Volume 3 (RAD‑TF‑3), Cross-Transaction Specifications and Content Specifications, Revision 22.0, June 25, 2024</td><td>Initiating Imaging Gateway Responding Imaging Gateway</td><td>Cross Gateway Retrieve Image Document Set [RAD‑75]</td><td>Non</td></tr>
<tr><td>XCPD</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Initiating Gateway Responding Gateway</td><td>Cross Gateway Patient Discovery [ITI‑55]</td><td>Complément 1 à l’annexe 5 de l’ODEP‑DFI, édition 8</td></tr>
<tr><td>XDM</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Portable Media Creator Portable Media Importer</td><td>Distribute Document Set on Media [ITI‑32]</td><td>Non</td></tr>
<tr><td>XDS</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Document Consumer Document Source Document Repository Document Registry Patient Identity Source</td><td>Registry Stored Query [ITI‑18] Provide and Register Document Set-b [ITI‑41] Register Document Set‑b [ITI‑42] Retrieve Document Set [ITI‑43] Patient Identity Feed HL7v3 [ITI‑44]</td><td>Complément 1 à l’annexe 5 de l’ODEP‑DFI, édition 8</td></tr>
<tr><td>XDS-I.b</td><td>IHE Radiology Technical Framework, Volume 3 (RAD‑TF‑3), Cross-Transaction Specifications and Content Specifications, Revision 22.0, June 25, 2024</td><td>Imaging Document Source Imaging Document Consumer</td><td>Provide & Register Imaging Document Set – MTOM/XOP [RAD‑68] Retrieve Imaging Document Set [RAD‑69]</td><td>Complément 1 à l’annexe 5 de l’ODEP‑DFI, édition 8</td></tr>
<tr><td>XDS Metadata Update</td><td>IHE IT Infrastructure Technical Framework, Supplement XDS Metadata Update, Revision 1.13, June 17, 2022</td><td>Document Administrator Document Registry</td><td>Update Document Set [ITI‑57]</td><td>Complément 1 à l’annexe 5 de l’ODEP‑DFI, édition 8</td></tr>
<tr><td>XUA</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>X-Service User X-Service Provider X-Assertion Provider User Authentication Provider</td><td>Authenticate User Get X-User Assertion Provide X-User Assertion [ITI‑40]</td><td>Complément 1 à l’annexe 5 de l’ODEP‑DFI, édition 8</td></tr>
</table>

[^annex5-lvlu1-lvl1-2]: Le contenu du présent complément peut être consulté à l’adresse suivante: [https://fedlex.data.admin.ch/eli/oc/2025/309](https://fedlex.data.admin.ch/eli/oc/2025/309) &gt; Informations générales &gt; Étendue de la publication &gt; Publication d’une partie d’un texte sous la forme d’un renvoi.

### 2 Profils d’intégration nationaux

<table>
<tr><th>Profil d’intégration</th><th>Document technique</th><th>Acteurs</th><th>Transactions</th></tr>
<tr><td>CH:ADR</td><td>Complément 2.1[^annex5-lvlu1-lvl2-1] à l’annexe 5 de l’ODEP-DFI, profil d’intégration de l’Authorization Decision Request (CH:ADR), édition 7</td><td>Authorization Decision Provider Authorization Decision Consumer</td><td>Authorization Decision Request (CH:ADR)</td></tr>
<tr><td>CH:ATC</td><td>Audit Trail Consumption (CH:ATC), CH ATC, Implementation Guide Version 3.3.0, 2024‑12‑18</td><td>Patient Audit Consumer Patient Audit Record Repository</td><td>Retrieve ATNA Audit Event [ITI‑81]</td></tr>
<tr><td>CH:CPI</td><td>Complément 2.3[^annex5-lvlu1-lvl2-2] à l’annexe 5 de l’ODEP-DFI, profil d’intégration du Community Portal Index (CH:CPI), édition 7</td><td>CH:CPI Consumer CH:CPI Provider</td><td>Community Information Query (CH:CIQ) Community Information Delta Download (CH:CIDD)</td></tr>
<tr><td>CH:PPQ</td><td>Complément 2.1 à l’annexe 5 de l’ODEP-DFI, profil d’intégration du Privacy Policy Query (CH:PPQ), édition 7</td><td>Policy Source Policy Repository Policy Consumer</td><td>Privacy Policy Feed (CH:PPQ‑1) Privacy Policy Retrieve (CH:PPQ‑2)</td></tr>
<tr><td>CH:PPQm</td><td>Privacy Policy Query for Mobile (CH:PPQm), CH EPR FHIR (R4), CH:PPQm, Implementation Guide Version 4.0.1, 2024‑12‑18</td><td>Policy Repository Policy Source Policy Consumer</td><td>Mobile Privacy Policy Feed (PPQ‑3) Mobile Privacy Policy Bundle Feed (PPQ‑4) Mobile Privacy Policy Retrieve (PPQ‑5)</td></tr>
</table>

[^annex5-lvlu1-lvl2-1]: Le contenu du présent complément peut être consulté à l’adresse suivante: [https://fedlex.data.admin.ch/eli/oc/2025/309](https://fedlex.data.admin.ch/eli/oc/2025/309) &gt; Informations générales &gt; Étendue de la publication &gt; Publication d’une partie d’un texte sous la forme d’un renvoi.
[^annex5-lvlu1-lvl2-2]: Le contenu du présent complément peut être consulté à l’adresse suivante: [https://fedlex.data.admin.ch/eli/oc/2025/309](https://fedlex.data.admin.ch/eli/oc/2025/309) &gt; Informations générales &gt; Étendue de la publication &gt; Publication d’une partie d’un texte sous la forme d’un renvoi.
