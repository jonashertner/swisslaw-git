---
sr: "832.102.14"
title: Verordnung des EDI vom 20. November 2012 über die Datensätze für die Datenweitergabe zwischen Leistungserbringern und Versicherern
eli: "https://fedlex.data.admin.ch/eli/cc/2012/867"
language: de
version: 2022-01-01
adopted: 2012-11-20
in_force: 2013-01-01
source: "https://fedlex.data.admin.ch/filestore/fedlex.data.admin.ch/eli/cc/2012/867/20220101/de/xml/fedlex-data-admin-ch-eli-cc-2012-867-20220101-de-xml-2.xml"
url: "https://www.fedlex.admin.ch/eli/cc/2012/867/20220101/de"
---

> Nicht amtliche Wiedergabe der konsolidierten Fassung (Fedlex). Massgebend ist die Veröffentlichung in der Amtlichen Sammlung (Art. 15 PublG, SR 170.512).

# Verordnung des EDI über die Datensätze für die Datenweitergabe zwischen Leistungserbringern und Versicherern

vom 20. November 2012 (Stand am 1. Januar 2022)

Das Eidgenössische Departement des Innern (EDI),

gestützt auf Artikel 59*a* Absatz 1 der Verordnung vom 27. Juni 1995[^ingress-1] über die Krankenversicherung (KVV),

verordnet:

