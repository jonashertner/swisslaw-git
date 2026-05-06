---
status: "beschlossen, noch nicht in Kraft"
reference: AS 2026 194
title: Ordinanza del DFI sugli insiemi di dati per la trasmissione dei dati tra fornitori di prestazioni e assicuratori
language: it
adopted: 2026-05-06
published: 2026-05-07
in_force: ["2026-06-01"]
url: "https://www.fedlex.admin.ch/eli/oc/2026/194/it"
---

> Riproduzione non ufficiale della Raccolta ufficiale (RU). L’atto è pubblicato ma non ancora in vigore; fa stato la pubblicazione nella RU (art. 15 LPubb, RS 170.512).

# Ordinanza del DFI sugli insiemi di dati per la trasmissione dei dati tra fornitori di prestazioni e assicuratori

Modifiche del 6 maggio 2026

Il Dipartimento federale dell’interno (DFI)

ordina:

## I

L’allegato dell’ordinanza del DFI del 20 novembre 2012[^lvlI-1] sugli insiemi di dati per la trasmissione dei dati tra fornitori di prestazioni e assicuratori è sostituito dalla versione qui annessa.

[^lvlI-1]: [RS 832.102.14](https://fedlex.data.admin.ch/vocabulary/legal-taxonomy/10136)

## II

La presente ordinanza entra in vigore il 1° giugno 2026.

<table>
<tr><td>6 maggio 2026</td><td>Dipartimento federale dell’interno: Elisabeth Baume-Schneider</td></tr>
</table>

Allegato

(art. 1)

## Struttura uniforme degli insiemi di dati valida in tutta la Svizzera

### 1 In generale

### 1.1 Abbreviazioni e definizioni

- CHOP Classificazione svizzera degli interventi chirurgici
- GM German Modification
- SpiGes Rilevazione dei dati dei fornitori di prestazioni ai sensi dell’articolo 59*a* della legge federale del 18 marzo 1994[^annexu1-lvlu1-lvl1-lvl11-1] sull’assicurazione malattie e dell’articolo 30 dell’ordinanza del 27 giugno 1995[^annexu1-lvlu1-lvl1-lvl11-2] sull’assicurazione malattie nell’ambito dell’assistenza sanitaria in caso di degenza ospedaliera
- ICD-10 Classificazione statistica internazionale delle malattie e dei problemi sanitari correlati

[^annexu1-lvlu1-lvl1-lvl11-1]: [RS 832.10](https://fedlex.data.admin.ch/vocabulary/legal-taxonomy/10133)
[^annexu1-lvlu1-lvl1-lvl11-2]: [RS 832.102](https://fedlex.data.admin.ch/vocabulary/legal-taxonomy/10135)

### 1.2 Insieme di dati medici

<table>
<tr><th>Denominazione secondo SpiGes</th><th>Variabile secondo SpiGes</th><th>Descrizione</th></tr>
<tr><td>Peso alla nascita</td><td>geburtsgewicht</td><td>In grammi</td></tr>
<tr><td>Codice della diagnosi Rango della diagnosi</td><td>diagnose\_kode diagnose\_id</td><td>Codice ICD-10-GM Numero della diagnosi. Il rango 1 corrisponde alla diagnosi principale.</td></tr>
<tr><td>Codice del trattamento ID trattamento</td><td>behandlung\_chop behandlung\_id</td><td>Codice CHOP Numero progressivo del trattamento</td></tr>
<tr><td>Lateralità del trattamento</td><td>behandlung\_seitigkeit</td><td>0 = bilaterale 1 = unilaterale, destra 2 = unilaterale, sinistra 3 = unilaterale, lato sconosciuto 9 = sconosciuto Vuoto = non applicabile</td></tr>
<tr><td>Inizio del trattamento</td><td>behandlung\_beginn</td><td>Data (con indicazione dell’ora)</td></tr>
<tr><td>Durata della ventilazione artificiale</td><td>beatmung</td><td>Numero di ore</td></tr>
<tr><td>Peso all’ammissione</td><td>aufnahmegewicht</td><td>In grammi</td></tr>
<tr><td>Malformazioni congenite</td><td>missbildungen</td><td>0 = no 1 = sì 9 = sconosciuto</td></tr>
<tr><td>Motivazione della degenza in ospedale</td><td>–</td><td>Secondo la colonna «N.» dell’allegato 1*a* cifra II dell’ordinanza del 29 settembre 1995[^annexu1-lvlu1-lvl1-lvl12-1] sulle prestazioni</td></tr>
<tr><td>ID medicamento</td><td>medi\_id</td><td>Identificatore per distinguere i medicamenti</td></tr>
<tr><td>Codice ATC del medicamento</td><td>medi\_atc</td><td>Codice ATC dei medicamenti molto costosi secondo le direttive di SwissDRG SA (ATC=Anatomical Therapeutic Chemical)</td></tr>
<tr><td>Informazioni supplementari</td><td>medi\_zusatz</td><td>Informazioni supplementari per i medicamenti molto costosi secondo le direttive di SwissDRG SA</td></tr>
<tr><td>Modo di somministrazione</td><td>medi\_verabreichungsart</td><td>Modo di somministrazione dei medicamenti molto costosi secondo le direttive di SwissDRG SA</td></tr>
<tr><td>Dose</td><td>medi\_dosis</td><td>Quantità (unità di misura) per i medicamenti molto costosi secondo le direttive di SwissDRG SA</td></tr>
<tr><td>Unità di misura</td><td>medi\_einheit</td><td>Unità di misura per i medicamenti molto costosi secondo le direttive di SwissDRG SA</td></tr>
</table>

[^annexu1-lvlu1-lvl1-lvl12-1]: [RS 832.112.31](https://fedlex.data.admin.ch/vocabulary/legal-taxonomy/10157)

### 1.3 Insieme di dati amministrativi

<table>
<tr><th>Denominazione secondo SpiGes</th><th>Variabile secondo SpiGes</th><th>Descrizione</th></tr>
<tr><td>Sesso</td><td>geschlecht</td><td>1 = uomo 2 = donna</td></tr>
<tr><td>Data di nascita</td><td>geburtsdatum</td><td>Indicazione della data</td></tr>
<tr><td>Età all’ammissione</td><td>alter</td><td>Età esatta</td></tr>
<tr><td>Età in giorni dei bambini sotto 1 anno</td><td>alter\_U1</td><td>Età di ammissione in giorni</td></tr>
<tr><td>Data e ora di ammissione</td><td>eintrittsdatum</td><td></td></tr>
<tr><td>Luogo di residenza prima dell’ammissione</td><td>eintritt\_aufenthalt</td><td>1 = domicilio 2 = domicilio con assistenza Spitex 3 = casa di cura (comprese case per anziani medicalizzate) 4 = altro istituto sanitario non ospedaliero, non medicalizzato 5 = clinica psichiatrica, altro istituto 55 = reparto psichiatrico / clinica psichiatrica, stesso istituto 6 = altro istituto ospedaliero (ospedale acuto) o casa per partorienti 66 = reparto acuto / ospedale acuto, stesso istituto 7 = penitenziario 8 = altro 83 = clinica di riabilitazione, altro istituto 84 = reparto di riabilitazione / clinica di riabilitazione, stesso istituto 9 = sconosciuto</td></tr>
<tr><td>Modalità di ammissione</td><td>eintrittsart</td><td>1 = urgenza (necessità di trattamento entro 12 ore) 2 = annunciata, programmata 3 = nascita (neonato nato nell’istituto) 4 = trasferimento interno 5 = trasferimento entro 24 ore [tab] 6 = paziente ritrasferito [tab] 7 = rimpatrio 8 = altro 9 = sconosciuto</td></tr>
<tr><td>Congedo amministrativo e vacanze</td><td>admin\_urlaub</td><td>Ore intere</td></tr>
<tr><td>Centro di prestazione medica principale</td><td>hauptleistungsstelle</td><td>M000 = specializzazioni mediche (in generale) M050 = cure intense M100 = medicina interna M200 = chirurgia M300 = ginecologia e ostetricia M400 = pediatria M500 = psichiatria e psicoterapia M600 = oftalmologia M700 = otorinolaringoiatria M800 = dermatologia e venereologia M850 = radiologia M900 = geriatria M950 = medicina fisica e riabilitazione M960 = centro di pronto soccorso M970 = studio medico d’urgenza M990 = altri settori di attività</td></tr>
<tr><td>Data e ora della dimissione</td><td>austrittsdatum</td><td></td></tr>
<tr><td>Decisione della dimissione</td><td>austrittsentscheid</td><td>1 = su iniziativa del curante 2 = su iniziativa del paziente (contro il parere del curante) 3 = su iniziativa di terzi 4 = trasferimento interno 5 = decesso 8 = altro 9 = sconosciuto</td></tr>
<tr><td>Residenza dopo la dimissione</td><td>austritt\_aufenthalt</td><td>1 = domicilio 2 = casa di cura (comprese case per anziani medicalizzate) 3 = altro istituto sanitario non ospedaliero, non medicalizzato 4 = clinica psichiatrica, altro istituto 44 = reparto psichiatrico / clinica psichiatrica, stesso istituto 5 = clinica di riabilitazione, altro istituto 55 = reparto di riabilitazione / clinica di riabilitazione, stesso istituto 6 = altro istituto ospedaliero (ospedale acuto) o casa per partorienti 66 = reparto acuto / ospedale acuto, stesso istituto 7 = penitenziario 8 = altro 9 = sconosciuto 0 = decesso</td></tr>
<tr><td>Inizio dell’episodio</td><td>episode\_beginn</td><td>Data (senza l’ora), solo per dimissioni intermedie / riammissioni (episode\_art = 2)</td></tr>
<tr><td>Fine dell’episodio</td><td>episode\_ende</td><td>Data (senza l’ora), solo per dimissioni intermedie / riammissioni (episode\_art = 2)</td></tr>
<tr><td>Luogo di residenza dopo la dimissione intermedia</td><td>wiedereintritt aufenthalt</td><td>1 = domicilio 2 = casa di cura (comprese case per anziani medicalizzate) 3 = altro istituto sanitario non ospedaliero, non medicalizzato 4 = clinica psichiatrica, altro istituto 44 = reparto psichiatrico / clinica psichiatrica, stesso istituto 5 = clinica di riabilitazione, altro istituto 55 = reparto di riabilitazione / clinica di riabilitazione, stesso istituto 6 = altro istituto ospedaliero (ospedale acuto) o casa per partorienti 66 = reparto acuto / ospedale acuto, stesso istituto 7 = penitenziario 8 = altro 9 = sconosciuto</td></tr>
<tr><td>Età di gestazione, mestruazione</td><td>gestationsalter1</td><td>Età di gestazione della madre, mestruazione</td></tr>
<tr><td>Età di gestazione, ecografia</td><td>gestationsalter2</td><td>[tab] Età di gestazione, ecografia</td></tr>
<tr><td>Istanza ricoverante</td><td>einw\_instanz</td><td>1 = paziente stesso, familiare 2 = servizio di soccorso (ambulanza, polizia) 3 = medico 4 = terapista non medico 5 = servizio sociosanitario 6 = autorità giudiziarie 8 = altro 9 = sconosciuto</td></tr>
<tr><td>Classe di degenza</td><td>liegeklasse</td><td>1 = comune 2 = semiprivata 3 = privata 9 = sconosciuto</td></tr>
</table>
