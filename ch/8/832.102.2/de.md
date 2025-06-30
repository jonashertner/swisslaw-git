---
sr: "832.102.2"
title: Verordnung des EDI vom 7. März 2025 über den Datenaustausch betreffend die Nichtbezahlung von Prämien und Kostenbeteiligungen sowie betreffend die Prämienverbilligung
eli: "https://fedlex.data.admin.ch/eli/cc/2025/172"
language: de
version: 2025-07-01
adopted: 2025-03-07
in_force: 2025-07-01
source: "https://fedlex.data.admin.ch/filestore/fedlex.data.admin.ch/eli/cc/2025/172/20250701/de/xml/fedlex-data-admin-ch-eli-cc-2025-172-20250701-de-xml-1.xml"
url: "https://www.fedlex.admin.ch/eli/cc/2025/172/20250701/de"
---

> Nicht amtliche Wiedergabe der konsolidierten Fassung (Fedlex). Massgebend ist die Veröffentlichung in der Amtlichen Sammlung (Art. 15 PublG, SR 170.512).

# Verordnung des EDI über den Datenaustausch betreffend die Nichtbezahlung von Prämien und Kostenbeteiligungen sowie betreffend die Prämienverbilligung

vom 7. März 2025 (Stand am 1. Juli 2025)

Das Eidgenössische Departement des Innern (EDI),

gestützt auf die Artikel 105*h*, 106*c* Absatz 2 und 106*d* Absatz 2 der Verordnung vom 27. Juni 1995[^ingress-1] über die Krankenversicherung (KVV), auf Artikel 14 Absatz 2 der Verordnung vom 3. Juli 2001[^ingress-2] über die Prämienverbilligung in der Krankenversicherung für Rentner und Rentnerinnen, die in einem Mitgliedstaat der Europäischen Union, in Island, in Norwegen oder im Vereinigten Königreich wohnen und auf Artikel 54*a* Absatz 6 der Verordnung vom 15. Januar 1971[^ingress-3] über die Ergänzungsleistungen zur Alters-, Hinterlassenen- und Invalidenversicherung (ELV),

verordnet:

