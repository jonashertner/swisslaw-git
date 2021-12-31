---
sr: "832.105.1"
title: Verordnung des EDI vom 20. März 2008 über die technischen und grafischen Anforderungen an die Versichertenkarte für die obligatorische Krankenpflegeversicherung (VVK-EDI)
short: VVK-EDI
eli: "https://fedlex.data.admin.ch/eli/cc/2008/228"
language: de
version: 2022-01-01
adopted: 2008-03-20
in_force: 2008-04-01
source: "https://fedlex.data.admin.ch/filestore/fedlex.data.admin.ch/eli/cc/2008/228/20220101/de/xml/fedlex-data-admin-ch-eli-cc-2008-228-20220101-de-xml-6.xml"
url: "https://www.fedlex.admin.ch/eli/cc/2008/228/20220101/de"
---

> Nicht amtliche Wiedergabe der konsolidierten Fassung (Fedlex). Massgebend ist die Veröffentlichung in der Amtlichen Sammlung (Art. 15 PublG, SR 170.512).

# Verordnung des EDI über die technischen und grafischen Anforderungen an die Versichertenkarte für die obligatorische Krankenpflegeversicherung

(VVK-EDI)

vom 20. März 2008 (Stand am 1. Januar 2022)

Das Eidgenössische Departement des Innern,

gestützt auf die Artikel 3 Absatz 3 und 17 der Verordnung vom 14. Februar 2007[^ingress-1] über die Versichertenkarte für die obligatorische Krankenpflegeversicherung (VVK),

verordnet:

