---
sr: "172.010.59"
title: Verordnung vom 19. Oktober 2016 über Identitätsverwaltungs-Systeme und Verzeichnisdienste des Bundes (IAMV)
short: IAMV
eli: "https://fedlex.data.admin.ch/eli/cc/2016/610"
language: de
version: 2022-06-01
adopted: 2016-10-19
in_force: 2017-01-01
source: "https://fedlex.data.admin.ch/filestore/fedlex.data.admin.ch/eli/cc/2016/610/20220601/de/xml/fedlex-data-admin-ch-eli-cc-2016-610-20220601-de-xml-2.xml"
url: "https://www.fedlex.admin.ch/eli/cc/2016/610/20220601/de"
---

> Nicht amtliche Wiedergabe der konsolidierten Fassung (Fedlex). Massgebend ist die Veröffentlichung in der Amtlichen Sammlung (Art. 15 PublG, SR 170.512).

# Verordnung über Identitätsverwaltungs-Systeme und Verzeichnisdienste des Bundes

(IAMV)

vom 19. Oktober 2016 (Stand am 1. Juni 2022)

Der Schweizerische Bundesrat,

gestützt auf das Regierungs- und Verwaltungsorganisationsgesetz vom 21. März 1997[^ingress-1] (RVOG), auf Artikel 27 Absätze 5 und 6 des Bundespersonalgesetzes vom 24. März 2000[^ingress-2] und auf die Artikel 2*a* Absatz 2 und 186 des Bundesgesetzes vom 3. Oktober 2008[^ingress-3] über die militärischen Informationssysteme (MIG),[^ingress-4]

verordnet:

