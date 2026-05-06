---
status: "beschlossen, noch nicht in Kraft"
reference: AS 2026 194
title: Ordonnance du DFI sur les fichiers de données pour la transmission des données entre fournisseurs de prestations et assureurs
language: fr
adopted: 2026-05-06
published: 2026-05-07
in_force: ["2026-06-01"]
url: "https://www.fedlex.admin.ch/eli/oc/2026/194/fr"
---

> Reproduction non officielle du Recueil officiel (RO). L’acte est publié mais n’est pas encore en vigueur ; seule la publication au RO fait foi (art. 15 LPubl, RS 170.512).

# Ordonnance du DFI sur les fichiers de données pour la transmission des données entre fournisseurs de prestations et assureurs

Modification du 6 mai 2026

Le Département fédéral de l’intérieur (DFI)

arrête:

## I

L’annexe de l’ordonnance du DFI du 20 novembre 2012 sur les fichiers de données pour la transmission des données entre fournisseurs de prestations et assureurs[^lvlI-1] est remplacée par la version ci-jointe.

[^lvlI-1]: [RS 832.102.14](https://fedlex.data.admin.ch/vocabulary/legal-taxonomy/10136)

## II

La présente ordonnance entre en vigueur le 1<sup>er</sup> juin 2026.

<table>
<tr><td>6 mai 2026</td><td>Département fédéral de l’intérieur: Elisabeth Baume-Schneider</td></tr>
</table>

Annexe

(art. 1)

## Structure uniforme au niveau suisse des fichiers de données

### 1 Généralités

### 1.1 Abréviations et définitions

- CHOP Classification suisse des interventions chirurgicales
- GM German Modification
- SpiGes Relevé des données des fournisseurs de prestations au sens de l’art. 59*a* de la loi fédérale du 18 mars 1994 sur l’assurance-maladie[^annexu1-lvlu1-lvl1-lvl11-1] et de l’art. 30 de l’ordonnance du 27 juin 1995 sur l’assurance-maladie[^annexu1-lvlu1-lvl1-lvl11-2] dans le domaine des services de santé en cas de séjour hospitalier
- CIM-10 Classification statistique internationale des maladies et des problèmes de santé connexes

[^annexu1-lvlu1-lvl1-lvl11-1]: [RS 832.10](https://fedlex.data.admin.ch/vocabulary/legal-taxonomy/10133)
[^annexu1-lvlu1-lvl1-lvl11-2]: [RS 832.102](https://fedlex.data.admin.ch/vocabulary/legal-taxonomy/10135)

### 1.2 Fichier de données médicales

<table>
<tr><th>Désignation selon SpiGes</th><th>Variable selon SpiGes</th><th>Description</th></tr>
<tr><td>Poids à la naissance</td><td>geburtsgewicht</td><td>En grammes</td></tr>
<tr><td>Code diagnostic Classement du diagnostic</td><td>diagnose\_kode diagnose\_id</td><td>Code CIM-10-GM Numéro attribué au diagnostic. La catégorie 1 caractérise le diagnostic principal</td></tr>
<tr><td>Code de traitement ID du traitement</td><td>behandlung\_chop behandlung\_id</td><td>Code CHOP Numéro attribué au traitement, dans l’ordre</td></tr>
<tr><td>Latéralité pour le traitement</td><td>behandlung\_seitigkeit</td><td>0 = bilatéral 1 = unilatéral droit 2 = unilatéral gauche 3 = unilatéral côté inconnu 9 = inconnu Vide = la question ne se pose pas</td></tr>
<tr><td>Début du traitement</td><td>behandlung\_beginn</td><td>Date (avec indication de l’heure)</td></tr>
<tr><td>Durée de la ventilation artificielle</td><td>beatmung</td><td>Nombre d’heures</td></tr>
<tr><td>Poids à l’admission</td><td>aufnahmegewicht</td><td>En grammes</td></tr>
<tr><td>Malformations congénitales</td><td>missbildungen</td><td>0 = non 1 = oui 9 = inconnu</td></tr>
<tr><td>Justification pour le séjour à l’hôpital</td><td>–</td><td>Selon colonne «N<sup>o</sup>» de l’annexe 1*a*, ch. II, de l’ordonnance du 29 septembre 1995 sur les prestations de l’assurance des soins[^annexu1-lvlu1-lvl1-lvl12-1]</td></tr>
<tr><td>ID du médicament</td><td>medi\_id</td><td>Identificateur permettant de distinguer les médicaments</td></tr>
<tr><td>Code ATC du médicament</td><td>medi\_atc</td><td>Code ATC des médicaments onéreux selon les directives de SwissDRG SA (ATC=*Anatomical* *Therapeutic* *Chemical*)</td></tr>
<tr><td>Indications supplémentaires</td><td>medi\_zusatz</td><td>Indications supplémentaires pour les médicaments onéreux selon les directives de SwissDRG SA</td></tr>
<tr><td>Mode d’administration</td><td>medi\_verabreichungsart</td><td>Mode d’administration des médicaments onéreux selon les directives de SwissDRG SA</td></tr>
<tr><td>Dosage</td><td>medi\_dosis</td><td>Nombre (unité de mesure) pour les médicaments onéreux selon les directives de SwissDRG SA</td></tr>
<tr><td>Unité de mesure</td><td>medi\_einheit</td><td>Unité de mesure pour les médicaments onéreux selon les directives de SwissDRG SA</td></tr>
</table>

[^annexu1-lvlu1-lvl1-lvl12-1]: [RS 832.112.31](https://fedlex.data.admin.ch/vocabulary/legal-taxonomy/10157)

### 1.3 Fichier de données administratives

<table>
<tr><th>Désignation selon SpiGes</th><th>Variable selon SpiGes</th><th>Description</th></tr>
<tr><td>Sexe</td><td>geschlecht</td><td>1 = masculin 2 = féminin</td></tr>
<tr><td>Date de naissance</td><td>geburtsdatum</td><td>Indication de la date</td></tr>
<tr><td>Âge à l’admission</td><td>alter</td><td>Âge exact</td></tr>
<tr><td>Âge en jours des enfants de moins d’un an</td><td>alter\_U1</td><td>Âge à l’entrée en jours</td></tr>
<tr><td>Date et heure d’admission</td><td>eintrittsdatum</td><td></td></tr>
<tr><td>Séjour avant l’admission</td><td>eintritt\_aufenthalt</td><td>1 = domicile 2 = domicile avec soins à domicile 3 = établissement de santé non hospitalier médicalisé 4 = établissement de santé non hospitalier non médicalisé 5 = hôpital psychiatrique, autre établissement 55 = division/clinique psychiatrique, même établissement 6 = autre institution hospitalière (soins aigus) ou maison de naissance 66 = division/clinique de soins aigus, même établissement 7 = institution d’exécution des peines 8 = autre 83 = clinique de réadaptation, autre établissement 84 = division/clinique de réadaptation, même établissement 9 = inconnu</td></tr>
<tr><td>Mode d’admission</td><td>eintrittsart</td><td>1 = urgence (nécessité d’un traitement dans les 12 heures) 2 = annoncé, planifié 3 = naissance (enfant né lors de ce séjour stationnaire et dans cette clinique) 4 = transfert interne 5 = transfert dans les 24 heures [tab] 6 = réhospitalisation [tab] 7 = rapatriement 8 = autre 9 = inconnu</td></tr>
<tr><td>Vacances, congés administratifs</td><td>admin\_urlaub</td><td>Heures révolues</td></tr>
<tr><td>Centre de prestations médicales principal</td><td>hauptleistungsstelle</td><td>M000 = Disciplines médicales (en général) M050 = Soins intensifs M100 = Médecine interne M200 = Chirurgie M300 = Gynécologie et obstétrique M400 = Pédiatrie M500 = Psychiatrie et psychothérapie M600 = Ophtalmologie M700 = Oto-rhino-laryngologie M800 = Dermatologie et vénérologie M850 = Radiologie médicale M900 = Gériatrie M950 = Médecine physique et réadaptation M960 = Centres d’urgence M970 = Cabinet d’urgences des médecins M990 = Autres domaines d’activités</td></tr>
<tr><td>Date et heure de sortie</td><td>austrittsdatum</td><td></td></tr>
<tr><td>Décision de sortie</td><td>austrittsentscheid</td><td>1 = sur l’initiative du traitant 2 = sur l’initiative du patient (contre l’avis du traitant) 3 = sur l’initiative d’une tierce personne 4 = transfert interne 5 = décédé 8 = autre 9 = inconnu</td></tr>
<tr><td>Séjour après la sortie</td><td>austritt\_aufenthalt</td><td>1 = domicile 2 = établissement de santé non hospitalier médicalisé 3 = établissement de santé non hospitalier non médicalisé 4 = institution psychiatrique, autre établissement 44 = division/clinique psychiatrique, même établissement 5 = institution de réadaptation, autre établissement 55 = division/clinique de réadaptation, même établissement 6 = autre institution hospitalière (soins aigus) ou maison de naissance 66 = division/clinique de soins aigus, même établissement 7 = institution d’exécution des peines 8 = autre 9 = inconnu 0 = décédé</td></tr>
<tr><td>Début de l’épisode</td><td>episode\_beginn</td><td>Date (sans heure), seulement pour séjours après interruption/réadmission (episode\_art = 2)</td></tr>
<tr><td>Fin de l’épisode</td><td>episode\_ende</td><td>Date (sans heure), seulement pour séjours après interruption/réadmission (episode\_art = 2)</td></tr>
<tr><td>Séjour après interruption</td><td>wiedereintritt\_ aufenthalt</td><td>1 = domicile 2 = établissement de santé non hospitalier médicalisé 3 = établissement de santé non hospitalier non médicalisé 4 = institution psychiatrique, dans un autre établissement 44 = division/institution psychiatrique, dans le même établissement 5 = institution de réadaptation, dans un autre établissement 55 = division/institution de réadaptation, dans le même établissement 6 = autre institution hospitalière (soins aigus) ou maison de naissance 66 = division/clinique de soins aigus, dans le même établissement 7 = institution d’exécution des peines 8 = autre 9 = inconnu</td></tr>
<tr><td>Durée de la grossesse en fonction des dernières menstruations</td><td>gestationsalter1</td><td>Durée de la grossesse de la mère en fonction des dernières menstruation</td></tr>
<tr><td>Durée de la grossesse en fonction de l’échographie</td><td>gestationsalter2</td><td>Durée de la grossesse de la mère en fonction de l’échographie</td></tr>
<tr><td>Décision d’envoi</td><td>einw\_instanz</td><td>1 = initiative propre, proches 2 = service de sauvetage (ambulance, police) 3 = médecin 4 = thérapeute non médecin [tab] 5 = services socio-médicaux [tab] 6 = autorités judiciaires 8 = autre 9 = inconnu</td></tr>
<tr><td>Classe (de traitement)</td><td>liegeklasse</td><td>1 = chambre commune 2 = semi-privé 3 = privé 9 = inconnu</td></tr>
</table>
