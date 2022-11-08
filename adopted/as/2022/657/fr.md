---
status: "beschlossen, noch nicht in Kraft"
reference: AS 2022 657
title: Ordonnance du DFI sur le dossier électronique du patient (ODEP-DFI)
language: fr
adopted: 2022-10-28
published: 2022-11-09
in_force: ["2022-12-01"]
url: "https://www.fedlex.admin.ch/eli/oc/2022/657/fr"
---

> Reproduction non officielle du Recueil officiel (RO). L’acte est publié mais n’est pas encore en vigueur ; seule la publication au RO fait foi (art. 15 LPubl, RS 170.512).

# Ordonnance du DFI sur le dossier électronique du patient

(ODEP-DFI)

Modification du 28 octobre 2022

Le Département fédéral de l’intérieur (DFI)

arrête:

## I

L’ordonnance du DFI du 22 mars 2017 sur le dossier électronique du patient[^lvlI-1] est modifiée comme suit:

*Art. 8b* Disposition transitoire relative à la modification du 28 octobre 2022

Les communautés et communautés de référence doivent mettre en œuvre la modification du 28 octobre 2022 le 31 décembre 2023 au plus tard.

[^lvlI-1]: [RS 816.111](https://fedlex.data.admin.ch/eli/cc/2017/205)

## II

<sup>1</sup> Les annexes 2 à 4[^lvlII-1] sont modifiés.

<sup>2</sup> L’annexe 5 est remplacée par la version ci-jointe.

[^lvlII-1]: Le contenu des présentes annexes est publié dans le RO et le RS uniquement sous forme de renvoi. Il peut être consulté à l’adresse suivante: [https://fedlex.data.admin.ch/eli/oc/2022/657](https://fedlex.data.admin.ch/eli/oc/2022/657) &gt; Informations générales &gt; Étendue de la publication &gt; Publication d’une partie d’un texte sous la forme d’un renvoi.

## III

La présente ordonnance entre en vigueur le 1<sup>er</sup> décembre 2022.

<table>
<tr><td>28 octobre 2022</td><td>Département fédéral de l’intérieur: Alain Berset</td></tr>
</table>

Annexe 5

(art. 5)

## Profils d’intégration

### 1 Profils d’intégration IHE

[^annex5-lvlu1-lvl1-1]

[^annex5-lvlu1-lvl1-1]: Integrating the Healthcare Enterprise

<table>
<tr><th>Profil d’intégration</th><th>Document technique</th><th>Transactions</th><th>Adaptations nationales</th></tr>
<tr><td>ATNA</td><td>IHE IT Infrastructure Technical Framework, Volume 2a (ITI TF-2a), Revision 15.0, July 24, 2018</td><td>Authenticate Node [ITI-19] Record Audit Event [ITI-20]</td><td>Complément 1[^annex5-lvlu1-lvl1-2] à l’annexe 5 de l’ODEP-DFI, édition 5</td></tr>
<tr><td>CT</td><td>IHE IT Infrastructure Technical Framework, Volume 2a (ITI TF-2a), Revision 15.0, July 24, 2018</td><td>Maintain Time [ITI-1]</td><td>Non</td></tr>
<tr><td>HPD</td><td>IHE IT Infrastructure Technical Framework, Supplement Healthcare Provider Directory (HPD), Revision 1.7, July 24, 2018</td><td>Provider Information Query [ITI-58] Provider Information Feed [ITI-59] Provider Information Delta Download (CH:PIDD)</td><td>Complément 1 à l’annexe 5 de l’ODEP‑DFI, édition 5</td></tr>
<tr><td>PDQv3</td><td>IHE IT Infrastructure Technical Framework, Volume 2b (ITI TF-2b), Revision 15.0, July 24, 2018</td><td>Patient Demographics Query HL7 V3 [ITI-47]</td><td>Complément 1 à l’annexe 5 de l’ODEP‑DFI, édition 5</td></tr>
<tr><td>PIXv3</td><td>IHE IT Infrastructure Technical Framework, Volume 2b (ITI TF-2b), Revision 15.0, July 24, 2018</td><td>Patient Identity Feed HL7 V3 [ITI-44] PIXV3 Query [ITI-45] PIXV3 Update Notification [ITI-46]</td><td>Complément 1 à l’annexe 5 de l’ODEP‑DFI, édition 5</td></tr>
<tr><td>RMU</td><td>IHE IT Infrastructure Technical Framework, Supplement Restricted Metadata Update, Revision 1.0, May 23, 2018</td><td>Restricted Update Document Set [ITI‑92]</td><td>Complément 1 à l’annexe 5 de l’ODEP‑DFI, édition 5</td></tr>
<tr><td>SVS</td><td>IHE IT Infrastructure Technical Framework, Volume 2b (ITI TF-2b), Revision 15.0, July 24, 2018</td><td>Retrieve Value Set [ITI-48]</td><td>Non</td></tr>
<tr><td>XCA</td><td>IHE IT Infrastructure Technical Framework, Volume 2b (ITI TF-2b), Revision 15.0, July 24, 2018</td><td>Cross Gateway Query [ITI-38] Cross Gateway Retrieve [ITI-39]</td><td>Complément 1 à l’annexe 5 de l’ODEP‑DFI, édition 5</td></tr>
<tr><td>XCA-I</td><td>IHE Radiology Technical Framework, Volume 3 (RAD-TF-3), Revision 17.0, July 27, 2018</td><td>Cross Gateway Retrieve Image Document Set [RAD-75]</td><td>Non</td></tr>
<tr><td>XCPD</td><td>IHE IT Infrastructure Technical Framework, Volume 2b (ITI TF-2b), Revision 15.0, July 24, 2018</td><td>Cross Gateway Patient Discovery [ITI-55]</td><td>Complément 1 à l’annexe 5 de l’ODEP‑DFI, édition 5</td></tr>
<tr><td>XDM</td><td>IHE IT Infrastructure Technical Framework, Volume 2b (ITI TF-2b), Revision 15.0, July 24, 2018</td><td>Distribute Document Set on Media [ITI-32]</td><td>Non</td></tr>
<tr><td>XDS</td><td>IHE IT Infrastructure Technical Framework, Volume 2a (ITI TF-2a), Revision 15.0, July 24, 2018</td><td>Registry Stored Query [ITI-18]</td><td>Complément 1 à l’annexe 5 de l’ODEP‑DFI, édition 5</td></tr>
<tr><td></td><td>IHE IT Infrastructure Technical Framework, Volume 2b (ITI TF-2b), Revision 15.0, July 24, 2018</td><td>Provide and Register Document Set-b [ITI-41] Register Document Set-b [ITI-42] Retrieve Document Set [ITI-43] Patient Identity Feed HL7v3 [ITI-44]</td><td></td></tr>
<tr><td>XDS-I.b</td><td>IHE Radiology Technical Framework, Volume 3 (RAD-TF-3), Revision 17.0, July 27, 2018</td><td>Provide & Register Imaging Document Set – MTOM/XOP [RAD-68] Retrieve Imaging Document Set [RAD-69]</td><td>Complément 1 à l’annexe 5 de l’ODEP‑DFI, édition 5</td></tr>
<tr><td>XDS Metadata Update</td><td>IHE IT Infrastructure Technical Framework, Supplement XDS Metadata Update, Revision 1.10, July 24, 2018</td><td>Update Document Set [ITI-57]</td><td>Complément 1 à l’annexe 5 de l’ODEP‑DFI, édition 5</td></tr>
<tr><td>XUA</td><td>IHE IT Infrastructure Technical Framework, Volume 2b (ITI TF-2b), Revision 15.0, July 24, 2018</td><td>Authenticate User Get X-User Assertion Provide X-User Assertion [ITI-40]</td><td>Complément 1 à l’annexe 5 de l’ODEP‑DFI, édition 5</td></tr>
</table>

[^annex5-lvlu1-lvl1-2]: Le contenu du complément 1 à l’annexe 5 peut être consulté à l’adresse suivante: [https://fedlex.data.admin.ch/eli/oc/2022/657](https://fedlex.data.admin.ch/eli/oc/2022/657) &gt; Informations générales &gt; Étendue de la publication &gt; Publication d’une partie d’un texte sous la forme d’un renvoi.

### 2 Profils d’intégration nationaux

<table>
<tr><th>Profil d’intégration</th><th>Document technique</th><th>Transactions</th></tr>
<tr><td>CH:ADR</td><td>Complément 2.1[^annex5-lvlu1-lvl2-1] à l’annexe 5 de l’ODEP-DFI, profil d’intégration de l’Authorization Decision Request (CH:ADR), édition 4</td><td>Authorization Decision Request (CH:ADR)</td></tr>
<tr><td>CH:ATC</td><td>Complément 2.2[^annex5-lvlu1-lvl2-2] à l’annexe 5 de l’ODEP-DFI, profil d’intégration de l’Audit Trail Consumption (CH:ATC), édition 4</td><td>Retrieve ATNA Audit Event [ITI-81]</td></tr>
<tr><td></td><td>IHE IT Infrastructure Technical Framework, Supplement Internet User Authorization (IUA), August 31, 2015</td><td>Incorporate Authorization Token [ITI-72]</td></tr>
<tr><td>CH:CPI</td><td>Complément 2.3[^annex5-lvlu1-lvl2-3] à l’annexe 5 de l’ODEP-DFI, profil d’intégration du Community Portal Index (CH:CPI), édition 4</td><td>Community Information Query (CH:CIQ) Community Information Delta Download (CH:CIDD)</td></tr>
<tr><td>CH:PPQ</td><td>Complément 2.1 à l’annexe 5 de l’ODEP-DFI, profil d’intégration du Privacy Policy Query (CH:PPQ), édition 4</td><td>Privacy Policy Feed (CH:PPQ-1) Privacy Policy Retrieve (CH:PPQ-2)</td></tr>
</table>

[^annex5-lvlu1-lvl2-1]: Le contenu du complément 2.1 à l’annexe 5 peut être obtenu auprès de l’OFSP, Schwarzenburgstrasse 157, 3003 Berne ou consulté à l’adresse suivante: www.ehealth.admin.ch.
[^annex5-lvlu1-lvl2-2]: Le contenu du complément 2.2 à l’annexe 5 peut être obtenu auprès de l’OFSP, Schwarzenburgstrasse 157, 3003 Berne ou consulté à l’adresse suivante: www.ehealth.admin.ch.
[^annex5-lvlu1-lvl2-3]: Le contenu du complément 2.3 à l’annexe 5 peut être obtenu auprès de l’OFSP, Schwarzenburgstrasse 157, 3003 Berne ou consulté à l’adresse suivante: www.ehealth.admin.ch.
