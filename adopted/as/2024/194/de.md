---
status: "beschlossen, noch nicht in Kraft"
reference: AS 2024 194
title: Verordnung des EDI über das elektronische Patientendossier (EPDV-EDI)
language: de
adopted: 2024-04-24
published: 2024-05-06
in_force: ["2024-06-01"]
url: "https://www.fedlex.admin.ch/eli/oc/2024/194/de"
---

> Nicht amtliche Wiedergabe aus der Amtlichen Sammlung (AS). Der Erlass ist veröffentlicht, aber noch nicht in Kraft; massgebend ist die Veröffentlichung in der AS (Art. 15 PublG, SR 170.512).

# Verordnung des EDI über das elektronische Patientendossier

(EPDV-EDI)

Änderung vom 24. April 2024

Das Eidgenössische Departement des Innern (EDI)

verordnet:

## I

Die Verordnung des EDI vom 22. März 2017[^lvlI-1] über das elektronische Patientendossier wird wie folgt geändert:

***Art. 8d* Übergangsbestimmung zur Änderung vom 24. April 2024**

Bis zum 31. Mai 2025 müssen Gemeinschaften und Stammgemeinschaften die Änderung vom 24. April 2024 nicht umsetzen.

[^lvlI-1]: [SR 816.111](https://fedlex.data.admin.ch/eli/cc/2017/205)

## II

<sup>1</sup> Die Anhänge 2–4 und 8[^lvlII-1] werden geändert.

<sup>2</sup> Die Anhänge 5 und 6 erhalten die neuen Fassungen gemäss Beilage.

[^lvlII-1]: Der Inhalt dieser Anhänge wird in der AS und in der SR nur durch Verweis veröffentlicht. Er kann abgerufen werden unter [https://fedlex.data.admin.ch/eli/oc/2024/194](https://fedlex.data.admin.ch/eli/oc/2024/194) &gt; Allgemeine Informationen &gt; Umfang der Veröffentlichung &gt; Veröffentlichung eines Textteils durch Verweis.

## III

Diese Verordnung tritt am 1. Juni 2024 in Kraft.

<table>
<tr><td>24. April 2024</td><td>Eidgenössisches Departement des Innern: Elisabeth Baume-Schneider</td></tr>
</table>

Anhang 5

(Art. 5)

## Integrationsprofile

### 1 IHE Integrationsprofile

[^annex5-lvlu1-lvl1-1]

[^annex5-lvlu1-lvl1-1]: Integrating the Healthcare Enterprise.

<table>
<tr><th>Integrationsprofil</th><th>Technisches Dokument</th><th>Akteure</th><th>Transaktionen</th><th>Nationale Anpassungen</th></tr>
<tr><td>ATNA</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Secure Application Secure Node Audit Record Repository</td><td>Authenticate Node [ITI‑19] Record Audit Event [ITI‑20]</td><td>Ergänzung 1[^annex5-lvlu1-lvl1-2] zu Anhang 5 der EPDV‑EDI, Ausgabe 7</td></tr>
<tr><td></td><td>IHE IT Infrastructure Technical Framework Supplement, Add RESTful ATNA (Query and Feed), Revision 3.3, July 2, 2021</td><td>Audit Consumer Audit Record Repository</td><td>Retrieve ATNA Audit Event [ITI‑81]</td><td>Ergänzung 2.2[^annex5-lvlu1-lvl1-3] zu Anhang 5 der EPDV-EDI, Integrationsprofil Audit Trail Consumption (CH:ATC), Ausgabe 5</td></tr>
<tr><td>CT</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Time Client Time Server</td><td>Maintain Time [ITI‑1]</td><td>Nein</td></tr>
<tr><td>HPD</td><td>IHE IT Infrastructure Technical Framework, Supplement Healthcare Provider Directory (HPD), Revision 1.8, August 28, 2020</td><td>Provider Information Source Provider Information Consumer Provider Information Directory</td><td>Provider Information Query [ITI‑58] Provider Information Feed [ITI‑59] Provider Information Delta Download (CH:PIDD)</td><td>Ergänzung 1 zu Anhang 5 der EPDV‑EDI, Ausgabe 7</td></tr>
<tr><td>IUA</td><td>IHE IT Infrastructure Technical Framework, Supplement Internet User Authorization (IUA), Revision 2.2, June 17, 2022</td><td>Authorization Client Resource Server</td><td>Incorporate Authorization Token [ITI‑72]</td><td>Nein</td></tr>
<tr><td>PCC</td><td>IHE Patient Care Coordination (PCC) Technical Framework, Volume 2, Revision 11.1, April 14, 2021</td><td>Content Creator Content Consumer</td><td></td><td>Nein</td></tr>
<tr><td>PDQV3</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Patient Demographics Consumer Patient Demographics Supplier</td><td>Patient Demographics Query HL7 V3 [ITI‑47]</td><td>Ergänzung 1 zu Anhang 5 der EPDV‑EDI, Ausgabe 7</td></tr>
<tr><td>PIXV3</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Patient Identity Source Patient Identifier Cross-reference Consumer Patient Identifier Cross-reference Manager</td><td>Patient Identity Feed HL7 V3 [ITI‑44] PIXV3 Query [ITI‑45] PIXV3 Update Notification [ITI‑46]</td><td>Ergänzung 1 zu Anhang 5 der EPDV‑EDI, Ausgabe 7</td></tr>
<tr><td>RMU</td><td>IHE IT Infrastructure Technical Framework, Supplement Restricted Metadata Update (RMU), Revision 1.3, July 2, 2021</td><td>Update Initiator Update Responder</td><td>Restricted Update Document Set [ITI‑92]</td><td>Ergänzung 1 zu Anhang 5 der EPDV‑EDI, Ausgabe 7</td></tr>
<tr><td>SVS</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Value Set Consumer Value Set Repository</td><td>Retrieve Value Set [ITI‑48]</td><td>Nein</td></tr>
<tr><td>XCA</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Initiating Gateway Responding Gateway</td><td>Cross Gateway Query [ITI‑38] Cross Gateway Retrieve [ITI‑39]</td><td>Ergänzung 1 zu Anhang 5 der EPDV‑EDI, Ausgabe 7</td></tr>
<tr><td>XCA-I</td><td>IHE Radiology Technical Framework, Volume 3 (RAD‑TF‑3), Cross-Transaction Specifications and Content Specifications, Revision 20.0, March 10, 2022</td><td>Initiating Imaging Gateway Responding Imaging Gateway</td><td>Cross Gateway Retrieve Image Document Set [RAD‑75]</td><td>Nein</td></tr>
<tr><td>XCPD</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Initiating Gateway Responding Gateway</td><td>Cross Gateway Patient Discovery [ITI‑55]</td><td>Ergänzung 1 zu Anhang 5 der EPDV‑EDI, Ausgabe 7</td></tr>
<tr><td>XDM</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Portable Media Creator Portable Media Importer</td><td>Distribute Document Set on Media [ITI‑32]</td><td>Nein</td></tr>
<tr><td>XDS</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Document Consumer Document Source Document Repository Document Registry Patient Identity Source</td><td>Registry Stored Query [ITI‑18] Provide and Register Document Set‑b [ITI‑41] Register Document Set‑b [ITI‑42] Retrieve Document Set [ITI‑43] Patient Identity Feed HL7v3 [ITI‑44]</td><td>Ergänzung 1 zu Anhang 5 der EPDV‑EDI, Ausgabe 7</td></tr>
<tr><td>XDS-I.b</td><td>IHE Radiology Technical Framework, Volume 3 (RAD‑TF‑3), Cross-Transaction Specifications and Content Specifications, Revision 20.0, March 10, 2022</td><td>Imaging Document Source Imaging Document Consumer</td><td>Provide & Register Imaging Document Set – MTOM/XOP [RAD‑68] Retrieve Imaging Document Set [RAD‑69]</td><td>Ergänzung 1 zu Anhang 5 der EPDV‑EDI, Ausgabe 7</td></tr>
<tr><td>XDS Metadata Update</td><td>IHE IT Infrastructure Technical Framework, Supplement XDS Metadata Update, Revision 1.13, June 17, 2022</td><td>Document Administrator Document Registry</td><td>Update Document Set [ITI‑57]</td><td>Ergänzung 1 zu Anhang 5 der EPDV‑EDI, Ausgabe 7</td></tr>
<tr><td>XUA</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>X-Service User X-Service Provider X-Assertion Provider User Authentication Provider</td><td>Authenticate User Get X‑User Assertion Provide X‑User Assertion [ITI‑40]</td><td>Ergänzung 1 zu Anhang 5 der EPDV‑EDI, Ausgabe 7</td></tr>
</table>

[^annex5-lvlu1-lvl1-2]: Der Inhalt der Ergänzung 1 zu Anhang 5 kann abgerufen werden unter [https://fedlex.data.admin.ch/eli/oc/2024/194](https://fedlex.data.admin.ch/eli/oc/2024/194) &gt; Allgemeine Informationen &gt; Umfang der Veröffentlichung &gt; Veröffentlichung eines Textteils durch Verweis.
[^annex5-lvlu1-lvl1-3]: Der Inhalt der Ergänzung 2.2 zu Anhang 5 kann abgerufen werden unter [https://fedlex.data.admin.ch/eli/oc/2024/194](https://fedlex.data.admin.ch/eli/oc/2024/194) &gt; Allgemeine Informationen &gt; Umfang der Veröffentlichung &gt; Veröffentlichung eines Textteils durch Verweis.

### 2 Nationale Integrationsprofile

<table>
<tr><th>Integrationsprofil</th><th>Technisches Dokument</th><th>Akteure</th><th>Transaktionen</th></tr>
<tr><td>CH:ADR</td><td>Ergänzung 2.1[^annex5-lvlu1-lvl2-1] zu Anhang 5 EPDV‑EDI, Integrationsprofil Authorization Decision Request (CH:ADR), Ausgabe 6</td><td>Authorization Decision Provider Authorization Decision Consumer</td><td>Authorization Decision Request (CH:ADR)</td></tr>
<tr><td>CH:ATC</td><td>Ergänzung 2.2 zu Anhang 5 EPDV‑EDI, Integrationsprofil Audit Trail Consumption (CH:ATC), Ausgabe 5</td><td>Patient Audit Consumer Patient Audit Record Repository</td><td>Retrieve ATNA Audit Event [ITI‑81]</td></tr>
<tr><td>CH:CPI</td><td>Ergänzung 2.3[^annex5-lvlu1-lvl2-2] zu Anhang 5 EPDV‑EDI, Integrationsprofil Community Portal Index (CH:CPI), Ausgabe 6</td><td>CH:CPI Consumer CH:CPI Provider</td><td>Community Information Query (CH:CIQ) Community Information Delta Download (CH:CIDD)</td></tr>
<tr><td>CH:PPQ</td><td>Ergänzung 2.1 zu Anhang 5 EPDV‑EDI, Integrationsprofil Privacy Policy Query (CH:PPQ), Ausgabe 6</td><td>Policy Source Policy Repository Policy Consumer</td><td>Privacy Policy Feed (CH:PPQ‑1) Privacy Policy Retrieve (CH:PPQ‑2)</td></tr>
</table>

[^annex5-lvlu1-lvl2-1]: Der Inhalt der Ergänzung 2.1 zu Anhang 5 kann abgerufen werden unter [https://fedlex.data.admin.ch/eli/oc/2024/194](https://fedlex.data.admin.ch/eli/oc/2024/194) &gt; Allgemeine Informationen &gt; Umfang der Veröffentlichung &gt; Veröffentlichung eines Textteils durch Verweis.
[^annex5-lvlu1-lvl2-2]: Der Inhalt der Ergänzung 2.3 zu Anhang 5 kann abgerufen werden unter [https://fedlex.data.admin.ch/eli/oc/2024/194](https://fedlex.data.admin.ch/eli/oc/2024/194) &gt; Allgemeine Informationen &gt; Umfang der Veröffentlichung &gt; Veröffentlichung eines Textteils durch Verweis.

Anhang 6

(Art. 6)

## Evaluation und Forschung

### 1 Allgemeine Vorgaben

- 1\.1

  Es sind die Metadaten nach Anhang 3 zu verwenden für:

  - a. organisatorischen Typ der Gesundheitseinrichtung (Ziff. 2.3);
  - b. Dokumentenklasse (Ziff. 2.5);
  - c. Dokumententyp (Ziff. 2.6);
  - d. Rolle der initial bereitstellenden Person (Ziff. 2.14).

- 1\.2 Es gelten die 5-Jahres-Altersklassen (0–4; 5–9; 10–14 … 95–99; 100+ Jahre).

### 2 Von Gemeinschaften zu erhebende Daten

- 2\.1

  Anzahl der Dokumente, die über das elektronische Patientendossier bereitgestellt sind, aufgeschlüsselt nach:

  - a. organisatorischem Typ der Gesundheitseinrichtung;
  - b. Dokumentenklasse;
  - c. Dokumententyp;
  - d. Rolle der initial bereitstellenden Person.

- 2\.2 Anzahl der Dokumente, die in einem standardisierten Austauschformat nach Anhang 4 erfasst sind, aufgeschlüsselt nach Typ der Gesundheitseinrichtung.
- 2\.3

  Anzahl der Dokumente je Vertraulichkeitsstufe nach Artikel 1 EPDV, aufgeschlüsselt nach:

  - a. organisatorischem Typ der Gesundheitseinrichtung;
  - b. Dokumentenklasse;
  - c. Dokumententyp;
  - d. Rolle der initial bereitstellenden Person.

- 2\.4

  Anzahl der Abrufe von bereitgestellten Dokumenten, aufgeschlüsselt nach:

  - a. Anzahl Zugriffe in medizinischen Notfallsituationen;
  - b. organisatorischem Typ der Gesundheitseinrichtung, die auf die Dokumente zugreift;
  - c. Rolle der initial bereitstellenden Person, die auf die Dokumente zugreift.

### 3 Von Stammgemeinschaften zusätzlich zu erhebende Daten

- 3\.1 Anzahl der Personen, die über ein elektronisches Patientendossier verfügen, aufgeschlüsselt nach

  :

  - a. Kanton;
  - b. Geschlecht in Kombination mit der Altersklasse.

- 3\.2

  Anzahl der Widerrufe von Einwilligungen zur Führung eines elektronischen Patientendossiers, aufgeschlüsselt nach:

  - a. Kanton;
  - b. Geschlecht in Kombination mit der Altersklasse.

- 3\.3

  Anzahl der Anpassungen der Zugriffsrechte, aufgeschlüsselt nach Geschlecht in Kombination mit der Altersklasse der Patientinnen und Patienten, die vorgenommen wurden in folgenden Bereichen:

  - a. Festlegung der Vertraulichkeitsstufe, der neu eingestellte medizinische Daten zugeordnet werden, nach Artikel 4 Buchstabe a EPDV;
  - b. Ausschluss einzelner Gesundheitsfachpersonen vom Zugriff auf das elektronische Patientendossier nach Artikel 4 Buchstabe b EPDV;
  - c. Information über den Eintritt von Gesundheitsfachpersonen in Gruppen nach Artikel 4 Buchstabe c EPDV;
  - d. Befristung der Zugriffsrechte nach Artikel 4 Buchstabe d EPDV;
  - e. Erweiterung des Zugriffsrechts bei medizinischen Notfallsituationen auf die Vertraulichkeitsstufe «Eingeschränkt zugänglich» nach Artikel 4 Buchstabe e EPDV;
  - f. Ausschluss des Zugriffs in medizinischen Notfallsituationen nach Artikel 4 Buchstabe e EPDV;
  - g. Ermächtigung einer Gesundheitsfachperson ihrer oder seiner Stammgemeinschaft, die ihr übertragenen Zugriffsrechte nach Artikel 4 Buchstabe g an weitere Gesundheitsfachpersonen oder Gruppen von Gesundheitsfachpersonen zu übertragen.

- 3\.4 Anzahl der Patientinnen und Patienten, die keine Anpassungen an den Zugriffsrechten vorgenommen haben, aufgeschlüsselt nach Geschlecht in Kombination mit der Altersklasse.
- 3\.5 Anzahl der Gesundheitsfachpersonen und Gruppen von Gesundheitsfachpersonen mit Zugriffsrechten pro elektronisches Patientendossier.
- 3\.6 Anzahl der Personen, die nach Artikel 4 Buchstabe f EPDV eine Stellvertretung benannt haben, aufgeschlüsselt nach Geschlecht in Kombination mit der Altersklasse.
