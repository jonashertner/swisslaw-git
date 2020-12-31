---
sr: "211.432.11"
title: Technische Verordnung des EJPD und des VBS vom 28. Dezember 2012 über das Grundbuch (TGBV)
short: TGBV
eli: "https://fedlex.data.admin.ch/eli/cc/2013/3"
language: de
version: 2013-02-01
adopted: 2012-12-28
in_force: 2013-02-01
source: "https://fedlex.data.admin.ch/filestore/fedlex.data.admin.ch/eli/cc/2013/3/20130201/de/xml/fedlex-data-admin-ch-eli-cc-2013-3-20130201-de-xml-1.xml"
url: "https://www.fedlex.admin.ch/eli/cc/2013/3/20130201/de"
---

> Nicht amtliche Wiedergabe der konsolidierten Fassung (Fedlex). Massgebend ist die Veröffentlichung in der Amtlichen Sammlung (Art. 15 PublG, SR 170.512).

# Technische Verordnung des EJPD und des VBS über das Grundbuch

(TGBV)

vom 28. Dezember 2012 (Stand am 1. Februar 2013)

Das Eidgenössische Justiz- und Polizeidepartement (EJPD) und das Eidgenössische Departement für Verteidigung, Bevölkerungsschutz und Sport (VBS),

gestützt auf Artikel 949*a* Absatz 3 des Zivilgesetzbuches[^ingress-1], die Artikel 19 Absatz 4, 40 Absatz 2 und 41 Absatz 1 der Grundbuchverordnung vom 23. September 2011[^ingress-2] (GBV) und Artikel 6*a* Absatz 2 der Verordnung vom 18. November 1992[^ingress-3] über die amtliche Vermessung (VAV),

verordnen:

[^ingress-1]: [SR 210](https://fedlex.data.admin.ch/eli/cc/24/233_245_233)
[^ingress-2]: [SR 211.432.1](https://fedlex.data.admin.ch/eli/cc/2011/667)
[^ingress-3]: [SR 211.432.2](https://fedlex.data.admin.ch/eli/cc/1992/2446_2446_2446)

## 1. Abschnitt: Gegenstand

#### Art. 1

Diese Verordnung regelt:

- a. das Datenmodell für das Grundbuch (eGRISDM; Anhang 1);
- b. das Datenmodell für den Datenaustausch zwischen der amtlichen Vermessung und dem Grundbuch (AVGBSDM; Anhang 2);
- c. die Schnittstelle für den Bezug und den Austausch von Grundbuchdaten (GBDBS; Anhang 3);
- d. die Schnittstelle für den Datenaustausch zwischen der amtlichen Vermessung und dem Grundbuch (AVGBS);
- e. die eidgenössische Grundstücksidentifikation (E-GRID);
- f. die Datenformate von Dokumenten für den elektronischen Geschäftsverkehr mit den Grundbuchämtern;
- g. die alternativen Übermittlungsverfahren für den elektronischen Geschäftsverkehr (Anhang 4);
- h. die Langzeitsicherung.

## 2. Abschnitt: Zuständigkeiten

#### Art. 2

**EJPD**

<sup>1</sup>

Das EJPD definiert für das Grundbuch:

- a. das eGRISDM und die Anforderungen an die darin zu haltenden Daten sowie den Geltungsbeginn der jeweils neuen Version;
- b. die Datenbeschreibungssprache;
- c. die GBDBS und den Geltungsbeginn der jeweils neuen Version sowie das Ende der Gültigkeit von vorangehenden Versionen;
- d. den Kriterienkatalog für die Anerkennung von alternativen Plattformen für den elektronischen Geschäftsverkehr mit dem Grundbuchamt.

<sup>2</sup> Es anerkennt alternative Plattformen für den elektronischen Geschäftsverkehr mit dem Grundbuchamt.

#### Art. 3

**EJPD und VBS**

<sup>1</sup>

Das EJPD und das VBS definieren für den Datenaustausch zwischen der amtlichen Vermessung und dem Grundbuch:

- a. das AVGBSDM und den Geltungsbeginn der jeweils neuen Version;
- b. die Datenbeschreibungssprache;
- c. die AVGBS.

<sup>2</sup> Sie definieren die E-GRID.

#### Art. 4

**Eidgenössisches Amt für Grundbuch- und Bodenrecht**

<sup>1</sup> Das Eidgenössische Amt für Grundbuch- und Bodenrecht (EGBA) sorgt für die Verbreitung des eGRISDM und der GBDBS sowie der entsprechenden Dokumentation.

<sup>2</sup> Es erarbeitet unter Mitwirkung der Kantone, der Systemhersteller und weiterer Beteiligter für die Weiterentwicklung des informatisierten Grundbuchs und dessen Vernetzung mit anderen Systemen eine Planung. Es passt die Planung jährlich an.

#### Art. 5

**EGBA und Eidgenössische Vermessungsdirektion**

<sup>1</sup> Das EGBA und die Eidgenössische Vermessungsdirektion (V+D) sorgen für die Verbreitung des AVGBSDM und der AVGBS sowie der entsprechenden Dokumentation.

<sup>2</sup> Sie stellen unter Mitwirkung der Kantone und der Systemhersteller die Weiterentwicklung des AVGBSDM sicher.

#### Art. 6

**Kantone**

<sup>1</sup> Die Kantone integrieren die im Anhang 1 als obligatorisch bezeichneten Elemente des eGRISDM in ihre Grundbuchsysteme.

<sup>2</sup> Sie realisieren die im Anhang 3 als obligatorisch bezeichneten Elemente der GBDBS in ihren Grundbuchsystemen.

<sup>3</sup> Sie stellen den Datenaustausch zwischen dem Grundbuch und der amtlichen Vermessung im Umfang des AVGBSDM sicher.

## 3. Abschnitt: Datenbeschreibungssprachen

#### Art. 7

<sup>1</sup> Das eGRISDM und das AVGBSDM werden in der Beschreibungssprache INTERLIS gemäss Schweizer Norm SN 612031, Ausgabe 2006-05[^7-1] beschrieben.

<sup>2</sup> Die GBDBS wird in XML beschrieben.

[^7-1]: Diese Norm kann kostenlos eingesehen und gegen Bezahlung bezogen werden bei der Schweizerischen Normen-Vereinigung (SNV), Sulzerallee 70, 8404 Winterthur; www.snv.ch.

## 4. Abschnitt: Das Datenmodell für das Grundbuch

#### Art. 8

<sup>1</sup> Das eGRISDM legt die Datentypen und den Detaillierungsgrad der Daten des Grundbuchs sowie die Beziehungen unter den Daten fest. Es bildet die Grundlage für die GBDBS.

<sup>2</sup> Der Detaillierungsgrad der im Anhang 1 als obligatorisch bezeichneten Elemente des eGRISDM darf nicht eingeschränkt werden. Erweiterungen dürfen die vorhandenen obligatorischen Elemente nicht ersetzen.

<sup>3</sup>

Das eGRISDM umfasst die folgenden Teilmodelle:

- a.

  obligatorische Teilmodelle:

  - 1\. Hauptbuch mit den dazugehörenden Codetabellen,
  - 2\. Tagebuch mit den dazugehörenden Codetabellen;

- b.

  fakultative Teilmodelle:

  - 1\. Personen-Stamm,
  - 2\. Notizen.

<sup>4</sup> Die obligatorischen Teilmodelle des eGRISDM müssen in ihrer jeweils geltenden Version in allen Grundbuchsystemen innerhalb von 24 Monaten ab Geltungsbeginn installiert und verfügbar gemacht werden.

## 5. Abschnitt: Das Datenmodell für den Datenaustausch zwischen der amtlichen Vermessung und dem Grundbuch

#### Art. 9

<sup>1</sup> Das AVGBSDM beschreibt die zwischen der amtlichen Vermessung und dem Grundbuch auszutauschenden Daten.

<sup>2</sup> Der Detaillierungsgrad des AVGBSDM darf nicht eingeschränkt werden. Erweiterungen dürfen die vorhandenen Elemente nicht ersetzen.

<sup>3</sup> Erweiterungen des AVGBSDM dürfen dem Datenmodell der amtlichen Vermessung (Art. 6 VAV) und dem eGRISDM nicht widersprechen.

<sup>4</sup>

Das AVGBSDM ist in folgende Teilmodelle unterteilt:

- a. Eigentumsverhältnisse;
- b. Grundstücksbeschreibung;
- c. Mutationstabelle;
- d. Vollzugsgegenstände.

<sup>5</sup> Es identifiziert die Grundstücke mittels E-GRID.

<sup>6</sup> Es muss in seiner jeweils geltenden Version in allen Grundbuchsystemen und in der amtlichen Vermessung innerhalb von 24 Monaten ab Geltungsbeginn installiert und verfügbar gemacht werden.

## 6. Abschnitt: Die Schnittstelle für den Bezug und den Austausch von Grundbuchdaten

#### Art. 10

<sup>1</sup>

Die GBDBS ermöglicht:

- a. die Übertragung der rechtswirksamen und der gelöschten Daten des Hauptbuchs, des Tagebuchs und der Belege in strukturierter und maschinenlesbarer Form;
- b. die Erstellung des gesamtschweizerischen Grundstücksindexes nach Artikel 27 Absatz 3 GBV;
- c. den Export der rechtswirksamen und der gelöschten Daten des Hauptbuchs für die langfristige Sicherung durch den Bund;
- d. den elektronischen Geschäftsverkehr mit den Grundbuchämtern.

<sup>2</sup> Die Datenstrukturen richten sich in Inhalt und Detaillierungsgrad nach dem eGRISDM.

<sup>3</sup> Das EGBA oder eine von ihm beauftragte Organisation ausserhalb der Bundesverwaltung kann unter Mitwirkung der Kantone die GBDBS weiterentwickeln. Es kann zu diesem Zweck eine aus Vertretern der Kantone, der amtlichen Vermessung, der betroffenen Systemhersteller und weiterer Fachkreise bestehende Begleitgruppe einsetzen.

<sup>4</sup> Die Systemhersteller nehmen Änderungsanträge entgegen, erstellen eine bereinigte Liste und unterbreiten diese der Begleitgruppe zur Verabschiedung. Nach Umsetzung der verabschiedeten Anträge, Prüfung der neuen Version im praktischen Einsatz und Abnahme durch die Begleitgruppe wird die neue Version dem EJPD zur Genehmigung unterbreitet.

<sup>5</sup> Die GBDBS muss in ihrer jeweils geltenden Version in allen Grundbuchsystemen innerhalb von 24 Monaten ab Geltungsbeginn installiert und verfügbar gemacht werden.

## 7. Abschnitt: Die Schnittstelle für den Datenaustausch zwischen der amtlichen Vermessung und dem Grundbuch

#### Art. 11

**Definition**

Die AVGBS wird definiert durch das AVGBSDM und das Transferformat, das sich aus dem AVGBSDM und der SN 612031, Ausgabe 2006-05[^11-1] ergibt.

[^11-1]: Diese Norm kann kostenlos eingesehen und gegen Bezahlung bezogen werden bei der Schweizerischen Normen-Vereinigung (SNV), Sulzerallee 70, 8404 Winterthur; www.snv.ch.

#### Art. 12

**Einsatz**

<sup>1</sup> Die AVGBS muss in ihrer jeweils geltenden Version in allen Grundbuchsystemen und in der amtlichen Vermessung innerhalb von 24 Monaten ab Geltungsbeginn installiert und verfügbar gemacht werden.

<sup>2</sup> Anstelle der AVGBS können die Kantone auf andere Weise dafür sorgen, dass die im AVGBSDM definierten Daten der amtlichen Vermessung im Rahmen des ordentlichen Betriebs vollständig in das Grundbuch übertragen werden.

## 8. Abschnitt: Anforderungen an die Informatiksysteme

#### Art. 13

**Anforderungen für die Grundbuchführung**

Die für die Grundbuchführung eingesetzten Informatiksysteme müssen:

- a. die Daten über die GBDBS liefern können;
- b. die rechtswirksamen und die gelöschten Hauptbuchdaten für die langfristige Sicherung in eine GBDBS-Datei exportieren können;
- c. alle obligatorischen Identifikatoren gemäss eGRISDM erzeugen und zuordnen können.

#### Art. 14

**Datenhaltung der Grundbuchsysteme**

<sup>1</sup> Die Haltung der Grundbuchdaten richtet sich bezüglich des Inhalts, des Detaillierungsgrades und der Vollständigkeit der Daten nach dem eGRISDM.

<sup>2</sup> Bei der Überführung des Papier-Grundbuchs in das informatisierte Grundbuch müssen alle rechtswirksamen Daten der einzelnen Abteilungen übernommen werden. Gelöschte Daten und entsprechende Hinweise auf die Belege müssen nicht erfasst werden.

#### Art. 15

**Anforderungen für die Grundbuchführung und die amtliche Vermessung**

Die für die Grundbuchführung und für die amtliche Vermessung eingesetzten Informatiksysteme müssen Daten im Umfang und im Detaillierungsgrad des AVGBSDM beziehen und liefern können.

## 9. Abschnitt: Die eidgenössische Grundstücksidentifikation

#### Art. 16

**Grundsätze**

<sup>1</sup> Die E-GRID ist landesweit eindeutig, enthält keine klassifizierenden Merkmale und wird nur einmal vergeben.

<sup>2</sup> Sie dient als Grundstücksidentifikator im Datenmodell der amtlichen Vermessung, im eGRISDM und im AVGBSDM.

<sup>3</sup> Sie bildet die Grundlage für den grundstücksbezogenen Datenaustausch.

<sup>4</sup> Sie muss in grundstücksbezogenen Auskunftssystemen als Suchbegriff verwendet werden können.

#### Art. 17

**Zuordnung zu den Grundstücken**

<sup>1</sup> Die E-GRID für die Liegenschaften sowie für die flächenmässig ausgeschiedenen selbstständigen und dauernden Rechte und Bergwerke werden durch die amtliche Vermessung erstellt und vergeben. Für die restlichen Grundstücke wird sie durch das Grundbuchamt erstellt und vergeben. Die Kantone können abweichende Vorschriften erlassen.

<sup>2</sup> Bei Veränderungen am Bestand oder am Gebiet der Gemeinden behalten alle betroffenen Grundstücke ihre E-GRID.

<sup>3</sup> Bei der Teilung eines Grundstücks behält in der Regel ein Teil die bestehende E‑GRID. Bei der Vereinigung von mehreren Grundstücken wird für das neue Grundstück in der Regel die E-GRID eines der beteiligten Grundstücke weiterverwendet.

## 10. Abschnitt: Datenformate von Dokumenten für den elektronischen Geschäftsverkehr mit den Grundbuchämtern

#### Art. 18

**Eingaben an das Grundbuchamt**

Zulässige Datenformate für Eingaben an das Grundbuchamt sind:

- a. für Grundbuchanmeldungen, die nicht bereits im Rechtsgrundausweis enthalten sind: PDF mit einer qualifizierten elektronischen Signatur nach Artikel 14 Absatz 2<sup>bis</sup> des Obligationenrechts[^18-1] (OR); die in der Anmeldung enthaltenen Angaben können zusätzlich im Format XML beigefügt werden;
- b. für öffentlich beurkundete Rechtsgrundausweise: die Formate nach der Verordnung des EJPD vom 2. Dezember 2011[^18-2] über die anerkannten Formate im Bereich der elektronischen öffentlichen Beurkundung;
- c. für Rechtsgrundausweise in schriftlicher Form einschliesslich Beilagen: PDF/A mit einer qualifizierten elektronischen Signatur nach Artikel 14 Absatz 2<sup>bis</sup> OR;
- d. für Gesuche um Ausstellung eines Grundbuchauszugs oder einer Eintragungsbescheinigung: PDF mit einer qualifizierten elektronischen Signatur nach Artikel 14 Absatz 2<sup>bis</sup> OR; vorbehalten bleiben Gesuche von authentifizierten Teilnehmerinnen oder Teilnehmern im Rahmen von alternativen Übermittlungsverfahren und kantonalen Grundbuch-Informationssystemen.

[^18-1]: [SR 220](https://fedlex.data.admin.ch/eli/cc/27/317_321_377)
[^18-2]: [[AS 2011 6265](https://fedlex.data.admin.ch/eli/oc/2011/882). [AS 2013 2347](https://fedlex.data.admin.ch/eli/oc/2013/495)Art. 20]. Siehe heute: die V des EJPD vom 8. Dez. 2017 über die Erstellung elektronischer öffentlicher Urkunden und elektronischer Beglaubigungen ([SR 211.435.11](https://fedlex.data.admin.ch/eli/cc/2018/30)).

#### Art. 19

**Zustellungen des Grundbuchamtes**

Formate für Zustellungen des Grundbuchamtes an die Beteiligten sind:

- a. für Eintragungsbescheinigungen und Anzeigen von grundbuchlichen Verfügungen: PDF/A oder XML; auf Verlangen der Empfängerin oder des Empfängers kann das Dokument in PDF/A mit einer qualifizierten elektronischen Signatur nach Artikel 14 Absatz 2<sup>bis</sup> OR[^19-1] versehen werden; zusätzlich können ihm Angaben im Format XML beigefügt werden;
- b. für Fristansetzungen und Abweisungsverfügungen: PDF/A mit einer qualifizierten elektronischen Signatur nach Artikel 14 Absatz 2<sup>bis</sup> OR;
- c. für Grundbuchauszüge: PDF/A oder XML; auf Verlangen der Empfängerin oder des Empfängers kann der Auszug mit einer qualifizierten elektronischen Signatur nach Artikel 14 Absatz 2<sup>bis</sup> OR versehen werden; zusätzlich können ihm Angaben im Format XML beigefügt werden.

[^19-1]: [SR 220](https://fedlex.data.admin.ch/eli/cc/27/317_321_377)

#### Art. 20

**Zulässige Datenformate**

<sup>1</sup> Die zulässigen Versionen des Datenformats PDF/A richten sich nach dem Anhang der Verordnung des EJPD vom 2. Dezember 2011[^20-1] über die anerkannten Formate im Bereich der elektronischen öffentlichen Beurkundung.

<sup>2</sup> Die Formate PDF und XML können in jeder gängigen Version verwendet werden.

[^20-1]: [[AS 2011 6265](https://fedlex.data.admin.ch/eli/oc/2011/882). [AS 2013 2347](https://fedlex.data.admin.ch/eli/oc/2013/495)Art. 20]. Siehe heute: die V des EJPD vom 8. Dez. 2017 über die Erstellung elektronischer öffentlicher Urkunden und elektronischer Beglaubigungen ([SR 211.435.11](https://fedlex.data.admin.ch/eli/cc/2018/30)).

## 11. Abschnitt: Alternative Übermittlungsverfahren

#### Art. 21

**Anerkennung von alternativen Plattformen**

Das EJPD anerkennt eine alternative Plattform für den elektronischen Geschäftsverkehr mit dem Grundbuchamt, wenn sie:

- a. für Signatur und Verschlüsselung Maschinenzertifikate (SSL-Zertifikate) einsetzt, die von einer anerkannten Anbieterin von Zertifizierungsdiensten nach dem Bundesgesetz vom 19. Dezember 2003[^21-1] über die elektronische Signatur (anerkannte Anbieterin) stammen;
- b. nachweisen kann, welche Dokumente übermittelt beziehungsweise für die Erledigung der spezifizierten Aufgabe verwendet wurden;
- c. die Eingaben und Zustellungen in geeigneter Weise vor unberechtigtem Zugriff durch Dritte schützt;
- d. imstande ist, nach anerkannten Regeln bezüglich sicherer Übermittlung zu kommunizieren; dabei wird der Stand der Technik, wie er insbesondere in den eCH-Standards[^21-2] zum Ausdruck kommt, berücksichtigt;
- e über ausreichende Finanzmittel oder -garantien verfügt.

[^21-1]: [[AS 2004 5085](https://fedlex.data.admin.ch/eli/oc/2004/788), [2008 3437](https://fedlex.data.admin.ch/eli/oc/2008/447)Ziff. II 55. [AS 2016 4651](https://fedlex.data.admin.ch/eli/oc/2016/752)Anhang Ziff. I]. Siehe heute: das BG vom 18. März 2016 ([SR 943.03](https://fedlex.data.admin.ch/eli/cc/2016/752)).
[^21-2]: www.eCH.ch

#### Art. 22

**Anerkennungsverfahren**

<sup>1</sup> Anerkennungsgesuche sind beim EGBA einzureichen.

<sup>2</sup>

Das Gesuch enthält Angaben über:

- a. die Erfüllung des Kriterienkatalogs, namentlich der technischen und organisatorischen Massnahmen zur Gewährleistung der Datenintegrität, des Datenschutzes und der Datensicherheit während der Übermittlung und auf der Plattform;
- b. die Nachvollziehbarkeit der Übermittlung;
- c. die Verfügbarkeit des Systems.

<sup>3</sup>

Dem Gesuch sind beizulegen:

- a. eine Beschreibung des Systemaufbaus;
- b. die Ergebnisse der angewandten Tests und Überprüfungen.

<sup>4</sup> Das EGBA kann für die Prüfung der Anerkennungsvoraussetzungen verwaltungsexterne Fachpersonen beiziehen. Die Kosten gehen zulasten der Gesuchstellerin.

<sup>5</sup> Das EJPD entzieht die Anerkennung, wenn es feststellt, dass die Anerkennungsvoraussetzungen nicht mehr erfüllt sind.

<sup>6</sup> Die Entscheidgebühr wird nach Zeitaufwand berechnet; der Stundenansatz beträgt 250 Franken. Im Übrigen sind die Bestimmungen der Allgemeinen Gebührenverordnung vom 8. September 2004[^22-1] anwendbar.

[^22-1]: [SR 172.041.1](https://fedlex.data.admin.ch/eli/cc/2004/677)

## 12. Abschnitt: Langzeitsicherung

#### Art. 23

<sup>1</sup> Die Kantone liefern dem Bundesamt für Justiz (BJ) zum Zweck der Langzeitsicherung mindestens einmal pro Kalenderjahr zu einem frei wählbaren Zeitpunkt den gesamten Bestand der rechtswirksamen und der gelöschten Daten des Hauptbuchs, strukturiert nach den Vorgaben der GBDBS.

<sup>2</sup> Die Lieferung umfasst entweder eine Datei für das ganze Kantonsgebiet oder mehrere Dateien für je ein Teilgebiet (z.B. Grundbuchkreis).

<sup>3</sup> Die Übermittlung der Dateien erfolgt über eine gesicherte Verbindung mit einem vom Bund zur Verfügung gestellten Computerprogramm sowie einem qualifizierten Signaturzertifikat nach dem Bundesgesetz vom 19. Dezember 2003[^23-1] über die elektronische Signatur und einem Authentifizierungszertifikat der gleichen Anbieterin.

<sup>4</sup> Jeder Kanton bestimmt und meldet dem BJ pro Gebietseinheit eine für die Langzeitsicherung verantwortliche Person, welche dem Bund die von ihr signierte Datei übermittelt und mit ihrer Signatur bestätigt, dass es sich um den zu sichernden Datenbestand seines Grundbuchsystems handelt.

[^23-1]: [SR 943.03](https://fedlex.data.admin.ch/eli/cc/2016/752)

## 13. Abschnitt: Mindestanforderungen an die Betriebssicherheit der Grundbuchsysteme

#### Art. 24

<sup>1</sup> Das EJPD erarbeitet zusammen mit einer Vertretung der Kantone auf der Basis einer methodischen Risikobeurteilung einen Kriterienkatalog, der angemessene, wirksame und formal überprüfbare Massnahmen für den sicheren Betrieb eines Grundbuchsystems enthält.

<sup>2</sup> Der Katalog enthält Anforderungen an die Auditoren, die Häufigkeit und das Vorgehen der Überprüfung.

<sup>3</sup> Er wird den Kantonen als Empfehlung zur Verfügung gestellt.

## 14. Abschnitt: Schlussbestimmungen

#### Art. 25

**Aufhebung bisherigen Rechts**

Die Technische Verordnung des EJPD und des VBS vom 6. Juni 2007[^25-1] über das Grundbuch wird aufgehoben.

[^25-1]: [[AS 2007 3353](https://fedlex.data.admin.ch/eli/oc/2007/408)]

#### Art. 26

**Übergangsbestimmung**

<sup>1</sup>

Die Kantone machen bis zum 1. Januar 2014 in ihren Informatiksystemen verfügbar:

- a. für das Grundbuch und für die amtliche Vermessung: die AVGBS oder eine gleichwertige Datenübertragungsmethode und die E-GRID;
- b. für das Grundbuch: die obligatorischen Elemente des eGRISDM und die GBDBS, Teile Auskunft/Datenbezug und Langzeitsicherung.

<sup>2</sup> Das EJPD kann die Fristen in begründeten Fällen verlängern.

#### Art. 27

**Inkrafttreten**

Diese Verordnung tritt am 1. Februar 2013 in Kraft.

Anhang 1*[^t-1]*

(Art. 1 Bst. a, 2 Abs. 1 Bst. a und 8)

## Datenmodell für das Grundbuch eGRISDM, in INTERLIS beschrieben

[^t-1]: Dieser Anhang enthält das Datenmodell in der Version eGRISDM11. Der Text des Anhangs wird weder in der AS noch in der SR veröffentlicht. Die Verordnung einschliesslich des Anhangs kann via Internet unter www.bj.admin.ch &gt; Themen &gt; Wirtschaft &gt; Grundbuch & Schiffsregister konsultiert werden.

Anhang 2*[^t-2]*

(Art. 1 Bst. b, 3 Abs. 1 Bst. a und 9)

## Datenmodell für den Datenaustausch zwischen der amtlichen Vermessung und dem Grundbuch AVGBSDM, in INTERLIS beschrieben

[^t-2]: Dieser Anhang enthält das Datenmodell in der Version AVGBSDM05. Er wird weder in der AS noch in der SR veröffentlicht. Die Verordnung einschliesslich des Anhangs kann via Internet unter www.bj.admin.ch &gt; Themen &gt; Wirtschaft &gt; Grundbuch & Schiffsregister konsultiert werden.

Anhang 3*[^t-3]*

(Art. 1 Bst. c, 2 Abs. 1 Bst. c und 10)

## Schnittstelle für den Bezug und den Austausch von Grundbuchdaten GBDBS, in XML beschrieben

[^t-3]: Dieser Anhang enthält die Schnittstelle in der Version 2.0.5. Er wird weder in der AS noch in der SR veröffentlicht. Die Verordnung einschliesslich des Anhangs kann via Internet unter www.bj.admin.ch &gt; Themen &gt; Wirtschaft &gt; Grundbuch & Schiffsregister konsultiert werden.

Anhang 4*[^t-4]*

(Art. 1 Bst. g und 2 Abs. 1 Bst. d)

## Kriterienkatalog für die Anerkennung von alternativen Plattformen

[^t-4]: Der Text des Anhangs wird weder in der AS noch in der SR veröffentlicht. Die Verordnung einschliesslich des Anhangs kann via Internet unter www.bj.admin.ch &gt; Themen &gt; Wirtschaft &gt; Grundbuch & Schiffsregister konsultiert werden.
