---
status: "beschlossen, noch nicht in Kraft"
reference: AS 2022 657
title: Verordnung des EDI über das elektronische Patientendossier (EPDV-EDI)
language: de
adopted: 2022-10-28
published: 2022-11-09
in_force: ["2022-12-01"]
url: "https://www.fedlex.admin.ch/eli/oc/2022/657/de"
---

> Nicht amtliche Wiedergabe aus der Amtlichen Sammlung (AS). Der Erlass ist veröffentlicht, aber noch nicht in Kraft; massgebend ist die Veröffentlichung in der AS (Art. 15 PublG, SR 170.512).

# Verordnung des EDI über das elektronische Patientendossier

(EPDV-EDI)

Änderung vom 28. Oktober 2022

Das Eidgenössische Departement des Innern (EDI)

verordnet:

## I

Die Verordnung des EDI vom 22. März 2017[^lvlI-1] über das elektronische Patientendossier wird wie folgt geändert:

*Art. 8b* Übergangsbestimmung zur Änderung vom 28. Oktober 2022

Bis zum 31. Dezember 2023 müssen Gemeinschaften und Stammgemeinschaften die Änderung vom 28. Oktober 2022 nicht umsetzen.

[^lvlI-1]: [SR 816.111](https://fedlex.data.admin.ch/eli/cc/2017/205)

## II

<sup>1</sup> Die Anhänge 2–4[^lvlII-1] werden geändert.

<sup>2</sup> Anhang 5 erhält die neue Fassung gemäss Beilage.

[^lvlII-1]: Der Inhalt dieser Anhänge wird in der AS und in der SR nur durch Verweis veröffentlicht. Er kann abgerufen werden unter [https://fedlex.data.admin.ch/eli/oc/2022/657](https://fedlex.data.admin.ch/eli/oc/2022/657) &gt; Allgemeine Informationen &gt; Umfang der Veröffentlichung &gt; Veröffentlichung eines Textteils durch Verweis.

## III

Diese Verordnung tritt am 1. Dezember 2022 in Kraft.

<table>
<tr><td>28. Oktober 2022</td><td>Eidgenössisches Departement des Innern: Alain Berset</td></tr>
</table>

Anhang 5

(Art. 5)

## Integrationsprofile

### 1 IHE Integrationsprofile

[^annex5-lvlu1-lvl1-1]

[^annex5-lvlu1-lvl1-1]: Integrating the Healthcare Enterprise

<table>
<tr><th>Integrationsprofil</th><th>Technisches Dokument</th><th>Transaktionen</th><th>Nationale Anpassungen</th></tr>
<tr><td>ATNA</td><td>IHE IT Infrastructure Technical Framework, Volume 2a (ITI TF-2a), Revision 15.0, July 24, 2018</td><td>Authenticate Node [ITI-19] Record Audit Event [ITI-20]</td><td>Ergänzung 1[^annex5-lvlu1-lvl1-2] zu Anhang 5 der EPDV‑EDI, Ausgabe 5</td></tr>
<tr><td>CT</td><td>IHE IT Infrastructure Technical Framework, Volume 2a (ITI TF-2a), Revision 15.0, July 24, 2018</td><td>Maintain Time [ITI-1]</td><td>Nein</td></tr>
<tr><td>HPD</td><td>IHE IT Infrastructure Technical Framework, Supplement Healthcare Provider Directory (HPD), Revision 1.7, July 24, 2018</td><td>Provider Information Query [ITI-58] Provider Information Feed [ITI-59] Provider Information Delta Download (CH:PIDD)</td><td>Ergänzung 1 zu Anhang 5 der EPDV‑EDI, Ausgabe 5</td></tr>
<tr><td>PDQv3</td><td>IHE IT Infrastructure Technical Framework, Volume 2b (ITI TF-2b), Revision 15.0, July 24, 2018</td><td>Patient Demographics Query HL7 V3 [ITI-47]</td><td>Ergänzung 1 zu Anhang 5 der EPDV‑EDI, Ausgabe 5</td></tr>
<tr><td>PIXv3</td><td>IHE IT Infrastructure Technical Framework, Volume 2b (ITI TF-2b), Revision 15.0, July 24, 2018</td><td>Patient Identity Feed HL7 V3 [ITI-44] PIXV3 Query [ITI-45] PIXV3 Update Notification [ITI-46]</td><td>Ergänzung 1 zu Anhang 5 der EPDV‑EDI, Ausgabe 5</td></tr>
<tr><td>RMU</td><td>IHE IT Infrastructure Technical Framework, Supplement Restricted Metadata Update, Revision 1.0, May 23, 2018</td><td>Restricted Update Document Set [ITI‑92]</td><td>Ergänzung 1 zu Anhang 5 der EPDV‑EDI, Ausgabe 5</td></tr>
<tr><td>SVS</td><td>IHE IT Infrastructure Technical Framework, Volume 2b (ITI TF-2b), Revision 15.0, July 24, 2018</td><td>Retrieve Value Set [ITI-48]</td><td>Nein</td></tr>
<tr><td>XCA</td><td>IHE IT Infrastructure Technical Framework, Volume 2b (ITI TF-2b), Revision 15.0, July 24, 2018</td><td>Cross Gateway Query [ITI-38] Cross Gateway Retrieve [ITI-39]</td><td>Ergänzung 1 zu Anhang 5 der EPDV‑EDI, Ausgabe 5</td></tr>
<tr><td>XCA-I</td><td>IHE Radiology Technical Framework, Volume 3 (RAD-TF-3), Revision 17.0, July 27, 2018</td><td>Cross Gateway Retrieve Image Document Set [RAD-75]</td><td>Nein</td></tr>
<tr><td>XCPD</td><td>IHE IT Infrastructure Technical Framework, Volume 2b (ITI TF-2b), Revision 15.0, July 24, 2018</td><td>Cross Gateway Patient Discovery [ITI-55]</td><td>Ergänzung 1 zu Anhang 5 der EPDV‑EDI, Ausgabe 5</td></tr>
<tr><td>XDM</td><td>IHE IT Infrastructure Technical Framework, Volume 2b (ITI TF-2b), Revision 15.0, July 24, 2018</td><td>Distribute Document Set on Media [ITI-32]</td><td>Nein</td></tr>
<tr><td>XDS</td><td>IHE IT Infrastructure Technical Framework, Volume 2a (ITI TF-2a), Revision 15.0, July 24, 2018</td><td>Registry Stored Query [ITI-18]</td><td>Ergänzung 1 zu Anhang 5 der EPDV-EDI, Ausgabe 5</td></tr>
<tr><td></td><td>IHE IT Infrastructure Technical Framework, Volume 2b (ITI TF-2b), Revision 15.0, July 24, 2018</td><td>Provide and Register Document Set-b [ITI-41] Register Document Set-b [ITI-42] Retrieve Document Set [ITI-43] Patient Identity Feed HL7v3 [ITI-44]</td><td></td></tr>
<tr><td>XDS-I.b</td><td>IHE Radiology Technical Framework, Volume 3 (RAD-TF-3), Revision 17.0, July 27, 2018</td><td>Provide & Register Imaging Document Set – MTOM/XOP [RAD-68] Retrieve Imaging Document Set [RAD-69]</td><td>Ergänzung 1 zu Anhang 5 der EPDV‑EDI, Ausgabe 5</td></tr>
<tr><td>XDS Metadata Update</td><td>IHE IT Infrastructure Technical Framework, Supplement XDS Metadata Update, Revision 1.10, July 24, 2018</td><td>Update Document Set [ITI-57]</td><td>Ergänzung 1 zu Anhang 5 der EPDV‑EDI, Ausgabe 5</td></tr>
<tr><td>XUA</td><td>IHE IT Infrastructure Technical Framework, Volume 2b (ITI TF-2b), Revision 15.0, July 24, 2018</td><td>Authenticate User Get X-User Assertion Provide X-User Assertion [ITI-40]</td><td>Ergänzung 1 zu Anhang 5 der EPDV‑EDI, Ausgabe 5</td></tr>
</table>

[^annex5-lvlu1-lvl1-2]: Der Inhalt der Ergänzung 1 zu Anhang 5 kann abgerufen werden unter [https://fedlex.data.admin.ch/eli/oc/2022/657](https://fedlex.data.admin.ch/eli/oc/2022/657) &gt; Allgemeine Informationen &gt; Umfang der Veröffentlichung &gt; Veröffentlichung eines Textteils durch Verweis.

### 2 Nationale Integrationsprofile

<table>
<tr><th>Integrationsprofil</th><th>Technisches Dokument</th><th>Transaktionen</th></tr>
<tr><td>CH:ADR</td><td>Ergänzung 2.1[^annex5-lvlu1-lvl2-1] zu Anhang 5 EPDV-EDI, Integrationsprofil Authorization Decision Request (CH:ADR), Ausgabe 4</td><td>Authorization Decision Request (CH:ADR)</td></tr>
<tr><td>CH:ATC</td><td>Ergänzung 2.2[^annex5-lvlu1-lvl2-2] zu Anhang 5 EPDV-EDI, Integrationsprofil Audit Trail Consumption (CH:ATC), Ausgabe 3</td><td>Retrieve ATNA Audit Event [ITI-81]</td></tr>
<tr><td></td><td>IHE IT Infrastructure Technical Framework, Supplement Internet User Authorization (IUA), August 31, 2015</td><td>Incorporate Authorization Token [ITI-72]</td></tr>
<tr><td>CH:CPI</td><td>Ergänzung 2.3[^annex5-lvlu1-lvl2-3] zu Anhang 5 EPDV-EDI, Integrationsprofil Community Portal Index (CH:CPI), Ausgabe 4</td><td>Community Information Query (CH:CIQ) Community Information Delta Download (CH:CIDD)</td></tr>
<tr><td>CH:PPQ</td><td>Ergänzung 2.1 zu Anhang 5 EPDV-EDI, Integrationsprofil Privacy Policy Query (CH:PPQ), Ausgabe 4</td><td>Privacy Policy Feed (CH:PPQ-1) Privacy Policy Retrieve (CH:PPQ-2)</td></tr>
</table>

[^annex5-lvlu1-lvl2-1]: Der Inhalt der Ergänzung 2.1 zu Anhang 5 kann beim BAG, Schwarzenburgstrasse 157, 3003 Bern, bezogen oder im Internet unter www.ehealth.admin.ch abgerufen werden.
[^annex5-lvlu1-lvl2-2]: Der Inhalt der Ergänzung 2.2 zu Anhang 5 kann beim BAG, Schwarzenburgstrasse 157, 3003 Bern, bezogen oder im Internet unter www.ehealth.admin.ch abgerufen werden.
[^annex5-lvlu1-lvl2-3]: Der Inhalt der Ergänzung 2.3 zu Anhang 5 kann beim BAG, Schwarzenburgstrasse 157, 3003 Bern, bezogen oder im Internet unter www.ehealth.admin.ch abgerufen werden.
