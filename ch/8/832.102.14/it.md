---
sr: "832.102.14"
title: Ordinanza del DFI del 20 novembre 2012 sugli insiemi di dati per la trasmissione dei dati tra fornitori di prestazioni e assicuratori
eli: "https://fedlex.data.admin.ch/eli/cc/2012/867"
language: it
version: 2023-07-01
adopted: 2012-11-20
in_force: 2013-01-01
source: "https://fedlex.data.admin.ch/filestore/fedlex.data.admin.ch/eli/cc/2012/867/20230701/it/xml/fedlex-data-admin-ch-eli-cc-2012-867-20230701-it-xml-4.xml"
url: "https://www.fedlex.admin.ch/eli/cc/2012/867/20230701/it"
---

> Riproduzione non ufficiale della versione consolidata (Fedlex). Fa stato la pubblicazione nella Raccolta ufficiale (art. 15 LPubb, RS 170.512).

# Ordinanza del DFI sugli insiemi di dati per la trasmissione dei dati tra fornitori di prestazioni e assicuratori

del 20 novembre 2012 (Stato 1° luglio 2023)

Il Dipartimento federale dell’interno (DFI),

visto l’articolo 59*a* capoverso 1 dell’ordinanza del 27 giugno 1995[^ingress-1] sull’assicurazione malattie (OAMal),

ordina:

