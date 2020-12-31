---
sr: "832.102.2"
title: Verordnung des EDI vom 13. November 2012 über den Datenaustausch für die Prämienverbilligung (VDPV-EDI)
short: VDPV-EDI
eli: "https://fedlex.data.admin.ch/eli/cc/2012/828"
language: de
version: 2020-07-01
adopted: 2012-11-13
in_force: 2013-01-01
source: "https://fedlex.data.admin.ch/filestore/fedlex.data.admin.ch/eli/cc/2012/828/20200701/de/xml/fedlex-data-admin-ch-eli-cc-2012-828-20200701-de-xml-5.xml"
url: "https://www.fedlex.admin.ch/eli/cc/2012/828/20200701/de"
---

> Nicht amtliche Wiedergabe der konsolidierten Fassung (Fedlex). Massgebend ist die Veröffentlichung in der Amtlichen Sammlung (Art. 15 PublG, SR 170.512).

# Verordnung des EDI über den Datenaustausch für die Prämienverbilligung

(VDPV-EDI)

vom 13. November 2012 (Stand am 1. Juli 2020)

Das Eidgenössische Departement des Innern (EDI),

gestützt auf die Artikel 106*c* Absatz 2 und 106*d* Absatz 2 der Verordnung vom 27. Juni 1995[^ingress-1] über die Krankenversicherung (KVV), auf Artikel 14 Absatz 2 der Verordnung vom 3. Juli 2001[^ingress-2] über die Prämienverbilligung in der Krankenversicherung für Rentner und Rentnerinnen, die in einem Mitgliedstaat der Europäischen Union, in Island oder Norwegen wohnen (VPVKEU) und auf Artikel 54*a* Absätze 5<sup>bis</sup> und 6 der Verordnung vom 15. Januar 1971[^ingress-3] über die Ergänzungsleistungen zur Alters-, Hinterlassenen- und Invalidenversicherung (ELV),[^ingress-4]

verordnet:

