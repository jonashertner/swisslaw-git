---
status: "beschlossen, noch nicht in Kraft"
reference: AS 2026 202
title: Verordnung des EDI über das elektronische Patientendossier (EPDV-EDI)
language: de
adopted: 2026-04-30
published: 2026-05-08
in_force: ["2026-06-01"]
url: "https://www.fedlex.admin.ch/eli/oc/2026/202/de"
---

> Nicht amtliche Wiedergabe aus der Amtlichen Sammlung (AS). Der Erlass ist veröffentlicht, aber noch nicht in Kraft; massgebend ist die Veröffentlichung in der AS (Art. 15 PublG, SR 170.512).

# Verordnung des EDI über das elektronische Patientendossier

(EPDV-EDI)

Änderung vom 30. April 2026

Das Eidgenössische Departement des Innern (EDI)

verordnet:

## I

Die Verordnung des EDI vom 22. März 2017[^lvlI-1] über das elektronische Patientendossier wird wie folgt geändert:

***Art. 8f* Übergangsbestimmung zur Änderung vom 30. April 2026**

Bis zum 31. Mai 2027 müssen Herausgeber von Identifikationsmitteln, Gemeinschaften und Stammgemeinschaften die Änderung vom 30. April 2026 nicht umsetzen.

[^lvlI-1]: [SR 816.111](https://fedlex.data.admin.ch/vocabulary/legal-taxonomy/9642)

## II

<sup>1</sup> Die Anhänge 2, 4, 8 und 9[^lvlII-1] *(Betrifft nur den französischen Text)* werden geändert.

<sup>2</sup> Anhang 5 erhält die neue Fassung gemäss Beilage.

[^lvlII-1]: Der Inhalt dieser Anhänge wird in der AS und in der SR nur durch Verweis veröffentlicht. Er kann abgerufen werden unter [https://fedlex.data.admin.ch/eli/oc/2026/202](https://fedlex.data.admin.ch/eli/oc/2026/202) &gt; Allgemeine Informationen &gt; Umfang der Veröffentlichung &gt; Veröffentlichung eines Textteils durch Verweis.

## III

Diese Verordnung tritt am 1. Juni 2026 in Kraft.

<table>
<tr><td>30. April 2026</td><td>Eidgenössisches Departement des Innern: Elisabeth Baume-Schneider</td></tr>
</table>

Anhang 5

(Art. 5)

## Integrationsprofile

### 1 IHE Integrationsprofile

[^annex5-lvlu1-lvl1-1]

[^annex5-lvlu1-lvl1-1]: Integrating the Healthcare Enterprise.

<table>
<tr><th>Integrations- profil</th><th>Technisches Dokument</th><th>Akteure</th><th>Transaktionen</th><th>Nationale Anpassungen</th></tr>
<tr><td>ATNA</td><td>IHE IT Infra-structure Technical Framework[^annex5-lvlu1-lvl1-2], Volume 1, Revision 20.0, August 4, 2023 IHE IT Infrastructure Technical Framework, Volume 2, Revision 20.0, August 4, 2023 (ITI-19), and Revision 20.1, December 12, 2024 (ITI-20)</td><td>Secure Application Secure Node Audit Record Repository</td><td>Authenticate Node [ITI-19] Record Audit Event [ITI-20]</td><td>Ergänzung 1[^annex5-lvlu1-lvl1-3] zu Anhang 5 der EPDV‑EDI, Ausgabe 9 RESTful ATNA, CH EPR FHIR (R4)[^annex5-lvlu1-lvl1-4], RESTful ATNA Implementation Guide, Version 5.0.0, 2025-12-18</td></tr>
<tr><td>CT</td><td>IHE IT Infra-structure Technical Framework, Volume 1, Revision 20.0, August 4, 2023 IHE IT Infrastructure Technical Framework, Volume 2, Revision 20.0, August 4, 2023</td><td>Time Client Time Server</td><td>Maintain Time [ITI-1]</td><td>Nein</td></tr>
<tr><td>HPD</td><td>IHE IT Infrastructure Technical Framework, Supplement Healthcare Provider Directory (HPD), Revision 1.8, August 28, 2020</td><td>Provider Information Source Provider Information Consumer Provider Information Directory</td><td>Provider Information Query [ITI-58] Provider Information Feed [ITI-59] Provider Information Delta Download (CH:PIDD)</td><td>Ergänzung 1 zu Anhang 5 der EPDV‑EDI, Ausgabe 9</td></tr>
<tr><td>IUA</td><td>IHE IT Infrastructure Technical Framework, Supplement Internet User Authorization (IUA), Revision 2.3, May 24, 2024</td><td>Authorization Server Authorization Client Resource Server</td><td>Get Access Token [ITI-71] Incorporate Authorization Token [ITI-72] Get Authorization Server Metadata [ITI-103]</td><td>Internet User Authorization (IUA), CH EPR FHIR (R4) Implementation Guide, Version 5.0.0, 2025-12-18</td></tr>
<tr><td>mCSD</td><td>IHE IT Infrastructure Technical Framework, Mobile Care Services Discovery (mCSD) Implementation Guide, Version 4.0.0, 2025-05-21</td><td>Query Client Update Client Data Source Directory</td><td>Find Matching Care Services [ITI-90] Care Services Feed [ITI-130]</td><td>Mobile Care Services Discovery (mCSD), CH EPR FHIR (R4) Implementation Guide, Version 5.0.0, 2025-12-18</td></tr>
<tr><td>MHD</td><td>IHE IT Infrastructure Technical Framework, Mobile access to Health Documents (MHD) Implementation Guide, Version 4.2.2, 2024-05-18</td><td>Document Source Document Recipient Document Consumer Document Responder</td><td>Provide Document Bundle [ITI-65] Find Document References [ITI-67] Retrieve Document [ITI-68] Update Document Metadata [CH:MHD-1]</td><td>Mobile Access to Health Documents (MHD) with XDS on FHIR, CH EPR FHIR (R4) Implementation Guide, Version 5.0.0, 2025-12-18</td></tr>
<tr><td>PCC</td><td>IHE Patient Care Coordination (PCC) Technical Framework, Volume 1, Revision 11.1, November 11, 2016 IHE Patient Care Coordination (PCC) Technical Framework, Volume 2, Revision 11.1, April 14, 2021</td><td>Content Creator Content Consumer</td><td></td><td>Ergänzung 1 zu Anhang 5 der EPDV‑EDI, Ausgabe 9</td></tr>
<tr><td>PDQV3</td><td>IHE IT Infra-structure Technical Framework, Volume 1, Revision 20.0, August 4, 2023 IHE IT Infrastructure Technical Framework, Volume 2, Revision 20.1, December 12, 2024</td><td>Patient Demographics Consumer Patient Demographics Supplier</td><td>Patient Demographics Query HL7 V3 [ITI-47]</td><td>Ergänzung 1 zu Anhang 5 der EPDV‑EDI, Ausgabe 9</td></tr>
<tr><td>PDQm</td><td>IHE IT Infrastructure Technical Framework, Patient Demographics Query for Mobile (PDQm) Implementation Guide, Version 3.1.0, 2024-12-12</td><td>Patient Demographics Consumer Patient Demographics Supplier</td><td>Patient Demographics Match [ITI-119]</td><td>Patient Demographics Query for Mobile (PDQm), CH EPR FHIR (R4) Implementation Guide, Version 5.0.0, 2025-12-18</td></tr>
<tr><td>PIXV3</td><td>IHE IT Infra-structure Technical Framework, Volume 1, Revision 20.0, August 4, 2023 IHE IT Infrastructure Technical Framework, Volume 2, Revision 20.0, August 4, 2023</td><td>Patient Identity Source Patient Identifier Cross-reference Consumer Patient Identifier Cross-reference Manager</td><td>Patient Identity Feed HL7 V3 [ITI-44] PIXV3 Query [ITI-45]</td><td>Ergänzung 1 zu Anhang 5 der EPDV‑EDI, Ausgabe 9</td></tr>
<tr><td>PIXm</td><td>IHE IT Infrastructure Technical Framework, Patient Identifier Cross-referencing for Mobile (PIXm) Implementation Guide, Version 3.0.4, 2024-02-23</td><td>Patient Identity Source Patient Identifier Cross-reference Consumer Patient Identifier Cross-reference Manager</td><td>Mobile Patient Identifier Cross-reference Query [ITI-83] Patient Identity Feed FHIR [ITI-104]</td><td>Patient Identifier Cross-referencing for mobile (PIXm), CH EPR FHIR (R4) Implementation Guide, Version 5.0.0, 2025-12-18</td></tr>
<tr><td>RMU</td><td>IHE IT Infrastructure Technical Framework, Supplement Restricted Metadata Update (RMU), Revision 1.3, July 2, 2021</td><td>Update Initiator Update Responder</td><td>Restricted Update Document Set [ITI‑92]</td><td>Ergänzung 1 zu Anhang 5 der EPDV‑EDI, Ausgabe 9</td></tr>
<tr><td>SVS</td><td>IHE IT Infra-structure Technical Framework, Volume 1, Revision 20.0, August 4, 2023 IHE IT Infrastructure Technical Framework, Volume 2, Revision 20.0, August 4, 2023</td><td>Value Set Consumer Value Set Repository</td><td>Retrieve Value Set [ITI-48]</td><td>Nein</td></tr>
<tr><td>XCA</td><td>IHE IT Infra-structure Technical Framework, Volume 1, Revision 20.1, December 12, 2024 IHE IT Infrastructure Technical Framework, Volume 2, Revision 20.0, August 4, 2023 (ITI-39), and Revision 20.1, December 12, 2024 (ITI-38)</td><td>Initiating Gateway Responding Gateway</td><td>Cross Gateway Query [ITI-38] Cross Gateway Retrieve [ITI-39]</td><td>Ergänzung 1 zu Anhang 5 der EPDV‑EDI, Ausgabe 9</td></tr>
<tr><td>XCA-I</td><td>IHE Radiology Technical Framework, Volume 1 (RAD‑TF‑1), Integration Profiles, Revision 23.0, August 8, 2025 IHE Radiology Technical Framework, Volume 2 (RAD-TF-2), Transactions, Revision 23.0, August 8, 2025</td><td>Initiating Imaging Gateway Responding Imaging Gateway</td><td>Cross Gateway Retrieve Image Document Set [RAD-75]</td><td>Nein</td></tr>
<tr><td>XCPD</td><td>IHE IT Infra-structure Technical Framework, Volume 1, Revision 20.0, August 4, 2023 IHE IT Infrastructure Technical Framework, Volume 2, Revision 20.1, December 12, 2024</td><td>Initiating Gateway Responding Gateway</td><td>Cross Gateway Patient Discovery [ITI-55]</td><td>Ergänzung 1 zu Anhang 5 der EPDV‑EDI, Ausgabe 9</td></tr>
<tr><td>XDM</td><td>IHE IT Infrastructure Technical Framework, Volume 1, Revision 20.1, December 12, 2024 IHE IT Infrastructure Technical Framework, Volume 2, Revision 20.1, December 12, 2024</td><td>Portable Media Creator Portable Media Importer</td><td>Distribute Document Set on Media [ITI-32]</td><td>Nein</td></tr>
<tr><td>XDS</td><td>IHE IT Infrastructure Technical Framework, Volume 1, Revision 20.1, December 12, 2024 IHE IT Infrastructure Technical Framework, Volume 2, Revision 20.0, August 4, 2023 (ITI-42, ITI-43, ITI-44), and Revision 20.1, December 12, 2024 (ITI-18, ITI-41) IHE IT Infrastructure Technical Framework, Volume 3, Revision 20.1, December 12, 2024</td><td>Document Consumer Document Source Document Repository Document Registry Patient Identity Source</td><td>Registry Stored Query [ITI-18] Provide and Register Document Set-b [ITI-41] Register Document Set-b [ITI-42] Retrieve Document Set [ITI-43] Patient Identity Feed HL7v3 [ITI-44]</td><td>Ergänzung 1 zu Anhang 5 der EPDV‑EDI, Ausgabe 9</td></tr>
<tr><td>XDS-I.b</td><td>IHE Radiology Technical Framework, Volume 1 (RAD‑TF‑1), Integration Profiles, Revision 23.0, August 8, 2025 IHE Radiology Technical Framework, Volume 2 (RAD-TF-2), Transactions, Revision 23.0, August 8, 2025</td><td>Imaging Document Source Imaging Document Consumer</td><td>Provide & Register Imaging Document Set – MTOM/XOP [RAD-68] Retrieve Imaging Document Set [RAD-69]</td><td>Ergänzung 1 zu Anhang 5 der EPDV‑EDI, Ausgabe 9</td></tr>
<tr><td>XDS Metadata Update</td><td>IHE IT Infrastructure Technical Framework, Supplement XDS Metadata Update, Revision 1.14, August 4, 2023</td><td>Document Administrator Document Registry</td><td>Update Document Set [ITI-57]</td><td>Ergänzung 1 zu Anhang 5 der EPDV‑EDI, Ausgabe 9</td></tr>
<tr><td>XUA</td><td>IHE IT Infrastructure Technical Framework, Volume 1, Revision 20.0, August 4, 2023 IHE IT Infrastructure Technical Framework, Volume 2, Revision 20.1, December 12, 2024</td><td>X-Service User X-Service Provider X-Assertion Provider User Authentication Provider</td><td>Authenticate User Get X-User Assertion Provide X-User Assertion [ITI-40]</td><td>Ergänzung 1 zu Anhang 5 der EPDV‑EDI, Ausgabe 9</td></tr>
</table>

[^annex5-lvlu1-lvl1-2]: Das IHE Technical Framework kann kostenlos abgerufen werden unter [www.ihe.net](http://www.ihe.net/).
[^annex5-lvlu1-lvl1-3]: Der Inhalt der Ergänzung 1 zu Anhang 5 kann abgerufen werden unter [https://fedlex.data.admin.ch/eli/oc/2026/202](https://fedlex.data.admin.ch/eli/oc/2026/202) &gt; Allgemeine Informationen &gt; Umfang der Veröffentlichung &gt; Veröffentlichung eines Textteils durch Verweis.
[^annex5-lvlu1-lvl1-4]: Die nationalen Anpassungen des FHIR-Standards können kostenlos abgerufen werden unter [www.fhir.ch](http://www.fhir.ch).

### 2 Nationale Integrationsprofile

<table>
<tr><th>Integrations- profil</th><th>Technisches Dokument</th><th>Akteure</th><th>Transaktionen</th></tr>
<tr><td>CH:ADR</td><td>Ergänzung 2.1[^annex5-lvlu1-lvl2-1] zu Anhang 5 der EPDV-EDI, Integrationsprofil Authorization Decision Request (CH:ADR), Ausgabe 8</td><td>Authorization Decision Provider Authorization Decision Consumer</td><td>Authorization Decision Request (CH:ADR)</td></tr>
<tr><td>CH:ATC</td><td>Audit Trail Consumption (CH:ATC), CH EPR FHIR (R4) Implementation Guide, Version 5.0.0, 2025-12-18</td><td>Patient Audit Consumer Patient Audit Record Repository</td><td>Retrieve ATNA Audit Event [ITI-81]</td></tr>
<tr><td>CH:CPI</td><td>Ergänzung 2.3[^annex5-lvlu1-lvl2-2] zu Anhang 5 der EPDV-EDI, Integrationsprofil Community Portal Index (CH:CPI), Ausgabe 8</td><td>CH:CPI Consumer CH:CPI Provider</td><td>Community Information Query (CH:CIQ) Community Information Delta Download (CH:CIDD)</td></tr>
<tr><td>CH:PPQ</td><td>Ergänzung 2.1 zu Anhang 5 der EPDV-EDI, Integrationsprofil Privacy Policy Query (CH:PPQ), Ausgabe 8</td><td>Policy Source Policy Repository Policy Consumer</td><td>Privacy Policy Feed (CH:PPQ-1) Privacy Policy Retrieve (CH:PPQ-2)</td></tr>
<tr><td>CH:PPQm</td><td>Privacy Policy Query for Mobile (CH:PPQm), CH EPR FHIR (R4) Implementation Guide, Version 5.0.0, 2025-12-18</td><td>Policy Repository Policy Source Policy Consumer</td><td>Mobile Privacy Policy Feed (PPQ-3) Mobile Privacy Policy Bundle Feed (PPQ-4) Mobile Privacy Policy Retrieve (PPQ-5)</td></tr>
</table>

[^annex5-lvlu1-lvl2-1]: Der Inhalt der Ergänzung 2.1 zu Anhang 5 kann abgerufen werden unter [https://fedlex.data.admin.ch/eli/oc/2026/202](https://fedlex.data.admin.ch/eli/oc/2026/202) &gt; Allgemeine Informationen &gt; Umfang der Veröffentlichung &gt; Veröffentlichung eines Textteils durch Verweis.
[^annex5-lvlu1-lvl2-2]: Der Inhalt der Ergänzung 2.3 zu Anhang 5 kann abgerufen werden unter [https://fedlex.data.admin.ch/eli/oc/2026/202](https://fedlex.data.admin.ch/eli/oc/2026/202) &gt; Allgemeine Informationen &gt; Umfang der Veröffentlichung &gt; Veröffentlichung eines Textteils durch Verweis.