[^ingress-1]: [SR 832.102](https://fedlex.data.admin.ch/eli/cc/1995/3867_3867_3867)
[^ingress-2]: [SR 832.112.5](https://fedlex.data.admin.ch/eli/cc/2002/164)
[^ingress-3]: [SR 831.301](https://fedlex.data.admin.ch/eli/cc/1971/37_37_37)

## 1. Abschnitt: Gegenstand

#### Art. 1

Diese Verordnung regelt die technischen und organisatorischen Vorgaben und das Datenformat, nach denen Daten nach den Artikeln 64*a* Absatz 7<sup>ter</sup>, 65 Absatz 2 und 66*a* des Bundesgesetzes vom 18. März 1994[^1-1] über die Krankenversicherung (KVG) und Artikel 21*a* des Bundesgesetzes vom 6. Oktober 2006[^1-2] über Ergänzungsleistungen zur Alters-, Hinterlassenen- und Invalidenversicherung (ELG) elektronisch ausgetauscht werden.

[^1-1]: [SR 832.10](https://fedlex.data.admin.ch/eli/cc/1995/1328_1328_1328)
[^1-2]: [SR 831.30](https://fedlex.data.admin.ch/eli/cc/2007/804)

## 2. Abschnitt: Datenaustausch betreffend die Nichtbezahlung von Prämien und Kostenbeteiligungen

#### Art. 2

**Verbund**

Die kantonalen Behörden nach Artikel 105*d* KVV und die Versicherer bilden eine geschlossene Benutzergruppe (Verbund).

#### Art. 3

**Datenaustauschplattform**

<sup>1</sup> Die am Verbund beteiligten kantonalen Behörden und Versicherer verwenden für den Datenaustausch die Datenaustauschplattform Sedex des Bundesamts für Statistik (BFS).

<sup>2</sup> Sie sind für die Meldungen und die Einhaltung der betrieblichen Richtlinien von Sedex verantwortlich und tragen die Umsetzungskosten. Dies gilt auch, wenn sie Dritte beauftragen, die Übermittlung der Meldungen zwischen ihnen und Sedex sicherzustellen.

#### Art. 4

**Meldeprozesse**

Der Datenaustausch erfolgt unter dem Vorbehalt von Artikel 6 Absatz 2 über folgende Meldeprozesse:

- a. Meldung eines Ereignisses im Rahmen einer Betreibung durch den Versicherer und Meldung einer Forderungsübernahme durch die kantonale Behörde;
- b. Meldung einer Übernahmegarantie für Forderungen des Versicherers durch die kantonale Behörde und periodische Meldung der betroffenen Forderungen und der diesbezüglich vom Kanton bereits geleisteten Zahlungen durch den Versicherer;
- c. Meldung eines zu beginnenden, zu beendenden oder aufzuhebenden Leistungsaufschubs durch die kantonale Behörde und Meldung einer entsprechenden Bestätigung der Vornahme durch den Versicherer;
- d. Meldung von Quartalsrechnungen für das laufende Kalenderjahr und einer Schlussabrechnung für das abgelaufene Kalenderjahr bezüglich der für die Versicherten erhaltenen Verlustscheine durch den Versicherer;
- e. Meldung der Übernahme einer Forderung gestützt auf Absatz 1 der Übergangsbestimmungen zur Änderung des KVG vom 18. März 2022[^4-1] durch die kantonale Behörde und Meldung einer entsprechenden Bestätigung der Abtretung und bereits geleisteter Teilzahlungen durch den Versicherer.

[^4-1]: [AS 2023 678](https://fedlex.data.admin.ch/eli/oc/2023/678)

#### Art. 5

**Standard für den Datenaustausch**

Die am Verbund beteiligten kantonalen Behörden und Versicherer halten für die Meldeprozesse nach Artikel 4 die Struktur und Semantik der zu meldenden Daten, die Aktionen, Reaktionen und Optionen sowie die Grundlagen zur technischen Einbindung in den Verbund gemäss dem «Konzept Datenaustausch zum Art. 64*a* KVG», Version 2-01 vom 10. Juni 2024[^5-1], (64*a*-Standard) ein.

[^5-1]: Das Dokument ist einsehbar unter: [www.bag.admin.ch](https://www.bag.admin.ch) &gt; Versicherungen &gt; Krankenversicherung &gt; Versicherer und Aufsicht &gt; Datenaustausch zwischen Versicherern und Kantonen betreffend die Nichtbezahlung von Prämien und Kostenbeteiligungen sowie die Prämienverbilligung.

#### Art. 6

**Zu meldende Daten**

<sup>1</sup> Die am Verbund beteiligten kantonalen Behörden und Versicherer melden die nach dem 64*a*-Standard für die Meldeprozesse nach Artikel 4 notwendigen Daten.

<sup>2</sup>

Sie dürfen folgende Daten nur melden, wenn eine Grundlage im kantonalen Recht besteht und der betreffende Kanton diese nachweist:

- a.

  Daten zu Meldungen nach Artikel 4 Buchstabe a durch den Versicherer, wonach:

  - 1\. die Voraussetzungen für die Stellung eines Fortsetzungsbegehrens erfüllt sind,
  - 2\. er ein Fortsetzungsbegehren gestellt hat,
  - 3\. er für eine versicherte Person einen Verlustschein erhalten hat;

- b. Daten zu Meldungen nach Artikel 4 Buchstabe b durch die kantonale Behörde, wonach aufgelistete Versicherte nicht betrieben werden sollen und sie deren Zahlungsausstände übernimmt;
- c.

  Daten zu Meldungen nach Artikel 4 Buchstabe b durch den Versicherer betreffend:

  - 1\. Forderungen gegenüber den Versicherten nach Buchstabe b,
  - 2\. von den Versicherten nach Buchstabe b geleistete Zahlungen.

## 3. Abschnitt: Datenaustausch betreffend Prämienverbilligung sowie betreffend den Betrag für die obligatorische Krankenpflegeversicherung im Bereich der Ergänzungsleistungen

#### Art. 7

**Verbund**

<sup>1</sup> Die kantonalen Stellen nach Artikel 106*b* Absatz 1 KVV und die Versicherer bilden einen Verbund.

<sup>2</sup> Die gemeinsame Einrichtung nach Artikel 18 KVG[^7-1] ist einer kantonalen Stelle gleichgestellt.

[^7-1]: [SR 832.10](https://fedlex.data.admin.ch/eli/cc/1995/1328_1328_1328)

#### Art. 8

**Datenaustauschplattform**

<sup>1</sup> Die am Verbund beteiligten kantonalen Stellen und Versicherer verwenden für den Datenaustausch die Datenaustauschplattform Sedex des BFS.

<sup>2</sup> Sie sind für die Meldungen und die Einhaltung der betrieblichen Richtlinien von Sedex verantwortlich und tragen die Umsetzungskosten. Dies gilt auch, wenn sie Dritte beauftragen, die Übermittlung der Meldungen zwischen ihnen und Sedex sicherzustellen.

#### Art. 9

**Meldeprozesse**

<sup>1</sup>

Der Datenaustausch erfolgt über folgende Meldeprozesse:

- a. Meldung einer Prämienverbilligung durch die kantonale Stelle;
- b. Meldung der Verkürzung oder Aufhebung einer Prämienverbilligung durch die kantonale Stelle;
- c. Meldung von wesentlichen Änderungen des Versicherungsverhältnisses durch den Versicherer;
- d. Meldung der Jahresrechnung durch den Versicherer;
- e. Meldung der tatsächlichen Prämie nach Artikel 16*d* ELV durch den Versicherer.

<sup>2</sup> Als wesentliche Änderungen des Versicherungsverhältnisses gelten Änderungen der Versicherungsdaten, die für die Gewährung der Prämienverbilligung entscheidend sind.

<sup>3</sup> Die Kantone können weitere Meldeprozesse vorsehen.

#### Art. 10

**Standard für den Datenaustausch**

<sup>1</sup> Die am Verbund beteiligten kantonalen Stellen und Versicherer halten für die Meldeprozesse nach Artikel 9 Absatz 1 die Struktur und Semantik der zu meldenden Daten, die Aktionen, Reaktionen und Optionen sowie die Grundlagen zur technischen Einbindung in den Verbund gemäss dem «Konzept Datenaustausch Prämienverbilligung», Version 4.1 vom 25. März 2020[^10-1], (PV-Standard) ein.

<sup>2</sup> Der Begriff der Tarifprämie nach Ziffer 3.2.5 des PV-Standards entspricht dem Begriff der tatsächlichen Prämie nach Artikel 16*d* ELV.

[^10-1]: Das Dokument ist einsehbar unter: [www.bag.admin.ch](https://www.bag.admin.ch) &gt; Versicherungen &gt; Krankenversicherung &gt; Versicherer und Aufsicht &gt; Datenaustausch zwischen Versicherern und Kantonen betreffend die Nichtbezahlung von Prämien und Kostenbeteiligungen sowie die Prämienverbilligung.

#### Art. 11

**Zu meldende Daten**

<sup>1</sup> Die am Verbund beteiligten kantonalen Stellen und Versicherer melden die nach dem PV-Standard für die Meldeprozesse nach Artikel 9 Absatz 1 notwendigen Daten.

<sup>2</sup> Sie dürfen Zusatzdaten im Sinne von Ziffer 3.2.17 des PV-Standards melden, wenn das kantonale Recht dies vorsieht.

<sup>3</sup> Die kantonalen Stellen dürfen Änderungen beim Betrag der jährlichen Ergänzungsleistung nach dem ELG[^11-1], die den Pauschalbetrag für die obligatorische Krankenpflegeversicherung nicht beeinflussen, nicht melden.

[^11-1]: [SR 831.30](https://fedlex.data.admin.ch/eli/cc/2007/804)

## 4. Abschnitt: Schlussbestimmungen

#### Art. 12

**Aufhebung eines anderen Erlasses**

Die Verordnung des EDI vom 13. November 2012[^12-1] über den Datenaustausch für die Prämienverbilligung wird aufgehoben.

[^12-1]: [[AS 2012 6853](https://fedlex.data.admin.ch/eli/oc/2012/828); [2013 4525](https://fedlex.data.admin.ch/eli/oc/2013/801); [2017 5527](https://fedlex.data.admin.ch/eli/oc/2017/596); [2020 2537](https://fedlex.data.admin.ch/eli/oc/2020/463)]

#### Art. 13

**Inkrafttreten**

Diese Verordnung tritt am 1. Juli 2025 in Kraft.