[^ingress-1]: [SR 832.102](https://fedlex.data.admin.ch/eli/cc/1995/3867_3867_3867)
[^ingress-2]: [SR 832.112.5](https://fedlex.data.admin.ch/eli/cc/2002/164)
[^ingress-3]: [SR 831.301](https://fedlex.data.admin.ch/eli/cc/1971/37_37_37)
[^ingress-4]: Fassung gemäss Ziff. I der V des EDI vom 4. Juni 2020, in Kraft seit 1. Juli 2020 ([AS 2020 2537](https://fedlex.data.admin.ch/eli/oc/2020/463)).

#### Art. 1

**Gegenstand**

Diese Verordnung regelt die technischen und organisatorischen Vorgaben und das Datenformat, nach denen Daten nach den Artikeln 65 Absatz 2 und 66*a* des Bundesgesetzes vom 18. März 1994[^1-1] über die Krankenversicherung (KVG) und Artikel 21*a* des Bundesgesetzes vom 6. Oktober 2006[^1-2] über Ergänzungsleistungen zur Alters-, Hinterlassenen- und Invalidenversicherung (ELG) elektronisch ausgetauscht werden.

[^1-1]: [SR 832.10](https://fedlex.data.admin.ch/eli/cc/1995/1328_1328_1328)
[^1-2]: [SR 831.30](https://fedlex.data.admin.ch/eli/cc/2007/804)

#### Art. 2

**Kantonale Stelle nach Artikel 106*b* Absatz 1 KVV**

<sup>1</sup> Die kantonale Stelle nach Artikel 106*b* Absatz 1 KVV meldet Daten zur Prämienverbilligung nach dem KVG[^2-1] und zum Pauschalbetrag für die obligatorische Krankenpflegeversicherung nach Artikel 10 Absatz 3 Buchstabe d ELG[^2-2].

<sup>2</sup> Die gemeinsame Einrichtung nach Artikel 18 KVG meldet die für den Vollzug der VPVKEU notwendigen Daten. Sie ist einer kantonalen Stelle nach Artikel 106*b* Absatz 1 KVV gleichgestellt.[^2-3]

[^2-1]: [SR 832.10](https://fedlex.data.admin.ch/eli/cc/1995/1328_1328_1328)
[^2-2]: [SR 831.30](https://fedlex.data.admin.ch/eli/cc/2007/804)
[^2-3]: Fassung gemäss Ziff. I der V des EDI vom 4. Juni 2020, in Kraft seit 1. Juli 2020 ([AS 2020 2537](https://fedlex.data.admin.ch/eli/oc/2020/463)).

#### Art. 3

**Verbund**

Die kantonalen Stellen nach Artikel 106*b* Absatz 1 KVV und die Versicherer müssen eine geschlossene Benutzergruppe (Verbund) bilden.

#### Art. 4

**Datenaustauschplattform**

<sup>1</sup> Die kantonalen Stellen nach Artikel 106*b* Absatz 1 KVV und Versicherer (Verbundteilnehmerinnen) verwenden für den Datenaustausch die Datenaustauschplattform Sedex des Bundesamts für Statistik.

<sup>2</sup> Sie sind für die Meldungen verantwortlich, stellen deren Verschlüsselung und Nachvollziehbarkeit von der Senderin bis zur Empfängerin sicher und tragen die Umsetzungskosten, auch wenn sie Dritte beauftragen, die Übermittlung der Meldungen zwischen ihnen und Sedex sicherzustellen.

#### Art. 5

**Meldeprozesse**

<sup>1</sup>

Der Datenaustausch erfolgt über folgende Meldeprozesse:

- a. Meldung einer Prämienverbilligung durch die kantonale Stelle nach Artikel 106*b* Absatz 1 KVV;
- b. Meldung der Verkürzung oder Aufhebung einer Prämienverbilligung durch die kantonale Stelle nach Artikel 106*b* Absatz 1 KVV;
- c. Meldung von wesentlichen Änderungen des Versicherungsverhältnisses durch den Versicherer;
- d. Meldung der Jahresrechnung durch den Versicherer;
- e.[^5-1] Meldung der tatsächlichen Prämie nach Artikel 16*d* ELV[^5-2] durch den Versicherer.

<sup>2</sup> Als wesentliche Änderungen des Versicherungsverhältnisses gelten Änderungen der Versicherungsdaten, die für die Gewährung der Prämienverbilligung entscheidend sind.

<sup>3</sup> Die Kantone können weitere Meldeprozesse vorsehen.

[^5-1]: Eingefügt durch Ziff. I der V des EDI vom 4. Juni 2020, in Kraft seit 1. Juli 2020 ([AS 2020 2537](https://fedlex.data.admin.ch/eli/oc/2020/463)).
[^5-2]: [AS 2020 599](https://fedlex.data.admin.ch/eli/oc/2020/112)

#### Art. 6

**Standard für den Datenaustausch**[^6-1]

<sup>1</sup> Die Verbundsteilnehmerinnen müssen für die Meldeprozesse nach Artikel 5 Absatz 1 die Struktur und Semantik der zu meldenden Daten (Meldeformat), die Aktionen, Reaktionen und Optionen der am Verbund Beteiligten (Verhalten) sowie die Grundlagen zur technischen Einbindung in den Verbund (Meldungsübermittlung) gemäss dem «Konzept Datenaustausch Prämienverbilligung», Version 4.1 vom 25. März 2020[^6-2], (PV-Standard) einhalten.

<sup>2</sup> Der Begriff der Tarifprämie nach Ziffer 3.2.5 des PV-Standards entspricht dem Begriff der tatsächlichen Prämie nach Artikel 16*d* ELV[^6-3].

[^6-1]: Fassung gemäss Ziff. I der V des EDI vom 4. Juni 2020, in Kraft seit 1. Juli 2020 ([AS 2020 2537](https://fedlex.data.admin.ch/eli/oc/2020/463)).
[^6-2]: Das Dokument ist einsehbar unter: [www.bag.admin.ch](https://www.bag.admin.ch/bag/de/home/versicherungen/krankenversicherung/krankenversicherung-versicherer-aufsicht/datenaustausch-praemienverbilligung.html) &gt; Versicherungen &gt; Krankenversicherung &gt; Versicherer und Aufsicht &gt; Datenaustausch für die Prämienverbilligung zwischen Versicherern und Kantonen.
[^6-3]: [AS 2020 599](https://fedlex.data.admin.ch/eli/oc/2020/112)

#### Art. 7

**Zu meldende Daten**

<sup>1</sup> Die Verbundsteilnehmerinnen melden die nach dem PV-Standard für die Meldeprozesse nach Artikel 5 Absatz 1 notwendigen Daten.

<sup>2</sup> Sie dürfen Zusatzdaten im Sinne von Ziffer 3.2.17 des PV-Standards melden, wenn das kantonale Recht dies vorsieht.[^7-1]

<sup>3</sup> Die kantonalen Stellen nach Artikel 106*b* Absatz 1 KVV dürfen Änderungen beim Betrag der jährlichen Ergänzungsleistung nach dem ELG[^7-2], die den Pauschalbetrag für die obligatorische Krankenpflegeversicherung nicht beeinflussen, nicht melden.

[^7-1]: Fassung gemäss Ziff. I der V des EDI vom 20. Sept. 2017, in Kraft seit 1. Jan. 2018 ([AS 2017 5527](https://fedlex.data.admin.ch/eli/oc/2017/596)).
[^7-2]: [SR 831.30](https://fedlex.data.admin.ch/eli/cc/2007/804)

#### Art. 8

**Test der Meldeprozesse**

<sup>1</sup> Die Verbundsteilnehmerinnen sind verpflichtet, vor dem Start des Datenaustauschs die Meldeprozesse nach Artikel 5 Absatz 1 mit den Daten nach Artikel 7 Absatz 1 zu testen.

<sup>2</sup> Das Testverfahren ist im «Test- und Einführungskonzept Datenaustausch Prämienverbilligung», Version 2.1 vom 21. August 2013[^8-1], festgelegt.[^8-2]

[^8-1]: Das Dokument ist einsehbar unter: [www.bag.admin.ch](https://www.bag.admin.ch/bag/de/home/versicherungen/krankenversicherung/krankenversicherung-versicherer-aufsicht/datenaustausch-praemienverbilligung.html) &gt; Versicherungen &gt; Krankenversicherung &gt; Versicherer und Aufsicht &gt; Datenaustausch für die Prämienverbilligung zwischen Versicherern und Kantonen.
[^8-2]: Fassung gemäss Ziff. I der V des EDI vom 27. Nov. 2013, in Kraft seit 1. Jan. 2014 ([AS 2013 4525](https://fedlex.data.admin.ch/eli/oc/2013/801)).

#### Art. 9

**Übergangsbestimmung zur Änderung vom 4. Juni 2020**[^9-1]

Bis zum 31. Oktober 2020 dürfen die Verbundsteilnehmerinnen das «Konzept Datenaustausch Prämienverbilligung» in der Version 2.4 vom 9. Mai 2017 verwenden.

[^9-1]: Fassung gemäss Ziff. I der V des EDI vom 4. Juni 2020, in Kraft seit 1. Juli 2020 ([AS 2020 2537](https://fedlex.data.admin.ch/eli/oc/2020/463)).

#### Art. 10

**Inkrafttreten**

Diese Verordnung tritt am 1. Januar 2013 in Kraft.
