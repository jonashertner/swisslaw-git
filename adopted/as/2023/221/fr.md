---
status: "beschlossen, noch nicht in Kraft"
reference: AS 2023 221
title: Ordonnance du DFI sur le dossier électronique du patient (ODEP-DFI)
language: fr
adopted: 2023-05-04
published: 2023-05-09
in_force: ["2023-06-01"]
url: "https://www.fedlex.admin.ch/eli/oc/2023/221/fr"
---

> Reproduction non officielle du Recueil officiel (RO). L’acte est publié mais n’est pas encore en vigueur ; seule la publication au RO fait foi (art. 15 LPubl, RS 170.512).

# Ordonnance du DFI sur le dossier électronique du patient

(ODEP-DFI)

Modification du 4 mai 2023

Le Département fédéral de l’intérieur (DFI)

arrête:

## I

L’ordonnance du DFI du 22 mars 2017 sur le dossier électronique du patient[^lvlI-1] est modifiée comme suit:

*Art. 8c* Disposition transitoire relative à la modification du 4 mai 2023

Les communautés et communautés de référence ne sont pas tenues de mettre en œuvre la modification du 4 mai 2023 avant le 31 mai 2024.

[^lvlI-1]: [RS 816.111](https://fedlex.data.admin.ch/eli/cc/2017/205)

## II

<sup>1</sup> Les annexes 2 à 4, 8 et 9[^lvlII-1] sont modifiées.

<sup>2</sup> L’annexe 5 est remplacée par la version ci-jointe.

[^lvlII-1]: Le contenu des présentes annexes est publié dans le RO et le RS uniquement sous forme de renvoi. Il peut être consulté à l’adresse suivante: [https://fedlex.data.admin.ch/eli/oc/2023/221](https://fedlex.data.admin.ch/eli/oc/2023/221) &gt; Informations générales &gt; Étendue de la publication &gt; Publication d’une partie d’un texte sous la forme d’un renvoi.

## III

La présente ordonnance entre en vigueur le 1<sup>er</sup> juin 2023.

<table>
<tr><td>4 mai 2023</td><td>Département fédéral de l’intérieur: Alain Berset</td></tr>
</table>

Annexe 5

(art. 5)

## Profils d’intégration

### 1 Profils d’intégration IHE

[^annex5-lvlu1-lvl1-1]

[^annex5-lvlu1-lvl1-1]: *Integrating the Healthcare Enterprise*

<table>
<tr><th>Profil d’intégration</th><th>Document technique</th><th>Acteurs</th><th>Transactions</th><th>Adaptations nationales</th></tr>
<tr><td>ATNA</td><td>IHE IT Infrastructure Technical Framework, Volume 2a (ITI TF-2a), Revision 15.0, July 24, 2018</td><td>Secure Application Secure Node Audit Record Repository</td><td>Authenticate Node [ITI-19] Record Audit Event [ITI-20]</td><td>Complément 1[^annex5-lvlu1-lvl1-2] à l’annexe 5 de l’ODEP-DFI, édition 6</td></tr>
<tr><td></td><td>IHE IT Infrastructure Technical Framework Supplement, Add RESTful ATNA (Query and Feed), Revision 3.3, July 2, 2021</td><td>Audit Consumer Audit Record Repository</td><td>Retrieve ATNA Audit Event [ITI-81]</td><td>Complément 2.2[^annex5-lvlu1-lvl1-3] à l’annexe 5 de l’ODEP-DFI, profil d’intégration de l’Audit Trail Consumption (CH:ATC), édition 4</td></tr>
<tr><td>CT</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Time Client Time Server</td><td>Maintain Time [ITI‑1]</td><td>Non</td></tr>
<tr><td>HPD</td><td>IHE IT Infrastructure Technical Framework, Supplement Healthcare Provider Directory (HPD), Revision 1.8, August 28, 2020</td><td>Provider Information Source Provider Information Consumer Provider Information Directory</td><td>Provider Information Query [ITI‑58] Provider Information Feed [ITI‑59] Provider Information Delta Download (CH:PIDD)</td><td>Complément 1 à l’annexe 5 de l’ODEP-DFI, édition 6</td></tr>
<tr><td>IUA</td><td>IHE IT Infrastructure Technical Framework, Supplement Internet User Authorization (IUA), Revision 2.2, June 17, 2022</td><td>Authorization Client Resource Server</td><td>Incorporate Authorization Token [ITI-72]</td><td>Non</td></tr>
<tr><td>PDQV3</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Patient Demographics Consumer Patient Demographics Supplier</td><td>Patient Demographics Query HL7 V3 [ITI-47]</td><td>Complément 1 à l’annexe 5 de l’ODEP-DFI, édition 6</td></tr>
<tr><td>PIXV3</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Patient Identity Source Patient Identifier Cross- reference Consumer Patient Identifier Cross-reference Manager</td><td>Patient Identity Feed HL7 V3 [ITI‑44] PIXV3 Query [ITI‑45] PIXV3 Update Notification [ITI-46]</td><td>Complément 1 à l’annexe 5 de l’ODEP-DFI, édition 6</td></tr>
<tr><td>RMU</td><td>IHE IT Infrastructure Technical Framework, Supplement Restricted Metadata Update (RMU), Revision 1.3, July 2, 2021</td><td>Update Initiator Update Responder</td><td>Restricted Update Document Set [ITI‑92]</td><td>Complément 1 à l’annexe 5 de l’ODEP-DFI, édition 6</td></tr>
<tr><td>SVS</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Value Set Consumer Value Set Repository</td><td>Retrieve Value Set [ITI-48]</td><td>Non</td></tr>
<tr><td>XCA</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Initiating Gateway Responding Gateway</td><td>Cross Gateway Query [ITI-38] Cross Gateway Retrieve [ITI-39]</td><td>Complément 1 à l’annexe 5 de l’ODEP-DFI, édition 6</td></tr>
<tr><td>XCA-I</td><td>IHE Radiology Technical Framework, Volume 3 (RAD-TF-3), Cross-Transaction Specifications and Content Specifications, Revision 20.0, March 10, 2022</td><td>Initiating Imaging Gateway Responding Imaging Gateway</td><td>Cross Gateway Retrieve Image Document Set [RAD-75]</td><td>Non</td></tr>
<tr><td>XCPD</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Initiating Gateway Responding Gateway</td><td>Cross Gateway Patient Discovery [ITI-55]</td><td>Complément 1 à l’annexe 5 de l’ODEP-DFI, édition 6</td></tr>
<tr><td>XDM</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Portable Media Creator Portable Media Importer</td><td>Distribute Document Set on Media [ITI-32]</td><td>Non</td></tr>
<tr><td>XDS</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Document Consumer Document Source Document Repository Document Registry Patient Identity Source</td><td>Registry Stored Query [ITI-18] Provide and Register Document Set-b [ITI-41] Register Document Set-b [ITI-42] Retrieve Document Set [ITI-43] Patient Identity Feed HL7v3 [ITI-44]</td><td>Complément 1 à l’annexe 5 de l’ODEP-DFI, édition 6</td></tr>
<tr><td>XDS-I.b</td><td>IHE Radiology Technical Framework, Volume 3 (RAD-TF-3), Cross-Transaction Specifications and Content Specifications, Revision 20.0, March 10, 2022</td><td>Imaging Document Source Imaging Document Consumer</td><td>Provide & Register Imaging Document Set – MTOM/XOP [RAD-68] Retrieve Imaging Document Set [RAD-69]</td><td>Complément 1 à l’annexe 5 de l’ODEP-DFI, édition 6</td></tr>
<tr><td>XDS Metadata Update</td><td>IHE IT Infrastructure Technical Framework, Supplement XDS Metadata Update, Revision 1.13, June 17, 2022</td><td>Document Administrator Document Registry</td><td>Update Document Set [ITI-57]</td><td>Complément 1 à l’annexe 5 de l’ODEP-DFI, édition 6</td></tr>
<tr><td>XUA</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>X-Service User X-Service Provider X-Assertion Provider User Authentication Provider</td><td>Authenticate User Get X-User Assertion Provide X-User Assertion [ITI-40]</td><td>Complément 1 à l’annexe 5 de l’ODEP-DFI, édition 6</td></tr>
</table>

[^annex5-lvlu1-lvl1-2]: Le contenu du complément 1 à l’annexe 5 peut être consulté à l’adresse suivante: [https://fedlex.data.admin.ch/eli/oc/2023/221](https://fedlex.data.admin.ch/eli/oc/2023/221) &gt; Informations générales &gt; Étendue de la publication &gt; Publication d’une partie d’un texte sous la forme d’un renvoi.
[^annex5-lvlu1-lvl1-3]: Le contenu du complément 2.2 à l’annexe 5 peut être consulté à l’adresse suivante: [https://fedlex.data.admin.ch/eli/oc/2023/221](https://fedlex.data.admin.ch/eli/oc/2023/221) &gt; Informations générales &gt; Étendue de la publication &gt; Publication d’une partie d’un texte sous la forme d’un renvoi.

### 2 Profils d’intégration nationaux

<table>
<tr><th>Profil d’intégration</th><th>Document technique</th><th>Acteurs</th><th>Transactions</th></tr>
<tr><td>CH:ADR</td><td>Complément 2.1[^annex5-lvlu1-lvl2-1] à l’annexe 5 de l’ODEP‑DFI, profil d’intégration de l’Authorization Decision Request (CH:ADR), édition 5</td><td>Authorization Decision Provider Authorization Decision Consumer</td><td>Authorization Decision Request (CH:ADR)</td></tr>
<tr><td>CH:ATC</td><td>Complément 2.2 à l’annexe 5 de l’ODEP‑DFI, profil d’intégration de l’Audit Trail Consumption (CH:ATC), édition 4</td><td>Patient Audit Consumer Patient Audit Record Repository</td><td>Retrieve ATNA Audit Event [ITI‑81]</td></tr>
<tr><td>CH:CPI</td><td>Complément 2.3[^annex5-lvlu1-lvl2-2] à l’annexe 5 de l’ODEP‑DFI, profil d’intégration du Community Portal Index (CH:CPI), édition 5</td><td>CH:CPI Consumer CH:CPI Provider</td><td>Community Information Query (CH:CIQ) Community Information Delta Download (CH:CIDD)</td></tr>
<tr><td>CH:PPQ</td><td>Complément 2.1 à l’annexe 5 de l’ODEP‑DFI, profil d’intégration du Privacy Policy Query (CH:PPQ), édition 5</td><td>Policy Source Policy Repository Policy Consumer</td><td>Privacy Policy Feed (CH:PPQ-1) Privacy Policy Retrieve (CH:PPQ‑2)</td></tr>
</table>

[^annex5-lvlu1-lvl2-1]: Le contenu du complément 2.1 à l’annexe 5 peut être consulté à l’adresse suivante: [https://fedlex.data.admin.ch/eli/oc/2023/221](https://fedlex.data.admin.ch/eli/oc/2023/221) &gt; Informations générales &gt; Étendue de la publication &gt; Publication d’une partie d’un texte sous la forme d’un renvoi.
[^annex5-lvlu1-lvl2-2]: Le contenu du complément 2.3 à l’annexe 5 peut être consulté à l’adresse suivante: [https://fedlex.data.admin.ch/eli/oc/2023/221](https://fedlex.data.admin.ch/eli/oc/2023/221) &gt; Informations générales &gt; Étendue de la publication &gt; Publication d’une partie d’un texte sous la forme d’un renvoi.