[^ingress-1]: [RS 832.102](https://fedlex.data.admin.ch/eli/cc/1995/3867_3867_3867)

#### Art. 1

La struttura degli insiemi di dati di cui all’articolo 59*a* capoverso 1 OAMal è definita nell’allegato 1.

#### Art. 2

La presente ordinanza entra in vigore il 1° gennaio 2013.

Allegato[^t-1]

(art. 1)

## Struttura uniforme degli insiemi di dati valida in tutta la Svizzera

[^t-1]: Aggiornato dal n. I dell’O del DFI del 3 dic. 2021 ([RU 2021 839](https://fedlex.data.admin.ch/eli/oc/2021/839)) e dall’all. dell’O del DFI del 16 giu. 2023, in vigore dal 1° lug. 2023 ([RU 2023 313](https://fedlex.data.admin.ch/eli/oc/2023/313)).

### 1 In generale

### 1.1 Abbreviazioni e definizioni

CHOP Classificazione svizzera degli interventi chirurgici

GM German Modification

Statistica medica Statistica medica degli stabilimenti ospedalieri di cui al numero 62 dell’allegato dell’ordinanza del 30 giugno 1993[^annexu1-lvlu1-lvl1-lvl11-1] sull’esecuzione di rilevazioni statistiche federali

ICD-10 Classificazione statistica internazionale delle malattie e dei problemi sanitari correlati

[^annexu1-lvlu1-lvl1-lvl11-1]: [RS 431.012.1](https://fedlex.data.admin.ch/eli/cc/1993/2100_2100_2100)

### 1.2 Insieme di dati medici

<table>
<tr><th>Denominazione</th><th>Variabile della statistica medica</th><th>Contenuto</th></tr>
<tr><td>Peso alla nascita</td><td>2.2.V04</td><td>In grammi</td></tr>
<tr><td>Diagnosi principale</td><td>4.2.V010</td><td>Codice ICD-10-GM</td></tr>
<tr><td>Complemento alla diagnosi principale</td><td>4.2.V020</td><td>Codice ICD-10-GM</td></tr>
<tr><td>1<sup>a</sup> – 49<sup>a</sup> diagnosi secondaria</td><td>4.2.V030, 4.2.V040 ecc. fino a 4.2.V510</td><td>Codice ICD-10-GM</td></tr>
<tr><td>Trattamento principale</td><td>4.3.V010</td><td>Codice CHOP</td></tr>
<tr><td>Lateralità del trattamento principale</td><td>4.3.V011</td><td>0 = da ambo i lati 1 = unilaterale a destra 2 = unilaterale a sinistra 3 = unilaterale, lato sconosciuto 9 = sconosciuto vuoto = non applicabile</td></tr>
<tr><td>Inizio del trattamento principale</td><td>4.3.V015</td><td>Data (con indicazione dell’ora)</td></tr>
<tr><td>1° – 99° trattamento secondario</td><td>4.3.V020, 4.3.V030 ecc. fino a 4.3.V1000</td><td>Codice CHOP</td></tr>
<tr><td>1° – 99° trattamento secondario, lateralità</td><td>4.3.V021, 4.3.V031 ecc. fino a 4.3.V1001</td><td>0 = da ambo i lati 1 = unilaterale a destra 2 = unilaterale a sinistra 3 = unilaterale, lato sconosciuto 9 = sconosciuto vuoto = non applicabile</td></tr>
<tr><td>1° – 99° trattamento secondario, inizio</td><td>4.3.V025, 4.3.V035 ecc. fino a 4.3.V1005</td><td>Data (con indicazione dell’ora)</td></tr>
<tr><td>Durata della respirazione artificiale</td><td>4.4.V01</td><td>Numero di ore</td></tr>
<tr><td>Peso all’ammissione</td><td>4.5.V01</td><td>In grammi</td></tr>
<tr><td>Chiarimento garante</td><td>2.2.V06</td><td>0 = no 1 = sì 9 = sconosciuto</td></tr>
<tr><td>Motivazione della degenza in ospedale</td><td>–</td><td>Secondo la colonna «N.» dell’allegato 1*a* cifra II dell’ordinanza del 29 settembre 1995[^annexu1-lvlu1-lvl1-lvl12-1] sulle prestazioni</td></tr>
</table>

[^annexu1-lvlu1-lvl1-lvl12-1]: [RS 832.112.31](https://fedlex.data.admin.ch/eli/cc/1995/4964_4964_4964)

### 1.3 Insieme di dati amministrativi

<table>
<tr><th>Denominazione</th><th>Variabile della statistica medica</th><th>Descrizione</th></tr>
<tr><td>Sesso</td><td>1.1.V01</td><td>1 = uomo 2 = donna</td></tr>
<tr><td>Data di nascita</td><td>1.1.V02</td><td>Indicazione della data</td></tr>
<tr><td>Età all’ammissione</td><td>1.1.V03</td><td>Età esatta</td></tr>
<tr><td>Data e ora di ammissione</td><td>1.2.V01</td><td></td></tr>
<tr><td>Luogo di soggiorno prima dell’ammissione</td><td>1.2.V02</td><td>1 = domicilio 2 = domicilio con assistenza Spitex 3 = casa di cura 4 = casa per anziani, altro stabilimento sanitario non ospedaliero 5 = clinica psichiatrica, altro istituto 55 = reparto psichiatrico / clinica psichiatrica, stesso istituto 6 = altro stabilimento ospedaliero (ospedale acuto) o casa per partorienti 66 = reparto acuto / ospedale acuto, stesso istituto 7 = penitenziario 8 = altro 83 = clinica di riabilitazione, altro istituto 84 = reparto di riabilitazione / clinica di riabilitazione, stesso istituto 9 = sconosciuto</td></tr>
<tr><td>Genere di ricovero</td><td>1.2.V03</td><td>1 = urgenza (necessità di trattamento entro 12 ore) 2 = annunciato, pianificato 3 = parto (bambino nato nello stabilimento) 4 = trasferimento interno 5 = trasferimento entro 24 ore 8 = altro 9 = sconosciuto</td></tr>
<tr><td>Congedo amministrativo e vacanze</td><td>1.3.V04</td><td>Ore complete</td></tr>
<tr><td>Centro di costo principale</td><td>1.4.V01</td><td>M000 = specializzazioni mediche (in generale) M050 = medicina intensiva M100 = medicina interna M200 = chirurgia M300 = ginecologia e ostetricia M400 = pediatria M500 = psichiatria e psicoterapia M600 = oftalmologia M700 = otorinolaringoiatria M800 = dermatologia e venereologia M850 = radiologia medica M900 = geriatria M950 = medicina fisica e riabilitazione M960 = centro di pronto soccorso M970 = ambulatorio medico d’urgenza M990 = altri ambiti di attività</td></tr>
<tr><td>Data e ora di uscita</td><td>1.5.V01</td><td></td></tr>
<tr><td>Decisione dell’uscita</td><td>1.5.V02</td><td>1 = su iniziativa del responsabile del trattamento 2 = su iniziativa del paziente (contro il parere del responsabile del trattamento) 3 = su iniziativa di terzi 4 = trasferimento interno 5 = defunto 8 = altro 9 = sconosciuto</td></tr>
<tr><td>Destinazione dopo l’uscita</td><td>1.5.V03</td><td>1 = domicilio 2 = casa di cura 3 = casa per anziani, altro stabilimento sanitario non ospedaliero 4 = clinica psichiatrica, altro istituto 44 = reparto psichiatrico / clinica psichiatrica, stesso istituto 5 = clinica di riabilitazione, altro istituto 55 = reparto di riabilitazione / clinica di riabilitazione, stesso istituto 6 = altro stabilimento ospedaliero (ospedale acuto) o casa per partorienti 66 = reparto acuto / ospedale acuto, stesso istituto 7 = penitenziario 8 = altro 9 = sconosciuto 0 = decesso</td></tr>
<tr><td>1<sup>a</sup> uscita intermedia</td><td>4.7.V01</td><td>Data (senza l’ora)</td></tr>
<tr><td>1<sup>a</sup> riammissione</td><td>4.7.V02</td><td>Data (senza l’ora)</td></tr>
<tr><td>2<sup>a</sup>–4<sup>a</sup> uscita intermedia</td><td>4.7.V11, 4.7.V21 risp. 4.7.V31</td><td>Data (senza l’ora)</td></tr>
<tr><td>2<sup>a</sup>–4<sup>a</sup> riammissione</td><td>4.7.V12, 4.7.V22 risp. 4.7.V32</td><td>Data (senza l’ora)</td></tr>
<tr><td>Altre riammissioni</td><td>4.7.V41</td><td>0 = (default) non più di cinque degenze o quattro riammissioni 1 = più di cinque degenze o quattro riammissioni</td></tr>
<tr><td>Età di gestazione</td><td>4.8.V16</td><td>Codificato</td></tr>
<tr><td>Luogo di soggiorno dopo 1<sup>a</sup> uscita intermedia</td><td>4.8.V17</td><td>1 = domicilio 2 = casa di cura 3 = casa per anziani, altro stabilimento sanitario non ospedaliero 4 = clinica psichiatrica, in un altro istituto 44 = reparto psichiatrico / clinica psichiatrica, nello stesso istituto 5 = clinica di riabilitazione, in un altro istituto 55 = reparto di riabilitazione / clinica di riabilitazione, nello stesso istituto 6 = altro stabilimento ospedaliero (ospedale acuto) o casa per partorienti 66 = reparto acuto / clinica acuta, nello stesso istituto 7 = penitenziario 8 = altro 9 = sconosciuto 0 = decesso</td></tr>
<tr><td>Luogo di soggiorno dopo 2<sup>a</sup> uscita intermedia</td><td>4.8.V18</td><td>1 = domicilio 2 = casa di cura 3 = casa per anziani, altro stabilimento sanitario non ospedaliero 4 = clinica psichiatrica, in un altro istituto 44 = reparto psichiatrico / clinica psichiatrica, nello stesso istituto 5 = clinica di riabilitazione, in un altro istituto 55 = reparto di riabilitazione / clinica di riabilitazione, nello stesso istituto 6 = altro stabilimento ospedaliero (ospedale acuto) o casa per partorienti 66 = reparto acuto / clinica acuta, nello stesso istituto 7 = penitenziario 8 = altro 9 = sconosciuto 0 = decesso</td></tr>
<tr><td>Luogo di soggiorno dopo 3<sup>a</sup> uscita intermedia</td><td>4.8.V19</td><td>1 = domicilio 2 = casa di cura 3 = casa per anziani, altro stabilimento sanitario non ospedaliero 4 = clinica psichiatrica, in un altro istituto 44 = reparto psichiatrico / clinica psichiatrica, nello stesso istituto 5 = clinica di riabilitazione, in un altro istituto 55 = reparto di riabilitazione / clinica di riabilitazione, nello stesso istituto 6 = altro stabilimento ospedaliero (ospedale acuto) o casa per partorienti 66 = reparto acuto / clinica acuta, nello stesso istituto 7 = penitenziario 8 = altro 9 = sconosciuto 0 = decesso</td></tr>
<tr><td>Luogo di soggiorno dopo 4<sup>a</sup> uscita intermedia</td><td>4.8.V20</td><td>1 = domicilio 2 = casa di cura 3 = casa per anziani, altro stabilimento sanitario non ospedaliero 4 = clinica psichiatrica, in un altro istituto 44 = reparto psichiatrico / clinica psichiatrica, nello stesso istituto 5 = clinica di riabilitazione, in un altro istituto 55 = reparto di riabilitazione / clinica di riabilitazione, nello stesso istituto 6 = altro stabilimento ospedaliero (ospedale acuto) o casa per partorienti 66 = reparto acuto / clinica acuta, nello stesso istituto 7 = penitenziario 8 = altro 9 = sconosciuto 0 = decesso</td></tr>
<tr><td>Istanza ricoverante</td><td>1.2.V04</td><td>1 = paziente stesso, familiare 2 = servizio di soccorso (ambulanza, polizia) 3 = medico 4 = terapista non medico 8 = altro 9 = sconosciuto</td></tr>
<tr><td>Genere di trattamento</td><td>1.3.V01</td><td>1 = ambulatoriale 3 = stazionario 9 = sconosciuto</td></tr>
<tr><td>Classe</td><td>1.3.V02</td><td>1 = comune 2 = semiprivata 3 = privata 9 = sconosciuto</td></tr>
<tr><td>Data di nascita della madre</td><td>2.3.V01</td><td>Indicazione della data (anno e mese)</td></tr>
</table>
