---
sr: "832.105.1"
title: "Ordonnance du DFI du 20 mars 2008 concernant les exigences techniques et graphiques relatives à la carte d'assuré pour l'assurance obligatoire des soins (OCA-DFI)"
short: OCA-DFI
eli: "https://fedlex.data.admin.ch/eli/cc/2008/228"
language: fr
version: 2022-01-01
adopted: 2008-03-20
in_force: 2008-04-01
source: "https://fedlex.data.admin.ch/filestore/fedlex.data.admin.ch/eli/cc/2008/228/20220101/fr/xml/fedlex-data-admin-ch-eli-cc-2008-228-20220101-fr-xml-6.xml"
url: "https://www.fedlex.admin.ch/eli/cc/2008/228/20220101/fr"
---

> Reproduction non officielle de la version consolidée (Fedlex). Seule la publication au Recueil officiel fait foi (art. 15 LPubl, RS 170.512).

# Ordonnance du DFI concernant les exigences techniques et graphiques relatives à la carte d’assuré pour l’assurance obligatoire des soins

(OCA-DFI)

du 20 mars 2008 (État le 1<sup>er</sup> janvier 2022)

Le Département fédéral de l’intérieur,

vu les art. 3, al. 3, et 17 de l’ordonnance du 14 février 2007 sur la carte d’assuré pour l’assurance obligatoire des soins (OCA)[^ingress-1],

arrête:

[^ingress-1]: [RS 832.105](https://fedlex.data.admin.ch/eli/cc/2007/101)

#### Art. 1

**Données destinées à la facturation**

La spécification des données destinées à la facturation figure à l’annexe 1.

#### Art. 2

**Données au sens de l’art. 6 OCA**

La spécification des données au sens de l’art. 6 OCA figure à l’annexe 2.

#### Art. 3

**Données pour l’interrogation en ligne**

La spécification des données pour l’interrogation en ligne au sens de l’art. 15 OCA figure à l’annexe 3.

#### Art. 4

**Exigences graphiques relatives à la carte d’assuré**

Les exigences graphiques relatives à la carte d’assuré figurent à l’annexe 4.

#### Art. 5

**Norme eCH-0064**

La norme eCH-0064 «Spécifications du système Carte d’assuré» du 4 février 2008[^5-1] est applicable. Elle définit:

- a. les exigences techniques et celles concernant la communication de la carte d’assuré;
- b. les exigences relatives aux systèmes d’exploitation et de fichiers de la carte d’assuré;
- c. les exigences relatives à l’attestation électronique justifiant de la qualité de fournisseur de prestations au sens de l’art. 8 OCA;
- d. la spécification des procédures d’authentification et d’autorisation entre la carte d’assuré et l’attestation électronique justifiant de la qualité de fournisseur de prestations au sens de l’art. 8 OCA;
- e. les exigences relatives à la gestion des codes NIP de la carte d’assuré;
- f. les exigences relatives à la procédure d’interrogation en ligne au sens de l’art. 15 OCA;
- g. les exigences relatives à la carte d’assuré pour son utilisation dans le cadre d’essais pilotes cantonaux au sens de l’art. 16 OCA.

[^5-1]: Cette norme n’est pas publiée au RO. Commande: association eCH, Mainaustrasse 30, 8008 Zürich, Office fédéral de la santé publique, Assurance‑maladie et accidents, 3003 Berne. Téléchargement: www.ech.ch.

#### Art. 6

**Entrée en vigueur**

La présente ordonnance entre en vigueur le 1<sup>er</sup> avril 2008.

Annexe 1[^t-1]

(art. 1)

## Spécification des données relatives à la facturation

[^t-1]: Mise à jour par l’annexe ch. II 38 de l’O du 17 nov. 2021, en vigueur depuis le 1<sup>er</sup> janv. 2022 ([RO 2021 800](https://fedlex.data.admin.ch/eli/oc/2021/800)).

### 1 Généralités

### 1.1 Références

<table>
<tr><td>Draft prEN ISO 21549-5:2006</td><td>Health informatics – Patient healthcard data – Part 5: Identification Data</td></tr>
<tr><td>ISO/DIS 21549-6:2006</td><td>Health informatics – Patient healthcard data – Part 6: Administrative Data</td></tr>
<tr><td>eCH-0010:2006</td><td>Adresses postales pour les personnes physiques, les entreprises, les organisations et les autorités</td></tr>
<tr><td>eCH-0064:2008</td><td>Spécifications du système Carte d’assuré</td></tr>
<tr><td>EN (norme européenne) 1867:1997</td><td>Cartes lisibles par machine – Applications dans le domaine de la santé – Système de numérotation et procédure d’enregistrement pour les identificateurs des émetteurs de cartes</td></tr>
</table>

### 1.2 Sources

<table>
<tr><td>Normes ISO</td><td>Secrétariat central de l’Organisation internationale de normalisation (ISO), Chemin de la Voie-Creuse 1, Case postale 56, 1211 Genève 20, http://www.iso.org Les normes peuvent être consultées auprès de l’Office fédéral de la santé publique.</td></tr>
<tr><td>Normes eCH</td><td>Association eCH, Mainaustrasse 30, 8008 Zurich, http://www.ech.ch/</td></tr>
<tr><td>Norme européenne</td><td>Comité européen de normalisation, rue de Stassart 36, B‑1050 Bruxelles, http://www.cenorm.be La norme peut être consultée auprès de l’Office fédéral de la santé publique.</td></tr>
</table>

### 1.3 Abréviations et définitions

<table>
<tr><td>AN</td><td>Alphanumérique</td></tr>
<tr><td>Char</td><td>Caractère</td></tr>
<tr><td>Class</td><td>Type de données complexes constitué de plusieurs éléments</td></tr>
<tr><td>Tag</td><td>Marqueur identifiant un élément</td></tr>
</table>

### 2 Spécification des données électroniques au sens de l’art. 4 OCA

Les données d’identification au sens du ch. 2.1 doivent être spécifiées conformément au projet de norme Draft prEN ISO/DIS 21549-5 «Health informatics – Patient healthcard data – Part 5: Identification data» dans son édition de 2006 (ISO 21549-5:2006) et les données administratives conformément à la norme ISO/DIS 21549-6 «Health informatics – Patient healthcard data – Part 6: Administrative data» dans son édition de 2006 (ISO/DIS 21549-6:2006). Les éléments obligatoires concernant des groupes de données facultatives ne doivent être pris en considération que si les données facultatives sont introduites.

Pour l’utilisation des données, l’OFSP met à disposition des schémas XML[^annex1-lvlu1-lvl2-1]. La désignation des tags et des schémas XML est indiquée.

### 2.1 Données d’identification (65, cardholderRelatedTemplate)

[^annex1-lvlu1-lvl2-1]: Les schémas XML peuvent être commandés auprès de l’Office fédéral de la santé publique, 3003 Berne, ou consultés à l’adresse www.ehealth.admin.ch.

Les données doivent être enregistrées sur la carte dans le fichier EF.ID défini dans la norme eCH-0064 «Spécifications du système Carte d’assuré» du 4 février 2008 (eCH-0064:2008).

<table>
<tr><td>2.1.1</td><td>Nom (80, name)</td></tr>
<tr><td></td><td>Cet élément comprend le nom et le prénom.</td></tr>
</table>

<table>
<tr><td>2.1.2</td><td colspan="2">Date de naissance (82, dateOfBirth)</td></tr>
<tr><td></td><td>Différence par rapport à la norme ISO 21549-5:2006:</td><td>cet élément est obligatoire.</td></tr>
</table>

<table>
<tr><td>2.1.3</td><td colspan="2">N<sup>o</sup> AVS (83, cardholderIdentifier)</td></tr>
<tr><td></td><td>Complément à la norme ISO 21549-5:2006:</td><td>la longueur de cet élément est de 13 caractères et ne comprend pas d’éléments de séparation.</td></tr>
<tr><td></td><td>Différence par rapport à la norme ISO 21549-5:2006:</td><td>cet élément est obligatoire.</td></tr>
</table>

<table>
<tr><td>2.1.4</td><td colspan="2">Sexe (84, sex)</td></tr>
<tr><td></td><td>Différence par rapport à la norme ISO 21549-5:2006:</td><td>cet élément est obligatoire.</td></tr>
</table>

### 2.2 Données administratives (65, cardholderRelatedTemplate)

Les données doivent être enregistrées sur la carte dans le fichier EF.AD défini dans la norme eCH-0064:2008.

<table>
<tr><td>2.2.1</td><td>Identification de l’Etat émetteur de la carte (90, issuingStateId Number)</td></tr>
<tr><td></td><td>L’Etat émetteur de la carte est la Suisse.</td></tr>
</table>

<table>
<tr><td>2.2.2</td><td>Nom de l’assureur (91, nameOfTheInstitution)</td></tr>
</table>

<table>
<tr><td>2.2.3</td><td>N<sup>o</sup> OFSP de l’assureur (92, identificationNumberOfTheInstitution)</td></tr>
</table>

<table>
<tr><td>2.2.4</td><td colspan="2">N<sup>o</sup> d’identification de la carte d’assuré (93, insuredPersonNumber)</td></tr>
<tr><td></td><td colspan="2">Numéro logique individuel visant à identifier chaque carte et attribué par l’émetteur de la carte. Les dix premiers caractères identifient l’émetteur de la carte, conformément à la norme européenne EN 1867 «Cartes lisibles par machine – Applications pour la santé – Système de numérotation et procédure d’enregistrement pour les identificateurs d’émetteur» dans son édition de 1997 (norme EN 1867:1997). Les dix derniers caractères forment le numéro de série unique.</td></tr>
<tr><td></td><td>Complément à la norme ISO/DIS 21549-6:2006:</td><td>Si les données de la carte européenne d’assurance-maladie (CEAM) sont imprimées au dos de la carte d’assuré (CA), le n<sup>o</sup> d’identification de la CA doit être identique à celui de la CEAM.</td></tr>
<tr><td></td><td>Différence par rapport à la norme ISO 21549-6:2006:</td><td>cet élément est obligatoire.</td></tr>
</table>

<table>
<tr><td>2.2.5</td><td colspan="2">Date d’expiration (94, expiryDate)</td></tr>
<tr><td></td><td>Complément à la norme ISO/DIS 21549-6:2006:</td><td>Si les données de la CEAM sont imprimées au dos de la CA, la date d’expiration des deux cartes doit être identique.</td></tr>
</table>

<table>
<tr><td>2.2.6</td><td colspan="3">Eléments nationaux</td></tr>
<tr><td>Tag: 10</td><td>Longueur: x</td><td>Valeur: nationalExtension</td><td>Type: class</td></tr>
</table>

<table>
<tr><td>2.2.6.1</td><td colspan="3">Adresse de la personne assurée (facultatif)</td></tr>
<tr><td>Tag: 09</td><td>Longueur: x</td><td>Valeur: mailAddress</td><td>Type: class</td></tr>
<tr><td colspan="4">Les données concernant l’adresse de la personne assurée doivent être spécifiées conformément à la norme eCH-0010 «Adresses postales pour les personnes physiques, les entreprises, les organisations et les autorités» dans son édition de 2006 (eCH-0010:2006).</td></tr>
</table>

<table>
<tr><td>2.2.6.2</td><td colspan="3">Données concernant l’assurance obligatoire des soins (AOS) (facultatif)</td></tr>
<tr><td>Tag: 10</td><td>Longueur: x</td><td>Valeur: KVGInformation</td><td>Type: class</td></tr>
<tr><td colspan="4">Les données concernant l’AOS comprennent les éléments suivants:</td></tr>
</table>

<table>
<tr><td>2.2.6.2.1</td><td colspan="3">Langue régionale officielle (facultatif)</td></tr>
<tr><td>Tag: 11</td><td>Longueur: 2</td><td>Valeur: languageRegion</td><td>Type: AN</td></tr>
</table>

<table>
<tr><td>Langue régionale officielle de l’assuré Codes à utiliser:</td></tr>
</table>

<table>
<tr><th>ID</th><th>Langue régionale officielle</th></tr>
<tr><td>de</td><td>allemand</td></tr>
<tr><td>fr</td><td>français</td></tr>
<tr><td>it</td><td>italien</td></tr>
<tr><td>rm</td><td>romanche</td></tr>
<tr><td>zz</td><td>autres</td></tr>
</table>

<table>
<tr><td>2.2.6.2.2</td><td colspan="3">Forme d’assurance (facultatif)</td></tr>
<tr><td>Tag: 12</td><td>Longueur: 2</td><td>Valeur: KVGModel</td><td>Type: AN</td></tr>
</table>

<table>
<tr><td>Codes à utiliser:</td></tr>
</table>

<table>
<tr><th>ID</th><th>Forme d’assurance</th></tr>
<tr><td>01</td><td>Modèle standard (sans restriction du choix des fournisseurs de prestations)</td></tr>
<tr><td>02</td><td>modèle du médecin de famille</td></tr>
<tr><td>03</td><td>modèle HMO</td></tr>
<tr><td>04</td><td>modèle avec liste</td></tr>
<tr><td>05</td><td>autres</td></tr>
<tr><td>99</td><td>inconnu</td></tr>
</table>

<table>
<tr><td>2.2.6.2.3</td><td colspan="3">Désignation précise de la forme d’assurance (facultatif)</td></tr>
<tr><td>Tag: 13</td><td>Longueur: 0–40</td><td>Valeur: KVGModelText</td><td>Type: AN</td></tr>
<tr><td colspan="4">Texte libre: désignation précise de la forme d’assurance</td></tr>
</table>

<table>
<tr><td>2.2.6.2.4</td><td colspan="3">Canton de résidence pour la couverture AOS (facultatif)</td></tr>
<tr><td>Tag: 14</td><td>Longueur: x</td><td>Valeur: KVGCanton</td><td>Type: class</td></tr>
</table>

<table>
<tr><td>Codes à utiliser:</td></tr>
</table>

<table>
<tr><th>ID</th><th>Canton de résidence pour la couverture AOS</th></tr>
<tr><td>AG</td><td>Argovie</td></tr>
<tr><td>AI</td><td>Appenzell Rhodes-Intérieures</td></tr>
<tr><td>AR</td><td>Appenzell Rhodes-Extérieures</td></tr>
<tr><td>BE</td><td>Berne</td></tr>
<tr><td>BL</td><td>Bâle-Campagne</td></tr>
<tr><td>BS</td><td>Bâle-Villet</td></tr>
<tr><td>FR</td><td>Fribourg</td></tr>
<tr><td>GE</td><td>Genève</td></tr>
<tr><td>GL</td><td>Glaris</td></tr>
<tr><td>GR</td><td>Grisons</td></tr>
<tr><td>JU</td><td>Jura</td></tr>
<tr><td>LU</td><td>Lucerne</td></tr>
<tr><td>NE</td><td>Neuchâtel</td></tr>
<tr><td>NW</td><td>Nidwald</td></tr>
<tr><td>OW</td><td>Obwald</td></tr>
<tr><td>SG</td><td>St-Gall</td></tr>
<tr><td>SH</td><td>Schaffhouse</td></tr>
<tr><td>SO</td><td>Soleure</td></tr>
<tr><td>SZ</td><td>Schwyz</td></tr>
<tr><td>TG</td><td>Thurgovie</td></tr>
<tr><td>TI</td><td>Tessin</td></tr>
<tr><td>UR</td><td>Uri</td></tr>
<tr><td>VD</td><td>Vaud</td></tr>
<tr><td>VS</td><td>Valais</td></tr>
<tr><td>ZG</td><td>Zoug</td></tr>
<tr><td>ZH</td><td>Zurich</td></tr>
<tr><td>ZZ</td><td>Pays étranger</td></tr>
<tr><td>AA</td><td>inconnu</td></tr>
</table>

<table>
<tr><td>2.2.6.2.5</td><td colspan="3">Couverture accident AOS (facultatif)</td></tr>
<tr><td>Tag: 15</td><td>Longueur: 2</td><td>Valeur: KVG accidentCoverage</td><td>Type: AN</td></tr>
</table>

<table>
<tr><td>Couverture accident AOS Codes à utiliser:</td></tr>
</table>

<table>
<tr><th>ID</th><th>Couverture accident AOS</th></tr>
<tr><td>01</td><td>couverture accident</td></tr>
<tr><td>02</td><td>pas de couverture accident</td></tr>
<tr><td>99</td><td>inconnu</td></tr>
</table>

<table>
<tr><td>2.2.6.3</td><td colspan="3">Données concernant l’assureur AOS (facultatif)</td></tr>
<tr><td>Tag: 16</td><td>Longueur: x</td><td>Valeur: insurerInformation</td><td>Type: class</td></tr>
<tr><td colspan="4">Les données concernant l’assureur AOS comprennent les éléments suivants:</td></tr>
</table>

<table>
<tr><td>2.2.6.3.1</td><td colspan="3">Contact téléphonique en allemand (facultatif)</td></tr>
<tr><td>Tag: 17</td><td>Longueur: 0–20</td><td>Valeur: contactNumber German</td><td>Type: AN</td></tr>
<tr><td colspan="4">Texte libre: contact téléphonique en allemand</td></tr>
</table>

<table>
<tr><td>2.2.6.3.2</td><td colspan="3">Contact téléphonique en français (facultatif)</td></tr>
<tr><td>Tag: 18</td><td>Longueur: 0–20</td><td>Valeur: contactNumber French</td><td>Type: AN</td></tr>
<tr><td colspan="4">Texte libre: contact téléphonique en français</td></tr>
</table>

<table>
<tr><td>2.2.6.3.3</td><td colspan="3">Contact téléphonique en italien (facultatif)</td></tr>
<tr><td>Tag: 19</td><td>Longueur: 0–20</td><td>Valeur: contactNumber Italian</td><td>Type: AN</td></tr>
<tr><td colspan="4">Texte libre: contact téléphonique en italien</td></tr>
</table>

<table>
<tr><td>*2.2.6.3.4*</td><td colspan="3">*Adresse électronique* *(facultatif)*</td></tr>
<tr><td>Tag: 20</td><td>Longueur: 0–100</td><td>Valeur: contactEmail Address</td><td>Type: AN</td></tr>
<tr><td colspan="4">Texte libre: adresse électronique</td></tr>
</table>

<table>
<tr><td>2.2.6.3.5</td><td colspan="3">Numéro EAN (European Article Numbering) (facultatif)</td></tr>
<tr><td>Tag: 21</td><td>Longueur: 0–13</td><td>Valeur: contactEan Number</td><td>Type: AN</td></tr>
<tr><td colspan="4">Texte libre: numéro EAN</td></tr>
</table>

<table>
<tr><td>2.2.6.3.6</td><td colspan="3">Adresse de facturation de l’assureur (facultatif)</td></tr>
<tr><td>Tag: 22</td><td>Longueur: x</td><td>Valeur: address</td><td>Type: class</td></tr>
<tr><td colspan="4">Les données concernant l’adresse de facturation de l’assureur doivent être spécifiées conformément à la norme eCH-0010:2006.</td></tr>
</table>

<table>
<tr><td>2.2.6.4</td><td colspan="4">Données concernant les assurances complémentaires selon la loi sur le contrat d’assurance (LCA; RS *221.229.1*) (facultatif)</td></tr>
<tr><td colspan="5">Il est possible d’enregistrer des données concernant jusqu’à cinq assureurs complémentaires.</td></tr>
<tr><td colspan="2">Tag: 34</td><td>Longueur: x</td><td>Valeur: VVG Information</td><td>Type: class</td></tr>
<tr><td colspan="5">Les données concernant les assurances complémentaires selon la LCA comprennent les éléments suivants:</td></tr>
<tr><td>2.2.6.4.1</td><td colspan="4">Nom de l’assureur LCA (obligatoire)</td></tr>
<tr><td>Tag: 35</td><td colspan="2">Longueur: 0–100</td><td>Valeur: nameOfVVG Insurer</td><td>Type: AN</td></tr>
<tr><td colspan="5">Texte libre: nom de l’assureur LCA</td></tr>
</table>

2.2.6.4.2 Données concernant l’assureur LCA (facultatif) Tag: 36 Longueur: x Valeur: VVGInsurer Information Type: class Les données concernant l’assureur LCA comprennent les éléments suivants:

- – contact téléphonique en allemand, cf. ch. 2.2.6.3.1
- – contact téléphonique en français, cf. ch. 2.2.6.3.2
- – contact téléphonique en italien, cf. ch. 2.2.6.3.3
- – adresse électronique, cf. ch. 2.2.6.3.4
- – numéro EAN, cf. ch. 2.2.6.3.5
- – adresse de facturation, cf. ch. 2.2.6.3.6

<table>
<tr><td>2.2.6.4.3</td><td colspan="3">Médicaments hors-liste (facultatif)</td></tr>
<tr><td>Tag: 37</td><td>Longueur: 2</td><td>Valeur: medicationHL</td><td>Type: AN</td></tr>
</table>

<table>
<tr><td>Codes à utiliser:</td></tr>
</table>

<table>
<tr><th>ID</th><th>Médicaments hors-liste</th></tr>
<tr><td>01</td><td>couverture des médicaments hors-liste</td></tr>
<tr><td>02</td><td>couverture limitée des médicaments hors-liste</td></tr>
<tr><td>00</td><td>pas de couverture des médicaments hors-liste</td></tr>
<tr><td>99</td><td>inconnu</td></tr>
</table>

<table>
<tr><td>2.2.6.4.4</td><td colspan="3">Médicaments hors-liste en cas d’accident (facultatif)</td></tr>
<tr><td>Tag: 38</td><td>Longueur: 2</td><td>Valeur: medication AccidentCoverageHL</td><td>Type: AN</td></tr>
</table>

<table>
<tr><td>Codes à utiliser:</td></tr>
</table>

<table>
<tr><th>ID</th><th>Médicaments hors-liste en cas d’accident</th></tr>
<tr><td>01</td><td>couverture des médicaments hors-liste en cas d’accident</td></tr>
<tr><td>00</td><td>pas de couverture des médicaments hors-liste en cas d’accident</td></tr>
<tr><td>99</td><td>inconnu</td></tr>
</table>

<table>
<tr><td>2.2.6.4.5</td><td colspan="3">Médicaments de médecine complémentaire (facultatif)</td></tr>
<tr><td>Tag: 39</td><td>Longueur: 2</td><td>Valeur: medication KM</td><td>Type: AN</td></tr>
</table>

<table>
<tr><td>Codes à utiliser:</td></tr>
</table>

<table>
<tr><th>ID</th><th>Médicaments de médecine complémentaire</th></tr>
<tr><td>01</td><td>couverture des médicaments de médecine complémentaire</td></tr>
<tr><td>02</td><td>couverture limitée des médicaments de médecine complémentaire</td></tr>
<tr><td>00</td><td>pas de couverture des médicaments de médecine complémentaire</td></tr>
<tr><td>99</td><td>inconnu</td></tr>
</table>

<table>
<tr><td>2.2.6.4.6</td><td colspan="3">Médicaments de médecine complémentaire en cas d’accident (facultatif)</td></tr>
<tr><td>Tag: 40</td><td>Longueur: 2</td><td>Valeur: medication AccidentCoverageKM</td><td>Type: AN</td></tr>
</table>

<table>
<tr><td>Codes à utiliser:</td></tr>
</table>

<table>
<tr><th>ID</th><th>Médicaments de médecine complémentaire en cas d’accident</th></tr>
<tr><td>01</td><td>couverture des médicaments de médecine complémentaire en cas d’accident</td></tr>
<tr><td>00</td><td>pas de couverture des médicaments de médecine complémentaire en cas d’accident</td></tr>
<tr><td>99</td><td>inconnu</td></tr>
</table>

<table>
<tr><td>2.2.6.4.7</td><td colspan="3">Division hospitalière (facultatif)</td></tr>
<tr><td>Tag: 41</td><td>Longueur: 2</td><td>Valeur: medicalService CoverageVVG</td><td>Type: AN</td></tr>
</table>

<table>
<tr><td>Codes à utiliser:</td></tr>
</table>

<table>
<tr><th>ID</th><th>Division hospitalière</th></tr>
<tr><td>01</td><td>division commune dans toute la Suisse</td></tr>
<tr><td>02</td><td>division semi-privée</td></tr>
<tr><td>03</td><td>division privée</td></tr>
<tr><td>00</td><td>pas de division (semi-)privée</td></tr>
<tr><td>99</td><td>inconnu</td></tr>
</table>

<table>
<tr><td>2.2.6.4.8</td><td colspan="3">Couverture hospitalière (facultatif)</td></tr>
<tr><td>Tag: 42</td><td>Longueur: 2</td><td>Valeur: hospitalModelVVG</td><td>Type: AN</td></tr>
</table>

<table>
<tr><td>Codes à utiliser:</td></tr>
</table>

<table>
<tr><th>ID</th><th>Couverture hospitalière</th></tr>
<tr><td>01</td><td>couverture standard en division privée ousemi-privée</td></tr>
<tr><td>02</td><td>assurance pour supplément hôtelier</td></tr>
<tr><td>03</td><td>assurance pour le libre choix du médecin</td></tr>
<tr><td>99</td><td>inconnu</td></tr>
</table>

<table>
<tr><td>2.2.6.4.9</td><td colspan="3">Frais d’hôpital en cas d’accident (facultatif)</td></tr>
<tr><td>Tag: 43</td><td>Longueur: 2</td><td>Valeur: accident CoverageVVG</td><td>Type: AN</td></tr>
</table>

<table>
<tr><td>Codes à utiliser:</td></tr>
</table>

<table>
<tr><th>ID</th><th>Frais d’hôpital en cas d’accident</th></tr>
<tr><td>01</td><td>couverture des frais d’hôpital en cas d’accident</td></tr>
<tr><td>00</td><td>pas de couverture des frais d’hôpital en cas d’accident</td></tr>
<tr><td>99</td><td>inconnu</td></tr>
</table>

Annexe 2

(art. 2)

## Spécification des données au sens de l’art. 6 OCA

### 1 Généralités

### 1.1 Références

<table>
<tr><td>eCH-0010:2006</td><td>Adresses postales pour les personnes physiques, les entreprises, les organisations et les autorités</td></tr>
<tr><td>eCH-0064:2008</td><td>Spécifications du système Carte d’assuré</td></tr>
</table>

### 1.2 Source

<table>
<tr><td>Normes eCH</td><td>Association eCH, Mainaustrasse 30, 8008 Zurich, http://www.ech.ch/</td></tr>
</table>

### 1.3 Abréviations et définitions

<table>
<tr><td>AN</td><td>Alphanumérique</td></tr>
<tr><td>Char</td><td>Caractère</td></tr>
<tr><td>Class</td><td>Type de données complexes constitué de plusieurs éléments</td></tr>
<tr><td>Tag</td><td>Marqueur identifiant un élément</td></tr>
</table>

### 2 Spécification des données au sens de l’art. 6 OCA

Pour les données au sens de l’art. 6 OCA, il convient d’utiliser le même format de données et le même jeu de caractères que pour les données d’identification mentionnées à l’annexe 1, ch. 2.1 et les données administratives mentionnées à l’annexe 1, ch. 2.2.

Les éléments obligatoires concernant des groupes de données facultatives ne doivent être pris en considération que si les données facultatives sont introduites.

Pour l’utilisation des données, l’OFSP met à disposition des schémas XML[^annex2-lvlu1-lvl2-1]. La désignation des tags et des schémas XML est indiquée.

### 2.1 Maladies et séquelles d’accidents (facultatif multiple)

[^annex2-lvlu1-lvl2-1]: Les schémas XML peuvent être commandés auprès de l’Office fédéral de la santé publique, 3003 Berne, ou consultés à l’adresse www.ehealth.admin.ch.

Il est possible d’enregistrer [0–50] données; cf. enregistrements [1–50] du fichier EF.KHUF défini dans la norme eCH-0064 du 4 février 2008 «Spécifications du système Carte d’assuré» (eCH-0064:2008).

<table>
<tr><td>Tag: 200</td><td>Longueur: x</td><td>Valeur: DiseasesAnd PostTraumaticSequels</td><td>Type: Class</td></tr>
</table>

Les données relatives aux maladies et séquelles d’accidents se composent des éléments suivants:

<table>
<tr><td>2.1.1</td><td colspan="3">Désignation de la maladie ou de la séquelle d’accident (facultatif)</td></tr>
<tr><td>Tag: 44</td><td>Longueur: 2</td><td>Valeur: diseaseName</td><td>Type: AN</td></tr>
</table>

Codes à utiliser:

<table>
<tr><th>ID</th><th>Désignation de la maladie ou de la séquelle d’accident</th></tr>
<tr><td>01</td><td>Asthme bronchique</td></tr>
<tr><td>02</td><td>BPCO (broncho-pneumopathie chronique obstructive)</td></tr>
<tr><td>03</td><td>Maladie coronarienne</td></tr>
<tr><td>04</td><td>Insuffisance cardiaque</td></tr>
<tr><td>05</td><td>Troubles du rythme cardiaque</td></tr>
<tr><td>06</td><td>Maladie artérielle périphérique</td></tr>
<tr><td>07</td><td>Anévrisme de l’aorte abdominale</td></tr>
<tr><td>08</td><td>Crises convulsives</td></tr>
<tr><td>09</td><td>Trouble de coagulation congénital</td></tr>
<tr><td>10</td><td>Trouble de coagulation acquis</td></tr>
<tr><td>11</td><td>Trouble de coagulation acquis suite à la prise de médicaments</td></tr>
<tr><td>12</td><td>Diabète sucré</td></tr>
<tr><td>13</td><td>Maladie d’Addison</td></tr>
<tr><td>14</td><td>Glaucome</td></tr>
<tr><td>15</td><td>Insuffisance rénale/dialyse</td></tr>
<tr><td>16</td><td>Acétylation lente</td></tr>
<tr><td>17</td><td>Maladie chronique du foie</td></tr>
<tr><td>18</td><td>Maladies infectieuses de premier plan</td></tr>
<tr><td>19</td><td>Maladies infectieuses</td></tr>
<tr><td>20</td><td>Organe manquant</td></tr>
<tr><td>21</td><td>Prothèse vasculaire</td></tr>
<tr><td>22</td><td>Valvules cardiaques artificielles</td></tr>
<tr><td>23</td><td>Dispositifs intravasculaires (stents, clips)</td></tr>
<tr><td>24</td><td>Prothèse articulaire</td></tr>
<tr><td>25</td><td>Stimulateur cardiaque/défibrillateur</td></tr>
<tr><td>26</td><td>Matériel d’ostéosynthèse</td></tr>
<tr><td>27</td><td>Œil de verre</td></tr>
<tr><td>28</td><td>Lentilles de contact</td></tr>
<tr><td>29</td><td>Prothèses amovibles</td></tr>
<tr><td>30</td><td>Autres maladies ou séquelles d’accidents</td></tr>
</table>

<table>
<tr><td>2.1.2</td><td colspan="3">Commentaire concernant la maladie ou la séquelle d’accident (facultatif)</td></tr>
<tr><td>Tag: 70</td><td>Longueur: 1–100</td><td>Valeur: DiseaseFreetext</td><td>Type: AN</td></tr>
<tr><td colspan="4">Texte libre: commentaire concernant la maladie ou la séquelle d’accident</td></tr>
</table>

<table>
<tr><td>2.1.3</td><td colspan="3">Numéro EAN (European Article Numbering) de l’auteur de l’inscription (obligatoire)</td></tr>
<tr><td>Tag: 80</td><td>Longueur: 13</td><td>Valeur: healthCare ProviderEanNumber</td><td>Type: AN</td></tr>
<tr><td colspan="4">Numéro identifiant à 13 chiffres</td></tr>
</table>

<table>
<tr><td>2.1.4</td><td colspan="3">Date de l’enregistrement (obligatoire)</td></tr>
<tr><td>Tag: 90</td><td>Longueur: 10</td><td>Valeur: dateOfRecord</td><td>Type: AN</td></tr>
<tr><td colspan="4">Date au format (AAAA-MM-JJ)</td></tr>
</table>

### 2.2 Données concernant la transplantation

<table>
<tr><td>2.2.1</td><td>Inscription sur la liste d’attente pour une transplantation (facultatif, multiple)</td></tr>
</table>

Il est possible d’enregistre [0–10] données; cf. enregistrements [1–10] du fichier EF.TPLD défini dans la norme eCH-0064:2008.

<table>
<tr><td>Tag: 300</td><td>Longueur: x</td><td>Valeur: transplantation Registration</td><td>Type: class</td></tr>
</table>

Les données relatives à l’inscription sur une liste d’attente pour une transplantation se composent des éléments suivants:

<table>
<tr><td>2.2.1.1</td><td colspan="3">Commentaire concernant l’inscription sur la liste d’attente (facultatif)</td></tr>
<tr><td>Tag: 70</td><td>Longueur: 0–100</td><td>Valeur: transplantation RegistrationFreetext</td><td>Type: AN</td></tr>
<tr><td colspan="4">Texte libre: commentaire concernant l’inscription sur la liste d’attente pour une transplantation</td></tr>
</table>

<table>
<tr><td>2.2.1.2</td><td colspan="3">Numéro EAN de l’auteur de l’inscription (obligatoire)</td></tr>
<tr><td>Tag: 80</td><td>Longueur: 13</td><td>Valeur: healthCare ProviderEanNumber</td><td>Type: AN</td></tr>
<tr><td colspan="4">Numéro identifiant à 13 chiffres</td></tr>
</table>

<table>
<tr><td>2.2.1.3</td><td colspan="3">Date de l’enregistrement (obligatoire)</td></tr>
<tr><td>Tag: 90</td><td>Longueur: 10</td><td>Valeur: dateOfRecord</td><td>Type: AN</td></tr>
<tr><td colspan="4">Date au format (AAAA-MM-JJ)</td></tr>
</table>

<table>
<tr><td>2.2.2</td><td>Transplantations déjà subies (facultatif, multiple)</td></tr>
</table>

Il est possible d’enregistrer [0–10] données; cf. enregistrements [11–20] du fichier EF.TPLD défini dans la norme eCH-0064:2008.

<table>
<tr><td>Tag: 400</td><td>Longueur: x</td><td>Valeur: transplantations</td><td>Type: class</td></tr>
</table>

Les données relatives aux transplantations déjà subies se composent des éléments suivants:

<table>
<tr><td>2.2.2.1</td><td colspan="3">Nom de l’organe ou des tissus et des cellules transplantés (facultatif, multiple)</td></tr>
<tr><td>Tag: 46</td><td>Longueur: 0–30</td><td>Valeur: transplant</td><td>Type: AN</td></tr>
<tr><td colspan="4">Texte libre: nom de l’organe ou des tissus et des cellules transplantés</td></tr>
</table>

<table>
<tr><td>2.2.2.2</td><td colspan="3">N<sup>o</sup> suisse de transplantation (facultatif)</td></tr>
<tr><td>Tag: 47</td><td>Longueur: 0–12</td><td>Valeur: swiss TransplantNumber</td><td>Type: AN</td></tr>
<tr><td colspan="4">Texte libre: n<sup>o</sup> suisse de transplantation (p. ex. RS-2001-4645)</td></tr>
</table>

<table>
<tr><td>2.2.2.3</td><td colspan="3">Date de la transplantation (facultatif)</td></tr>
<tr><td>Tag: 48</td><td>Longueur: 10</td><td>Valeur: dateOf Transplantation</td><td>Type: AN</td></tr>
<tr><td colspan="4">Date au format (AAAA-MM-JJ)</td></tr>
</table>

<table>
<tr><td>2.2.2.4</td><td colspan="3">Commentaire concernant la transplantation (facultatif)</td></tr>
<tr><td>Tag: 70</td><td>Longueur: 0–100</td><td>Valeur: transplantation Freetext</td><td>Type: AN</td></tr>
<tr><td colspan="4">Texte libre: commentaire concernant la transplantation</td></tr>
</table>

<table>
<tr><td>2.2.2.5</td><td colspan="3">Numéro EAN de l’auteur de l’inscription (obligatoire)</td></tr>
<tr><td>Tag: 80</td><td>Longueur: 13</td><td>Valeur: healthCare ProviderEanNumber</td><td>Type: AN</td></tr>
<tr><td colspan="4">Numéro identifiant à 13 chiffres</td></tr>
</table>

<table>
<tr><td>2.2.2.6</td><td colspan="3">Date de l’enregistrement (obligatoire)</td></tr>
<tr><td>Tag: 90</td><td>Longueur: 10</td><td>Valeur: dateOfRecord</td><td>Type: AN</td></tr>
<tr><td colspan="4">Date au format (AAAA-MM-JJ)</td></tr>
</table>

### 2.3 Allergies

Les données concernant des allergies ou hypersensibilités aux médicaments, à certaines substances ou à certains allergènes (poisons d’insectes, aliments) se composent des éléments suivants:

<table>
<tr><td>2.3.1</td><td>Réactions de type instantané (facultatif, multiple)</td></tr>
</table>

Il est possible d’enregistrer [0–25] données; cf. enregistrements [1–25] du fichier EF.ALLG défini dans la norme eCH-0064:2008.

<table>
<tr><td>Tag: 500</td><td>Longueur: x</td><td>Valeur: immediate TypeReactions</td><td>Type: class</td></tr>
</table>

<table>
<tr><td>2.3.1.1</td><td colspan="3">Désignation de l’agent provoquant l’allergie (facultatif)</td></tr>
<tr><td>Tag: 91</td><td>Longueur: x</td><td>Valeur: allergy Stimulator</td><td>Type: class</td></tr>
</table>

<table>
<tr><td>2.3.1.1.1</td><td colspan="3">Désignation générale (facultatif)</td></tr>
<tr><td>Tag: 92</td><td>Longueur: 0–20</td><td>Valeur: generalName OfAllergyStimulator</td><td>Type: AN</td></tr>
<tr><td colspan="4">Texte libre: désignation générale de l’agent provoquant l’allergie (par ex. nom international d’un médicament, allergène)</td></tr>
</table>

<table>
<tr><td>2.3.1.1.2</td><td colspan="3">Désignation spéciale (facultatif)</td></tr>
<tr><td>Tag: 93</td><td>Longueur: 0–20</td><td>Valeur: specialName ofAllergyStimulator</td><td>Type: AN</td></tr>
<tr><td colspan="4">Texte libre: désignation spéciale de l’agent provoquant l’allergie (par ex. marque d’un médicament)</td></tr>
</table>

<table>
<tr><td>2.3.1.2</td><td colspan="3">Réaction clinique (facultatif)</td></tr>
<tr><td>Tag: 94</td><td>Longueur: x</td><td>Valeur: immediate ClinicalReaction</td><td>Type: class</td></tr>
</table>

<table>
<tr><td>2.3.1.2.1</td><td colspan="3">Genre de la réaction clinique (facultatif)</td></tr>
<tr><td>Tag: 95</td><td>Longueur: 1</td><td>Valeur: immediate ResponseTypeOf ClinicalReaction</td><td>Type: AN</td></tr>
</table>

Codes à utiliser:

<table>
<tr><th>ID</th><th>Genre de la réaction clinique pour les réactions de type instantané</th></tr>
<tr><td>1</td><td>Angio-oedème</td></tr>
<tr><td>2</td><td>Urticaire</td></tr>
<tr><td>3</td><td>Asthme, bronchospasme</td></tr>
<tr><td>4</td><td>Coliques, diarrhée</td></tr>
<tr><td>5</td><td>Choc anaphylactique</td></tr>
<tr><td>6</td><td>Autre réaction clinique</td></tr>
</table>

<table>
<tr><td>2.3.1.2.2</td><td colspan="3">Date de la réaction clinique (facultatif)</td></tr>
<tr><td>Tag: 96</td><td>Longueur: 10</td><td>Valeur: dateOfClinical Reaction</td><td>Type: AN</td></tr>
<tr><td colspan="4">Date au format (AAAA-MM-JJ)</td></tr>
</table>

<table>
<tr><td>2.3.1.2.3</td><td colspan="3">Remarque concernant la réaction clinique (facultatif)</td></tr>
<tr><td>Tag: 70</td><td>Longueur: 0–40</td><td>Valeur: clinical ReactionFreetext</td><td>Type: AN</td></tr>
<tr><td colspan="4">Texte libre: remarque concernant la réaction clinique</td></tr>
</table>

<table>
<tr><td>2.3.1.3</td><td colspan="3">Preuve de l’hypersensibilité (facultatif)</td></tr>
<tr><td>Tag: 97</td><td>Longueur: x</td><td>Valeur: allergyTest</td><td>Type: class</td></tr>
</table>

<table>
<tr><td>2.3.1.3.1</td><td colspan="3">Méthode de la preuve (facultatif)</td></tr>
<tr><td>Tag: 98</td><td>Longueur: 1</td><td>Valeur: typeOfAllergyTest</td><td>Type: AN</td></tr>
</table>

Codes à utiliser:

<table>
<tr><th>ID</th><th>Méthode de la preuve</th></tr>
<tr><td>1</td><td>Anamnèse</td></tr>
<tr><td>2</td><td>Manifestation clinique</td></tr>
<tr><td>3</td><td>Test cutané (Prick, intradermal)</td></tr>
<tr><td>4</td><td>Test épicutané (patch test)</td></tr>
<tr><td>5</td><td>Anticorps spécifiques</td></tr>
<tr><td>6</td><td>Test de provocation</td></tr>
<tr><td>7</td><td>Test cellulaire</td></tr>
<tr><td>8</td><td>Autre preuve de l’hypersensibilité</td></tr>
</table>

<table>
<tr><td>2.3.1.3.2</td><td colspan="3">Date de la preuve (facultatif)</td></tr>
<tr><td>Tag: 99</td><td>Longueur: 10</td><td>Valeur: dateOfAllergyTest</td><td>Type: AN</td></tr>
<tr><td colspan="4">Date au format (AAAA-MM-JJ)</td></tr>
</table>

<table>
<tr><td>2.3.1.3.3</td><td colspan="3">Remarque concernant la preuve (facultatif)</td></tr>
<tr><td>Tag: 70</td><td>Longueur: 0–40</td><td>Valeur: allergyTestFreetex*t*</td><td>Type: AN</td></tr>
<tr><td colspan="4">Texte libre: remarque concernant la preuve (par ex. résultat, dose, allergène)</td></tr>
</table>

<table>
<tr><td>2.3.1.4</td><td colspan="3">Médicament de remplacement (facultatif)</td></tr>
<tr><td>Tag: 100</td><td>Longueur: x</td><td>Valeur: substitute Medicine</td><td>Type: class</td></tr>
</table>

<table>
<tr><td>2.3.1.4.1</td><td colspan="3">Désignation du médicament de remplacement (facultatif)</td></tr>
<tr><td>Tag: 101</td><td>Longueur: 0–20</td><td>Valeur: nameOf SubstituteMedicine</td><td>Type: AN</td></tr>
<tr><td colspan="4">Texte libre: désignation du médicament de remplacement (par ex. nom de la marque)</td></tr>
</table>

<table>
<tr><td>2.3.1.4.2</td><td colspan="3">Nom générique du médicament de remplacement (facultatif)</td></tr>
<tr><td>Tag: 102</td><td>Longueur: 0–20</td><td>Valeur: genericName OfSubstituteMedicine</td><td>Type: AN</td></tr>
<tr><td colspan="4">Texte libre: nom générique du médicament de remplacement (par ex. agent actif)</td></tr>
</table>

<table>
<tr><td>2.3.1.4.3</td><td colspan="3">Sécurité du médicament de remplacement (facultatif)</td></tr>
<tr><td>Tag: 103</td><td>Longueur: 1</td><td>Valeur: reliabilityOf SubstituteMedicine</td><td>Type: AN</td></tr>
</table>

Codes à utiliser:

<table>
<tr><th>ID</th><th>Sécurité du médicament de remplacement</th></tr>
<tr><td>1</td><td>provoqué</td></tr>
<tr><td>2</td><td>testé</td></tr>
<tr><td>3</td><td>conseillé</td></tr>
</table>

<table>
<tr><td>2.3.1.4.4</td><td colspan="3">Date-test du médicament de remplacement (facultatif)</td></tr>
<tr><td>Tag: 104</td><td>Longueur: 10</td><td>Valeur: dateOfTest SubstituteMedicine</td><td>Type: AN</td></tr>
<tr><td colspan="4">Date au format (AAAA-MM-JJ)</td></tr>
</table>

<table>
<tr><td>2.3.1.4.5</td><td colspan="3">Remarque concernant le médicament de remplacement (facultatif)</td></tr>
<tr><td>Tag: 70</td><td>Longueur: 0–40</td><td>Valeur: substitute MedicineFreetext</td><td>Type: AN</td></tr>
<tr><td colspan="4">Texte libre: remarque concernant le médicament de remplacement</td></tr>
</table>

<table>
<tr><td>2.3.1.5</td><td colspan="3">Médicament d’urgence (facultatif)</td></tr>
<tr><td>Tag: 105</td><td>Longueur: x</td><td>Valeur: emergency Medicine</td><td>Type: class</td></tr>
</table>

<table>
<tr><td>2.3.1.5.1</td><td colspan="3">Désignation du médicament d’urgence (facultatif)</td></tr>
<tr><td>Tag: 106</td><td>Longueur: 1</td><td>Valeur: nameOf EmergencyMedicine</td><td>Type: AN</td></tr>
</table>

Codes à utiliser:

<table>
<tr><th>ID</th><th>Médicament d’urgence</th></tr>
<tr><td>1</td><td>Anti-histaminique et tablettes corticostéroïdes</td></tr>
<tr><td>2</td><td>Adrénaline à injecter</td></tr>
<tr><td>3</td><td>Médicament à inhaler</td></tr>
<tr><td>4</td><td>Autres médicaments</td></tr>
</table>

<table>
<tr><td>2.3.1.5.2</td><td colspan="3">Remarque concernant le médicament d’urgence (facultatif)</td></tr>
<tr><td>Tag: 107</td><td>Longueur: 0–40</td><td>Valeur: emergency MedicineFreetext</td><td>Type: AN</td></tr>
<tr><td colspan="4">Texte libre: remarque concernant le médicament d’urgence dont le patient est muni</td></tr>
</table>

<table>
<tr><td>2.3.1.6</td><td colspan="3">Numéro EAN de l’auteur de l’inscription (obligatoire)</td></tr>
<tr><td>Tag: 80</td><td>Longueur: 13</td><td>Valeur: healthCare ProviderEanNumber</td><td>Type: AN</td></tr>
<tr><td colspan="4">Numéro d’identification à 13 chiffres</td></tr>
</table>

<table>
<tr><td>2.3.1.7</td><td colspan="3">Date de l’enregistrement (obligatoire)</td></tr>
<tr><td>Tag: 90</td><td>Longueur: 10</td><td>Valeur: dateOf Record</td><td>Type: AN</td></tr>
<tr><td colspan="4">Date au format (AAAA-MM-JJ)</td></tr>
</table>

<table>
<tr><td>2.3.2</td><td>Réactions de type tardif (facultatif, multiple)</td></tr>
</table>

Il est possible d’enregistrer [0–25] données; cf. enregistrements [26–50] du fichier EF.ALLG défini dans la norme eCH-0064:2008.

<table>
<tr><td>Tag: 600</td><td>Longueur: x</td><td>Valeur: delayedType Reactions</td><td>Type: class</td></tr>
</table>

- – Désignation de l’agent provoquant l’allergie, cf. ch. 2.3.1.1
  - – Désignation générale, cf. ch. 2.3.1.1.1
  - – Désignation spéciale, cf. ch. 2.3.1.1.2

- – Réaction clinique, cf. ch. 2.3.2.1
  - – Genre de la réaction clinique, cf. ch. 2.3.2.1.1
  - – Date de la réaction clinique, cf. ch. 2.3.1.2.2
  - – Remarque concernant la réaction clinique, cf. ch. 2.3.1.2.3

- – Preuve de l’hypersensibilité, cf. ch. 2.3.1.3
  - – Méthode de la preuve, cf. ch. 2.3.1.3.1
  - – Date de la preuve, cf. ch. 2.3.1.3.2
  - – Remarque concernant la preuve, cf. ch. 2.3.1.3.3

- – Médicament de remplacement, cf. ch. 2.3.1.4
  - – Désignation du médicament de remplacement, cf. ch. 2.3.1.4.1
  - – Nom générique du médicament de remplacement, cf. ch. 2.3.1.4.2
  - – Sécurité du médicament de remplacement, cf. ch. 2.3.1.4.3
  - – Date-test du médicament de remplacement, cf. ch. 2.3.1.4.4
  - – Remarque concernant le médicament de remplacement, cf. ch. 2.3.1.4.5

- – Médicament d’urgence, cf. ch. 2.3.1.5
  - – Désignation du médicament d’urgence, cf. ch. 2.3.1.5.1
  - – Remarque concernant le médicament d’urgence, cf. ch. 2.3.1.5.2

- – Numéro EAN de l’auteur de l’inscription, cf. ch. 2.3.1.6
- – Date de l’enregistrement, cf. ch. 2.3.1.7

<table>
<tr><td>2.3.2.1</td><td colspan="3">Réaction clinique (facultatif)</td></tr>
<tr><td>Tag: 111</td><td>Longueur: x</td><td>Valeur: delayed ClinicalReaction</td><td>Type: class</td></tr>
</table>

<table>
<tr><td>2.3.2.1.1</td><td colspan="3">Genre de la réaction clinique (facultatif)</td></tr>
<tr><td>Tag: 108</td><td>Longueur: 1</td><td>Valeur: delayed ResponseTypeOf ClinicalReaction</td><td>Type: AN</td></tr>
</table>

Codes à utiliser:

<table>
<tr><th>ID</th><th>Genre de la réaction clinique pour les réactions de type tardif</th></tr>
<tr><td>1</td><td>Eczéma</td></tr>
<tr><td>2</td><td>Réaction locale</td></tr>
<tr><td>3</td><td>Formation d’ampoules, vascularites</td></tr>
<tr><td>4</td><td>Autre réaction clinique</td></tr>
</table>

### 2.4 Médication (facultatif, multiple)

Il est possible d’enregistrer [0–50] données; cf. enregistrements [1–50] du fichier EF.MEDI défini dans la norme eCH-0064:2008.

<table>
<tr><td>Tag: 900</td><td>Longueur: x</td><td>Valeur: medication</td><td>Type: class</td></tr>
</table>

Les données relatives à la médication contiennent en premier lieu des indications relatives à la médication de longue durée et se composent des éléments suivants:

<table>
<tr><td>2.4.1</td><td colspan="3">Désignation de la médication (facultatif)</td></tr>
<tr><td>Tag: 55</td><td>Longueur: 2</td><td>Valeur: medication Name</td><td>Type: AN</td></tr>
</table>

Codes à utiliser:

<table>
<tr><th>ID</th><th>Médication</th></tr>
<tr><td>01</td><td>Antiépileptiques</td></tr>
<tr><td>02</td><td>Antidépresseurs</td></tr>
<tr><td>03</td><td>Neuroleptiques</td></tr>
<tr><td>04</td><td>Médicaments contre la démence</td></tr>
<tr><td>05</td><td>Opiacés</td></tr>
<tr><td>06</td><td>AINS</td></tr>
<tr><td>07</td><td>Tranquilisants</td></tr>
<tr><td>08</td><td>Bêtabloquants</td></tr>
<tr><td>09</td><td>Inhibiteurs ECA</td></tr>
<tr><td>10</td><td>Diurétiques</td></tr>
<tr><td>11</td><td>Inhibiteurs calciques</td></tr>
<tr><td>12</td><td>Dérivés nitrés</td></tr>
<tr><td>13</td><td>Antiarythmiques</td></tr>
<tr><td>14</td><td>Digitaliques</td></tr>
<tr><td>15</td><td>Antagonistes de l’aldostérone</td></tr>
<tr><td>16</td><td>Bêtamimétiques</td></tr>
<tr><td>17</td><td>Immunosuppresseurs</td></tr>
<tr><td>18</td><td>Antithrombotiques</td></tr>
<tr><td>19</td><td>Anticoagulants, par ex. Marcoumar ou héparine</td></tr>
<tr><td>20</td><td>Antihistaminiques</td></tr>
<tr><td>21</td><td>Facteurs VIII/IX</td></tr>
<tr><td>22</td><td>Desmopressine, par ex. Minirin</td></tr>
<tr><td>23</td><td>Antidiabétiques, insuline</td></tr>
<tr><td>24</td><td>Cortisone</td></tr>
<tr><td>25</td><td>Autres médicaments</td></tr>
</table>

<table>
<tr><td>2.4.2</td><td colspan="3">Remarque concernant l’indication de la médication (facultatif)</td></tr>
<tr><td>Tag: 70</td><td>Longueur: 0–100</td><td>Valeur: indicationOf MedicationFreetext</td><td>Type: AN</td></tr>
<tr><td colspan="4">Texte libre: remarque concernant la médication</td></tr>
</table>

<table>
<tr><td>2.4.3</td><td colspan="3">Numéro EAN de la médication (facultatif)</td></tr>
<tr><td>Tag: 109</td><td>Longueur: 13</td><td>Valeur: medication EanNumber</td><td>Type: AN</td></tr>
<tr><td colspan="4">Numéro identifiant à 13 chiffres</td></tr>
</table>

<table>
<tr><td>2.4.4</td><td colspan="3">Numéro ATC (Anatomical Therapeutical Chemical)[^annex2-lvlu1-lvl2-lvl24-1] de la médication (facultatif)</td></tr>
<tr><td>Tag: 110</td><td>Longueur: 0–15</td><td>Valeur: medication AtcNumber</td><td>Type: AN</td></tr>
<tr><td colspan="4">Numéro identifiant</td></tr>
</table>

<table>
<tr><td>2.4.5</td><td colspan="3">Remarque concernant la médication (facultatif)</td></tr>
<tr><td>Tag: 70</td><td>Longueur: 0–100</td><td>Valeur: medication Freetext</td><td>Type: AN</td></tr>
<tr><td colspan="4">Texte libre: remarque concernant la médication</td></tr>
</table>

<table>
<tr><td>2.4.6</td><td colspan="3">Numéro EAN de l’auteur de l’inscription (obligatoire)</td></tr>
<tr><td>Tag: 80</td><td>Longueur: 13</td><td>Valeur: healthCare ProviderEanNumber</td><td>Type: AN</td></tr>
<tr><td colspan="4">Numéro identifiant à 13 chiffres</td></tr>
</table>

<table>
<tr><td>2.4.7</td><td colspan="3">Date de l’enregistrement (obligatoire)</td></tr>
<tr><td>Tag: 90</td><td>Longueur: 10</td><td>Valeur: dateOf Record</td><td>Type: AN</td></tr>
<tr><td colspan="4">Date au format (AAAA-MM-JJ)</td></tr>
</table>

[^annex2-lvlu1-lvl2-lvl24-1]: Anatomical Therapeutical Chemical (ATC) classification index. L’index peut être consulté à l’adresse http://www.whocc.no/atcddd ou commandé auprès de: World Health Organization (WHO), Collaborating Centre for Druc Statistics Methodology, Norwegian Institute of Public Health, Postboks 4404 Nydalen, 0403 Oslo, Norway.

### 2.5 Vaccins (facultatif, multiple)

Il est possible d’enregistrer [0–50] données; cf. enregistrements [1–50] du fichier EF.IMMD défini dans la norme eCH-0064:2008.

<table>
<tr><td>Tag: 1000</td><td>Longueur: x</td><td>Valeur: vaccinations</td><td>Type: class</td></tr>
</table>

Les données relatives aux vaccins se composent des éléments suivants:

<table>
<tr><td>2.5.1</td><td colspan="3">Désignation du vaccin (facultatif)</td></tr>
<tr><td>Tag: 56</td><td>Longueur: 2</td><td>Valeur: vaccination Taxonomy</td><td>Type: AN</td></tr>
</table>

Codes à utiliser:

<table>
<tr><th>ID</th><th>Vaccin</th></tr>
<tr><td>01</td><td>Diphtérie</td></tr>
<tr><td>02</td><td>Tétanos</td></tr>
<tr><td>03</td><td>Coqueluche</td></tr>
<tr><td>04</td><td>Poliomyélite – paralysie infantile</td></tr>
<tr><td>05</td><td>Haemophilus influenzae type b (Hib)</td></tr>
<tr><td>06</td><td>Hépatite B</td></tr>
<tr><td>07</td><td>Hépatite A</td></tr>
<tr><td>08</td><td>Rougeole</td></tr>
<tr><td>09</td><td>Oreillons</td></tr>
<tr><td>10</td><td>Rubéole</td></tr>
<tr><td>11</td><td>Papillomavirus humain (HPV)</td></tr>
<tr><td>12</td><td>Varicelle</td></tr>
<tr><td>13</td><td>Pneumocoques</td></tr>
<tr><td>14</td><td>Méningocoques</td></tr>
<tr><td>15</td><td>Encéphalite à tiques (FSME, TBE)</td></tr>
<tr><td>16</td><td>Tuberculose (BCG)</td></tr>
<tr><td>17</td><td>Grippe</td></tr>
<tr><td>18</td><td>Rage</td></tr>
<tr><td>19</td><td>Fièvre jaune</td></tr>
<tr><td>20</td><td>Encéphalite japonaise</td></tr>
<tr><td>21</td><td>Fièvre typhoïde</td></tr>
<tr><td>22</td><td>Choléra</td></tr>
<tr><td>23</td><td>Anthrax</td></tr>
<tr><td>24</td><td>Autres vaccins</td></tr>
</table>

<table>
<tr><td>2.5.2</td><td colspan="3">Remarque concernant le vaccin (facultatif)</td></tr>
<tr><td>Tag: 70</td><td>Longueur: 0–100</td><td>Valeur: vaccination Freetext</td><td>Type: AN</td></tr>
<tr><td colspan="4">Texte libre: remarque concernant le vaccin</td></tr>
</table>

<table>
<tr><td>2.5.3</td><td colspan="3">Nom commercial du vaccin (facultatif)</td></tr>
<tr><td>Tag: 57</td><td>Longueur: 0–50</td><td>Valeur: vaccineName</td><td>Type: AN</td></tr>
<tr><td colspan="4">Texte libre: nom commercial du vaccin</td></tr>
</table>

<table>
<tr><td>2.5.4</td><td colspan="3">Fabricant du vaccin (facultatif)</td></tr>
<tr><td>Tag: 58</td><td>Longueur: 0–50</td><td>Valeur: manufacturer OfVaccine</td><td>Type: AN</td></tr>
<tr><td colspan="4">Texte libre: fabricant du vaccin</td></tr>
</table>

<table>
<tr><td>2.5.5</td><td colspan="3">Numéro de lot du vaccin (facultatif)</td></tr>
<tr><td>Tag: 59</td><td>Longueur: 8</td><td>Valeur: vaccineLot Number</td><td>Type: AN</td></tr>
<tr><td colspan="4">Texte libre: numéro de lot du vaccin</td></tr>
</table>

<table>
<tr><td>2.5.6</td><td colspan="3">Date de la vaccination (facultatif)</td></tr>
<tr><td>Tag: 60</td><td>Longueur: 10</td><td>Valeur: vaccination Date</td><td>Type: AN</td></tr>
<tr><td colspan="4">Date au format (AAAA-MM-JJ)</td></tr>
</table>

<table>
<tr><td>2.5.7</td><td colspan="3">Numéro EAN de l’auteur de l’inscription (obligatoire)</td></tr>
<tr><td>Tag: 80</td><td>Longueur: 13</td><td>Valeur: healthCare ProviderEanNumber</td><td>Type: AN</td></tr>
<tr><td colspan="4">Numéro identifiant à 13 chiffres</td></tr>
</table>

<table>
<tr><td>2.5.8</td><td colspan="3">Date de l’enregistrement (obligatoire)</td></tr>
<tr><td>Tag: 90</td><td>Longueur: 10</td><td>Valeur: dateOf Record</td><td>Type: AN</td></tr>
<tr><td colspan="4">Date au format (AAAA-MM-JJ)</td></tr>
</table>

### 2.6 Données concernant le groupe sanguin et les transfusions

Il est possible d’enregistrer [0–50] données; cf. enregistrements [1] du fichier EF.BGTD défini dans la norme eCH-0064:2008.

<table>
<tr><td>Tag: 1100</td><td>Longueur: x</td><td>Valeur: bloodGroup AndTransfusion</td><td>Type: class</td></tr>
</table>

Les données relatives au groupe sanguin et aux transfusions se composent des éléments suivants:

<table>
<tr><td>2.6.1</td><td colspan="3">Données concernant le groupe sanguin (facultatif)</td></tr>
<tr><td>Tag: 61</td><td>Longueur: x</td><td>Valeur: bloodGroup</td><td>Type: class</td></tr>
</table>

<table>
<tr><td>2.6.1.1</td><td colspan="3">Désignation du groupe sanguin (facultatif)</td></tr>
<tr><td>Tag: 62</td><td>Longueur: 1</td><td>Valeur: bloodGroup Taxonomy</td><td>Type: AN</td></tr>
</table>

Codes à utiliser:

<table>
<tr><th>ID</th><th>Groupe sanguin</th></tr>
<tr><td>0</td><td>O</td></tr>
<tr><td>1</td><td>A</td></tr>
<tr><td>2</td><td>B</td></tr>
<tr><td>3</td><td>AB</td></tr>
</table>

<table>
<tr><td>2.6.1.2</td><td colspan="3">Désignation du facteur rhésus (facultatif)</td></tr>
<tr><td>Tag: 63</td><td>Longueur: 1</td><td>Valeur: rhesusFactor</td><td>Type: AN</td></tr>
</table>

Codes à utiliser:

<table>
<tr><th>ID</th><th>Facteur rhésus</th></tr>
<tr><td>0</td><td>Rh+ signe positif</td></tr>
<tr><td>1</td><td>Rh– signe négatif</td></tr>
</table>

<table>
<tr><td>2.6.1.3</td><td colspan="3">Date du test de détermination du groupe sanguin (facultatif)</td></tr>
<tr><td>Tag: 64</td><td>Longueur: 10</td><td>Valeur: dateOf BloodGroupTest</td><td>Type: AN</td></tr>
<tr><td colspan="4">Date au format (AAAA-MM-JJ)</td></tr>
</table>

<table>
<tr><td>2.6.1.4</td><td colspan="3">Remarque concernant le groupe sanguin (facultatif)</td></tr>
<tr><td>Tag: 70</td><td>Longueur: 0–100</td><td>Valeur: bloodGroup Freetext</td><td>Type: AN</td></tr>
<tr><td colspan="4">Texte libre: remarque concernant le groupe sanguin</td></tr>
</table>

<table>
<tr><td>2.6.1.5</td><td colspan="3">Numéro EAN de l’auteur de l’inscription (obligatoire)</td></tr>
<tr><td>Tag: 80</td><td>Longueur: 13</td><td>Valeur: healthCare ProviderEanNumber</td><td>Type: AN</td></tr>
<tr><td colspan="4">Numéro identifiant à 13 chiffres</td></tr>
</table>

<table>
<tr><td>2.6.1.6</td><td colspan="3">Date de l’enregistrement (obligatoire)</td></tr>
<tr><td>Tag: 90</td><td>Longueur: 10</td><td>Valeur: dateOf Record</td><td>Type: AN</td></tr>
<tr><td colspan="4">Date au format (AAAA-MM-JJ)</td></tr>
</table>

<table>
<tr><td>2.6.2</td><td colspan="3">Données concernant les transfusions (facultatif)</td></tr>
<tr><td>Tag: 65</td><td>Longueur: x</td><td>Valeur: transfusion</td><td>Type: class</td></tr>
</table>

<table>
<tr><td>2.6.2.1</td><td colspan="3">Indication du nombre de transfusions sanguines (facultatif)</td></tr>
<tr><td>Tag: 66</td><td>Longueur: 1</td><td>Valeur: numberOf BloodTransfusions</td><td>Type: AN</td></tr>
</table>

Codes à utiliser:

<table>
<tr><th>ID</th><th>Nombre de transfusions sanguines</th></tr>
<tr><td>0</td><td>Jamais</td></tr>
<tr><td>1</td><td>Une fois</td></tr>
<tr><td>2</td><td>Plus d’une fois</td></tr>
</table>

<table>
<tr><td>2.6.2.2</td><td colspan="3">Date de la dernière transfusion sanguine (facultatif)</td></tr>
<tr><td>Tag: 67</td><td>Longueur: 10</td><td>Valeur: dateOfLast BloodTransfusion</td><td>Type: AN</td></tr>
<tr><td colspan="4">Date au format (AAAA-MM-JJ)</td></tr>
</table>

<table>
<tr><td>2.6.2.3</td><td colspan="3">Remarque concernant la dernière transfusion sanguine (facultatif)</td></tr>
<tr><td>Tag: 70</td><td>Longueur: 0–100</td><td>Valeur: blood TransfusionFreetext</td><td>Type: AN</td></tr>
<tr><td colspan="4">Texte libre: remarque concernant la dernière transfusion sanguine</td></tr>
</table>

<table>
<tr><td>2.6.2.4</td><td colspan="3">Numéro EAN de l’auteur de l’inscription (obligatoire)</td></tr>
<tr><td>Tag: 80</td><td>Longueur: 13</td><td>Valeur: healthCare ProviderEanNumber</td><td>Type: AN</td></tr>
<tr><td colspan="4">Numéro identifiant à 13 chiffres</td></tr>
</table>

<table>
<tr><td>2.6.2.5</td><td colspan="3">Date de l’enregistrement (obligatoire)</td></tr>
<tr><td>Tag: 90</td><td>Longueur: 10</td><td>Valeur: dateOf Record</td><td>Type: AN</td></tr>
<tr><td colspan="4">Date au format (AAAA-MM-JJ)</td></tr>
</table>

### 2.7 Inscription supplémentaire pour les cas médicalement fondés

<table>
<tr><td>2.7.1</td><td>Renseignements sur les dossiers médicaux ou pharmaceutiques à disposition (facultatif, multiple)</td></tr>
</table>

Il est possible d’enregistrer [0–10] données; cf. enregistrements [1–10] du fichier EF.ZUSE défini dans la norme eCH-0064:2008.

<table>
<tr><td>Tag: 1200</td><td>Longueur: x</td><td>Valeur: medical Pharmaceutical Dossier</td><td>Type: class</td></tr>
</table>

Les données relatives aux renseignements sur les dossiers médicaux ou pharmaceutiques se composent des éléments suivants:

<table>
<tr><td>2.7.1.1</td><td>Les données concernant l’adresse du dépositaire doivent être spécifiées conformément à la norme eCH-0010 «Adresses postales pour les personnes physiques, les entreprises, les organisations et les autorités» dans son édition de 2006 (eCH-0010:2006).</td></tr>
</table>

<table>
<tr><td>2.7.1.2</td><td colspan="3">Commentaire concernant le dossier médical ou pharmaceutique (facultatif)</td></tr>
<tr><td>Tag: 70</td><td>Longueur: 0–100</td><td>Valeur: medical DossierFreetext</td><td>Type: AN</td></tr>
<tr><td colspan="4">Texte libre: remarque concernant le dossier médical ou pharmaceutique (par ex. remarques sur le contenu, mention de dossiers électroniques)</td></tr>
</table>

<table>
<tr><td>2.7.1.3</td><td colspan="3">Numéro EAN de l’auteur de l’inscription (obligatoire)</td></tr>
<tr><td>Tag: 80</td><td>Longueur: 13</td><td>Valeur: healthCare ProviderEanNumber</td><td>Type: AN</td></tr>
<tr><td colspan="4">Numéro identifiant à 13 chiffres</td></tr>
</table>

<table>
<tr><td>2.7.1.4</td><td colspan="3">Date de l’enregistrement (obligatoire)</td></tr>
<tr><td>Tag: 90</td><td>Longueur: 10</td><td>Valeur: dateOf Record</td><td>Type: AN</td></tr>
<tr><td colspan="4">Date au format (AAAA-MM-JJ)</td></tr>
</table>

<table>
<tr><td>2.7.2</td><td>Informations médicales ou pharmaceutiques supplémentaires (facultatif, multiple)</td></tr>
</table>

Il est possible d’enregistrer [0–25] données; cf. enregistrements [11–35] du fichier EF.ZUSE défini dans la norme eCH-0064:2008.

<table>
<tr><td>Tag: 1300</td><td>Longueur: x</td><td>Valeur: additional MedicalAnd Pharmaceutical Entries</td><td>Type: class</td></tr>
</table>

Les données relatives aux informations médicales ou pharmaceutiques supplémentaires se composent des éléments suivants:

<table>
<tr><td>2.7.2.1</td><td colspan="3">Désignation des informations médicales ou pharmaceutiques supplémentaires (facultatif)</td></tr>
<tr><td>Tag: 60</td><td>Longueur: 0–20</td><td>Valeur: additional MedicalAnd Pharmaceutical Entries</td><td>Type: AN</td></tr>
<tr><td colspan="4">Texte libre: désignation des informations médicales ou pharmaceutiques supplémentaires</td></tr>
</table>

<table>
<tr><td>2.7.2.2</td><td colspan="3">Remarque concernant les informations médicales ou pharmaceutiques supplémentaires (facultatif)</td></tr>
<tr><td>Tag: 70</td><td>Longueur: 0–100</td><td>Valeur: additional MedicalAnd Pharmaceutical EntriesFreetext</td><td>Type: AN</td></tr>
<tr><td colspan="4">Texte libre: remarque concernant les informations médicales ou pharmaceutiques supplémentaires</td></tr>
</table>

<table>
<tr><td>2.7.2.3</td><td colspan="3">Numéro EAN de l’auteur de l’inscription (obligatoire)</td></tr>
<tr><td>Tag: 80</td><td>Longueur: 13</td><td>Valeur: healthCare ProviderEanNumber</td><td>Type: AN</td></tr>
<tr><td colspan="4">Numéro identifiant à 13 chiffres</td></tr>
</table>

<table>
<tr><td>2.7.2.4</td><td colspan="3">Date de l’enregistrement (obligatoire)</td></tr>
<tr><td>Tag: 90</td><td>Longueur: 10</td><td>Valeur: dateOf Record</td><td>Type: AN</td></tr>
<tr><td colspan="4">Date au format (AAAA-MM-JJ)</td></tr>
</table>

### 2.8 Adresses de personnes à prévenir en cas d’urgence (facultatif, multiple)

Il est possible d’enregistrer [0–10] données; cf. enregistrements [1–10] du fichier EF.ADDR défini dans la norme eCH-0064:2008.

<table>
<tr><td>Tag: 1400</td><td>Longueur: x</td><td>Valeur: contact AddressesFor Emergency</td><td>Type: class</td></tr>
</table>

Les données relatives aux personnes à prévenir en cas d’urgence se composent des éléments suivants:

<table>
<tr><td>2.8.1</td><td colspan="3">Type de contact (facultatif)</td></tr>
<tr><td>Tag: 77</td><td>Longueur: 1</td><td>Valeur: kindOfAddressee</td><td>Type: AN</td></tr>
</table>

Codes à utiliser:

<table>
<tr><th>ID</th><th>Type de contact</th></tr>
<tr><td>1</td><td>contact privé</td></tr>
<tr><td>2</td><td>contact médical</td></tr>
</table>

<table>
<tr><td>2.8.2</td><td>Données concernant l’adresse de contact au format défini dans la norme eCH-0010:2006</td></tr>
</table>

### 2.9 Mention de l’existence de directives anticipées du patient ou de certificats de donneur d’organes (facultatif, multiple)

Il est possible d’enregistrer [0–10] données; cf. enregistrements [1–10] du fichier EF.VERF défini dans la norme eCH-0064:2008.

<table>
<tr><td>Tag: 1500</td><td>Longueur: x</td><td>Valeur: noticeOn PatientDecree</td><td>Type: class</td></tr>
</table>

Les données relatives aux directives anticipées ou aux certificats de donneur d’organes du patient se composent des éléments suivants:

<table>
<tr><td>2.9.1</td><td colspan="3">Type de dépositaire du document (facultatif)</td></tr>
<tr><td>Tag: 78</td><td>Longueur: 1</td><td>Valeur: keeperOf Documents</td><td>Type: AN</td></tr>
</table>

Codes à utiliser:

<table>
<tr><th>ID</th><th>Type de dépositaire</th></tr>
<tr><td>1</td><td>contact privé</td></tr>
<tr><td>2</td><td>contact médical</td></tr>
</table>

<table>
<tr><td>2.9.2</td><td>Données concernant l’adresse du dépositaire au format défini dans la norme eCH-0010:2006</td></tr>
</table>

<table>
<tr><td>2.9.3</td><td colspan="3">Remarque concernant la directive ou le certificat (facultatif)</td></tr>
<tr><td>Tag: 70</td><td>Longueur: 0–100</td><td>Valeur: noticeOn PatientDecreeFreetext</td><td>Type: AN</td></tr>
<tr><td colspan="4">Texte libre: remarque concernant la directive ou le certificat</td></tr>
</table>

Annexe 3

(art. 3)

## Spécification des données pour l’interrogation en ligne au sens de l’art. 15 OCA

Les spécifications ci-après relatives aux données d’accès et aux données mises à disposition lors de l’interrogation en ligne incluent le descriptif de l’élément dans le titre et, entre parenthèses, les désignations de l’élément contenues dans les schémas XML[^annex3-lvlu1-1], ainsi que le format et la longueur.

### 1 Entrée des données lors de l’interrogation (inputData)

[^annex3-lvlu1-1]: Les schémas XML peuvent être commandés auprès de l’Office fédéral de la santé publique, 3003 Berne, ou consultés à l’adresse www.ehealth.admin.ch.

Format: complex

Pour une interrogation des données en ligne, les fournisseurs de prestations doivent entrer les données suivantes:

<table>
<tr><td>1.1</td><td>Numéro d’identification de la carte d’assuré (cardNoVeKa)</td></tr>
<tr><td colspan="2">Format: token, longueur 20</td></tr>
</table>

<table>
<tr><td>1.2</td><td>Numéro RCC (Registre des codes-créanciers) de l’auteur de l’inscription (ZSRno)</td></tr>
<tr><td colspan="2">Format: token, longueur 9</td></tr>
</table>

### 2 Données mises à disposition lors de la réponse (outputData)

Format: complex

Lors de la réponse, le service en ligne affiche les informations actuelles au moment de la requête selon la liste suivante:

<table>
<tr><td>2.1</td><td>Données entrées lors de l’interrogation</td></tr>
<tr><td colspan="2">Les données entrées lors de l’interrogation décrites au ch. 1 apparaissent à titre de vérification.</td></tr>
</table>

<table>
<tr><td>2.2</td><td>Date de l’interrogation (qualifyingDate)</td></tr>
<tr><td colspan="2">Format: date, AAAA-MM-JJ, longueur 10</td></tr>
<tr><td colspan="2">La date indique le moment où le fournisseur de prestations a procédé à l’interrogation.</td></tr>
</table>

<table>
<tr><td>2.3</td><td>Numéro de l’interrogation (queryNumber)</td></tr>
<tr><td colspan="2">Format: token, longueur 20</td></tr>
<tr><td colspan="2">L’élément comporte un numéro, attribué lors de chaque interrogation. Ce numéro vise à confirmer l’interrogation.</td></tr>
</table>

<table>
<tr><td>2.4</td><td>Validité de la carte d’assuré (validCard)</td></tr>
<tr><td colspan="2">Format: string, longueur 1</td></tr>
<tr><td colspan="2">Cet élément permet de vérifier si la carte est valide. Seules les informations suivantes sont disponibles:</td></tr>
<tr><td colspan="2">oui = 1</td></tr>
<tr><td colspan="2">non = 2</td></tr>
</table>

<table>
<tr><td>2.5</td><td>Données spécifiées à l’art. 3, al. 1, OCA</td></tr>
<tr><td colspan="2">Si la carte d’assuré est valide, les données spécifiées à l’art. 3, al. 1, OCA doivent être mises à disposition.</td></tr>
</table>

<table>
<tr><td>2.6</td><td>Données spécifiées à l’art. 4, al. 2, OCA</td></tr>
<tr><td colspan="2">Si la carte d’assuré est valide, les données spécifiées à l’art. 4, al. 2, OCA peuvent être mises à disposition.</td></tr>
</table>

Annexe 4[^t-2]

(art. 4)

## Exigences graphiques relatives à la carte d’assuré

[^t-2]: Mise à jour par l’annexe ch. II 38 de l’O du 17 nov. 2021, en vigueur depuis le 1<sup>er</sup> janv. 2022 ([RO 2021 800](https://fedlex.data.admin.ch/eli/oc/2021/800)).

### 1 Généralités

### 1.1 Référence

<table>
<tr><td>EN (norme européenne) 1867:1997</td><td>Cartes lisibles par machine – Applications dans le domaine de la santé – Système de numérotation et procédure d’enregistrement pour les identificateurs des émetteurs de cartes</td></tr>
</table>

### 1.2 Source

<table>
<tr><td>Norme européenne</td><td>Comité européen de normalisation, rue de Stassart 36, B-1050 Bruxelles, http://www.cenorm.be La norme peut être consultée auprès de l’Office fédéral de la santé publique.</td></tr>
</table>

### 1.3 Abréviation

<table>
<tr><td>Char</td><td>Caractère</td></tr>
</table>

### 2 Exigences graphiques

### 2.1 Structure de la carte d’assuré

La carte d’assuré comprend trois parties horizontales:

– la partie comprenant la désignation de la carte:

- Située en haut de la carte et large de 10 mm, cette partie comprend la croix suisse ainsi que la désignation «Carte suisse d’assurance-maladie LAMal» dans les quatre langues nationales.

– la partie consacrée à l’assureur:

- La puce électronique et le nom de l’assureur doivent figurer dans cette partie de la carte. L’assureur est libre quant au graphisme de cette partie.

– la partie relative à l’assuré:

- Les données énumérées à l’art. 3, al. 1, OCA apparaissent dans cette partie, large de 20 mm et placée au bas de la carte.

### 2.2 Graphisme

L’illustration 1 présente les mesures et la structure de la carte d’assuré ainsi que l’agencement des différents éléments graphiques (tels que le logo, les textes et la désignation de la carte). Les chiffres figurant dans un cadre correspondent aux divers éléments graphiques.

Illustration 1

Agencement des éléments graphiques

![](https://fedlex.data.admin.ch/filestore/fedlex.data.admin.ch/eli/cc/2008/228/20220101/fr/xml/image/image1.png)

Tableau 1

Police et emplacement des éléments graphiques

<table>
<tr><th>N<sup>o</sup> de l’élément</th><th>Désignation</th><th>Police et taille</th><th>Coordonnée x (mm)</th><th>Coordonnée y (mm)</th><th>Emplacement</th></tr>
<tr><td></td><td>Désignation de la carte</td><td></td><td></td><td></td><td></td></tr>
<tr><td>03</td><td>de</td><td>Verdana 6, gras</td><td>19.0</td><td>50.0</td><td>à gauche</td></tr>
<tr><td>03’’</td><td>fr</td><td>Verdana 6, gras</td><td>19.0</td><td>48.0</td><td>à gauche</td></tr>
<tr><td>03’’’</td><td>it</td><td>Verdana 6, gras</td><td>19.0</td><td>46.0</td><td>à gauche</td></tr>
<tr><td>03’’’’</td><td>rm</td><td>Verdana 6, gras</td><td>19.0</td><td>44.0</td><td>à gauche</td></tr>
<tr><td>06</td><td>Nom, Prénom</td><td>Verdana 8 Pt. Fett</td><td>3.0</td><td>16.4</td><td>à gauche</td></tr>
<tr><td>07</td><td>Titre: Nom, Prénom</td><td>Verdana 4, normal</td><td>3.0</td><td>14.8</td><td>à gauche</td></tr>
<tr><td>08</td><td>N<sup>o</sup> d’identification de la carte d’assuré (CA)</td><td>Verdana 8, normal</td><td>3.0</td><td>11.0</td><td>à gauche</td></tr>
<tr><td>09</td><td>No d’identification de la CA</td><td>Verdana 4, normal</td><td>3.0</td><td>9.4</td><td>à gauche</td></tr>
<tr><td>10</td><td>Date de naissance Sexe</td><td>Verdana 8, normal</td><td>3.0</td><td>5.6</td><td>à gauche</td></tr>
<tr><td>11</td><td>Titre: Date de naissance, sexe (1<sup>re</sup> ligne)</td><td>Verdana 4, normal</td><td>3.0</td><td>4.0</td><td>à gauche</td></tr>
<tr><td>11’’</td><td>Titre: Date de naissance, sexe (2<sup>e</sup> ligne)</td><td>Verdana 4, normal</td><td>3.0</td><td>2.4</td><td>à gauche</td></tr>
<tr><td>12</td><td>N<sup>o</sup> OFSP</td><td>Verdana 8, normal</td><td>44.5</td><td>11.0</td><td>à gauche</td></tr>
<tr><td>13</td><td>Titre: N<sup>o</sup> OFSP (1<sup>re</sup> ligne)</td><td>Verdana 4, normal</td><td>44.5</td><td>9.4</td><td>à gauche</td></tr>
<tr><td>13’’</td><td>Titre: N<sup>o</sup> OFSP (2<sup>e</sup> ligne)</td><td>Verdana 4, normal</td><td>44.5</td><td>7.8</td><td>à gauche</td></tr>
<tr><td>14</td><td>No AVS</td><td>Verdana 8, normal</td><td>82.6</td><td>11.0</td><td>à droite</td></tr>
<tr><td>15</td><td>Titre: No AVS</td><td>Verdana 4, normal</td><td>82.6</td><td>9.4</td><td>à droite</td></tr>
<tr><td>16</td><td>Date d’expiration</td><td>Verdana 8, normal</td><td>82.6</td><td>5.6</td><td>à droite</td></tr>
<tr><td>17</td><td>Titre: Date d’expiration (1<sup>re</sup> ligne)</td><td>Verdana 4, normal</td><td>82.6</td><td>4.0</td><td>à droite</td></tr>
<tr><td>17’’</td><td>Titre: Date d’expiration (2<sup>e</sup> ligne)</td><td>Verdana 4, normal</td><td>82.6</td><td>2.4</td><td>à droite</td></tr>
</table>

Spécifications des éléments graphiques et des données au sens de l’art. 3 OCA

<table>
<tr><th>N<sup>o</sup> d’élément</th><th>Désignation</th><th>Descriptif: exemples</th><th>Type de donnée</th><th>Longueur, format</th><th>pi: préimprimé pers.: personalisé</th></tr>
<tr><td>01</td><td>Fond</td><td>L’assureur peut choisir le motif qui ornera le fond de la carte, ce dernier devant offrir un contraste suffisant pour que les données y figurant soient lisibles.</td><td>Image</td><td></td><td>pi</td></tr>
<tr><td>02</td><td>Croix suisse</td><td>Logo national Croix suisse selon l’arrêté fédéral du 12 décembre 1889 (RS *111*)</td><td>Image</td><td></td><td>pi</td></tr>
<tr><td>03</td><td>Désignation</td><td>Désignation de la carte dans les quatre langues nationales</td><td>Char</td><td></td><td>pi</td></tr>
<tr><td></td><td>de</td><td>Schweizerische Krankenversicherungskarte KVG</td><td></td><td></td><td></td></tr>
<tr><td></td><td>fr</td><td>Carte suisse d’assurance-maladie LAMal</td><td></td><td></td><td></td></tr>
<tr><td></td><td>it</td><td>Tessera svizzera d’assicurazione malattie LAMal</td><td></td><td></td><td></td></tr>
<tr><td></td><td>rm</td><td>Carta svizra da l’assicuranza da malsauns LAM</td><td></td><td></td><td></td></tr>
<tr><td>04</td><td>Puce</td><td>Microprocesseur La partie visible de la puce a une surface d’env. 13 × 12 mm. A noter qu’il faut laisser une marge de 1 mm autour de la puce afin de tenir compte de petites différences lors de son implantation.</td><td></td><td></td><td></td></tr>
<tr><td>05</td><td>Nom de l’assureur</td><td>Aucune exigence</td><td></td><td></td><td></td></tr>
<tr><td>06</td><td>Nom, prénom</td><td>Nom (1<sup>re</sup> partie) et prénom = prénom usuel (2<sup>e</sup> partie), 2<sup>e</sup> partie évent. abrégée. Insérer une virgule suivie d’une espace entre la 1<sup>re</sup> et la 2<sup>e</sup> partie; majuscules et minuscules Ex.: **Dupont, Jean**</td><td>Char</td><td>50 (y compris virgule et espace entre la 1<sup>re</sup> et la 2<sup>e</sup> partie)</td><td>pers</td></tr>
<tr><td>07</td><td>Titre: Nom, prénom</td><td>Name, Vorname/Nom, prénom/Cognome, nome/Num, preum</td><td>Char</td><td>48</td><td>pers</td></tr>
<tr><td>08</td><td>N<sup>o</sup> d’identification de la carte d’assuré (N<sup>o</sup> carte)</td><td>Numéro logique individuel visant à identifier chaque carte et attribué à celle-ci par l’émetteur de la carte. Les dix premiers caractères identifient l’émetteur de la carte, conformément à la norme européenne EN 1867 «Cartes lisibles par machine –Applications pour la santé – Système de numérotation et procédure d’enregistrement pour les identificateurs d’émetteur» dans son édition de 1997 (norme EN 1867:1997). Les dix derniers caractères forment le numéro de série unique. Si les données de la carte européenne d’assurance-maladie (CEAM) sont imprimées au dos de la carte d’assuré (CA), le n<sup>o</sup> d’identification de la CA doit être identique à celui de la CEAM.</td><td>Char</td><td>20</td><td>pers</td></tr>
<tr><td>09</td><td>Titre: N<sup>o</sup> carte</td><td>Karten-Nr./N<sup>o</sup> Carte/N. Carta/Nr. da la Carta</td><td>Char</td><td>35</td><td>pers</td></tr>
<tr><td>10</td><td>Date de naissance</td><td>Date de naissance Ex: **13.12.1996**</td><td>Date</td><td>10 **TT.MM.JJJJ**</td><td>pers</td></tr>
<tr><td></td><td>Sexe</td><td>Sexe **M** = masculin **F** = féminin</td><td>Char</td><td>1 M **F**</td><td></td></tr>
<tr><td>11</td><td>Titre: Date de naissance, sexe</td><td>Geburtsdatum, Geschlecht/Date de naissance, sexe</td><td>Char</td><td>48</td><td>pers</td></tr>
<tr><td></td><td></td><td>Data die nascita, sesso/Data da naschientscha, schlattaina</td><td></td><td>58</td><td></td></tr>
<tr><td>12</td><td>N<sup>o</sup> OFSP</td><td>N<sup>o</sup> OFSP de l’assureur: ex. **12345**</td><td>Char</td><td>5</td><td>pers</td></tr>
<tr><td>13</td><td>Titre: N<sup>o</sup> OFSP</td><td>BAG-Nr./N<sup>o</sup> OFSP</td><td>Char</td><td>14</td><td>pers</td></tr>
<tr><td></td><td></td><td>N. UFSP/Nr. UFSP</td><td></td><td>15</td><td></td></tr>
<tr><td>14</td><td>N<sup>o</sup> AVS de l’assuré</td><td>Nouveau n<sup>o</sup> AVS à 13 chiffres avec points de séparation après les 3<sup>e</sup>, 7<sup>e</sup> et 11<sup>e</sup> chiffres: ex: **756.3047.5009.62**</td><td>Char</td><td>16 y compris 3 points</td><td>pers</td></tr>
<tr><td>15</td><td>Titre: N<sup>o</sup> AVS</td><td>AHV-Nr./N<sup>o</sup> AVS/N. AVS/Nr. AVS</td><td>Char</td><td>28</td><td>pers</td></tr>
<tr><td>16</td><td>Date d’expiration de la carte</td><td>Si les données de la CEAM sont imprimées au dos de la CA, la date d’expiration de la CA doit être identique à celle de la CEAM.</td><td>Date</td><td>10 **TT.MM.JJJJ**</td><td>pers</td></tr>
<tr><td>17</td><td>Titre: Date d’expiration</td><td>Ablaufdatum/Date d’expiration</td><td>Char</td><td>28</td><td>pers</td></tr>
<tr><td></td><td></td><td>Data di scadenza/Data da scadenza</td><td></td><td>35</td><td></td></tr>
</table>