[^ingress-1]: [SR 832.102](https://fedlex.data.admin.ch/eli/cc/1995/3867_3867_3867)

#### Art. 1

Die Struktur der Datensätze nach Artikel 59*a* Absatz 1 KVV ist im Anhang festgelegt.

#### Art. 2

Diese Verordnung tritt am 1. Januar 2013 in Kraft.

Anhang*[^t-1]*

(Art. 1)

## Gesamtschweizerisch einheitliche Struktur der Datensätze

[^t-1]: Bereinigt gemäss Ziff. I der V des EDI vom 25. Okt. 2017 ([AS 2017 6341](https://fedlex.data.admin.ch/eli/oc/2017/704)), gemäss Beilage der V des EDI vom 30. Nov. 2018 ([AS 2018 5085](https://fedlex.data.admin.ch/eli/oc/2018/793)), Ziff. III der V vom 6. Juni 2019 ([AS 2019 1931](https://fedlex.data.admin.ch/eli/oc/2019/355)), Ziff. I der V des EDI vom 6. Dez. 2019 ([AS 2019 4381](https://fedlex.data.admin.ch/eli/oc/2019/755)) und vom 3. Dez. 2021, in Kraft seit 1. Jan. 2022 ([AS 2021 839](https://fedlex.data.admin.ch/eli/oc/2021/839)).

### 1 Allgemeines

### 1.1 Abkürzungen und Definitionen

- CHOP Schweizerische Operationsklassifikation
- GM German Modification
- Medizinische Statistik Medizinische Statistik der Krankenhäuser nach Ziffer 62 des Anhangs der Verordnung vom 30. Juni 1993[^annexu1-lvlu1-lvl1-lvl11-1] über die Durchführung von statistischen Erhebungen des Bundes
- ICD-10 Internationale statistische Klassifikation der Krankheiten und verwandter Gesundheitsprobleme

[^annexu1-lvlu1-lvl1-lvl11-1]: [SR 431.012.1](https://fedlex.data.admin.ch/eli/cc/1993/2100_2100_2100)

### 1.2 Medizinischer Datensatz

<table>
<tr><th>Bezeichnung</th><th>Variable der medizinischen Statistik</th><th>Inhalt</th></tr>
<tr><td>Geburtsgewicht</td><td>2.2.V04</td><td>in Gramm</td></tr>
<tr><td>Hauptdiagnose</td><td>4.2.V010</td><td>ICD-10-GM-Kode</td></tr>
<tr><td>Zusatz zu Hauptdiagnose</td><td>4.2.V020</td><td>ICD-10-GM-Kode</td></tr>
<tr><td>1. bis 49. Nebendiagnose</td><td>4.2.V030, 4.2.V040 usw. bis 4.2.V510</td><td>ICD-10-GM-Kode</td></tr>
<tr><td>Hauptbehandlung</td><td>4.3.V010</td><td>CHOP-Code</td></tr>
<tr><td>Seitigkeit der Hauptbehandlung</td><td>4.3.V011</td><td>0 = beidseitig 1 = einseitig rechts 2 = einseitig links 3 = einseitig unbekannt 9 = unbekannt leer = Frage stellt sich nicht</td></tr>
<tr><td>Beginn der Hauptbehandlung</td><td>4.3.V015</td><td>Datum (mit Angabe der Stunde)</td></tr>
<tr><td>1. bis 99. Nebenbehandlung</td><td>4.3.V020, 4.3.V030 usw. bis 4.3.V1000</td><td>CHOP-Code</td></tr>
<tr><td>1. bis 99. Nebenbehandlung Seitigkeit</td><td>4.3.V021, 4.3.V031 usw. bis 4.3.V1001</td><td>0 = beidseitig 1 = einseitig rechts 2 = einseitig links 3 = einseitig unbekannt 9 = unbekannt leer = Frage stellt sich nicht</td></tr>
<tr><td>1. bis 99. Nebenbehandlung, Beginn</td><td>4.3.V025, 4.3.V035 usw. bis 4.3.V1005</td><td>Datum (mit Angabe der Stunde)</td></tr>
<tr><td>Dauer der künstlichen Beatmung</td><td>4.4.V01</td><td>Anzahl Stunden</td></tr>
<tr><td>Aufnahmegewicht</td><td>4.5.V01</td><td>in Gramm</td></tr>
<tr><td>Abklärung Garant</td><td>2.2.V06</td><td>0 = nein 1 = ja 9 = unbekannt</td></tr>
<tr><td>Begründung für stationären Aufenthalt</td><td>–</td><td>1-99[^annexu1-lvlu1-lvl1-lvl12-1]</td></tr>
</table>

[^annexu1-lvlu1-lvl1-lvl12-1]: Gemäss Anhang 1*a* KLV Ziff. II. Kriterien zugunsten einer stationären Durchführung ([SR 832.112.31](https://fedlex.data.admin.ch/eli/cc/1995/4964_4964_4964)).

### 1.3 Administrativer Datensatz

<table>
<tr><th>Bezeichnung gemäss der medizinischen Statistik</th><th>Variable der medizinischen Statistik</th><th>Beschreibung</th></tr>
<tr><td>Geschlecht</td><td>1.1.V01</td><td>1 = Mann 2 = Frau</td></tr>
<tr><td>Geburtsdatum</td><td>1.1.V02</td><td>Datumsangabe</td></tr>
<tr><td>Alter bei Eintritt</td><td>1.1.V03</td><td>Exaktes Alter</td></tr>
<tr><td>Eintrittsdatum und -stunde</td><td>1.2.V01</td><td></td></tr>
<tr><td>Aufenthaltsort vor dem Eintritt</td><td>1.2.V02</td><td>1 = zuhause 2 = zuhause mit Spitex-Versorgung 3 = Krankenheim, Pflegeheim 4 = Altersheim, andere sozial-medizinische Institution 5 = psychiatrische Klinik, anderer Betrieb 55 = psychiatrische Abteilung/Klinik, gleicher Betrieb 6 = anderes Krankenhaus (Akutspital) oder Geburtshaus 66 = Akutabteilung/-klinik, gleicher Betrieb 7 = Strafvollzugsanstalt 8 = andere 83 = Rehabilitationsklinik, anderer Betrieb 84 = Rehabilitationsabteilung/-klinik, gleicher Betrieb 9 = unbekannt</td></tr>
<tr><td>Eintrittsart</td><td>1.2.V03</td><td>1 = Notfall (Behandlung innerhalb von 12 Stunden unabdingbar) 2 = angemeldet, geplant 3 = Geburt (Kind in dieser Klinik geboren) 4 = interner Übertritt 5 = Verlegung innerhalb 24 Std. 8 = andere 9 = unbekannt</td></tr>
<tr><td>Administrativer Urlaub und Ferien</td><td>1.3.V04</td><td>vollendete Stunden</td></tr>
<tr><td>Hauptkostenstelle</td><td>1.4.V01</td><td>M000 = Fachgebiete (allgemein) M050 = Intensivmedizin M100 = Innere Medizin M200 = Chirurgie M300 = Gynäkologie und Geburtshilfe M400 = Pädiatrie M500 = Psychiatrie und Psychotherapie M600 = Ophthalmologie M700 = Oto-Rhino-Laryngologie M800 = Dermatologie und Venereologie M850 = Medizinische Radiologie M900 = Geriatrie M950 = Physikalische Medizin und Rehabilitation M960 = Notfallzentrum M970 = Ärztenotfallpraxis M990 = Anderer Tätigkeitsbereich</td></tr>
<tr><td>Austrittsdatum und -Stunde</td><td>1.5.V01</td><td></td></tr>
<tr><td>Entscheid für Austritt</td><td>1.5.V02</td><td>1 = auf Initiative der behandelnden Person 2 = auf Initiative des Patienten/der Patientin (gegen Ansicht der behandelnden Person) 3 = auf Initiative einer Drittperson 4 = interner Übertritt 5 = gestorben 8 = anderes 9 = unbekannt</td></tr>
<tr><td>Aufenthalt nach Austritt</td><td>1.5.V03</td><td>1 = zuhause 2 = Krankenheim, Pflegeheim 3 = Altersheim, andere sozial-medizinische Institution 4 = psychiatrische Klinik, anderer Betrieb 44 = psychiatrische Abteilung/Klinik, gleicher Betrieb 5 = Rehabilitationsklinik, anderer Betrieb [tab] 55 = Rehabilitationsabteilung/-klinik, gleicher Betrieb 6 = anderes Krankenhaus (Akutspital) oder Geburtshaus 66 = Akutabteilung/-klinik, gleicher Betrieb 7 = Strafvollzugsanstalt 8 = andere 9 = unbekannt 0 = Todesfall</td></tr>
<tr><td>1. Zwischenaustritt</td><td>4.7.V01</td><td>Datum (ohne Stunde)</td></tr>
<tr><td>1. Wiedereintritt</td><td>4.7.V02</td><td>Datum (ohne Stunde)</td></tr>
<tr><td>2. bis 4. Zwischenaustritt</td><td>4.7.V11, 4.7.V21 bzw. 4.7.V31</td><td>Datum (ohne Stunde)</td></tr>
<tr><td>2. bis 4. Wiedereintritt</td><td>4.7.V12, 4.7.V22 bzw. 4.7.V32</td><td>Datum (ohne Stunde)</td></tr>
<tr><td>Weitere Wiedereintritte</td><td>4.7.V41</td><td>0 = (default) nicht mehr als 5 Aufenthalte bzw. 4. Wiedereintritte 1 = mehr als 5 Aufenthalte bzw. 4. Wiedereintritte</td></tr>
<tr><td>Gestationsalter</td><td>4.8V16</td><td>Verschlüsselt</td></tr>
<tr><td>Aufenthaltsort nach dem 1. Zwischenaustritt</td><td>4.8V17</td><td>1 = zuhause 2 = Krankenheim, Pflegeheim 3 = Altersheim, andere sozialmedizinische Institution 4 = psychiatrische Klinik, in einem anderen Betrieb 44 = psychiatrische Abteilung/Klinik, im gleichen Betrieb 5 = Rehabilitationsklinik, in einem anderen Betrieb 55 = Rehabilitationsabteilung/ -klinik, im gleichen Betrieb 6 = anderes Krankenhaus (Akutspital) oder Geburtshaus 66 = Akutabteilung/-klinik, im gleichen Betrieb 7 = Strafvollzugsanstalt 8 = andere 9 = unbekannt 0 = Todesfall</td></tr>
<tr><td>Aufenthaltsort nach dem 2. Zwischenaustritt</td><td>4.8.V18</td><td>1 = zuhause 2 = Krankenheim, Pflegeheim 3 = Altersheim, andere sozialmedizinische Institution 4 = psychiatrische Klinik, in einem anderen Betrieb 44 = psychiatrische Abteilung/Klinik, im gleichen Betrieb 5 = Rehabilitationsklinik, in einem anderen Betrieb 55 = Rehabilitationsabteilung/ -klinik, im gleichen Betrieb 6 = anderes Krankenhaus (Akutspital) oder Geburtshaus 66 = Akutabteilung/-klinik, im gleichen Betrieb 7 = Strafvollzugsanstalt 8 = andere 9 = unbekannt 0 = Todesfall</td></tr>
<tr><td>Aufenthaltsort nach dem 3. Zwischenaustritt</td><td>4.8.V19</td><td>1 = zuhause 2 = Krankenheim, Pflegeheim 3 = Altersheim, andere sozialmedizinische Institution 4 = psychiatrische Klinik, in einem anderen Betrieb 44 = psychiatrische Abteilung/Klinik, im gleichen Betrieb 5 = Rehabilitationsklinik, in einem anderen Betrieb 55 = Rehabilitationsabteilung/-klinik, im gleichen Betrieb 6 = anderes Krankenhaus (Akutspital) oder Geburtshaus 66 = Akutabteilung/-klinik, im gleichen Betrieb 7 = Strafvollzugsanstalt 8 = andere 9 = unbekannt 0 = Todesfall</td></tr>
<tr><td>Aufenthaltsort nach dem 4. Zwischenaustritt</td><td>4.8.V20</td><td>1 = zuhause 2 = Krankenheim, Pflegeheim 3 = Altersheim, andere sozialmedizinische Institution 4 = psychiatrische Klinik, in einem anderen Betrieb 44 = psychiatrische Abteilung/Klinik, im gleichen Betrieb 5 = Rehabilitationsklinik, in einem anderen Betrieb 55 = Rehabilitationsabteilung/ -klinik, im gleichen Betrieb 6 = anderes Krankenhaus (Akutspital) oder Geburtshaus 66 = Akutabteilung/-klinik, im gleichen Betrieb 7 = Strafvollzugsanstalt 8 = andere 9 = unbekannt 0 = Todesfall</td></tr>
<tr><td>Einweisende Instanz</td><td>1.2.V04</td><td>1 = selbst, Angehörige 2 = Rettungsdienst (Ambulanz, Polizei) 3 = Arzt 4 = nichtmedizinische/r Therapeut/in 8 = andere 9 = unbekannt</td></tr>
<tr><td></td><td></td><td>[tab]</td></tr>
<tr><td>Behandlungsart</td><td>1.3.V01</td><td>1 = ambulant 3 = stationär 9 = unbekannt</td></tr>
<tr><td>Klasse</td><td>1.3.V02</td><td>1 = allgemein 2 = halbprivat 3 = privat 9 = unbekannt</td></tr>
<tr><td>Geburtsdatum der Mutter</td><td>2.3.V01</td><td>Datumsangabe (Jahr und Monat)</td></tr>
</table>
