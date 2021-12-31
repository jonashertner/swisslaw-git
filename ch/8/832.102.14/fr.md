---
sr: "832.102.14"
title: Ordonnance du DFI du 20 novembre 2012 sur les fichiers de données pour la transmission des données entre fournisseurs de prestations et assureurs
eli: "https://fedlex.data.admin.ch/eli/cc/2012/867"
language: fr
version: 2022-01-01
adopted: 2012-11-20
in_force: 2013-01-01
source: "https://fedlex.data.admin.ch/filestore/fedlex.data.admin.ch/eli/cc/2012/867/20220101/fr/xml/fedlex-data-admin-ch-eli-cc-2012-867-20220101-fr-xml-2.xml"
url: "https://www.fedlex.admin.ch/eli/cc/2012/867/20220101/fr"
---

> Reproduction non officielle de la version consolidée (Fedlex). Seule la publication au Recueil officiel fait foi (art. 15 LPubl, RS 170.512).

# Ordonnance du DFI sur les fichiers de données pour la transmission des données entre fournisseurs de prestations et assureurs

du 20 novembre 2012 (Etat le 1<sup>er</sup> janvier 2022)

Le Département fédéral de l’intérieur (DFI),

vu l’art. 59*a*, al. 1, de l’ordonnance du 27 juin 1995 sur l’assurance-maladie (OAmal)[^ingress-1],

arrête:

[^ingress-1]: [RS 832.102](https://fedlex.data.admin.ch/eli/cc/1995/3867_3867_3867)

#### Art. 1

La structure des fichiers de données visée à l’art. 59*a*, al. 1, OAMal est définie à l’annexe.

#### Art. 2

La présente ordonnance entre en vigueur le 1<sup>er</sup> janvier 2013.

Annexe*[^t-1]*

(art. 1)

## Structure uniforme au niveau suisse des fichiers de données

[^t-1]: Mise à jour par le ch. I de l’O du DFI du 25 oct. 2017 ([RO 2017 6341](https://fedlex.data.admin.ch/eli/oc/2017/704)), l’annexe de l’O du DFI du 30 nov. 2018 ([RO 2018 5085](https://fedlex.data.admin.ch/eli/oc/2018/793)), le ch. III de l’O du DFI du 6 juin 2019 ([RO 2019 1931](https://fedlex.data.admin.ch/eli/oc/2019/355)), le ch. I des O du DFI du 6 déc. 2019 ([RO 2019 4381](https://fedlex.data.admin.ch/eli/oc/2019/755)) et du 3 déc. 2021, en vigueur depuis le 1<sup>er</sup> janv. 2022 ([RO 2021 839](https://fedlex.data.admin.ch/eli/oc/2021/839)).

### 1 Généralités

### 1.1 Abréviations et définitions

- CHOP Classification suisse des interventions chirurgicales
- GM German Modification
- Statistique médicale Statistique médicale des hôpitaux visée au ch. 62 de l’annexe de l’ordonnance du 30 juin 1993 concernant l’exécution des relevés statistiques fédéraux[^annexu1-lvlu1-lvl1-lvl11-1]
- CIM-10 Classification statistique internationale des maladies et des problèmes de santé connexes

[^annexu1-lvlu1-lvl1-lvl11-1]: [RS 431.012.1](https://fedlex.data.admin.ch/eli/cc/1993/2100_2100_2100)

### 1.2 Fichier de données médicales

<table>
<tr><th>Intitulé</th><th>Variable de la statistique médicale</th><th>Teneur</th></tr>
<tr><td>Poids à la naissance</td><td>2.2.V04</td><td>En grammes</td></tr>
<tr><td>Diagnostic principal</td><td>4.2.V010</td><td>Code CIM-10-GM</td></tr>
<tr><td>Complément au diagnostic principal</td><td>4.2.V020</td><td>Code CIM-10-GM</td></tr>
<tr><td>1<sup>er</sup> au 49<sup>e</sup> diagnostic supplémentaire</td><td>4.2.V030, 4.2.V040 etc. jusqu’à 4.2.V510</td><td>Code CIM-10-GM</td></tr>
<tr><td>Traitement principal</td><td>4.3.V010</td><td>Code CHOP</td></tr>
<tr><td>Latéralité pour le traitement principal</td><td>4.3.V011</td><td>0 = bilatéral 1 = unilatéral droit 2 = unilatéral gauche 3 = unilatéral côté inconnu 9 = inconnu Vide = la question ne se pose pas</td></tr>
<tr><td>Début du traitement principal</td><td>4.3.V015</td><td>Date (avec indication de l’heure)</td></tr>
<tr><td>1<sup>er</sup> au 99<sup>e</sup> traitement supplémentaire</td><td>4.3.V020, 4.3.V030 etc. jusqu’à 4.3.V1000</td><td>Code CHOP</td></tr>
<tr><td>Latéralité 1<sup>er</sup> au 99<sup>e</sup> traitement supplémentaire</td><td>4.3.V021, 4.3.V031 etc. jusqu’à 4.3.V1001</td><td>0 = bilatéral 1 = unilatéral droit 2 = unilatéral gauche 3 = unilatéral côté inconnu 9 = inconnu Vide = la question ne se pose pas</td></tr>
<tr><td>Début du 1<sup>er</sup> au 99<sup>e</sup> traitement supplémentaire</td><td>4.3.V025, 4.3.V035 etc. jusqu’à 4.3.V1005</td><td>Date (avec indication de l’heure)</td></tr>
<tr><td>Durée de la ventilation artificielle</td><td>4.4.V01</td><td>Nombre d’heures</td></tr>
<tr><td>Poids à l’admission</td><td>4.5.V01</td><td>En grammes</td></tr>
<tr><td>Prise en charge</td><td>2.2.V06</td><td>0 = non 1 = oui 9 = inconnu</td></tr>
<tr><td>Justification pour le séjour à l’hôpital</td><td>–</td><td>1-99[^annexu1-lvlu1-lvl1-lvl12-1]</td></tr>
</table>

[^annexu1-lvlu1-lvl1-lvl12-1]: Selon l’annexe 1*a* OPAS, ch. II. Critères à satisfaire pour un traitement en milieu hospitalier ([RS 832.112.31](https://fedlex.data.admin.ch/eli/cc/1995/4964_4964_4964)).

### 1.3 Fichier de données administratives

<table>
<tr><th>Intitulé selon la statistique médicale</th><th>Variable de la statistique médicale</th><th>Teneur</th></tr>
<tr><td>Sexe</td><td>1.1.V01</td><td>1 = masculin 2 = féminin</td></tr>
<tr><td>Date de naissance</td><td>1.1.V02</td><td>Indication de la date</td></tr>
<tr><td>Âge à l’admission</td><td>1.1.V03</td><td>Âge exact</td></tr>
<tr><td>Date et heure d’admission</td><td>1.2.V01</td><td></td></tr>
<tr><td>Séjour avant l’admission</td><td>1.2.V02</td><td>1 = domicile 2 = domicile avec soins à domicile 3 = établissement de santé non hospitalier médicalisé 4 = établissement de santé non hospitalier non médicalisé 5 = hôpital psychiatrique, autre établissement 55 = division/clinique psychiatrique, même établissement 6 = autre institution hospitalière (soins aigus) ou maison de naissance 66 = division/clinique de soins aigus, même établissement 7 = institution d’exécution des peines 8 = autre 83 = clinique de réadaptation, autre établissement 84 = division/clinique de réadaptation, même établissement 9 = inconnu</td></tr>
<tr><td>Mode d’admission</td><td>1.2.V03</td><td>1 = urgence (nécessité d’un traitement dans les 12 heures) 2 = annoncé, planifié 3 = naissance (enfant né intra-muros) 4 = transfert interne 5 = transfert dans les 24 heures 8 = autre 9 = inconnu</td></tr>
<tr><td>Vacances, congés administratifs</td><td>1.3.V04</td><td>Heures révolues</td></tr>
<tr><td>Centre de prise en charge des coûts</td><td>1.4.V01</td><td>M000 = Disciplines médicales (en général) M050 = Soins intensifs M100 = Médecine interne M200 = Chirurgie M300 = Gynécologie et obstétrique M400 = Pédiatrie M500 = Psychiatrie et psychothérapie M600 = Ophtalmologie M700 = Oto-rhino-laryngologie M800 = Dermatologie et vénérologie M850 = Radiologie médicale M900 = Gériatrie M950 = Médecine physique et réadaptation M960 = Centres d’urgence M970 = Cabinet d’urgences des médecins M990 = Autres domaines d’activités</td></tr>
<tr><td>Date et heure de sortie</td><td>1.5.V01</td><td></td></tr>
<tr><td>Décision de sortie</td><td>1.5.V02</td><td>1 = sur l’initiative du traitant 2 = sur l’initiative du patient (contre l’avis du traitant) 3 = sur l’initiative d’une tierce personne 4 = transfert interne 5 = décédé 8 = autre 9 = inconnu</td></tr>
<tr><td>Séjour après la sortie</td><td>1.5.V03</td><td>1 = domicile 2 = établissement de santé non hospitalier médicalisé 3 = établissement de santé non hospitalier non médicalisé 4 = institution psychiatrique, autre établissement 44 = division/clinique psychiatrique, même établissement 5 = institution de réadaptation, autre établissement 55 = division/clinique de réadaptation, même établissement 6 = autre institution hospitalière (soins aigus) ou maison de naissance 66 = division/clinique de soins aigus, même établissement 7 = institution d’exécution des peines 8 = autre 9 = inconnu 0 = décédé</td></tr>
<tr><td>1<sup>re</sup> interruption, sortie</td><td>4.7.V01</td><td>Date (sans heure)</td></tr>
<tr><td>1<sup>re</sup> interruption, réadmission</td><td>4.7.V02</td><td>Date (sans heure)</td></tr>
<tr><td>2<sup>e</sup> à 4<sup>e</sup> interruptions, sortie</td><td>4.7.V11, 4.7.V21 resp. 4.7.V31</td><td>Date (sans heure)</td></tr>
<tr><td>2<sup>e</sup> à 4<sup>e</sup> interruptions, réadmission</td><td>4.7.V12, 4.7.V22 resp. 4.7.V32</td><td>Date (sans heure)</td></tr>
<tr><td>Réadmissions ultérieures</td><td>4.7.V41</td><td>0 = (défaut), pas plus de 5 séjours (soit 4 réadmissions) 1 = plus de 5 séjours (4 réadmissions)</td></tr>
<tr><td>Durée de la grossesse</td><td>4.8.V16</td><td>Sous forme chiffrée</td></tr>
<tr><td>Séjour après première interruption</td><td>4.8.V17</td><td>1 = domicile 2 = établissement de santé non hospitalier médicalisé 3 = établissement de santé non hospitalier non médicalisé 4 = institution psychiatrique, dans un autre établissement 44 = division/institution psychiatrique, dans le même établissement 5 = institution de réadaptation, dans un autre établissement 55 = division/institution de réadaptation, dans le même établissement 6 = autre institution hospitalière (soins aigus) ou maison de naissance 66 = division/clinique de soins aigus, dans le même établissement 7 = institution d’exécution des peines 8 = autre 9 = inconnu 0 = décédé</td></tr>
<tr><td>Séjour après deuxième interruption</td><td>4.8.V18</td><td>1 = domicile 2 = établissement de santé non hospitalier médicalisé 3 = établissement de santé non hospitalier non médicalisé 4 = institution psychiatrique, dans un autre établissement 44 = division/institution psychiatrique, dans le même établissement 5 = institution de réadaptation, dans un autre établissement 55 = division/institution de réadaptation, dans le même établissement 6 = autre institution hospitalière (soins aigus) ou maison de naissance 66 = division/clinique de soins aigus, dans le même établissement 7 = institution d’exécution des peines 8 = autre 9 = inconnu 0 = décédé</td></tr>
<tr><td>Séjour après troisième interruption</td><td>4.8.V19</td><td>1 = domicile 2 = établissement de santé non hospitalier médicalisé 3 = établissement de santé non hospitalier non médicalisé 4 = institution psychiatrique, dans un autre établissement 44 = division/institution psychiatrique, dans le même établissement 5 = institution de réadaptation, dans un autre établissement 55 = division/institution de réadaptation, dans le même établissement 6 = autre institution hospitalière (soins aigus) ou maison de naissance 66 = division/clinique de soins aigus, dans le même établissement 7 = institution d’exécution des peines 8 = autre 9 = inconnu 0 = décédé</td></tr>
<tr><td>Séjour après quatrième interruption</td><td>4.8.V20</td><td>1 = domicile 2 = établissement de santé non hospitalier médicalisé 3 = établissement de santé non hospitalier non médicalisé 4 = institution psychiatrique, dans un autre établissement 44 = division/institution psychiatrique, dans le même établissement 5 = institution de réadaptation, dans un autre établissement 55 = division/institution de réadaptation, dans le même établissement 6 = autre institution hospitalière (soins aigus) ou maison de naissance 66 = division/clinique de soins aigus, dans le même établissement 7 = institution d’exécution des peines 8 = autre 9 = inconnu 0 = décédé</td></tr>
<tr><td>Décision d’envoi</td><td>1.2.V04</td><td>1 = initiative propre, proches 2 = service de sauvetage (ambulance, police) 3 = médecin 4 = thérapeute non médecin 8 = autre 9 = inconnu</td></tr>
<tr><td>Type de prise en charge</td><td>1.3.V01</td><td>1 = ambulatoire 3 = hospitalisation 9 = inconnu</td></tr>
<tr><td>Classe</td><td>1.3.V02</td><td>1 = chambre commune 2 = semi-privé 3 = privé 9 = inconnu</td></tr>
<tr><td>Date de naissance de la mère</td><td>2.3.V01</td><td>Date (année et mois)</td></tr>
</table>