[^ingress-1]: [SR 172.010](https://fedlex.data.admin.ch/eli/cc/1997/2022_2022_2022)
[^ingress-2]: [SR 172.220.1](https://fedlex.data.admin.ch/eli/cc/2001/123)
[^ingress-3]: [SR 510.91](https://fedlex.data.admin.ch/eli/cc/2009/823)
[^ingress-4]: Fassung gemäss Ziff. I der V vom 14. Nov. 2018, in Kraft seit 1. Jan. 2019 ([AS 2018 4739](https://fedlex.data.admin.ch/eli/oc/2018/752)).

## 1. Abschnitt: Allgemeine Bestimmungen

#### Art. 1

**Gegenstand**

Diese Verordnung regelt für die Identitätsverwaltungs-Systeme (IAM[^1-1]-Systeme), die Verzeichnisdienste und den zentralen Identitätsspeicher des Bundes die Zuständigkeiten, die Bearbeitung und Bekanntgabe von Personendaten und die Anforderungen an die Informationssicherheit.

[^1-1]: IAM = *Identity and Access Management*

#### Art. 2

**Geltungsbereich**

<sup>1</sup> Diese Verordnung gilt für die Verwaltungseinheiten der zentralen Bundesverwaltung nach Artikel 7 der Regierungs- und Verwaltungsorganisationsverordnung vom 25. November 1998[^2-1] (RVOV).

<sup>2</sup>

Folgende Behörden und Stellen können sich, unter Vorbehalt anders lautender Organisationsbestimmungen des Bundesrechts, durch Vereinbarung verpflichten, diese Verordnung und die darauf gestützten Vorgaben einzuhalten:

- a. Einheiten der dezentralen Bundesverwaltung nach Artikel 7*a* RVOV;
- b. andere Bundesbehörden;
- c. Organisationen und Personen des öffentlichen oder privaten Rechts, die nicht der Bundesverwaltung angehören, aber mit Bundesverwaltungsaufgaben betraut sind (Art. 2 Abs. 4 RVOG);
- d. bundesnahe Institutionen mit öffentlicher Zweckbestimmung, wenn ihre Systeme mit den Systemen der Bundesverwaltung verbunden werden sollen.

[^2-1]: [SR 172.010.1](https://fedlex.data.admin.ch/eli/cc/1999/170)

## 2. Abschnitt: Zweck und grundsätzliche Funktion der Systeme

#### Art. 3

**IAM-Systeme**

<sup>1</sup> Der Zweck eines IAM-Systems ist es, Daten über die Identität und die Berechtigungen von Personen, Maschinen und Systemen gebündelt zu verwalten, um sie nachgelagerten Systemen und anderen IAM-Systemen auf Anfrage zur Verfügung zu stellen.

<sup>2</sup> Die nachgelagerten Systeme sind Fachanwendungen oder vermitteln den Zugang zu Informationen, Informatikmitteln, Räumlichkeiten und anderen Infrastrukturen.

<sup>3</sup> Im Einsatz prüft das IAM-System als vorgelagertes System die Identität und bestimmte berechtigungsrelevante Eigenschaften von Personen, Maschinen und Systemen, die auf ein nachgelagertes System zugreifen wollen, und übermittelt das Resultat der Überprüfung an das nachgelagerte Informationssystem, damit dieses die Berechtigungen ermitteln kann.

#### Art. 4

**Verzeichnisdienste**

Der Zweck eines Verzeichnisdienstes ist es, Informationen über Benutzerinnen und Benutzer von Infrastrukturen des Bundes zu führen, um damit die Personen zu identifizieren und die ihnen zugeordneten Geräte, Anschlüsse, Kontaktangaben und dergleichen zu verwalten.

## 3. Abschnitt: Verantwortliche Organe

#### Art. 5

**IAM-Systeme**

<sup>1</sup>

Die für IAM-Systeme verantwortlichen Bundesorgane sind:

- a.[^5-1] der Bereich digitale Transformation und IKT-Lenkung der Bundeskanzlei (Bereich DTI der BK) für alle als Standarddienste angebotenen oder dem Bereich DTI der BK ausdrücklich zugewiesenen IAM-Systeme;
- b. die Direktion für Ressourcen im Eidgenössischen Departement für auswärtige Angelegenheiten (EDA) für das von der Informatik EDA betriebene IAM-System;
- c.[^5-2] das Generalsekretariat des Eidgenössischen Departements für Verteidigung, Bevölkerungsschutz und Sport für das von der Führungsunterstützungsbasis (FUB) der Schweizer Armee betriebene IAM-System;
- d. das Generalsekretariat des Eidgenössischen Departements für Wirtschaft, Bildung und Forschung (WBF) für das beim Information Service Center WBF (ISCeco) betriebene IAM-System.

<sup>2</sup> Die Verantwortung für das nachgelagerte System, insbesondere für den Zugang dazu, bleibt bei der zuständigen Fachstelle.

[^5-1]: Fassung gemäss Anhang Ziff. 8 der V vom 25. Nov. 2020 über die digitale Transformation und die Informatik, in Kraft seit 1. Jan. 2021 ([AS 2020 5871](https://fedlex.data.admin.ch/eli/oc/2020/988)).
[^5-2]: Fassung gemäss Ziff. I der V vom 14. Nov. 2018, in Kraft seit 1. Jan. 2019 ([AS 2018 4739](https://fedlex.data.admin.ch/eli/oc/2018/752)).

#### Art. 6

**Verzeichnisdienste**

Die für Verzeichnisdienste ausserhalb von IAM-Systemen verantwortlichen Bundesorgane sind:

- a. für die Standarddienste: der Bereich DTI der BK[^6-1];
- b.

  für die anderen Verzeichnisse: die Informatik-Leistungserbringer, die diese Systeme betreiben, im Einzelnen:

  - 1\. die Informatik EDA der Direktion für Ressourcen im EDA,
  - 2\. das Informatik Service Center des Eidgenössischen Justiz- und Polizeidepartements (ISC-EJPD),
  - 3\. die FUB,
  - 4\. das Bundesamt für Informatik und Telekommunikation (BIT),
  - 5\. das ISCeco.

[^6-1]: Ausdruck gemäss Anhang Ziff. 8 der V vom 25. Nov. 2020 über die digitale Transformation und die Informatik, in Kraft seit 1. Jan. 2021 ([AS 2020 5871](https://fedlex.data.admin.ch/eli/oc/2020/988)). Diese Änd. wurde im ganzen Erlass berücksichtigt.

#### Art. 7

**Geltendmachung von Rechten**

Die betroffenen Personen machen ihre Rechte in Bezug auf IAM-Systeme und Verzeichnisdienste bei den folgenden Stellen geltend:

- a. ihr Auskunftsrecht: bei den verantwortlichen Organen;
- b. ihr Berichtigungs- und Vernichtungsrecht: beim Personaldienst ihrer Verwaltungseinheit oder ihrer Organisation oder bei der sonst für die Nachführung ihrer Daten zuständigen Stelle.

## 4. Abschnitt: Bearbeitete Daten, Bezug der Daten und Aufbewahrungsfrist

#### Art. 8

**In IAM-Systemen und Verzeichnisdiensten geführte Personen**

<sup>1</sup>

In den IAM-Systemen und den Verzeichnisdiensten können Daten über die folgenden Personen bearbeitet werden:

- a. Angehörige der zentralen Bundesverwaltung nach Artikel 7 RVOV[^8-1];
- b. Angehörige der dezentralen Bundesverwaltung nach Artikel 7*a* RVOV;
- c. Mitglieder der Bundesversammlung und Angehörige der Parlamentsdienste nach dem 4. Titel 7. Kapitel des Parlamentsgesetzes vom 13. Dezember 2002[^8-2];
- d. von der Bundesversammlung nach Artikel 168 der Bundesverfassung[^8-3] gewählte Personen;
- e. Angehörige des Bundesgerichts, des Bundesverwaltungsgerichts, des Bundesstrafgerichts und des Bundespatentgerichts, soweit die Gesetzgebung nichts anderes vorsieht;
- f. Angehörige der Bundesanwaltschaft nach den Artikeln 7–22 des Strafbehördenorganisationsgesetzes vom 19. März 2010[^8-4] (StBOG);
- g. Angehörige des Sekretariats der Aufsichtsbehörde über die Bundesanwaltschaft nach Artikel 27 Absatz 2 StBOG;
- h.[^8-5] Angehörige der Armee und des Zivilschutzes.

<sup>2</sup>

Zusätzlich können Daten bearbeitet werden von Angehörigen der folgenden Unternehmen, sofern diese Angehörigen regelmässig in Kontakt mit Stellen nach Absatz 1 stehen:

- a. Schweizerische Bundesbahnen;
- b. Schweizerische Post;
- c. RUAG;
- d. Schweizerischen Unfallversicherungsanstalt.

<sup>3</sup>

Weiter können in den IAM-Systemen und den Verzeichnisdiensten Daten über die folgenden Personen bearbeitet werden:

- a. externe Personen, die für die Stellen nach Absatz 1 oder 2 tätig sind;
- b. externe Personen, die aus anderen Gründen Zugang zu Informationen, Informatikmitteln, Räumlichkeiten und anderen Infrastrukturen der Bundesverwaltung haben.

[^8-1]: [SR 172.010.1](https://fedlex.data.admin.ch/eli/cc/1999/170)
[^8-2]: [SR 171.10](https://fedlex.data.admin.ch/eli/cc/2003/510)
[^8-3]: [SR 101](https://fedlex.data.admin.ch/eli/cc/1999/404)
[^8-4]: [SR 173.71](https://fedlex.data.admin.ch/eli/cc/2010/444)
[^8-5]: Eingefügt durch Ziff. I der V vom 14. Nov. 2018, in Kraft seit 1. Jan. 2019 ([AS 2018 4739](https://fedlex.data.admin.ch/eli/oc/2018/752)).

#### Art. 9

**In IAM-Systemen geführte Personen**

In den IAM-Systemen können, zusätzlich zu den Daten nach Artikel 8, Daten der folgenden Personen bearbeitet werden:

- a. von Angehörigen kantonaler oder kommunaler Behörden, wenn diese Personen vom Bund bereitgestellte Informationssysteme benutzen;
- b. von Privatpersonen und Vertreterinnen oder Vertretern von Organisationen, die auf vom Bund bereitgestellte Informationssysteme, wie E-Government-Anwendungen, zugreifen.

#### Art. 10

**In Verzeichnisdiensten geführte Personen**

In den Verzeichnisdiensten können, zusätzlich zu den Daten nach Artikel 8, Daten von Angehörigen von kantonalen und kommunalen Behörden und von anderen als den in Artikel 8 Absatz 2 genannten bundesnahen Betrieben bearbeitet werden, die ein digitales Zertifikat des Bundes benutzen.

#### Art. 11

**Kategorien von Personendaten**

<sup>1</sup> In den IAM-Systemen, den Verzeichnisdiensten und dem zentralen Identitätsspeicher nach Artikel 13 dürfen Personendaten gemäss Anhang bearbeitet werden.

<sup>2</sup> Es dürfen in diesen Systemen keine Persönlichkeitsprofile bearbeitet werden.

<sup>3</sup> Es dürfen in diesen Systemen, sofern hierfür keine besondere rechtliche Grundlage besteht, keine besonders schützenswerten Personendaten bearbeitet werden.

<sup>4</sup> Die im Anhang mit einem Stern gekennzeichneten Daten von Personen nach Artikel 8 dürfen in einem Personenverzeichnis publiziert werden, das allen darin erfassten Personen zugänglich ist.

#### Art. 12

**Bezug von Personendaten**

<sup>1</sup> IAM-Systeme und Verzeichnisdienste können Daten der im Informationssystem Personaldatenmanagement (IPDM) geführten Personen nach Artikel 34 der Verordnung vom 22. November 2017[^12-1] über den Schutz von Personendaten des Bundespersonals automatisch beziehen.[^12-2]

<sup>2</sup> Sie können Daten von nicht im IPDM[^12-3] erfassten Personen automatisch von den jeweiligen Stellen nach Artikel 8 beziehen, sofern die entsprechende Personengruppe grundsätzlich Zugang zu Informationssystemen oder anderen Ressourcen des Bundes benötigt.

<sup>3</sup> Sie können Daten von externen Personen mit regelmässigem Zugang zu Ressourcen des Bundes automatisch von den jeweiligen Informationssystemen beziehen.

[^12-1]: [SR 172.220.111.4](https://fedlex.data.admin.ch/eli/cc/2017/793)
[^12-2]: Fassung gemäss Anhang 8 Ziff. II 1 der V vom 22. Nov. 2017 über den Schutz von Personendaten des Bundespersonals, in Kraft seit 1. Jan. 2018 ([AS 2017 7271](https://fedlex.data.admin.ch/eli/oc/2017/793)).
[^12-3]: Audruck gemäss Anhang 8 Ziff. II 1 der V vom 22. Nov. 2017 über den Schutz von Personendaten des Bundespersonals, in Kraft seit 1. Jan. 2018 ([AS 2017 7271](https://fedlex.data.admin.ch/eli/oc/2017/793)). Diese Änd. wurde im ganzen Erlass berücksichtigt.

#### Art. 13

**Zentraler Identitätsspeicher als Verteiler**

<sup>1</sup> Für die Verteilung von Benutzerdaten auf die verschiedenen IAM-Systeme und Verzeichnisdienste betreibt das BIT einen zentralen Identitätsspeicher. In diesem können alle Personendaten gemäss Anhang bearbeitet werden. Verantwortliches Bundesorgan ist der Bereich DTI der BK.

<sup>2</sup> Das IPDM liefert die Daten gemäss Anhang soweit verfügbar regelmässig an den zentralen Identitätsspeicher. Jeder automatische Bezug von Personendaten aus dem IPDM erfolgt über diesen Verteiler. Ausgenommen ist der direkte Bezug von Personalstammdaten im SAP-Standard für die berechtigten SAP-Systeme.

<sup>3</sup> Die Personendaten gemäss Artikel 8 Absatz 1 Buchstabe c und Absatz 3 werden den Parlamentsdiensten zur Übernahme und zum Abgleich bereitgestellt.

<sup>4</sup>

Die Daten können weiteren bundesinternen Informationssystemen automatisch zur Übernahme und zum Abgleich bereitgestellt werden, sofern das jeweilige System:

- a. über eine Rechtsgrundlage und ein Bearbeitungsreglement nach Artikel 21 der Verordnung vom 14. Juni 1993[^13-1] zum Bundesgesetz über den Datenschutz (VDSG) verfügt; und
- b. beim Eidgenössischen Datenschutz- und Öffentlichkeitsbeauftragten angemeldet ist oder gemäss Artikel 18 VDSG nicht gemeldet werden muss.

<sup>4bis</sup> Die AHV-Nummer wird nur bereitgestellt, sofern ihre Verwendung der Zentralen Ausgleichsstelle nach Artikel 134<sup>ter</sup> der Verordnung vom 31. Oktober 1947[^13-2] über die Alters- und Hinterlassenenversicherung gemeldet wird.[^13-3]

<sup>5</sup> Die für die Publikation des Eidgenössischen Staatskalenders nötigen Daten nach Artikel 5 der Organisationsverordnung vom 29. Oktober 2008[^13-4] für die Bundeskanzlei werden regelmässig an die Bundeskanzlei übermittelt.

[^13-1]: [SR 235.11](https://fedlex.data.admin.ch/eli/cc/2022/568)
[^13-2]: [SR 831.101](https://fedlex.data.admin.ch/eli/cc/63/1185_1183_1185)
[^13-3]: Eingefügt durch Ziff. I der V vom 4. Mai 2022, in Kraft seit 1. Juni 2022 ([AS 2022 282](https://fedlex.data.admin.ch/eli/oc/2022/282)).
[^13-4]: [SR 172.210.10](https://fedlex.data.admin.ch/eli/cc/2008/719)

#### Art. 14

**Aufbewahrungsfrist für Personendaten**

<sup>1</sup> Ist eine Person aus dem Geltungsbereich dieser Verordnung ausgeschieden, so werden ihre Daten in den IAM-Systemen und den Verzeichnisdiensten spätestens nach zwei Jahren vernichtet.

<sup>2</sup> Vorbehalten bleiben die Bestimmungen über die Vernichtung von biometrischen Daten nach Artikel 2*a* MIG.[^14-1]

[^14-1]: Eingefügt durch Ziff. I der V vom 14. Nov. 2018, in Kraft seit 1. Jan. 2019 ([AS 2018 4739](https://fedlex.data.admin.ch/eli/oc/2018/752)).

## 5. Abschnitt: Datenbekanntgaben bei IAM-Systemen

#### Art. 15

**Datenbekanntgabe beim Anschluss eines Informationssystems an ein IAM-System**

<sup>1</sup> Wird ein bisher autonomes Informationssystem an ein IAM-System angeschlossen und diesem die Prüfung der Identität und bestimmter berechtigungsrelevanter Eigenschaften von Personen übertragen, so dürfen die entsprechenden Personendaten ins IAM-System importiert werden.

<sup>2</sup> Im IAM-System muss für jedes nachgelagerte Informationssystem eine Liste der Personendaten geführt werden, die es diesem aufgrund dieser Verordnung und der gesetzlichen Grundlagen des nachgelagerten Systems bekanntgeben darf.

#### Art. 16

**Datenbekanntgabe beim einzelnen Zugang**

Das IAM-System authentifiziert Personen, Maschinen oder Systeme, die den Zugang zu einem nachgelagerten Informationssystem verlangen, überprüft die notwendigen Identitätsdaten und die notwendigen weiteren Eigenschaften und Bestätigungen und leitet das Ergebnis der Prüfung mit den festgelegten Identitätsdaten, Eigenschaften und Bestätigungen an das nachgelagerte System weiter.

#### Art. 17

**Bekanntgabe von Personendaten an einen externen Betreiber**

<sup>1</sup> Wird ein Informationssystem des Bundes von einem externen Betreiber im Auftrag des Bundes betrieben oder müssen Personen nach Artikel 8 Absatz 1 oder 3 Buchstabe a auf fremde Informationssysteme zugreifen, so dürfen die dazu notwendigen Personendaten aus Personalinformationssystemen, dem zentralen Identitätsspeicher oder IAM-Systemen automatisiert dem externen Betreiber bekanntgegeben werden.

<sup>2</sup> Dazu erstellt die Stelle, die für das extern betriebene Informationssystem zuständig ist oder den Zugang auf das fremde Informationssystem benötigt, einen schriftlichen Antrag, der den betroffenen Personenkreis nennt, und stellt diesen via die zuständige Datenschutzverantwortliche oder den zuständigen Datenschutzverantwortlichen dem für das liefernde Informationssystem zuständigen Bundesorgan zu.

<sup>3</sup> Der Antrag enthält die schriftliche Verpflichtung der zuständigen Stelle nach Absatz 2, die Datenschutzgesetzgebung des Bundes einzuhalten, die Daten ausschliesslich für den beabsichtigten Zweck zu verwenden und diese nach dem Stand der Technik zu schützen. Dem für das liefernde Informationssystem zuständigen Bundesorgan ist ein Inspektionsrecht einzuräumen.

<sup>4</sup> Die betroffenen Personen müssen vorgängig informiert werden.

## 6. Abschnitt: Massnahmen zum Schutz der IAM-Systeme

#### Art. 18

**Anforderungen an die Informationssicherheit**

<sup>1</sup> Interne und externe Betreiber von Komponenten eines IAM-Systems müssen über dokumentierte Vorgaben für die Handhabung der Informationssicherheit und der Risiken verfügen. Insbesondere erlässt jedes verantwortliche Organ eines Systems nach dieser Verordnung ein Bearbeitungsreglement nach Artikel 21 VDSG[^18-1].

<sup>2</sup> IAM-Systeme, die nicht von Stellen nach Artikel 2 oder in deren Auftrag geführt werden, dürfen nur mit bundesinternen IAM-Systemen verbunden werden, wenn sie die vordefinierten Minimalanforderungen bezüglich der Informationssicherheit erfüllen.

<sup>3</sup> Für den Zugang zu bestimmten Informationssystemen können von der zuständigen Stelle oder vom Bereich DTI der BK die Einhaltung höherer Anforderungen und bestimmte Zertifizierungen verlangt werden.

<sup>4</sup> Der Bereich DTI der BK regelt in Weisungen die einzuhaltenden Sicherheitsanforderungen und Verfahren.

[^18-1]: [SR 235.11](https://fedlex.data.admin.ch/eli/cc/2022/568)

#### Art. 19

**Datenbearbeitung beim Ausstellen von elektronischen Identifikationsmitteln**

<sup>1</sup> Der Aussteller eines Identifikationsmittels darf für die Prüfung der Identität von der antragstellenden Person die Vorlage eines Passes, der Schweizer Identitätskarte oder eines für die Einreise in die Schweiz anerkannten Ausweisdokuments verlangen.

<sup>2</sup> Er kann von der Person ein Foto oder eine Unterschrift aufnehmen oder im System bereits hinterlegte Fotos oder Unterschriften zum Abgleich mit dem Ausweisdokument verwenden.

<sup>3</sup> Die zur Identifikation verwendeten Daten werden zusammen mit den Daten zum Identifikationsmittel gespeichert. Wenn es die Sicherheitsanforderungen für das betreffende Identifikationsmittel verlangen, kann auch ein Bild der für die Identifikation verwendeten Ausweisdokumente gespeichert werden.

## 7. Abschnitt: Verbund von IAM-Systemen

#### Art. 20

**IAM-Verbund des Bundes**

Die IAM-Systeme der Bundesverwaltung können untereinander und mit den IAM-Systemen der Parlamentsdienste oder der Armee zu einem Gesamtsystem verbunden werden.

#### Art. 21

**Anschluss externer IAM-Systeme: Voraussetzungen**

Nachstehende externe IAM-Systeme können für den Zugang der in ihnen geführten Personen zu den Ressourcen des Bundes an die IAM-Systeme des Bundes angeschlossen werden, sofern sie die Bedingungen und Verfahren nach den Artikeln 22 und 23 einhalten:

- a. IAM-Systeme mit kantonalen und kommunalen Mitarbeiterinnen und Mitarbeitern nach Artikel 9 Buchstabe a;
- b. vom Bereich DTI der BK anerkannte IAM-Systeme, die für den Identitätsverbund im E‑Government vorgesehen sind;
- c. ausländische IAM-Systeme oder Identitätsverbunde, deren gegenseitige Anbindung in einem Staatsvertrag vorgesehen ist; oder
- d. Attribut-Register, die Angaben zu beruflichen Funktionen gemäss Anhang Buchstabe b für den Abruf bereitstellen.

#### Art. 22

**Anschluss externer IAM-Systeme: Antrag**

<sup>1</sup> Die zuständige Stelle richtet den Antrag auf Anschluss eines externen IAM-Systems an ein IAM-System des Bundes an das nach Artikel 5 verantwortliche Bundesorgan.

<sup>2</sup>

Der Antrag enthält insbesondere:

- a. den Zweck des Anschlusses;
- b. die Rechtsgrundlagen und die weiteren Regelungen für das anzuschliessende System;
- c. eine technische Beschreibung des anzuschliessenden Systems;
- d. die Belege für die Einhaltung der Anforderungen an die Informationssicherheit nach Artikel 18 Absatz 2 oder 3;
- e. eine zustimmende Stellungnahme des zuständigen Departements;
- f. die unterstützende Stellungnahme mindestens einer Stelle, die für ein nachgelagertes System verantwortlich ist, auf das mittels des anzuschliessenden IAM-Systems zugegriffen werden soll.

#### Art. 23

**Anschluss externer IAM-Systeme: Entscheid**

<sup>1</sup> Das für ein IAM-System des Bundes verantwortliche Bundesorgan ist für den Entscheid über den Antrag zuständig.

<sup>2</sup> Soll das externe IAM-System über das direkt angeschlossene IAM-System hinaus auch mit anderen IAM-Systemen des Bundes verbunden sein, so ist für die Gutheissung des Antrags das Einverständnis des Bereichs DTI der BK erforderlich.

<sup>3</sup> Das verantwortliche Bundesorgan schliesst mit der antragstellenden Stelle die Vereinbarung ab, informiert der Bereich DTI der BK und gibt dem zuständigen Leistungserbringer den Auftrag für den Anschluss.

<sup>4</sup> Anträge auf Änderungen oder Abschaltungen werden wie Anschlussanträge behandelt.

#### Art. 24

**Anschluss von IAM-Systemen des Bundes an externe IAM-Systeme**

<sup>1</sup>

IAM-Systeme des Bundes können als Lieferant von Identitäts- und Authentifizierungsinformationen an ein externes IAM-System oder einen externen Identitätsverbund angeschlossen werden, wenn die folgenden Voraussetzungen erfüllt sind:

- a. Der Anschluss dient dazu, Personen nach Artikel 8 oder 9 den Zugang zu im Auftrag des Bundes von Externen betriebenen Informationssystemen oder zu fremden Informationssystemen zu gewähren, auf die sie zur Erfüllung ihrer gesetzlichen Aufgaben zugreifen müssen.
- b. Es besteht eine Vereinbarung zwischen dem Bund und dem Betreiber des empfangenden Informationssystems, welche die Beziehung in rechtlicher, organisatorischer und technischer Hinsicht regelt.
- c. Die Verbindung ist so konfiguriert, dass sie einzig für den Zugang zu bestimmten, vordefinierten Informationssystemen verwendet werden kann.

<sup>2</sup> Der Bereich DTI der BK regelt in Weisungen die einzuhaltenden Sicherheitsanforderungen in Absprache mit dem für das entsprechende IAM-System verantwortlichen Organ und überprüft die Einhaltung periodisch.

<sup>3</sup> Ebenfalls möglich ist die Teilnahme an einem internationalen Identitätsverbund auf der Basis eines Staatsvertrags, sofern gewährleistet ist, dass die Anforderungen an die Informationssicherheit eingehalten werden.

## 8. Abschnitt: Protokollierung, Statistiken und Dokumentation

#### Art. 25

**Protokollierung bei IAM-Systemen**

<sup>1</sup> Das IAM-System protokolliert Authentifizierungen und die Bekanntgabe von Identitätsdaten nur in dem Umfang und nur so lange, wie es für einen sicheren und geordneten Betrieb der eigenen und der nachgelagerten Systeme erforderlich ist.

<sup>2</sup> Protokolldaten werden spätestens nach zwei Jahren vernichtet. Es werden keine Protokolldaten archiviert.

<sup>3</sup> Vorbehalten bleibt eine umfangreichere Protokollierung, eine längere Aufbewahrung oder eine Archivierung der Protokolldaten für die Zugriffe auf ein bestimmtes Informationssystem auf der Basis einer besonderen rechtlichen Grundlage.

#### Art. 26

**Weitergabe von Protokolldaten von IAM-Systemen**

<sup>1</sup> Die Betreiber von IAM-Systemen des Bundes dürfen Protokolldaten über Authentifizierungen und über die Bekanntgabe von Identitätsdaten der für das jeweilige nachgelagerte System zuständigen Stelle bekanntgeben.

<sup>2</sup> Dazu ist ein schriftlicher Antrag mit Angabe des Zwecks und der rechtlichen Grundlage via die zuständige Datenschutzverantwortliche oder den zuständigen Datenschutzverantwortlichen an das für das IAM-System verantwortliche Organ zu richten. Die Lieferung kann mit den gleichen Angaben auch in der Betriebsvereinbarung zwischen dem verantwortlichen Organ und dem Betreiber des IAM-Systems vereinbart werden.

<sup>3</sup> Die Lieferung kann nach den für den bundesinternen Bezug von Informatikdienstleistungen geltenden Grundsätzen kostenpflichtig sein.

#### Art. 27

**Statistiken bei IAM-Systemen**

Für die Bedürfnisse der für das IAM-System oder für das nachgelagerte Informationssystem zuständigen Stelle dürfen Zugangsstatistiken erstellt werden. Personendaten sind zu anonymisieren.

#### Art. 28

**Inventar und Dokumentation**

<sup>1</sup>

Jedes Organ, das für ein IAM-System, für einen Verzeichnisdienst oder für ein anderes Informationssystem nach dieser Verordnung verantwortlich ist, führt ein Inventar über:

- a. seine IAM-Systeme und Verzeichnisdienste;
- b. die Informationssysteme, aus denen automatisch Daten bezogen werden;
- c. die Informationssysteme, denen Daten automatisch zur Verfügung gestellt werden;
- d. alle IAM-Systeme, mit denen sein IAM-System verbunden ist.

<sup>2</sup> Wichtige Dokumente und Belege, insbesondere die Anträge nach dieser Verordnung, müssen mindestens so lange aufbewahrt werden, wie sie gelten.

## 9. Abschnitt: Schlussbestimmungen

#### Art. 29

**Vollzug**

Der Bereich DTI der BK erlässt die administrativen und technischen Weisungen zum Aufbau und zum Betrieb der IAM-Systeme des Bundes.

#### Art. 30

**Aufhebung eines anderen Erlasses**

Die Verordnung vom 6. Dezember 2013[^30-1] über die vom BIT betriebenen Verzeichnisdienste des Bundes wird aufgehoben.

[^30-1]: [[AS 2013 4553](https://fedlex.data.admin.ch/eli/oc/2013/811)]

#### Art. 31

**Inkrafttreten**

Diese Verordnung tritt am 1. Januar 2017 in Kraft.

Anhang*[^t-1]*

(Art. 11 Abs. 1 und 4 sowie 13 Abs. 1 und 2)

## Datenkategorien

[^t-1]: Bereinigt gemäss Ziff. II der V vom 14. Nov. 2018 ([AS 2018 4739](https://fedlex.data.admin.ch/eli/oc/2018/752)) und Ziff. II der V vom 4. Mai 2022, in Kraft seit 1. Juni 2022 ([AS 2022 282](https://fedlex.data.admin.ch/eli/oc/2022/282)).

Vorbemerkung: Zur Bedeutung der Sterne (\*) siehe Artikel 11 Absatz 4.

<table>
<tr><th></th><th>Verzeichnis-Dienste</th><th>IAM-Systeme, mit Personen nach Art. 8 und 9 Bst. a</th><th>IAM-Systeme mit Personen nach Art. 9 Bst. b</th></tr>
<tr><td>a. Angaben zur Person</td><td></td><td></td><td></td></tr>
<tr><td>1. derzeitige(r) Familienname(n)\*</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>2. derzeitige(r) Vorname(n)\*</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>3. Geburtsdatum</td><td></td><td>x</td><td>x</td></tr>
<tr><td>4. Geschlecht</td><td></td><td>x</td><td>x</td></tr>
<tr><td>5. Anrede\*</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>6. Titel\*</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>7. Initialen\*</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>8. Lokale Personenidentifikatoren</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>9. Berufsbezeichnung\*</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>10. Korrespondenzsprache\*</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>11. Gesichtsbild für Ausweise</td><td>x</td><td>x</td><td></td></tr>
<tr><td>12. AHV-Nummer</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>b. Angaben zum Verhältnis zum Arbeit-/Auftraggeber</td><td></td><td></td><td></td></tr>
<tr><td>1. Anstellungsverhältnis (intern/extern)\*</td><td>x</td><td>x</td><td></td></tr>
<tr><td>2. Informationen zur Organisation und zu den Planstellen\*</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>3. künftige Zuordnung zu einer Organisationseinheit</td><td>x</td><td>x</td><td></td></tr>
<tr><td>4. Personalkategorie</td><td></td><td>x</td><td></td></tr>
<tr><td>5. Personalnummer (auch kantonale)</td><td>x</td><td>x</td><td></td></tr>
<tr><td>6. Funktion\*</td><td>x</td><td>x</td><td></td></tr>
<tr><td>7. Stellenbezeichnung\*</td><td>x</td><td>x</td><td></td></tr>
<tr><td>8. Kennung des Personalinformationssystems (Quelle)</td><td>x</td><td>x</td><td></td></tr>
<tr><td>9. Eintritts- und Austrittsdatum</td><td>x</td><td>x</td><td></td></tr>
<tr><td>[tab]</td><td></td><td></td><td></td></tr>
<tr><td>10. Ausweis- und/oder Badgenummer</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>c. Kontaktangaben</td><td></td><td></td><td></td></tr>
<tr><td>1. Arbeitsort und geschäftliche Postadresse\*</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>2. Büronummer\*</td><td>x</td><td></td><td></td></tr>
<tr><td>3. geschäftliche Adressierungselemente\* wie E‑Mail‑Adresse\*, Telefonnummern\*, Faxnummer\*, VOIP-Adresse\*</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>4. externe Adressierungselemente\* (für Mitarbeiter/innen und Beauftragte\*) oder private Adressierungselemente</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>d. Angaben zu beruflichen Funktionen</td><td></td><td></td><td></td></tr>
<tr><td>1. Einträge aus offiziellen Berufsregistern (Arzt/Ärztin, Urkundsperson, Anwalt/Anwältin usw.)</td><td></td><td>x</td><td>x</td></tr>
<tr><td>2. Funktionen gemäss Handelsregister und weiteren Vertretungsregistern</td><td></td><td>x</td><td>x</td></tr>
<tr><td>e. technische Angaben</td><td></td><td></td><td></td></tr>
<tr><td>1. Zugeordnete Geräte, Anschlüsse, Systeme, Anwendungen usw.</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>2. Adressierungselemente, Kennnummern usw.</td><td>x</td><td></td><td></td></tr>
<tr><td>3. Systemsprache der Geräte, Anschlüsse usw.</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>4. öffentliche Schlüssel der digitalen Zertifikate\*</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>5. Berechtigungsgruppen</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>6. Namen für Anmeldung an den IT-Systemen</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>7. Passwort(e)</td><td></td><td>x</td><td>x</td></tr>
<tr><td>8. Letztes Login</td><td></td><td>x</td><td>x</td></tr>
<tr><td>9. Fehlgeschlagene Login-Versuche</td><td></td><td>x</td><td>x</td></tr>
<tr><td>10. Status (aktiv/passiv)</td><td></td><td>x</td><td>x</td></tr>
<tr><td>f. Daten über die Personensicherheitsprüfung, sofern diese zu einer auflagenfreien Sicherheitserklärung geführt hat oder die entscheidende Instanz einen positiven Entscheid gefällt hat</td><td></td><td></td><td></td></tr>
<tr><td>1. Prüfstufe</td><td></td><td>x</td><td></td></tr>
<tr><td>2. Zeitpunkt der nächsten Wiederholung der Personensicherheitsprüfung</td><td></td><td>x</td><td></td></tr>
<tr><td>[tab] g. Daten, die nur in dem von der Führungsunterstützungsbasis der Schweizer Armee betriebenen IAM-System (Art. 5 Abs. 1 Bst. c) bearbeitet werden dürfen</td><td></td><td></td><td></td></tr>
<tr><td>1. …</td><td></td><td></td><td></td></tr>
<tr><td>2. besondere biometrische Personenmerkmale: Irisbild, Venenscan, Fingerabdruck, Handabdruck, Gesichtsformmerkmale und Stimmprofil (Art. 2*a* MIG)</td><td></td><td>x</td><td></td></tr>
</table>