[^ingress-1]: [SR 832.105](https://fedlex.data.admin.ch/eli/cc/2007/101)

#### Art. 1

**Daten für die Rechnungstellung**

Die Spezifikation der Daten für die Rechnungstellung ist in Anhang 1 festgelegt.

#### Art. 2

**Daten nach Artikel 6 VVK**

Die Spezifikation der Daten nach Artikel 6 VVK ist in Anhang 2 festgelegt.

#### Art. 3

**Daten für die Abfrage im Online-Verfahren**

Die Spezifikation der Daten für die Abfrage im Online-Verfahren nach Artikel 15 VVK ist in Anhang 3 festgelegt.

#### Art. 4

**Grafische Anforderungen an die Versichertenkarte**

Die grafischen Anforderungen an die Versichertenkarte sind in Anhang 4 festgelegt.

#### Art. 5

**Standard eCH-0064**

Der Standard eCH-0064 «Spezifikationen für das System Versichertenkarte» vom 4. Februar 2008[^5-1] ist anzuwenden. Er definiert:

- a. die technischen Anforderungen und die Kommunikationsanforderungen an die Versichertenkarte;
- b. die Anforderungen an das Betriebs- und das Dateisystem der Versichertenkarte;
- c. die Anforderungen an den elektronischen Leistungserbringernachweis nach Artikel 8 VVK;
- d. die Spezifikation des Authentisierungs- und des Autorisierungsverfahrens zwischen der Versichertenkarte und dem elektronischen Leistungserbringernachweis nach Artikel 8 VVK;
- e. die Anforderungen an das PIN-Management der Versichertenkarte;
- f. die Anforderungen an das Online-Verfahren nach Artikel 15 VVK;
- g. die Anforderungen an die Versichertenkarte für deren Nutzung im Rahmen kantonaler Modellversuche nach Artikel 16 VVK.

[^5-1]: Der Standard eCH-0064 «Spezifikationen für das System Versichertenkarte» vom 4. Februar 2008 kann beim Verein eCH, Mainaustrasse 30, 8008 Zürich oder beim Bundesamt für Gesundheit, Kranken- und Unfallversicherung, 3003 Bern bestellt werden oder unter www.ech.ch eingesehen werden.

#### Art. 6

**Inkrafttreten**

Diese Verordnung tritt am 1. April 2008 in Kraft.

Anhang 1[^t-1]

(Art. 1)

## Spezifikation der Daten für die Rechnungstellung

[^t-1]: Bereinigt gemäss Anhang Ziff. II 38 der V vom 17. Nov. 2021, in Kraft seit 1. Jan. 2022 ([AS 2021 800](https://fedlex.data.admin.ch/eli/oc/2021/800)).

### 1 Allgemeines

### 1.1 Referenzen

<table>
<tr><td>Draft prEN ISO 21549-5:2006</td><td>Health informatics – Patient healthcard data – Part 5: Identification Data</td></tr>
<tr><td>ISO/DIS 21549-6:2006</td><td>Health informatics – Patient healthcard data – Part 6: Administrative Data</td></tr>
<tr><td>eCH-0010:2006</td><td>Datenstandard Postadresse für natürliche Personen, Firmen, Organisationen und Behörden</td></tr>
<tr><td>eCH-0064:2008</td><td>Spezifikationen für das System Versichertenkarte</td></tr>
<tr><td>EN (Europäische Norm) 1867:1997</td><td>Maschinenlesbare Karten – Anwendungen im Gesundheitswesen – Benummerungssystem und Registrierungsverfahren für Kartenausgeberschlüssel</td></tr>
</table>

### 1.2 Bezugsquellen

<table>
<tr><td>ISO-Normen</td><td>Zentralsekretariat der internationalen Organisation für Normung (ISO), 1, ch. de la Voie-Creuse, 1211 Genève, http://www.iso.org Die Normen können beim Bundesamt für Gesundheit eingesehen werden.</td></tr>
<tr><td>eCH-Standards</td><td>Verein eCH, Mainaustrasse 30, 8008 Zürich, http://www.ech.ch/</td></tr>
<tr><td>Europäische Norm</td><td>Europäisches Komitee für Normung (CEN), rue de Stassart 36, B-1050 Brüssel, http://www.cenorm.be Die Norm kann beim Bundesamt für Gesundheit eingesehen werden.</td></tr>
</table>

### 1.3 Abkürzungen und Definitionen

<table>
<tr><td>AN</td><td>Alphanumerisch</td></tr>
<tr><td>Char</td><td>Charakter</td></tr>
<tr><td>Class</td><td>Komplexer Datentyp bestehend aus mehreren Elementen</td></tr>
<tr><td>Tag</td><td>Markierung, Identifikator eines Datenelements</td></tr>
</table>

### 2 Spezifikation der elektronischen Daten nach Artikel 4 VVK

Die Identifikationsdaten nach Ziffer 2.1 müssen nach dem Standard Draft prEN ISO 21549-5 «Health informatics – Patient healthcard data – Part 5: Identification data» in der Fassung des Jahres 2006 (ISO 21549-5:2006) und die administrativen Daten nach Ziffer 2.2 nach dem Standard ISO/DIS 21549-6 «Health informatics – Patient healthcard data – Part 6: Administrative data» in der Fassung des Jahres 2006 (ISO/DIS 21549-6:2006) spezifiziert werden. Obligatorische Elemente in optionalen Datenblöcken müssen nur dann angegeben werden, wenn im optionalen Bereich Eingaben vorgenommen wurden.

Für die Bearbeitung der Daten werden vom BAG XML-Schemata[^annex1-lvlu1-lvl2-1] zur Verfügung gestellt. Die Tagbezeichnungen sowie die Elementbezeichnungen der XML-Schemata werden jeweils angegeben.

### 2.1 Identifikationsdaten (65, cardholderRelatedTemplate)

[^annex1-lvlu1-lvl2-1]: Die XML-Schemata sind zu beziehen beim Bundesamt für Gesundheit, 3003 Bern oder einzusehen unter www.ehealth.admin.ch.

Die Daten müssen auf der Karte in der im Standard eCH-0064 «Spezifikationen für das System Versichertenkarte» vom 4. Februar 2008 (eCH-0064:2008) definierten Datei EF.ID gespeichert werden.

<table>
<tr><td>2.1.1</td><td>Name (80, name)</td></tr>
<tr><td></td><td>Das Element enthält den Namen und den Vornamen.</td></tr>
</table>

<table>
<tr><td>2.1.2</td><td>Geburtsdatum (82, dateOfBirth)</td><td></td></tr>
<tr><td></td><td>Abweichung von ISO 21549-5:2006:</td><td>Das Element ist obligatorisch.</td></tr>
</table>

<table>
<tr><td>2.1.3</td><td colspan="2">AHV-Nummer (83, cardholderIdentifier)</td></tr>
<tr><td></td><td>Ergänzung zu ISO 21549-5:2006:</td><td>Die Länge des Elements beträgt 13 Zeichen und enthält keine Trennzeichen.</td></tr>
<tr><td></td><td>Abweichung von ISO 21549-5:2006:</td><td>Das Element ist obligatorisch.</td></tr>
</table>

<table>
<tr><td>2.1.4</td><td colspan="2">Geschlecht (84, sex)</td></tr>
<tr><td></td><td>Abweichung von ISO 21549-5:2006:</td><td>Das Element ist obligatorisch.</td></tr>
</table>

### 2.2 Administrative Daten (65, cardholderRelatedTemplate)

Die Daten müssen auf der Karte in der im Standard eCH-0064:2008 definierten Datei EF.AD gespeichert werden.

<table>
<tr><td>2.2.1</td><td>Identifikation des ausstellenden Staates (90, issuingStateIdNumber)</td></tr>
<tr><td></td><td>Der ausstellende Staat ist die Schweiz.</td></tr>
</table>

<table>
<tr><td>2.2.2</td><td>Name des Versicherers (91, nameOfTheInstitution)</td></tr>
</table>

<table>
<tr><td>2.2.3</td><td>BAG-Nummer des Versicherers (92, identificationNumberOfThe Institution)</td></tr>
</table>

<table>
<tr><td>2.2.4</td><td colspan="2">Kennnummer der Versichertenkarte (93, insuredPersonNumber)</td></tr>
<tr><td></td><td colspan="2">Individuelle fortlaufende Nummer, mit der der Versicherer jede Karte versieht, um die einzelnen Karten zu identifizieren. Die ersten 10 Zeichen bezeichnen den Versicherer gemäss der Europäischen Norm 1867 «Maschinenlesbare Karten – Anwendungen im Gesundheitswesen – Benummerungssystem und Registrierungsverfahren für Kartenausgeberschlüssel» in der Fassung des Jahres 1997 (Norm EN 1867:1997). Die letzten 10 Stellen ergeben die einmalige Seriennummer.</td></tr>
<tr><td></td><td>Ergänzung zu ISO/DIS 21549-6:2006:</td><td>Sind auf der Rückseite der Versichertenkarte (VK) die Daten der Europäischen Krankenversicherungskarte (EU-KVK) aufgedruckt, so muss die Kennnummer der VK identisch sein mit der Kennnummer der EU-KVK.</td></tr>
<tr><td></td><td>Abweichung von ISO/DIS 21549-6:2006:</td><td>Das Element ist obligatorisch.</td></tr>
</table>

<table>
<tr><td>2.2.5</td><td colspan="2">Ablaufdatum (94, expiryDate)</td></tr>
<tr><td></td><td>Ergänzung zu ISO/DIS 21549-6:2006:</td><td>Sind die Daten der EU-KVK auf der Rückseite der VK aufgedruckt, so muss das Ablaufdatum der beiden Karten identisch sein.</td></tr>
</table>

<table>
<tr><td>2.2.6</td><td colspan="3">Nationale Definitionen</td></tr>
<tr><td>Tag: 73</td><td>Länge: x</td><td>Wert: nationalExtension</td><td>Datentyp: Class</td></tr>
</table>

<table>
<tr><td>2.2.6.1</td><td colspan="3">Zustelladresse der versicherten Person (optional)</td></tr>
<tr><td>Tag: 09</td><td>Länge: x</td><td>Wert: mailAddress</td><td>Datentyp: Class</td></tr>
<tr><td colspan="4">Die Angaben zur Zustelladresse der versicherten Person müssen nach dem Standard eCH-0010 «Datenstandard Postadresse für natürliche Personen, Firmen, Organisationen und Behörden» in der Fassung des Jahres 2006 (eCH-0010:2006) spezifiziert werden.</td></tr>
</table>

<table>
<tr><td>2.2.6.2</td><td colspan="3">Angaben zur obligatorischen Krankenpflegeversicherung (OKP) (optional)</td></tr>
<tr><td>Tag: 10</td><td>Länge: x</td><td>Wert: KVG Information</td><td>Datentyp: Class</td></tr>
<tr><td colspan="4">Die Angaben zur OKP bestehen aus folgenden Daten:</td></tr>
</table>

<table>
<tr><td>2.2.6.2.1</td><td colspan="3">Offizielle Sprachregion (optional)</td></tr>
<tr><td>Tag: 11</td><td>Länge: 2</td><td>Wert: language Region</td><td>Datentyp: AN</td></tr>
</table>

<table>
<tr><td>Offizielle Sprachregion der versicherten Person Tabelle der erlaubten Codes:</td></tr>
</table>

<table>
<tr><th>ID</th><th>Offizielle Sprachregion</th></tr>
<tr><td>de</td><td>Deutsch</td></tr>
<tr><td>fr</td><td>Französisch</td></tr>
<tr><td>it</td><td>Italienisch</td></tr>
<tr><td>rm</td><td>Rätoromanisch</td></tr>
<tr><td>zz</td><td>Andere</td></tr>
</table>

<table>
<tr><td>2.2.6.2.2</td><td colspan="3">Versicherungsform (optional)</td></tr>
<tr><td>Tag: 12</td><td>Länge: 2</td><td>Wert: KVGModel</td><td>Datentyp: AN</td></tr>
</table>

<table>
<tr><td>Tabelle der erlaubten Codes:</td></tr>
</table>

<table>
<tr><th>ID</th><th>Versicherungsform</th></tr>
<tr><td>01</td><td>Standardmodell (ohne Einschränkung der Leistungserbringer)</td></tr>
<tr><td>02</td><td>Hausarzt-Modell</td></tr>
<tr><td>03</td><td>HMO-Modell</td></tr>
<tr><td>04</td><td>Listen-Modell</td></tr>
<tr><td>05</td><td>Andere</td></tr>
<tr><td>99</td><td>Unbekannt</td></tr>
</table>

<table>
<tr><td>2.2.6.2.3</td><td colspan="3">Nähere Bezeichnung der Versicherungsform (optional)</td></tr>
<tr><td>Tag: 13</td><td>Länge: 0–40</td><td>Wert: KVGModel Text</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Freitext: Nähere Bezeichnung der Versicherungsform</td></tr>
</table>

<table>
<tr><td>2.2.6.2.4</td><td colspan="3">Wohnkanton KVG-Deckung (optional)</td></tr>
<tr><td>Tag: 14</td><td>Länge: x</td><td>Wert: KVGCanton</td><td>Datentyp: Class</td></tr>
</table>

<table>
<tr><td>Tabelle der erlaubten Codes:</td></tr>
</table>

<table>
<tr><th>ID</th><th>Wohnkanton KVG-Deckung</th></tr>
<tr><th>AG</th><th>Aargau</th></tr>
<tr><th>AI</th><th>Appenzell Innerrhoden</th></tr>
<tr><th>AR</th><th>Appenzell Ausserhoden</th></tr>
<tr><th>BE</th><th>Bern</th></tr>
<tr><th>BL</th><th>Basel-Landschaft</th></tr>
<tr><th>BS</th><th>Basel-Stadt</th></tr>
<tr><th>FR</th><th>Freiburg</th></tr>
<tr><th>GE</th><th>Genf</th></tr>
<tr><th>GL</th><th>Glarus</th></tr>
<tr><th>GR</th><th>Graubünden</th></tr>
<tr><th>JU</th><th>Jura</th></tr>
<tr><th>LU</th><th>Luzern</th></tr>
<tr><th>NE</th><th>Neuenburg</th></tr>
<tr><th>NW</th><th>Nidwalden</th></tr>
<tr><th>OW</th><th>Obwalden</th></tr>
<tr><th>SG</th><th>St. Gallen</th></tr>
<tr><th>SH</th><th>Schaffhausen</th></tr>
<tr><th>SO</th><th>Solothurn</th></tr>
<tr><th>SZ</th><th>Schwyz</th></tr>
<tr><th>TG</th><th>Thurgau</th></tr>
<tr><th>TI</th><th>Tessin</th></tr>
<tr><th>UR</th><th>Uri</th></tr>
<tr><th>VD</th><th>Waadt</th></tr>
<tr><th>VS</th><th>Wallis</th></tr>
<tr><th>ZG</th><th>Zug</th></tr>
<tr><th>ZH</th><th>Zürich</th></tr>
<tr><th>ZZ</th><th>Ausland</th></tr>
<tr><th>AA</th><th>Unbekannt</th></tr>
</table>

<table>
<tr><td>2.2.6.2.5</td><td colspan="3">Unfalldeckung KVG (optional)</td></tr>
<tr><td>Tag: 15</td><td>Länge: 2</td><td>Wert: KVGaccident Coverage</td><td>Datentyp: AN</td></tr>
</table>

<table>
<tr><td>Unfalldeckung KVG Tabelle der erlaubten Codes:</td></tr>
</table>

<table>
<tr><th>ID</th><th>Unfalldeckung KVG</th></tr>
<tr><td>01</td><td>Unfalldeckung</td></tr>
<tr><td>02</td><td>Keine Unfalldeckung</td></tr>
<tr><td>99</td><td>Unbekannt</td></tr>
</table>

<table>
<tr><td>2.2.6.3</td><td colspan="3">Angaben zum OKP-Versicherer (optional)</td></tr>
<tr><td>Tag: 16</td><td>Länge: x</td><td>Wert: insurer Information</td><td>Datentyp: Class</td></tr>
<tr><td colspan="4">Die Angaben zum OKP-Versicherer bestehen aus folgenden Daten:</td></tr>
</table>

<table>
<tr><td>2.2.6.3.1</td><td colspan="3">Kontakt Telefon deutsch (optional)</td></tr>
<tr><td>Tag: 17</td><td>Länge: 0–20</td><td>Wert: contactNumber German</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Freitext: Kontakt Telefon deutsch</td></tr>
</table>

<table>
<tr><td>2.2.6.3.2</td><td colspan="3">Kontakt Telefon französisch (optional)</td></tr>
<tr><td>Tag: 18</td><td>Länge: 0–20</td><td>Wert: contactNumber French</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Freitext: Kontakt Telefon französisch</td></tr>
</table>

<table>
<tr><td>2.2.6.3.3</td><td colspan="3">Kontakt Telefon italienisch (optional)</td></tr>
<tr><td>Tag: 19</td><td>Länge: 0–20</td><td>Wert: contactNumber Italian</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Freitext: Kontakt Telefon italienisch</td></tr>
</table>

<table>
<tr><td>2.2.6.3.4</td><td colspan="3">Kontakt E-Mail (optional)</td></tr>
<tr><td>Tag: 20</td><td>Länge: 0–100</td><td>Wert: contactEmail Address</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Freitext: Kontakt E-Mail</td></tr>
</table>

<table>
<tr><td>2.2.6.3.5</td><td colspan="3">Kontakt EAN-Nummer (optional)</td></tr>
<tr><td>Tag: 21</td><td>Länge: 0–13</td><td>Wert: contactEan Number</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Freitext: Kontakt EAN-Nummer</td></tr>
</table>

<table>
<tr><td>2.2.6.3.6</td><td colspan="3">Rechnungsadresse des Versicherers (optional)</td></tr>
<tr><td>Tag: 22</td><td>Länge: x</td><td>Wert: address</td><td>Datentyp: Class</td></tr>
<tr><td colspan="4">Die Angaben zur Rechnungsadresse des Versicherers müssen nach dem Standard eCH-0010:2006 spezifiziert werden.</td></tr>
</table>

<table>
<tr><td>2.2.6.4</td><td colspan="4">Angaben zu Zusatzversicherungen nach dem Versicherungsvertragsgesetz (VVG; SR *221.229.1*) (optional)</td></tr>
<tr><td colspan="5">Es können Angaben von bis zu fünf Zusatzversicherern aufgenommen werden.</td></tr>
<tr><td colspan="2">Tag: 34</td><td>Länge: x</td><td>Wert: VVG Information</td><td>Datentyp: Class</td></tr>
<tr><td colspan="5">Die Angaben über die Zusatzversicherungen nach VVG bestehen aus folgenden Daten:</td></tr>
</table>

<table>
<tr><td>2.2.6.4.1</td><td colspan="3">Name des VVG-Versicherers (obligatorisch)</td></tr>
<tr><td>Tag: 35</td><td>Länge: 0–100</td><td>Wert: nameOfVVG Insurer</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Freitext: Name des VVG-Versicherers</td></tr>
</table>

2.2.6.4.2 Angaben zum VVG-Versicherer (optional) Tag: 36 Länge: x Wert: VVGInsurer Information Datentyp: Class Die Angaben zum VVG-Versicherer bestehen aus folgenden Daten:

- – Kontakt Telefon deutsch, siehe Ziffer 2.2.6.3.1
- – Kontakt Telefon französisch, siehe Ziffer 2.2.6.3.2
- – Kontakt Telefon italienisch, siehe Ziffer 2.2.6.3.3
- – Kontakt E-Mail, siehe Ziffer 2.2.6.3.4
- – Kontakt EAN-Nummer, siehe Ziffer 2.2.6.3.5
- – Rechnungsadresse, siehe Ziffer 2.2.6.3.6

<table>
<tr><td>2.2.6.4.3</td><td colspan="3">Hors-Liste-Medikamente (optional)</td></tr>
<tr><td>Tag: 37</td><td>Länge: 2</td><td>Wert: medicationHL</td><td>Datentyp: AN</td></tr>
</table>

<table>
<tr><td>Tabelle der erlaubten Codes:</td></tr>
</table>

<table>
<tr><th>ID</th><th>Hors-Liste-Medikamente</th></tr>
<tr><td>01</td><td>Deckung für Hors-Liste-Medikamente</td></tr>
<tr><td>02</td><td>Eingeschränkte Deckung für Hors-Liste-Medikamente</td></tr>
<tr><td>00</td><td>Keine Deckung für Hors-Liste-Medikamente</td></tr>
<tr><td>99</td><td>Unbekannt</td></tr>
</table>

<table>
<tr><td>2.2.6.4.4</td><td colspan="3">Unfalldeckung Hors-Liste-Medikamente (optional)</td></tr>
<tr><td>Tag: 38</td><td>Länge: 2</td><td>Wert: medication AccidentCoverageHL</td><td>Datentyp: AN</td></tr>
</table>

<table>
<tr><td>Tabelle der erlaubten Codes:</td></tr>
</table>

<table>
<tr><th>ID</th><th>Unfalldeckung für Hors-Liste-Medikamente</th></tr>
<tr><td>01</td><td>Unfalldeckung für Hors-Liste-Medikamente</td></tr>
<tr><td>00</td><td>Keine Unfalldeckung für Hors-Liste-Medikamente</td></tr>
<tr><td>99</td><td>Unbekannt</td></tr>
</table>

<table>
<tr><td>2.2.6.4.5</td><td colspan="3">Medikamente Komplementärmedizin (optional)</td></tr>
<tr><td>Tag: 39</td><td>Länge: 2</td><td>Wert: medicationKM</td><td>Datentyp: AN</td></tr>
</table>

<table>
<tr><td>Tabelle der erlaubten Codes:</td></tr>
</table>

<table>
<tr><th>ID</th><th>Komplementärmedizin</th></tr>
<tr><td>01</td><td>Deckung für Medikamente Komplementärmedizin</td></tr>
<tr><td>02</td><td>Eingeschränkte Deckung für Medikamente Komplementärmedizin</td></tr>
<tr><td>00</td><td>Keine Deckung für Medikamente Komplementärmedizin</td></tr>
<tr><td>99</td><td>Unbekannt</td></tr>
</table>

<table>
<tr><td>2.2.6.4.6</td><td colspan="3">Unfalldeckung Medikamente Komplementärmedizin (optional)</td></tr>
<tr><td>Tag: 40</td><td>Länge: 2</td><td>Wert: medication AccidentCoverageKM</td><td>Datentyp: AN</td></tr>
</table>

<table>
<tr><td>Tabelle der erlaubten Codes:</td></tr>
</table>

<table>
<tr><th>ID</th><th>Unfalldeckung Medikamente Komplementärmedizin</th></tr>
<tr><td>01</td><td>Unfalldeckung für Medikamente Komplementärmedizin</td></tr>
<tr><td>00</td><td>Keine Unfalldeckung für Medikamente Komplementärmedizin</td></tr>
<tr><td>99</td><td>Unbekannt</td></tr>
</table>

<table>
<tr><td>2.2.6.4.7</td><td colspan="3">Spitalabteilung (optional)</td></tr>
<tr><td>Tag: 41</td><td>Länge: 2</td><td>Wert: medicalService CoverageVVG</td><td>Datentyp: AN</td></tr>
</table>

<table>
<tr><td>Tabelle der erlaubten Codes:</td></tr>
</table>

<table>
<tr><th>ID</th><th>Spitalabteilung</th></tr>
<tr><td>01</td><td>Allgemeine Spitalabteilung ganze Schweiz</td></tr>
<tr><td>02</td><td>Halbprivate Spitalabteilung</td></tr>
<tr><td>03</td><td>Private Spitalabteilung</td></tr>
<tr><td>00</td><td>Keine (halb-)private Spitalabteilung</td></tr>
<tr><td>99</td><td>Unbekannt</td></tr>
</table>

<table>
<tr><td>2.2.6.4.8</td><td colspan="3">Spitalmodell (optional)</td></tr>
<tr><td>Tag: 42</td><td>Länge: 2</td><td>Wert: hospitalModel VVG</td><td>Datentyp: AN</td></tr>
</table>

<table>
<tr><td>Tabelle der erlaubten Codes:</td></tr>
</table>

<table>
<tr><th>ID</th><th>Spitalmodell</th></tr>
<tr><td>01</td><td>Standard-Deckung Spitalabteilung Versicherung privat/halbprivat</td></tr>
<tr><td>02</td><td>Hotellerie-Versicherung</td></tr>
<tr><td>03</td><td>Arztwahl-Versicherung</td></tr>
<tr><td>99</td><td>Unbekannt</td></tr>
</table>

<table>
<tr><td>2.2.6.4.9</td><td colspan="3">Unfalldeckung Spitalversicherung (optional)</td></tr>
<tr><td>Tag: 43</td><td>Länge: 2</td><td>Wert: accident CoverageVVG</td><td>Datentyp: AN</td></tr>
</table>

<table>
<tr><td>Tabelle der erlaubten Codes:</td></tr>
</table>

<table>
<tr><th>ID</th><th>Spitalmodell</th></tr>
<tr><td>01</td><td>Unfalldeckung für Spitalversicherung</td></tr>
<tr><td>00</td><td>Keine Unfalldeckung für Spitalversicherung</td></tr>
<tr><td>99</td><td>Unbekannt</td></tr>
</table>

Anhang 2

(Art. 2)

## Spezifikation der Daten nach Artikel 6 VVK

### 1 Allgemeines

### 1.1 Referenzen

<table>
<tr><td>eCH-0010:2006</td><td>Datenstandard Postadresse für natürliche Personen, Firmen, Organisationen und Behörden</td></tr>
<tr><td>eCH-0064:2008</td><td>Spezifikationen für das System Versichertenkarte</td></tr>
</table>

### 1.2 Bezugsquelle

<table>
<tr><td>eCH-Standards</td><td>Verein eCH, Mainaustrasse 30, 8008 Zürich, http://www.ech.ch/</td></tr>
</table>

### 1.3 Abkürzungen und Definitionen

<table>
<tr><td>AN</td><td>Alphanumerisch</td></tr>
<tr><td>Char</td><td>Charakter</td></tr>
<tr><td>Class</td><td>Komplexer Datentyp bestehend aus mehreren Elementen</td></tr>
<tr><td>Tag</td><td>Markierung, Identifikator eines Datenelements</td></tr>
</table>

### 2 Spezifikation der Daten nach Artikel 6 VVK

Für die Daten nach Artikel 6 VVK werden dasselbe Datenformat und derselbe Zeichensatz verwendet wie für die Identifikationsdaten nach Anhang 1 Ziffer 2.1 und die administrativen Daten nach Anhang 1 Ziffer 2.2.

Obligatorische Elemente in optionalen Datenblöcken müssen nur dann angegeben werden, wenn im optionalen Bereich Eingaben vorgenommen wurden.

Für die Bearbeitung der Daten werden vom BAG XML-Schemata[^annex2-lvlu1-lvl2-1] zur Verfügung gestellt. Die Tagbezeichnungen sowie die Elementbezeichnungen der XML-Schemata werden jeweils angegeben.

### 2.1 Krankheiten und Unfallfolgen (optional, mehrfach)

[^annex2-lvlu1-lvl2-1]: Die XML-Schemata sind zu beziehen beim Bundesamt für Gesundheit, 3003 Bern oder einzusehen unter www.ehealth.admin.ch.

Es sind [0–50] Einträge möglich; Rekord [1–50] der im Standard eCH-0064 «Spezifikationen für das System Versichertenkarte» vom 4. Februar 2008 (eCH-0064:2008) definierten Datei EF.KHUF.

<table>
<tr><td>Tag: 200</td><td>Länge: x</td><td>Wert: diseases AndPostTraumatic Sequels</td><td>Datentyp: Class</td></tr>
</table>

Die Angaben zu den Krankheiten und Unfallfolgen bestehen aus folgenden Elementen:

<table>
<tr><td>2.1.1</td><td colspan="3">Bezeichnung der Krankheit oder Unfallfolge (optional)</td></tr>
<tr><td>Tag: 44</td><td>Länge: 2</td><td>Wert: diseaseName</td><td>Datentyp: AN</td></tr>
</table>

Tabelle der erlaubten Codes:

<table>
<tr><th>ID</th><th>Bezeichnung der Krankheit oder Unfallfolge</th></tr>
<tr><td>01</td><td>Asthma bronchiale</td></tr>
<tr><td>02</td><td>COPD (chronisch obstruktive Lungenerkrankung)</td></tr>
<tr><td>03</td><td>KHK (Koronare Herzkrankheit)</td></tr>
<tr><td>04</td><td>Herzinsuffizienz</td></tr>
<tr><td>05</td><td>Herzrhythmusstörungen</td></tr>
<tr><td>06</td><td>Periphere Verschlusskrankheiten</td></tr>
<tr><td>07</td><td>Bauchaortenaneurysma</td></tr>
<tr><td>08</td><td>Zerebrale Krampfanfälle</td></tr>
<tr><td>09</td><td>Angeborene Gerinnungsstörung</td></tr>
<tr><td>10</td><td>Erworbene Gerinnungsstörung</td></tr>
<tr><td>11</td><td>Medikamentös induzierte Gerinnungsstörung</td></tr>
<tr><td>12</td><td>Diabetes mellitus</td></tr>
<tr><td>13</td><td>Morbus Addison</td></tr>
<tr><td>14</td><td>Glaukom</td></tr>
<tr><td>15</td><td>Niereninsuffizienz/Dialyse</td></tr>
<tr><td>16</td><td>Langsame Acetylisierung</td></tr>
<tr><td>17</td><td>Chronische Lebererkrankung</td></tr>
<tr><td>18</td><td>Hyperthyreose</td></tr>
<tr><td>19</td><td>Infektionskrankheiten</td></tr>
<tr><td>20</td><td>Fehlendes Organ</td></tr>
<tr><td>21</td><td>Gefässprothese</td></tr>
<tr><td>22</td><td>Künstliche Herzklappe</td></tr>
<tr><td>23</td><td>Gefässeinlage (Stents, Clips)</td></tr>
<tr><td>24</td><td>Gelenkprothese</td></tr>
<tr><td>25</td><td>In-Situ-Schrittmacher/Defibrillator</td></tr>
<tr><td>26</td><td>Osteosynthesematerial</td></tr>
<tr><td>27</td><td>Glasauge</td></tr>
<tr><td>28</td><td>Kontaktlinsen</td></tr>
<tr><td>29</td><td>Abnehmbare Prothesen</td></tr>
<tr><td>30</td><td>Weitere Krankheiten oder Unfallfolgen</td></tr>
</table>

<table>
<tr><td>2.1.2</td><td colspan="3">Bemerkung zur Krankheit oder Unfallfolge (optional)</td></tr>
<tr><td>Tag: 70</td><td>Länge: 1–100</td><td>Wert: diseaseFreetext</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Freitext: Bemerkung zur Krankheit oder Unfallfolge</td></tr>
</table>

<table>
<tr><td>2.1.3</td><td colspan="3">EAN-Nummer (European Article Numbering) der eintragenden Person (obligatorisch)</td></tr>
<tr><td>Tag: 80</td><td>Länge: 13</td><td>Wert: healthCare ProviderEanNumber</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Identifizierende Nummer bestehend aus 13 Ziffern</td></tr>
</table>

<table>
<tr><td>2.1.4</td><td colspan="3">Datum der Eintragung (obligatorisch)</td></tr>
<tr><td>Tag: 90</td><td>Länge: 10</td><td>Wert: dateOfRecord</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Datum im Format (JJJJ-MM-TT)</td></tr>
</table>

### 2.2 Transplantationsdaten

<table>
<tr><td>2.2.1</td><td>Zur Transplantation angemeldet (optional, mehrfach)</td></tr>
</table>

Es sind [0–10] Einträge möglich; Rekord [1–10] der im Standard eCH-0064:2008 definierten Datei EF.TPLD.

<table>
<tr><td>Tag: 300</td><td>Länge: x</td><td>Wert: transplantation Registration</td><td>Datentyp: Class</td></tr>
</table>

Die Angaben zu «Zur Transplantation angemeldet» bestehen aus folgenden Elementen:

<table>
<tr><td>2.2.1.1</td><td colspan="3">Bemerkung zu «Zur Transplantation angemeldet» (optional)</td></tr>
<tr><td>Tag: 70</td><td>Länge: 0–100</td><td>Wert: transplantation RegistrationFreetext</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Freitext: Bemerkung zu «Zur Transplantation angemeldet»</td></tr>
</table>

<table>
<tr><td>2.2.1.2</td><td colspan="3">EAN-Nummer der eintragenden Person (obligatorisch)</td></tr>
<tr><td>Tag: 80</td><td>Länge: 13</td><td>Wert: healthCare ProviderEanNumber</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Identifizierende Nummer bestehend aus 13 Ziffern</td></tr>
</table>

<table>
<tr><td>2.2.1.3</td><td colspan="3">Datum der Eintragung (obligatorisch)</td></tr>
<tr><td>Tag: 90</td><td>Länge: 10</td><td>Wert: dateOfRecord</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Datum im Format (JJJJ-MM-TT)</td></tr>
</table>

<table>
<tr><td>2.2.2</td><td>Bereits durchgeführte Transplantationen (optional, mehrfach)</td></tr>
</table>

Es sind [0–10] Einträge möglich; Rekord [11–20] der im Standard eCH-0064:2008 definierten Datei EF.TPLD.

<table>
<tr><td>Tag: 400</td><td>Länge: x</td><td>Wert: transplantations</td><td>Datentyp: Class</td></tr>
</table>

Die Angaben zu bereits durchgeführten Transplantationen bestehen aus folgenden Elementen:

<table>
<tr><td>2.2.2.1</td><td colspan="3">Name des transplantierten Organs oder der transplantierten Gewebe und Zellen (optional, mehrfach)</td></tr>
<tr><td>Tag: 46</td><td>Länge: 0–30</td><td>Wert: transplant</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Freitext: Name des transplantierten Organs oder der transplantierten Gewebe und Zellen</td></tr>
</table>

<table>
<tr><td>2.2.2.2</td><td colspan="3">Schweizerische Transplantationsnummer (optional)</td></tr>
<tr><td>Tag: 47</td><td>Länge: 0–12</td><td>Wert: swissTransplant Number</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Freitext: Schweizerische Transplantationsnummer (z. B. RS-2001-4645)</td></tr>
</table>

<table>
<tr><td>2.2.2.3</td><td colspan="3">Datum der Transplantation (optional)</td></tr>
<tr><td>Tag: 48</td><td>Länge: 10</td><td>Wert: dateOf Transplantation</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Datum im Format (JJJJ-MM-TT)</td></tr>
</table>

<table>
<tr><td>2.2.2.4</td><td colspan="3">Bemerkung zur Transplantation (optional)</td></tr>
<tr><td>Tag: 70</td><td>Länge: 0–100</td><td>Wert: transplantation Freetext</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Freitext: Bemerkung zur Transplantation</td></tr>
</table>

<table>
<tr><td>2.2.2.5</td><td colspan="3">EAN-Nummer der eintragenden Person (obligatorisch)</td></tr>
<tr><td>Tag: 80</td><td>Länge: 13</td><td>Wert: healthCare ProviderEanNumber</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Identifizierende Nummer bestehend aus 13 Ziffern</td></tr>
</table>

<table>
<tr><td>2.2.2.6</td><td colspan="3">Datum der Eintragung (obligatorisch)</td></tr>
<tr><td>Tag: 90</td><td>Länge: 10</td><td>Wert: dateOfRecord</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Datum im Format (JJJJ-MM-TT)</td></tr>
</table>

### 2.3 Allergien

Die Angaben zu Allergien oder Überempfindlichkeiten auf Medikamente, Stoffe, Allergene (Insektengifte, Nahrungsmittel) oder Kontaktallergene bestehen aus folgenden Elementen:

<table>
<tr><td>2.3.1</td><td>Soforttypreaktionen (optional, mehrfach)</td></tr>
</table>

Es sind [0–25] Einträge möglich; Rekord [1–25] der im Standard eCH-0064:2008 definierten Datei EF.ALLG.

<table>
<tr><td>Tag: 500</td><td>Länge: x</td><td>Wert: immediateType Reactions</td><td>Datentyp: Class</td></tr>
</table>

<table>
<tr><td>2.3.1.1</td><td colspan="3">Bezeichnung des Auslösers der Allergie (optional)</td></tr>
<tr><td>Tag: 91</td><td>Länge: x</td><td>Wert: allergy Stimulator</td><td>Datentyp: Class</td></tr>
</table>

<table>
<tr><td>2.3.1.1.1</td><td colspan="3">Allgemeine Bezeichnung (optional)</td></tr>
<tr><td>Tag: 92</td><td>Länge: 0–20</td><td>Wert: generalNameOf AllergyStimulator</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Freitext: Allgemeine Bezeichnung des Auslösers der Allergie (z. B. internationaler Freiname eines Medikaments, Allergen)</td></tr>
</table>

<table>
<tr><td>2.3.1.1.2</td><td colspan="3">Spezielle Bezeichnung (optional)</td></tr>
<tr><td>Tag: 93</td><td>Länge: 0–20</td><td>Wert: specialNameOf AllergyStimulator</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Freitext: Spezielle Bezeichnung des Auslösers der Allergie (z. B. Markenname eines Medikaments)</td></tr>
</table>

<table>
<tr><td>2.3.1.2</td><td colspan="3">Klinische Reaktion (optional)</td></tr>
<tr><td>Tag: 94</td><td>Länge: x</td><td>Wert: immediate ClinicalReaction</td><td>Datentyp: Class</td></tr>
</table>

<table>
<tr><td>2.3.1.2.1</td><td colspan="3">Art der klinischen Reaktion (optional)</td></tr>
<tr><td>Tag: 95</td><td>Länge: 1</td><td>Wert: immediate ResponseTypeOf ClinicalReaction</td><td>Datentyp: AN</td></tr>
</table>

Tabelle der erlaubten Codes:

<table>
<tr><th>ID</th><th>Art der klinischen Reaktion für Soforttypreaktionen</th></tr>
<tr><td>1</td><td>Angioödem</td></tr>
<tr><td>2</td><td>Urtikaria</td></tr>
<tr><td>3</td><td>Asthma, Bronchospasmus</td></tr>
<tr><td>4</td><td>Koliken, Diarrhoe</td></tr>
<tr><td>5</td><td>Anaphylaktischer Schock</td></tr>
<tr><td>6</td><td>Andere klinische Reaktion</td></tr>
</table>

<table>
<tr><td>2.3.1.2.2</td><td colspan="3">Datum der klinischen Reaktion (optional)</td></tr>
<tr><td>Tag: 96</td><td>Länge: 10</td><td>Wert: dateOfClinical Reaction</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Datum im Format (JJJJ-MM-TT)</td></tr>
</table>

<table>
<tr><td>2.3.1.2.3</td><td colspan="3">Bemerkung zur klinischen Reaktion (optional)</td></tr>
<tr><td>Tag: 70</td><td>Länge: 0–40</td><td>Wert: clinical ReactionFreetext</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Freitext: Bemerkung zur klinischen Reaktion</td></tr>
</table>

<table>
<tr><td>2.3.1.3</td><td colspan="3">Nachweis der Überempfindlichkeit (optional)</td></tr>
<tr><td>Tag: 97</td><td>Länge: x</td><td>Wert: allergyTest</td><td>Datentyp: Class</td></tr>
</table>

<table>
<tr><td>2.3.1.3.1</td><td colspan="3">Nachweismethode (optional)</td></tr>
<tr><td>Tag: 98</td><td>Länge: 1</td><td>Wert: typeOfAllergy Test</td><td>Datentyp: AN</td></tr>
</table>

Tabelle der erlaubten Codes:

<table>
<tr><th>ID</th><th>Nachweismethode</th></tr>
<tr><td>1</td><td>Anamnese</td></tr>
<tr><td>2</td><td>Klinische Manifestation</td></tr>
<tr><td>3</td><td>Hauttest (Prick, intradermal)</td></tr>
<tr><td>4</td><td>Patchtest (Epikutantest)</td></tr>
<tr><td>5</td><td>Spezifische Antikörper</td></tr>
<tr><td>6</td><td>Provokationstest</td></tr>
<tr><td>7</td><td>Zellulärer Test</td></tr>
<tr><td>8</td><td>Anderer Nachweis der Überempfindlichkeit</td></tr>
</table>

<table>
<tr><td>2.3.1.3.2</td><td colspan="3">Datum des Nachweises (optional)</td></tr>
<tr><td>Tag: 99</td><td>Länge: 10</td><td>Wert: dateOf AllergyTest</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Datum im Format (JJJJ-MM-TT)</td></tr>
</table>

<table>
<tr><td>2.3.1.3.3</td><td colspan="3">Bemerkung zum Nachweis (optional)</td></tr>
<tr><td>Tag: 70</td><td>Länge: 0–40</td><td>Wert: allergyTest Freetext</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Freitext: Bemerkung zum Nachweis (z. B. Resultat, Dosis, Allergen)</td></tr>
</table>

<table>
<tr><td>2.3.1.4</td><td colspan="3">Ersatzmedikament (optional)</td></tr>
<tr><td>Tag: 100</td><td>Länge: x</td><td>Wert: substitute Medicine</td><td>Datentyp: Class</td></tr>
</table>

<table>
<tr><td>2.3.1.4.1</td><td colspan="3">Bezeichnung des Ersatzmedikaments (optional)</td></tr>
<tr><td>Tag: 101</td><td>Länge: 0–20</td><td>Wert: nameOf SubstituteMedicine</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Freitext: Bezeichnung des Ersatzmedikaments (z. B. Markennamen)</td></tr>
</table>

<table>
<tr><td>2.3.1.4.2</td><td colspan="3">Generischer Name des Ersatzmedikaments (optional)</td></tr>
<tr><td>Tag: 102</td><td>Länge: 0–20</td><td>Wert: genericName OfSubstituteMedicine</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Freitext: Generischer Name des Medikaments (z. B. Wirkstoff)</td></tr>
</table>

<table>
<tr><td>2.3.1.4.3</td><td colspan="3">Sicherheit des Ersatzmedikaments (optional)</td></tr>
<tr><td>Tag: 103</td><td>Länge: 1</td><td>Wert: reliabilityOf SubstituteMedicine</td><td>Datentyp: AN</td></tr>
</table>

Tabelle der erlaubten Codes:

<table>
<tr><th>ID</th><th>Sicherheit des Ersatzmedikaments</th></tr>
<tr><td>1</td><td>provoziert</td></tr>
<tr><td>2</td><td>getestet</td></tr>
<tr><td>3</td><td>empfohlen</td></tr>
</table>

<table>
<tr><td>2.3.1.4.4</td><td colspan="3">Testdatum des Ersatzmedikaments (optional)</td></tr>
<tr><td>Tag: 104</td><td>Länge: 10</td><td>Wert: dateOfTest SubstituteMedicine</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Datum im Format (JJJJ-MM-TT)</td></tr>
</table>

<table>
<tr><td>2.3.1.4.5</td><td colspan="3">Bemerkung zum Ersatzmedikament (optional)</td></tr>
<tr><td>Tag: 70</td><td>Länge: 0–40</td><td>Wert: substitute MedicineFreetext</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Freitext: Bemerkung zum Ersatzmedikament</td></tr>
</table>

<table>
<tr><td>2.3.1.5</td><td colspan="3">Notfallmedikament (optional)</td></tr>
<tr><td>Tag: 105</td><td>Länge: x</td><td>Wert: emergency Medicine</td><td>Datentyp: Class</td></tr>
</table>

<table>
<tr><td>2.3.1.5.1</td><td colspan="3">Bezeichnung des Notfallmedikaments (optional)</td></tr>
<tr><td>Tag: 106</td><td>Länge: 1</td><td>Wert: nameOf EmergencyMedicine</td><td>Datentyp: AN</td></tr>
</table>

Tabelle der erlaubten Codes:

<table>
<tr><th>ID</th><th>Notfallmedikament</th></tr>
<tr><td>1</td><td>Antihistaminikum und Kortikostereoid-Tabletten</td></tr>
<tr><td>2</td><td>Adrenalin injizierbar</td></tr>
<tr><td>3</td><td>Inhalationsmedikament</td></tr>
<tr><td>4</td><td>Andere Medikamente</td></tr>
</table>

<table>
<tr><td>2.3.1.5.2</td><td colspan="3">Bemerkung zum Notfallmedikament (optional)</td></tr>
<tr><td>Tag: 107</td><td>Länge: 0–40</td><td>Wert: emergency MedicineFreetext</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Freitext: Bemerkung zum Notfallmedikament, mit dem die Patientin oder der Patient ausgerüstet ist</td></tr>
</table>

<table>
<tr><td>2.3.1.6</td><td colspan="3">EAN-Nummer der eintragenden Person (obligatorisch)</td></tr>
<tr><td>Tag: 80</td><td>Länge: 13</td><td>Wert: healthCare ProviderEanNumber</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Identifizierende Nummer bestehend aus 13 Ziffern</td></tr>
</table>

<table>
<tr><td>2.3.1.7</td><td colspan="3">Datum der Eintragung (obligatorisch)</td></tr>
<tr><td>Tag: 90</td><td>Länge: 10</td><td>Wert: dateOfRecord</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Datum im Format (JJJJ-MM-TT)</td></tr>
</table>

<table>
<tr><td>2.3.2</td><td>Spättypreaktionen (optional, mehrfach)</td></tr>
</table>

Es sind [0–25] Einträge möglich; Rekord [26–50] der im Standard eCH-0064:2008 definierten Datei EF.ALLG.

<table>
<tr><td>Tag: 600</td><td>Länge: x</td><td>Wert: delayedType Reactions</td><td>Datentyp: Class</td></tr>
</table>

- – Bezeichnung des Auslösers der Allergie, siehe Ziffer 2.3.1.1
  - – Allgemeine Bezeichnung, siehe Ziffer 2.3.1.1.1
  - – Spezielle Bezeichnung, siehe Ziffer 2.3.1.1.2

- – Klinische Reaktion, siehe Ziffer 2.3.2.1
  - – Art der klinischen Reaktion, siehe Ziffer 2.3.2.1.1
  - – Datum der klinischen Reaktion, siehe Ziffer 2.3.1.2.2
  - – Bemerkung zur klinischen Reaktion, siehe Ziffer 2.3.1.2.3

- – Nachweis der Überempfindlichkeit, siehe Ziffer 2.3.1.3
  - – Nachweismethode, siehe Ziffer 2.3.1.3.1
  - – Datum des Nachweises, siehe Ziffer 2.3.1.3.2
  - – Bemerkung zum Nachweis, siehe Ziffer 2.3.1.3.3

- – Ersatzmedikament, siehe Ziffer 2.3.1.4
  - – Bezeichnung des Ersatzmedikaments, siehe Ziffer 2.3.1.4.1
  - – Generischer Name des Ersatzmedikaments, siehe Ziffer 2.3.1.4.2
  - – Sicherheit des Ersatzmedikaments, siehe Ziffer 2.3.1.4.3
  - – Testdatum des Ersatzmedikaments, siehe Ziffer 2.3.1.4.4
  - – Bemerkung zum Ersatzmedikament, siehe Ziffer 2.3.1.4.5

- – Notfallmedikament, siehe Ziffer 2.3.1.5
  - – Bezeichnung des Notfallmedikaments, siehe Ziffer 2.3.1.5.1
  - – Bemerkung zum Notfallmedikament, siehe Ziffer 2.3.1.5.2

- – EAN-Nummer der eintragenden Person, siehe Ziffer 2.3.1.6
- – Datum der Eintragung, siehe Ziffer 2.3.1.7

<table>
<tr><td>2.3.2.1</td><td colspan="3">Klinische Reaktion (optional)</td></tr>
<tr><td>Tag: 111</td><td>Länge: x</td><td>Wert: delayedClinical Reaction</td><td>Datentyp: Class</td></tr>
</table>

<table>
<tr><td>2.3.2.1.1</td><td colspan="3">Art der klinischen Reaktion (optional)</td></tr>
<tr><td>Tag: 108</td><td>Länge: 1</td><td>Wert: delayed ResponseTypeOf ClinicalReaction</td><td>Datentyp: AN</td></tr>
</table>

Tabelle der erlaubten Codes:

<table>
<tr><th>ID</th><th>Art der klinischen Reaktion für Spättypreaktionen</th></tr>
<tr><td>1</td><td>Ekzem</td></tr>
<tr><td>2</td><td>Lokalreaktion</td></tr>
<tr><td>3</td><td>Blasenbildung, Vaskulitis</td></tr>
<tr><td>4</td><td>Andere klinische Reaktion</td></tr>
</table>

### 2.4 Medikation (optional, mehrfach)

Es sind [0–50] Einträge möglich; Rekord [1–50] der im Standard eCH-0064:2008 definierten Datei EF.MEDI.

<table>
<tr><td>Tag: 900</td><td>Länge: x</td><td>Wert: medication</td><td>Datentyp: Class</td></tr>
</table>

Die Einträge enthalten Angaben primär zu Dauermedikationen mit folgenden Elementen:

<table>
<tr><td>2.4.1</td><td colspan="3">Bezeichnung der Medikation (optional)</td></tr>
<tr><td>Tag: 55</td><td>Länge: 2</td><td>Wert: medication Name</td><td>Datentyp: AN</td></tr>
</table>

Tabelle der erlaubten Codes:

<table>
<tr><th>ID</th><th>Medikation</th></tr>
<tr><td>01</td><td>Antiepileptikum</td></tr>
<tr><td>02</td><td>Antidepressivum</td></tr>
<tr><td>03</td><td>Neuroleptikum</td></tr>
<tr><td>04</td><td>Antidemenzia</td></tr>
<tr><td>05</td><td>Opiate</td></tr>
<tr><td>06</td><td>NSAR</td></tr>
<tr><td>07</td><td>Tranquilizer</td></tr>
<tr><td>08</td><td>Beta-Blocker</td></tr>
<tr><td>09</td><td>ACE-Hemmer</td></tr>
<tr><td>10</td><td>Diuretika</td></tr>
<tr><td>11</td><td>Calcium-Antagonist</td></tr>
<tr><td>12</td><td>Nitropräparat</td></tr>
<tr><td>13</td><td>Antiarrhythmikum</td></tr>
<tr><td>14</td><td>Digitalis</td></tr>
<tr><td>15</td><td>Aldosteron-Antagonist</td></tr>
<tr><td>16</td><td>Beta-Mimetikum/Antiasthmatika</td></tr>
<tr><td>17</td><td>Immunsuppressivum</td></tr>
<tr><td>18</td><td>Thrombozytenaggregationshemmer</td></tr>
<tr><td>19</td><td>Antikoagulanzien, z. B. Marcumar oder Heparin</td></tr>
<tr><td>20</td><td>Antihistamine</td></tr>
<tr><td>21</td><td>Faktor VIII/IX</td></tr>
<tr><td>22</td><td>Desmopressin, z. B. Minirin</td></tr>
<tr><td>23</td><td>Antidiabetika, Insulin</td></tr>
<tr><td>24</td><td>Kortison/Kortikosteroide</td></tr>
<tr><td>25</td><td>Weitere Medikamente</td></tr>
</table>

<table>
<tr><td>2.4.2</td><td colspan="3">Bemerkung zur Indikation der Medikation (optional)</td></tr>
<tr><td>Tag: 70</td><td>Länge: 0–100</td><td>Wert: indicationOf MedicationFreetext</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Freitext: Bemerkung zur Indikation der Medikation</td></tr>
</table>

<table>
<tr><td>2.4.3</td><td colspan="3">EAN-Nummer der Medikation (optional)</td></tr>
<tr><td>Tag: 109</td><td>Länge: 13</td><td>Wert: medication EanNumber</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Identifizierende Nummer bestehend aus 13 Ziffern</td></tr>
</table>

<table>
<tr><td>2.4.4</td><td colspan="3">ATC-Nummer (Anatomical Therapeutical Chemical)[^annex2-lvlu1-lvl2-lvl24-1] der Medikation (optional)</td></tr>
<tr><td>Tag: 110</td><td>Länge: 0–15</td><td>Wert: medication AtcNumber</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Identifizierende Nummer</td></tr>
</table>

<table>
<tr><td>2.4.5</td><td colspan="3">Angaben zur Medikation (optional)</td></tr>
<tr><td>Tag: 70</td><td>Länge: 0–100</td><td>Wert: medication Freetext</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Freitext: Angaben zur Medikation</td></tr>
</table>

<table>
<tr><td>2.4.6</td><td colspan="3">EAN-Nummer der eintragenden Person (obligatorisch)</td></tr>
<tr><td>Tag: 80</td><td>Länge: 13</td><td>Wert: healthCare ProviderEanNumber</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Identifizierende Nummer bestehend aus 13 Ziffern</td></tr>
</table>

<table>
<tr><td>2.4.7</td><td colspan="3">Datum der Eintragung (obligatorisch)</td></tr>
<tr><td>Tag: 90</td><td>Länge: 10</td><td>Wert: dateOfRecord</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Datum im Format (JJJJ-MM-TT)</td></tr>
</table>

[^annex2-lvlu1-lvl2-lvl24-1]: Anatomical Therapeutical Chemical (ATC) classification index. Der Index kann eingesehen werden unter http://www.whocc.no/atcddd oder bestellt werden bei: World Health Organization (WHO), Collaborating Centre for Drug Statistics Methodology, Norwegian Institute of Public Health, Postboks 4404 Nydalen, 0403 Oslo, Norway.

### 2.5 Impfungen (optional, mehrfach)

Es sind [0–50] Einträge möglich; Rekord [1–50] der im Standard eCH-0064:2008 definierten Datei EF.IMMD.

<table>
<tr><td>Tag: 1000</td><td>Länge: x</td><td>Wert: vaccinations</td><td>Datentyp: Class</td></tr>
</table>

Die Angaben zu Impfungen bestehen aus folgenden Elementen:

<table>
<tr><td>2.5.1</td><td colspan="3">Bezeichnung der Impfung (optional)</td></tr>
<tr><td>Tag: 56</td><td>Länge: 2</td><td>Wert: vaccination Taxonomy</td><td>Datentyp: AN</td></tr>
</table>

Tabelle der erlaubten Codes:

<table>
<tr><th>ID</th><th>Impfung</th></tr>
<tr><td>01</td><td>Diphtherie</td></tr>
<tr><td>02</td><td>Tetanus – Starrkrampf</td></tr>
<tr><td>03</td><td>Pertussis – Keuchhusten</td></tr>
<tr><td>04</td><td>Poliomyelitis – Kinderlähmung</td></tr>
<tr><td>05</td><td>Haemophilus influenzae Typ b (Hib)</td></tr>
<tr><td>06</td><td>Hepatitis B</td></tr>
<tr><td>07</td><td>Hepatitis A</td></tr>
<tr><td>08</td><td>Masern</td></tr>
<tr><td>09</td><td>Mumps</td></tr>
<tr><td>10</td><td>Röteln</td></tr>
<tr><td>11</td><td>Humane Papillomaviren (HPV)</td></tr>
<tr><td>12</td><td>Windpocken</td></tr>
<tr><td>13</td><td>Pneumokokken</td></tr>
<tr><td>14</td><td>Meningokokken</td></tr>
<tr><td>15</td><td>Zeckenenzephalitis (FSME, TBE)</td></tr>
<tr><td>16</td><td>Tuberkulose (BCG)</td></tr>
<tr><td>17</td><td>Grippe</td></tr>
<tr><td>18</td><td>Tollwut</td></tr>
<tr><td>19</td><td>Gelbfieber</td></tr>
<tr><td>20</td><td>Japanische Enzephalitis</td></tr>
<tr><td>21</td><td>Abdominaltyphus</td></tr>
<tr><td>22</td><td>Cholera</td></tr>
<tr><td>23</td><td>Anthrax – Milzbrand</td></tr>
<tr><td>24</td><td>Andere Impfungen</td></tr>
</table>

<table>
<tr><td>2.5.2</td><td colspan="3">Bemerkung zur Impfung (optional)</td></tr>
<tr><td>Tag: 70</td><td>Länge: 0–100</td><td>Wert: vaccination Freetext</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Freitext: Bemerkung zur Impfung</td></tr>
</table>

<table>
<tr><td>2.5.3</td><td colspan="3">Handelsname des Impfstoffes (optional)</td></tr>
<tr><td>Tag: 57</td><td>Länge: 0–50</td><td>Wert: vaccineName</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Freitext: Handelsname des Impfstoffes</td></tr>
</table>

<table>
<tr><td>2.5.4</td><td colspan="3">Hersteller des Impfstoffes (optional)</td></tr>
<tr><td>Tag: 58</td><td>Länge: 0–50</td><td>Wert: manufacturer OfVaccine</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Freitext: Hersteller des Impfstoffes</td></tr>
</table>

<table>
<tr><td>2.5.5</td><td colspan="3">Lot-Nummer des Impfstoffes (optional)</td></tr>
<tr><td>Tag: 59</td><td>Länge: 8</td><td>Wert: vaccineLot Number</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Freitext: Lot-Nummer des Impfstoffes</td></tr>
</table>

<table>
<tr><td>2.5.6</td><td colspan="3">Datum der Impfung (optional)</td></tr>
<tr><td>Tag: 60</td><td>Länge: 10</td><td>Wert: vaccination Date</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Datum im Format (JJJJ-MM-TT)</td></tr>
</table>

<table>
<tr><td>2.5.7</td><td colspan="3">EAN-Nummer der eintragenden Person (obligatorisch)</td></tr>
<tr><td>Tag: 80</td><td>Länge: 13</td><td>Wert: healthCare ProviderEanNumber</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Identifizierende Nummer bestehend aus 13 Ziffern</td></tr>
</table>

<table>
<tr><td>2.5.8</td><td colspan="3">Datum der Eintragung (obligatorisch)</td></tr>
<tr><td>Tag: 90</td><td>Länge: 10</td><td>Wert: dateOfRecord</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Datum im Format (JJJJ-MM-TT)</td></tr>
</table>

### 2.6 Daten zu Blutgruppe und Transfusionen

Es ist 0–1 Eintrag möglich, Rekord [1] der im Standard eCH-0064:2008 definierten Datei EF.BGTD.

<table>
<tr><td>Tag: 1100</td><td>Länge: x</td><td>Wert: bloodGroup AndTransfusion</td><td>Datentyp: Class</td></tr>
</table>

Die Angaben zu Blutgruppe und Transfusionen bestehen aus folgenden Elementen:

<table>
<tr><td>2.6.1</td><td colspan="3">Daten zur Blutgruppe (optional)</td></tr>
<tr><td>Tag: 61</td><td>Länge: x</td><td>Wert: bloodGroup</td><td>Datentyp: Class</td></tr>
</table>

<table>
<tr><td>2.6.1.1</td><td colspan="3">Bezeichnung der Blutgruppe (optional)</td></tr>
<tr><td>Tag: 62</td><td>Länge: 1</td><td>Wert: bloodGroup Taxonomy</td><td>Datentyp: AN</td></tr>
</table>

Tabelle der erlaubten Codes:

<table>
<tr><th>ID</th><th>Blutgruppe</th></tr>
<tr><td>0</td><td>O</td></tr>
<tr><td>1</td><td>A</td></tr>
<tr><td>2</td><td>B</td></tr>
<tr><td>3</td><td>AB</td></tr>
</table>

<table>
<tr><td>2.6.1.2</td><td colspan="3">Bezeichnung des Rhesusfaktors (optional)</td></tr>
<tr><td>Tag: 63</td><td>Länge: 1</td><td>Wert: rhesusFactor</td><td>Datentyp: AN</td></tr>
</table>

Tabelle der erlaubten Codes:

<table>
<tr><th>ID</th><th>Rhesus-Faktor</th></tr>
<tr><td>0</td><td>+ve Vorzeichen positiv</td></tr>
<tr><td>1</td><td>–ve Vorzeichen negativ</td></tr>
</table>

<table>
<tr><td>2.6.1.3</td><td colspan="3">Datum des Blutgruppentests (optional)</td></tr>
<tr><td>Tag: 64</td><td>Länge: 10</td><td>Wert: dateOfBlood GroupTest</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Datum im Format (JJJJ-MM-TT)</td></tr>
</table>

<table>
<tr><td>2.6.1.4</td><td colspan="3">Bemerkung zur Blutgruppe (optional)</td></tr>
<tr><td>Tag: 70</td><td>Länge: 0–100</td><td>Wert: bloodGroup Freetext</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Freitext: Bemerkung zur Blutgruppe</td></tr>
</table>

<table>
<tr><td>2.6.1.5</td><td colspan="3">EAN-Nummer der eintragenden Person (obligatorisch)</td></tr>
<tr><td>Tag: 80</td><td>Länge: 13</td><td>Wert: healthCare ProviderEanNumber</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Identifizierende Nummer bestehend aus 13 Ziffern</td></tr>
</table>

<table>
<tr><td>2.6.1.6</td><td colspan="3">Datum der Eintragung (obligatorisch)</td></tr>
<tr><td>Tag: 90</td><td>Länge: 10</td><td>Wert: dateOfRecord</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Datum im Format (JJJJ-MM-TT)</td></tr>
</table>

<table>
<tr><td>2.6.2</td><td colspan="3">Daten zu Transfusionen (optional)</td></tr>
<tr><td>Tag: 65</td><td>Länge: x</td><td>Wert: transfusion</td><td>Datentyp: Class</td></tr>
</table>

<table>
<tr><td>2.6.2.1</td><td colspan="3">Indikator für die Anzahl der Bluttransfusionen (optional)</td></tr>
<tr><td>Tag: 66</td><td>Länge: 1</td><td>Wert: numberOfBlood Transfusions</td><td>Datentyp: AN</td></tr>
</table>

Tabelle der erlaubten Codes:

<table>
<tr><th>ID</th><th>Indikator Transfusion</th></tr>
<tr><td>0</td><td>Nie</td></tr>
<tr><td>1</td><td>Einmal</td></tr>
<tr><td>2</td><td>Mehr als einmal</td></tr>
</table>

<table>
<tr><td>2.6.2.2</td><td colspan="3">Datum der letzten Bluttransfusion (optional)</td></tr>
<tr><td>Tag: 67</td><td>Länge: 10</td><td>Wert: dateOfLast BloodTransfusion</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Datum im Format (JJJJ-MM-TT)</td></tr>
</table>

<table>
<tr><td>2.6.2.3</td><td colspan="3">Bemerkung zur letzten Bluttransfusion (optional)</td></tr>
<tr><td>Tag: 70</td><td>Länge: 0–100</td><td>Wert: blood TransfusionFreetext</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Freitext: Bemerkung zur letzten Bluttransfusion</td></tr>
</table>

<table>
<tr><td>2.6.2.4</td><td colspan="3">EAN-Nummer der eintragenden Person (obligatorisch)</td></tr>
<tr><td>Tag: 80</td><td>Länge: 13</td><td>Wert: healthCare ProviderEanNumber</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Identifizierende Nummer bestehend aus 13 Ziffern</td></tr>
</table>

<table>
<tr><td>2.6.2.5</td><td colspan="3">Datum der Eintragung (obligatorisch)</td></tr>
<tr><td>Tag: 90</td><td>Länge: 10</td><td>Wert: dateOfRecord</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Datum im Format (JJJJ-MM-TT)</td></tr>
</table>

### 2.7 Zusätzlicher Eintrag in medizinisch begründeten Fällen

<table>
<tr><td>2.7.1</td><td>Hinweise auf verfügbare medizinische oder pharmazeutische Dossiers (optional, mehrfach)</td></tr>
</table>

Es sind [0–10] Einträge möglich; Rekord [1–10] der im Standard eCH-0064:2008 definierten Datei EF.ZUSE.

<table>
<tr><td>Tag: 1200</td><td>Länge: x</td><td>Wert: medical Pharmaceutical Dossier</td><td>Datentyp: Class</td></tr>
</table>

Die Angaben zu Hinweisen auf verfügbare medizinische oder pharmazeutische Dossiers bestehen aus folgenden Elementen:

<table>
<tr><td>2.7.1.1</td><td>Angaben zur Adresse des Verwahrers im Format gemäss dem Standard eCH-0010 «Datenstandard Postadresse für natürliche Personen, Firmen, Organisationen und Behörden» in der Fassung des Jahres 2006 (eCH-0010:2006)</td></tr>
</table>

<table>
<tr><td>2.7.1.2</td><td colspan="3">Bemerkung zum medizinischen oder pharmazeutischen Dossier (optional)</td></tr>
<tr><td>Tag: 70</td><td>Länge: 0–100</td><td>Wert: medical DossierFreetext</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Freitext: Bemerkung zum medizinischen oder pharmazeutischen Dossier (z. B. betreffend Inhalt, Hinweise auf elektronische Dossiers)</td></tr>
</table>

<table>
<tr><td>2.7.1.3</td><td colspan="3">EAN-Nummer der eintragenden Person (obligatorisch)</td></tr>
<tr><td>Tag: 80</td><td>Länge: 13</td><td>Wert: healthCare ProviderEanNumber</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Identifizierende Nummer, bestehend aus 13 Ziffern</td></tr>
</table>

<table>
<tr><td>2.7.1.4</td><td colspan="3">Datum der Eintragung (obligatorisch)</td></tr>
<tr><td>Tag: 90</td><td>Länge: 10</td><td>Wert: dateOfRecord</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Datum im Format (JJJJ-MM-TT)</td></tr>
</table>

<table>
<tr><td>2.7.2</td><td>Weitere medizinische oder pharmazeutische Einträge (optional, mehrfach)</td></tr>
</table>

Es sind [0–25] Einträge möglich; Rekord [11–35] der im Standard eCH-0064:2008 definierten Datei EF.ZUSE.

<table>
<tr><td>Tag: 1300</td><td>Länge: x</td><td>Wert: additional MedicalAnd PharmaceuticalEntries</td><td>Datentyp: Class</td></tr>
</table>

Die Angaben zu weiteren medizinischen oder pharmazeutischen Einträgen bestehen aus folgenden Elementen:

<table>
<tr><td>2.7.2.1</td><td colspan="3">Bezeichnung des weiteren medizinischen oder pharmazeutischen Eintrags (optional)</td></tr>
<tr><td>Tag: 60</td><td>Länge: 0–20</td><td>Wert: nameOfAdditionalMedicalAnd PharmaceuticalEntries</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Freitext: Bezeichnung des weiteren medizinischen oder pharmazeutischen Eintrags</td></tr>
</table>

<table>
<tr><td>2.7.2.2</td><td colspan="3">Bemerkung zum weiteren medizinischen oder pharmazeutischen Eintrag (optional)</td></tr>
<tr><td>Tag: 70</td><td>Länge: 0–100</td><td>Wert: additional MedicalAnd Pharmaceutical EntriesFreetext</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Freitext: Bemerkung zum weiteren medizinischen oder pharmazeutischen Eintrag</td></tr>
</table>

<table>
<tr><td>2.7.2.3</td><td colspan="3">EAN-Nummer der eintragenden Person (obligatorisch)</td></tr>
<tr><td>Tag: 80</td><td>Länge: 13</td><td>Wert: healthCare ProviderEanNumber</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Identifizierende Nummer bestehend aus 13 Ziffern</td></tr>
</table>

<table>
<tr><td>2.7.2.4</td><td colspan="3">Datum der Eintragung (obligatorisch)</td></tr>
<tr><td>Tag: 90</td><td>Länge: 10</td><td>Wert: dateOfRecord</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Datum im Format (JJJJ-MM-TT)</td></tr>
</table>

### 2.8 Kontaktadressen für den Notfall (optional, mehrfach)

Es sind [0–10] Einträge möglich; Rekord [1–10] der im Standard eCH-0064:2008 definierten Datei EF.ADDR.

<table>
<tr><td>Tag: 1400</td><td>Länge: x</td><td>Wert: contact AddressesFor Emergency</td><td>Datentyp: Class</td></tr>
</table>

Die Angaben zu den Kontaktadressen für den Notfall bestehen aus folgenden Elementen:

<table>
<tr><td>2.8.1</td><td colspan="3">Art der Kontaktadresse (optional)</td></tr>
<tr><td>Tag: 77</td><td>Länge: 1</td><td>Wert: kindOf Addressee</td><td>Datentyp: AN</td></tr>
</table>

Tabelle der erlaubten Codes:

<table>
<tr><th>ID</th><th>Art der Kontaktadresse</th></tr>
<tr><td>1</td><td>Kontaktadresse im privaten Umfeld</td></tr>
<tr><td>2</td><td>Kontaktadresse im medizinischen Umfeld</td></tr>
</table>

<table>
<tr><td>2.8.2</td><td>Angaben zur Kontaktadresse im Format gemäss dem Standard eCH-0010:2006</td></tr>
</table>

### 2.9 Hinweise auf bestehende Patientenverfügungen oder Organspendeausweise (optional, mehrfach)

Es sind [0–10] Einträge möglich; Rekord [1–10] der im Standard eCH-0064:2008 definierten Datei EF.VERF.

<table>
<tr><td>Tag: 1500</td><td>Länge: x</td><td>Wert: noticeOn PatientDecree</td><td>Datentyp: Class</td></tr>
</table>

Die Angaben zu Patientenverfügungen bestehen aus folgenden Elementen:

<table>
<tr><td>2.9.1</td><td colspan="3">Art des Verwahrers des Dokuments (optional)</td></tr>
<tr><td>Tag: 78</td><td>Länge: 1</td><td>Wert: keeperOf Documents</td><td>Datentyp: AN</td></tr>
</table>

Tabelle der erlaubten Codes:

<table>
<tr><th>ID</th><th>Art des Verwahrers</th></tr>
<tr><td>1</td><td>Kontaktadresse im privaten Umfeld</td></tr>
<tr><td>2</td><td>Kontaktadresse im medizinischen Umfeld</td></tr>
</table>

<table>
<tr><td>2.9.2</td><td>Angaben zur Adresse des Verwahrers im Format gemäss dem Standard eCH-0010:2006</td></tr>
</table>

<table>
<tr><td>2.9.3</td><td colspan="3">Bemerkung zur Beschreibung der Verfügung oder des Ausweises (optional)</td></tr>
<tr><td>Tag: 70</td><td>Länge: 0–100</td><td>Wert: noticeOn PatientDecreeFreetext</td><td>Datentyp: AN</td></tr>
<tr><td colspan="4">Freitext: Bemerkung zur Beschreibung der Verfügung oder des Ausweises</td></tr>
</table>

Anhang 3

(Art. 3)

## Spezifikation der Daten für die Abfrage im Online-Verfahren

Die folgenden Spezifikationen der Dateneingabe und Datenausgabe für die Abfrage im Online-Verfahren enthalten für alle Datenelemente im Titel die Beschreibung und in Klammern die Elementbezeichnungen der XML-Schemata[^annex3-lvlu1-1] sowie das Format und die Länge.

[^annex3-lvlu1-1]: Die XML-Schemata sind zu beziehen beim Bundesamt für Gesundheit, 3003 Bern oder einzusehen unter www.ehealth.admin.ch.

## 1 Dateneingabe Anfrage (inputData)

Format: complex

Anfragende Leistungserbringer müssen für eine Abfrage im Online-Verfahren folgende Eingabedaten angeben:

<table>
<tr><td>1.1</td><td>Kennnummer der Versichertenkarte (cardNoVeka)</td></tr>
<tr><td colspan="2">Format: token, Länge 20</td></tr>
</table>

<table>
<tr><td>1.2</td><td>ZSR-Nummer (Zentralstellenregister-Nummer) des Leistungserbringers (ZSRno)</td></tr>
<tr><td colspan="2">Format: token, Länge 9</td></tr>
</table>

### 2 Datenausgabe Antwort (outputData)

Format: complex

Vom Online-Service müssen die zum Zeitpunkt der Abfrage aktuellen Informationen gemäss nachfolgender Auflistung bekannt gegeben werden.

<table>
<tr><td>2.1</td><td>Eingabedaten</td></tr>
<tr><td colspan="2">Die Eingabedaten nach Ziffer 1 werden zu Kontrollzwecken bekannt gegeben.</td></tr>
</table>

<table>
<tr><td>2.2</td><td>Abfragedatum (qualifyingDate)</td></tr>
<tr><td colspan="2">Format: date, JJJJ-MM-TT, Länge 10</td></tr>
<tr><td colspan="2">Das Datum gibt an, wann der Leistungserbringer die Abfrage gemacht hat.</td></tr>
</table>

<table>
<tr><td>2.3</td><td>Abfragenummer (queryNumber)</td></tr>
<tr><td colspan="2">Format: token, Länge 20</td></tr>
<tr><td colspan="2">Das Datenelement enthält eine Nummer, die jeder Abfrage zugeordnet wird. Die Nummer bezweckt die Bestätigung der Abfrage.</td></tr>
<tr><td>2.4</td><td>Gültigkeit der Versichertenkarte (validCard)</td></tr>
<tr><td colspan="2">Format: string, Länge 1</td></tr>
<tr><td colspan="2">Das Datenelement zeigt an, ob die Versichertenkarte gültig ist. Es sind folgende Rückgabewerte erlaubt:</td></tr>
<tr><td colspan="2">Ja = 1</td></tr>
<tr><td colspan="2">Nein = 2</td></tr>
</table>

<table>
<tr><td>2.5</td><td>Daten nach Artikel 3 Absatz 1 VVK</td></tr>
<tr><td colspan="2">Falls die Versichertenkarte gültig ist, müssen die Daten nach Artikel 3 Absatz 1 VVK wie in Anhang 1 spezifiziert bekannt gegeben werden.</td></tr>
</table>

<table>
<tr><td>2.6</td><td>Daten nach Artikel 4 Absatz 2 VVK</td></tr>
<tr><td colspan="2">Falls die Versichertenkarte gültig ist, können die Daten nach Artikel 4 Absatz 2 VVK wie in Anhang 1 spezifiziert bekannt gegeben werden.</td></tr>
</table>

Anhang 4[^t-2]

(Art. 4)

## Grafische Anforderungen an die Versichertenkarte

[^t-2]: Bereinigt gemäss Anhang Ziff. II 38 der V vom 17. Nov. 2021, in Kraft seit 1. Jan. 2022 ([AS 2021 800](https://fedlex.data.admin.ch/eli/oc/2021/800)).

### 1 Allgemeines

### 1.1 Referenz

<table>
<tr><td>EN (Europäische Norm) 1867:1997</td><td>Maschinenlesbare Karten – Anwendungen im Gesundheitswesen – Benummerungssystem und Registrierungsverfahren für Kartenausgeberschlüssel</td></tr>
</table>

### 1.2 Bezugsquelle

<table>
<tr><td>Europäische Norm</td><td>Europäisches Komitee für Normung (CEN), Zentralsekretariat, rue de Stassart 36, B-1050 Brüssel, http://www.cenorm.be Die Norm kann beim Bundesamt für Gesundheit eingesehen werden.</td></tr>
</table>

### 1.3 Abkürzung

<table>
<tr><td>Char</td><td>Charakter</td></tr>
</table>

### 2 Grafische Anforderungen

### 2.1 Struktur der Versichertenkarte

Die Versichertenkarte muss in drei horizontale Bereiche aufgeteilt werden:

[tab] – Titelbereich:

- Dieser Bereich verläuft auf einer Breite von 10 mm unterhalb des oberen Kartenrands und enthält die Bezeichnung «Schweizerische Krankenversicherungskarte KVG» in den vier Landessprachen sowie das Schweizerkreuz.

[tab] – Bereich des Versicherers:

- Dieser Bereich enthält den Mikroprozessorchip sowie den Namen des Versicherers. Er kann vom Versicherer frei gestaltet werden.

[tab] – Bereich der versicherten Person:

- Dieser Bereich verläuft auf einer Breite von 20 mm oberhalb des unteren Kartenrands und enthält die Daten nach Artikel 3 Absatz 1 VVK.

### 2.2 Grafische Darstellung

Abbildung 1 zeigt die Masse und Strukturierung der Versichertenkarte sowie die Anordnung der einzelnen grafischen Elemente (z. B. Logo, Texte und Titel). Die umrahmten Nummern bezeichnen die einzelnen grafischen Elemente.

Abbildung 1

Darstellung der grafischen Elemente

![](https://fedlex.data.admin.ch/filestore/fedlex.data.admin.ch/eli/cc/2008/228/20220101/de/xml/image/image1.png)

Tabelle 1

Schriftart und Positionierung der grafischen Elemente

<table>
<tr><th>Element-Nummer</th><th>Bezeichnung</th><th>Schriftart Grösse</th><th>x-Koordinate (mm)</th><th>y-Koordinate (mm)</th><th>Ausrichtung</th></tr>
<tr><td></td><td>Kartentitel</td><td></td><td></td><td></td><td></td></tr>
<tr><td>03 03’’ 03’’’ 03’’’’</td><td>de fr it rm</td><td>Verdana 6 Pt. Fett Verdana 6 Pt. Fett Verdana 6 Pt. Fett Verdana 6 Pt. Fett</td><td>19.0 19.0 19.0 19.0</td><td>50.0 48.0 46.0 44.0</td><td>Links Links Links Links</td></tr>
<tr><td>06</td><td>Name, Vorname</td><td>Verdana 8 Pt. Fett</td><td>3.0</td><td>16.4</td><td>Links</td></tr>
<tr><td>07</td><td>Titel Name, Vorname</td><td>Verdana 4 Pt. Normal</td><td>3.0</td><td>14.8</td><td>Links</td></tr>
<tr><td>08</td><td>Kennnummer der Versichertenkarte (Karten-Nummer)</td><td>Verdana 8 Pt. Normal</td><td>3.0</td><td>11.0</td><td>Links</td></tr>
<tr><td>09</td><td>Titel Karten-Nummer</td><td>Verdana 4 Pt. Normal</td><td>3.0</td><td>9.4</td><td>Links</td></tr>
<tr><td>10</td><td>Geburtsdatum Geschlecht</td><td>Verdana 8 Pt. Normal</td><td>3.0</td><td>5.6</td><td>Links</td></tr>
<tr><td>11 11’’</td><td>Titel Geburtsdatum, Geschlecht 1. Zeile Titel Geburtsdatum, Geschlecht 2. Zeile</td><td>Verdana 4 Pt. Normal Verdana 4 Pt. Normal</td><td>3.0 3.0</td><td>4.0 2.4</td><td>Links Links</td></tr>
<tr><td>12</td><td>BAG-Nummer</td><td>Verdana 8 Pt. Normal</td><td>44.5</td><td>11.0</td><td>Links</td></tr>
<tr><td>13 13’’</td><td>Titel BAG-Nummer 1. Zeile Titel BAG-Nummer 2. Zeile</td><td>Verdana 4 Pt. Normal Verdana 4 Pt. Normal</td><td>44.5 44.5</td><td>9.4 7.8</td><td>Links Links</td></tr>
<tr><td>14</td><td>AHV-Nummer</td><td>Verdana 8 Pt. Normal</td><td>82.6</td><td>11.0</td><td>Rechts</td></tr>
<tr><td>15</td><td>Titel AHV-Nummer</td><td>Verdana 4 Pt. Normal</td><td>82.6</td><td>9.4</td><td>Rechts</td></tr>
<tr><td>16</td><td>Ablaufdatum</td><td>Verdana 8 Pt. Normal</td><td>82.6</td><td>5.6</td><td>Rechts</td></tr>
<tr><td>17 17’’</td><td>Titel Ablaufdatum 1. Zeile Titel Ablaufdatum 2. Zeile</td><td>Verdana 4 Pt. Normal Verdana 4 Pt. Normal</td><td>82.6 82.6</td><td>4.0 2.4</td><td>Rechts Rechts</td></tr>
</table>

Tabelle 2

Spezifikationen der grafischen Elemente und Daten nach Artikel 3 VVK

<table>
<tr><th>Element-Nummer</th><th>Bezeichnung</th><th>Beschreibung Beispiele</th><th>Datentyp</th><th>Länge, Format</th><th>v: Vorgedruckt p: Personalisiert</th></tr>
<tr><td>01</td><td>Hintergrund</td><td>Der Hintergrund der Karte darf vom Versicherer gestaltet werden. Der Kontrast muss so gewählt werden, dass alles gut lesbar ist.</td><td>Bild</td><td></td><td>v</td></tr>
<tr><td>02</td><td>Logo Karte Schweizerkreuz</td><td>Schweizerkreuz Gemäss Artikel 1 des Bundesbeschlusses vom 12. Dezember 1889 (SR *111*)</td><td>Bild</td><td></td><td>v</td></tr>
<tr><td>03</td><td>Kartentitel de fr it rm</td><td>Kartentitel in den vier Landessprachen Schweizerische Krankenversicherungskarte KVG Carte suisse d’assurance-maladie LAMal Tessera svizzera d’assicurazione malattie LAMal Carta svizra da l’assicuranza da malsauns LAM</td><td>Char</td><td></td><td>v</td></tr>
<tr><td>04</td><td>Chip</td><td>Mikroprozessorchip Die Grösse des von aussen sichtbaren Chip-Moduls beträgt ca. 13 × 12 mm. Rund um den Chip ist ein 1-mm-Rand für Implantierungstoleranzen zu berücksichtigen.</td><td></td><td></td><td></td></tr>
<tr><td>05</td><td>Name des Versicherers</td><td>Keine Vorgaben</td><td></td><td></td><td></td></tr>
<tr><td>06</td><td>Name, Vorname</td><td>Name (Teil 1) und Vorname (Rufname) (Teil 2); Teil 2 evtl. abgekürzt. Zwischen den Teilen 1 und 2 sind ein Komma und ein Leerschlag zu setzen; Gross- und Kleinschreibung Bsp: **Muster, Erich**</td><td>Char</td><td>50 (inkl. Komma und Leerschlag zwischen Teil 1 und 2)</td><td>p</td></tr>
<tr><td>07</td><td>Titel Name, Vorname</td><td>**Name, Vorname/Nom, prénom/Cognome, nome/Num, prenum**</td><td>Char</td><td>48</td><td>p</td></tr>
<tr><td>08</td><td>Kennnummer der Versichertenkarte (Karten-Nummer)</td><td>Individuelle fortlaufende Nummer, mit der der Versicherer jede Karte versieht, um die einzelnen Karten zu identifizieren. Die ersten 10 Zeichen bezeichnen den Versicherer gemäss der Europäischen Norm 1867 «Maschinenlesbare Karten – Anwendungen im Gesundheitswesen – Benummerungssystem und Registrierungsverfahren für Kartenausgeberschlüssel» in der Fassung des Jahres 1997 (EN 1867:1997). Die letzten 10 Stellen ergeben die einmalige Seriennummer. Falls auf der Rückseite der Versichertenkarte (VK) die Daten der europäischen Krankenversicherungskarte (EU-KVK) aufgedruckt sind, muss die Kennnummer der VK identisch sein mit der Kennnummer der EU-KVK.</td><td>Char</td><td>20</td><td>p</td></tr>
<tr><td>09</td><td>Titel Karten-Nummer</td><td>Karten-Nr./No carte/N. carta/Nr. da la carta</td><td>Char</td><td>35</td><td>p</td></tr>
<tr><td>10</td><td>Geburtsdatum Geschlecht</td><td>Geburtsdatum Bsp: **13.12.1996** Geschlecht **M** = männlich **F** = weiblich</td><td>Datum Char</td><td>10 TT.MM.JJJJ 1 **M** **F**</td><td>p</td></tr>
<tr><td>11</td><td>Titel Geburtsdatum, Geschlecht</td><td>**Geburtsdatum, Geschlecht/Date de naissance, sexe** Data die nascita, sesso/Data da naschientscha, schlattaina</td><td>Char</td><td>48 58</td><td>p</td></tr>
<tr><td>12</td><td>BAG-Nummer</td><td>BAG-Nummer des Versicherers: Bsp: **12345**</td><td>Char</td><td>5</td><td>p</td></tr>
<tr><td>13</td><td>Titel BAG-Nummer</td><td>**BAG-Nr./No OFSP** N. UFSP/Nr. UFSP</td><td>Char</td><td>14 15</td><td>p</td></tr>
<tr><td>14</td><td>AHV-Nummer</td><td>Neue 13-stellige AHV-Nummer mit Trennpunkten nach der 3., 7. und 11. Stelle: Bsp: **756.3047.5009.62**</td><td>Char</td><td>16 inkl. 3 Punkte</td><td>p</td></tr>
<tr><td>15</td><td>Titel AHV-Nummer</td><td>**AHV-Nr./No AVS/N. AVS/Nr. AVS**</td><td>Char</td><td>28</td><td>p</td></tr>
<tr><td>16</td><td>Ablaufdatum</td><td>Werden die Daten der EU-KVK auf der Rückseite der schweizerischen Versichertenkarte aufgedruckt, so muss das Ablaufdatum der beiden Karten identisch sein.</td><td>Datum</td><td>10 TT.MM.JJJJ</td><td>p</td></tr>
<tr><td>17</td><td>Titel Ablaufdatum</td><td>**Ablaufdatum/Date d’expiration** **Data di scadenza/Data da scadenza**</td><td>Char</td><td>28 35</td><td>p</td></tr>
</table>
