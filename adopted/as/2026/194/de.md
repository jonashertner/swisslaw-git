---
status: "beschlossen, noch nicht in Kraft"
reference: AS 2026 194
title: Verordnung des EDI über die Datensätze für die Datenweitergabe zwischen Leistungserbringern und Versicherern
language: de
adopted: 2026-05-06
published: 2026-05-07
in_force: ["2026-06-01"]
url: "https://www.fedlex.admin.ch/eli/oc/2026/194/de"
---

> Nicht amtliche Wiedergabe aus der Amtlichen Sammlung (AS). Der Erlass ist veröffentlicht, aber noch nicht in Kraft; massgebend ist die Veröffentlichung in der AS (Art. 15 PublG, SR 170.512).

# Verordnung des EDI über die Datensätze für die Datenweitergabe zwischen Leistungserbringern und Versicherern

Änderung vom 6. Mai 2026

Das Eidgenössische Departement des Innern (EDI)

verordnet:

## I

Der Anhang der Verordnung des EDI vom 20. November 2012[^lvlI-1] über die Datensätze für die Datenweitergabe zwischen Leistungserbringern und Versicherern erhält die neue Fassung gemäss Beilage.

[^lvlI-1]: [SR 832.102.14](https://fedlex.data.admin.ch/vocabulary/legal-taxonomy/10136)

## II

Diese Verordnung tritt am 1. Juni 2026 in Kraft.

<table>
<tr><td>6. Mai 2026</td><td>Eidgenössisches Departement des Innern: Elisabeth Baume-Schneider</td></tr>
</table>

Anhang

(Art. 1)

## Gesamtschweizerisch einheitliche Struktur der Datensätze

### 1 Allgemeines

### 1.1 Abkürzungen und Definitionen

- CHOP Schweizerische Operationsklassifikation
- GM German Modification
- SpiGes Erhebung der Daten der Leistungserbringer nach Artikel 59*a* des Bundesgesetzes vom 18. März 1994[^annexu1-lvlu1-lvl1-lvl11-1] über die Krankenversicherung und Artikel 30 der Verordnung vom 27. Juni 1995[^annexu1-lvlu1-lvl1-lvl11-2] über die Krankenversicherung im Bereich der Gesundheitsversorgung bei einem Spitalaufenthalt
- ICD-10 Internationale statistische Klassifikation der Krankheiten und verwandter Gesundheitsprobleme

[^annexu1-lvlu1-lvl1-lvl11-1]: [SR 832.10](https://fedlex.data.admin.ch/vocabulary/legal-taxonomy/10133)
[^annexu1-lvlu1-lvl1-lvl11-2]: [SR 832.102](https://fedlex.data.admin.ch/vocabulary/legal-taxonomy/10135)

### 1.2 Medizinischer Datensatz

<table>
<tr><th>Bezeichnung nach SpiGes</th><th>Variable nach SpiGes</th><th>Beschreibung</th></tr>
<tr><td>Geburtsgewicht</td><td>geburtsgewicht</td><td>in Gramm</td></tr>
<tr><td>Diagnose Rang der Diagnose</td><td>diagnose\_kode diagnose\_id</td><td>ICD-10-GM-Kode Nummer der Diagnose, wobei Rang 1 die Hauptdiagnose kennzeichnet</td></tr>
<tr><td>Behandlungskode Behandlungs-ID</td><td>behandlung\_chop behandlung\_id</td><td>CHOP-Code Fortlaufende Nummer der Behandlung</td></tr>
<tr><td>Seitigkeit der Behandlung</td><td>behandlung\_seitigkeit</td><td>0 = beidseitig 1 = einseitig rechts 2 = einseitig links 3 = einseitig unbekannt 9 = unbekannt leer = Frage stellt sich nicht</td></tr>
<tr><td>Beginn der Behandlung</td><td>behandlung\_beginn</td><td>Datum (mit Angabe der Stunde)</td></tr>
<tr><td>Dauer der künstlichen Beatmung</td><td>beatmung</td><td>Anzahl Stunden</td></tr>
<tr><td>Aufnahmegewicht</td><td>aufnahmegewicht</td><td>in Gramm</td></tr>
<tr><td>Angeborene Fehlbildungen</td><td>missbildungen</td><td>0 = nein 1 = ja 9 = unbekannt</td></tr>
<tr><td>Begründung für stationären Aufenthalt</td><td>–</td><td>Gemäss Spalte «Nr.» in Anhang 1*a* Ziffer II der Krankenpflege-Leistungsverordnung vom 29. Sept. 1995[^annexu1-lvlu1-lvl1-lvl12-1]</td></tr>
<tr><td>Arzneimittel-ID</td><td>medi\_id</td><td>Identifikator zur Unterscheidung der Arzneimittel</td></tr>
<tr><td>ATC-Kode des Arzneimittels</td><td>medi\_atc</td><td>ATC-Kode (*Anatomical Therapeutic Chemical*) der hochteuren Arzneimittel gemäss den Vorgaben der SwissDRG AG</td></tr>
<tr><td>Zusatzangaben</td><td>medi\_zusatz</td><td>Zusatzangaben zu hochteuren Arzneimitteln gemäss den Vorgaben der SwissDRG AG</td></tr>
<tr><td>Verabreichungsart</td><td>medi\_verabreichungsart</td><td>Verabreichungsart hochteurer Arzneimittel gemäss Vorgaben der SwissDRG AG</td></tr>
<tr><td>Dosis</td><td>medi\_dosis</td><td>Zahl (der Masseinheit) für hochteure Arzneimittel gemäss den Vorgaben der SwissDRG AG</td></tr>
<tr><td>Masseinheit</td><td>medi\_einheit</td><td>Masseinheit für hochteure Arzneimittel gemäss Vorgaben der SwissDRG AG</td></tr>
</table>

[^annexu1-lvlu1-lvl1-lvl12-1]: [SR 832.112.31](https://fedlex.data.admin.ch/vocabulary/legal-taxonomy/10157)

### 1.3 Administrativer Datensatz

<table>
<tr><th>Bezeichnung nach SpiGes</th><th>Variable nach SpiGes</th><th>Beschreibung</th></tr>
<tr><td>Geschlecht</td><td>geschlecht</td><td>1 = männlich 2 = weiblich</td></tr>
<tr><td>Geburtsdatum</td><td>geburtsdatum</td><td>Datumsangabe</td></tr>
<tr><td>Alter bei Eintritt</td><td>alter</td><td>Exaktes Alter</td></tr>
<tr><td>Alter in Tagen für unter Einjährige</td><td>alter\_U1</td><td>Alter bei Eintritt in Tagen</td></tr>
<tr><td>Eintrittsdatum und -stunde</td><td>eintrittsdatum</td><td></td></tr>
<tr><td>Aufenthaltsort vor dem Eintritt</td><td>eintritt\_aufenthalt</td><td>1 = zuhause 2 = zuhause mit SPITEX Versorgung 3 = Krankenheim, Pflegeheim 4 = Altersheim, andere sozial-medizinische Institution 5 = psychiatrische Klinik, anderer Betrieb 55 = psychiatrische Abteilung/ Klinik, gleicher Betrieb 6 = anderes Krankenhaus (Akutspital) oder Geburtshaus 66 = Akutabteilung/-klinik, gleicher Betrieb 7 = Strafvollzugsanstalt 8 = andere 83 = Rehabilitationsklinik, anderer Betrieb 84 = Rehabilitations-abteilung/-klinik, gleicher Betrieb 9 = unbekannt</td></tr>
<tr><td>Eintrittsart</td><td>eintrittsart</td><td>1 = Notfall (Behandlung innerhalb von 12 Stunden unabdingbar) 2 = angemeldet, geplant 3 = Geburt (Kind in diesem stationären Aufenthalt und in dieser Klinik geboren) 4 = interner Übertritt 5 = Verlegung innerhalb 24 Std. 6 = Rückverlegung 7= Repatriierung 8 = andere 9 = unbekannt</td></tr>
<tr><td>Administrativer Urlaub und Ferien</td><td>admin\_urlaub</td><td>vollendete Stunden</td></tr>
<tr><td>medizinische Hauptleistungsstelle</td><td>hauptleistungsstelle</td><td>M000 = Fachgebiete (allgemein) M050 = Intensivmedizin M100 = Innere Medizin M200 = Chirurgie M300 = Gynäkologie und Geburtshilfe M400 = Pädiatrie M500 = Psychiatrie und Psychotherapie M600 = Ophthalmologie M700 = Oto-Rhino-Laryngologie M800 = Dermatologie und Venereologie M850 = Medizinische Radiologie M900 = Geriatrie M950 = Physikalische Medizin und Rehabilitation M960 = Notfallzentrum M970 = Ärztenotfallpraxis M990 = anderer Tätigkeitsbereich</td></tr>
<tr><td>Austrittsdatum und -stunde</td><td>austrittsdatum</td><td></td></tr>
<tr><td>Entscheid für Austritt</td><td>austrittsentscheid</td><td>1 = auf Initiative der behandelnden Person 2 = auf Initiative des Patienten/der Patientin (gegen Ansicht der behandelnden Person) 3 = auf Initiative einer Drittperson 4 = interner Übertritt 5 = gestorben 8 = anderes 9 = unbekannt</td></tr>
<tr><td>Aufenthalt nach Austritt</td><td>austritt\_aufenthalt</td><td>1 = zuhause 2 = Krankenheim, Pflegeheim 3 = Altersheim, andere sozial-medizinische Institution 4 = psychiatrische Klinik, anderer Betrieb 44 = psychiatrische Abteilung/Klinik, gleicher Betrieb 5 = Rehabilitationsklinik, anderer Betrieb 55 = Rehabilitationsabteilung/-klinik, gleicher Betrieb 6 = anderes Krankenhaus (Akutspital) oder Geburtshaus 66 = Akutabteilung/-klinik, gleicher Betrieb 7 = Strafvollzugsanstalt 8 = andere 9 = unbekannt 0 = Todesfall</td></tr>
<tr><td>Beginn der Episode</td><td>episode\_beginn</td><td>Datum (ohne Stunde), nur für Zwischenaustritte/Wiedereintritte (episode\_art = 2)</td></tr>
<tr><td>Ende der Episode</td><td>episode\_ende</td><td>Datum (ohne Stunde), nur für Zwischenaustritte/Wiedereintritte (episode\_art = 2)</td></tr>
<tr><td>Aufenthaltsort nach dem Zwischenaustritt</td><td>wiedereintritt\_ aufenhalt</td><td>1 = zuhause 2 = Krankenheim, Pflegeheim 3 = Altersheim, andere sozial-medizinische Institution 4 = psychiatrische Klinik, in einem anderen Betrieb 44 = psychiatrische Abteilung/Klinik, im gleichen Betrieb 5 = Rehabilitationsklinik, in einem anderen Betrieb 55 = Rehabilitationsabteilung/-klinik, im gleichen Betrieb 6 = anderes Krankenhaus (Akutspital) oder Geburtshaus 66 = Akutabteilung/-klinik, im gleichen Betrieb 7 = Strafvollzugsanstalt 8 = andere 9 = unbekannt</td></tr>
<tr><td>Gestationsalter nach Menstruation</td><td>gestationsalter1</td><td>Gestationsalter der Mutter nach Menstruation</td></tr>
<tr><td>Gestationsalter nach Ultraschall</td><td>gestationsalter2</td><td>Gestationsalter der Mutter nach Ultraschall</td></tr>
<tr><td>Einweisende Instanz</td><td>einw\_instanz</td><td>1 = selbst, Angehörige 2 = Rettungsdienst (Ambulanz, Polizei) 3 = Arzt/Ärztin 4 = nichtmedizinische/r Therapeut/in 5 = sozialmedizinischer Dienst 6 = Justizbehörden 8 = andere 9 = unbekannt</td></tr>
<tr><td>Liegeklasse</td><td>liegeklasse</td><td>1 = allgemein 2 = halbprivat 3 = privat 9 = unbekannt</td></tr>
</table>
