---
status: "beschlossen, noch nicht in Kraft"
reference: AS 2024 194
title: Ordinanza del DFI sulla cartella informatizzata del paziente (OCIP-DFI)
language: it
adopted: 2024-04-24
published: 2024-05-06
in_force: ["2024-06-01"]
url: "https://www.fedlex.admin.ch/eli/oc/2024/194/it"
---

> Riproduzione non ufficiale della Raccolta ufficiale (RU). L’atto è pubblicato ma non ancora in vigore; fa stato la pubblicazione nella RU (art. 15 LPubb, RS 170.512).

# Ordinanza del DFI sulla cartella informatizzata del paziente

(OCIP-DFI)

Modifica del 24 aprile 2024

Il Dipartimento federale dell’interno (DFI)

ordina:

## I

L’ordinanza del DFI del 22 marzo 2017[^lvlI-1] sulla cartella informatizzata del paziente è modificata come segue:

***Art. 8d* Disposizione transitoria della modifica del 24 aprile 2024**

Fino al 31 maggio 2025 le comunità e le comunità di riferimento non sono tenute ad attuare la modifica del 24 aprile 2024.

[^lvlI-1]: [RS 816.111](https://fedlex.data.admin.ch/eli/cc/2017/205)

## II

<sup>1</sup> Gli allegati 2–4 e 8[^lvlII-1] sono modificati.

<sup>2</sup> Gli allegati 5 e 6 sono sostituiti dalla versione qui annessa.

[^lvlII-1]: Il contenuto di questi allegati è pubblicato nella RU e nella RS soltanto mediante rimando. Può essere consultato all’indirizzo: [https://fedlex.data.admin.ch/eli/oc/2024/194](https://fedlex.data.admin.ch/eli/oc/2024/194) &gt; Informazioni generali &gt; Portata della pubblicazione &gt; Pubblicazione di una parte di testo mediante rimando.

## III

La presente ordinanza entra in vigore il 1° giugno 2024.

<table>
<tr><td>24 aprile 2024</td><td>Dipartimento federale dell’interno: Elisabeth Baume-Schneider</td></tr>
</table>

Allegato 5

(art. 5)

## Profili d’integrazione

### 1 Profili d’integrazione IHE

[^annex5-lvlu1-lvl1-1]

[^annex5-lvlu1-lvl1-1]: Integrating the Healthcare Enterprise.

<table>
<tr><th>Profilo d’integrazione</th><th>Documento tecnico</th><th>Attori</th><th>Transazioni</th><th>Adeguamenti nazionali</th></tr>
<tr><td>ATNA</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Secure Application Secure Node Audit Record Repository</td><td>Authenticate Node [ITI‑19] Record Audit Event [ITI‑20]</td><td>Allegato 5 complemento 1[^annex5-lvlu1-lvl1-2] OCIP‑DFI, edizione 7</td></tr>
<tr><td></td><td>IHE IT Infrastructure Technical Framework Supplement, Add RESTful ATNA (Query and Feed), Revision 3.3, July 2, 2021</td><td>Audit Consumer Audit Record Repository</td><td>Retrieve ATNA Audit Event [ITI‑81]</td><td>Allegato 5 complemento 2.2[^annex5-lvlu1-lvl1-3] OCIP‑DFI, profilo d’integrazione Audit Trail Consumption (CH:ATC), edizione 5</td></tr>
<tr><td>CT</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Time Client Time Server</td><td>Maintain Time [ITI‑1]</td><td>No</td></tr>
<tr><td>HPD</td><td>IHE IT Infrastructure Technical Framework, Supplement Healthcare Provider Directory (HPD), Revision 1.8, August 28, 2020</td><td>Provider Information Source Provider Information Consumer Provider Information Directory</td><td>Provider Information Query [ITI‑58] Provider Information Feed [ITI‑59] Provider Information Delta Download (CH:PIDD)</td><td>Allegato 5 complemento 1 OCIP‑DFI, edizione 7</td></tr>
<tr><td>IUA</td><td>IHE IT Infrastructure Technical Framework, Supplement Internet User Authorization (IUA), Revision 2.2, June 17, 2022</td><td>Authorization Client Resource Server</td><td>Incorporate Authorization Token [ITI‑72]</td><td>No</td></tr>
<tr><td>PCC</td><td>IHE Patient Care Coordination (PCC) Technical Framework, Volume 2, Revision 11.1, April 14, 2021</td><td>Content Creator Content Consumer</td><td></td><td>No</td></tr>
<tr><td>PDQV3</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Patient Demographics Consumer Patient Demographics Supplier</td><td>Patient Demographics Query HL7 V3 [ITI‑47]</td><td>Allegato 5 complemento 1 OCIP‑DFI, edizione 7</td></tr>
<tr><td>PIXV3</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Patient Identity Source Patient Identifier Cross-reference Consumer Patient Identifier Cross-reference Manager</td><td>Patient Identity Feed HL7 V3 [ITI‑44] PIXV3 Query [ITI‑45] PIXV3 Update Notification [ITI‑46]</td><td>Allegato 5 complemento 1 OCIP‑DFI, edizione 7</td></tr>
<tr><td>RMU</td><td>IHE IT Infrastructure Technical Framework, Supplement Restricted Metadata Update (RMU), Revision 1.3, July 2, 2021</td><td>Update Initiator Update Responder</td><td>Restricted Update Document Set [ITI‑92]</td><td>Allegato 5 complemento 1 OCIP‑DFI, edizione 7</td></tr>
<tr><td>SVS</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Value Set Consumer Value Set Repository</td><td>Retrieve Value Set [ITI‑48]</td><td>No</td></tr>
<tr><td>XCA</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Initiating Gateway Responding Gateway</td><td>Cross Gateway Query [ITI‑38] Cross Gateway Retrieve [ITI‑39]</td><td>Allegato 5 complemento 1 OCIP‑DFI, edizione 7</td></tr>
<tr><td>XCA-I</td><td>IHE Radiology Technical Framework, Volume 3 (RAD‑TF‑3), Cross-Transaction Specifications and Content Specifications, Revision 20.0, March 10, 2022</td><td>Initiating Imaging Gateway Responding Imaging Gateway</td><td>Cross Gateway Retrieve Image Document Set [RAD‑75]</td><td>No</td></tr>
<tr><td>XCPD</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Initiating Gateway Responding Gateway</td><td>Cross Gateway Patient Discovery [ITI‑55]</td><td>Allegato 5 complemento 1 OCIP‑DFI, edizione 7</td></tr>
<tr><td>XDM</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Portable Media Creator Portable Media Importer</td><td>Distribute Document Set on Media [ITI‑32]</td><td>No</td></tr>
<tr><td>XDS</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Document Consumer Document Source Document Repository Document Registry Patient Identity Source</td><td>Registry Stored Query [ITI‑18] Provide and Register Document Set‑b [ITI‑41] Register Document Set‑b [ITI‑42] Retrieve Document Set [ITI‑43] Patient Identity Feed HL7v3 [ITI‑44]</td><td>Allegato 5 complemento 1 OCIP‑DFI, edizione 7</td></tr>
<tr><td>XDS-I.b</td><td>IHE Radiology Technical Framework, Volume 3 (RAD‑TF 3), Cross-Transaction Specifications and Content Specifications, Revision 20.0, March 10, 2022</td><td>Imaging Document Source Imaging Document Consumer</td><td>Provide & Register Imaging Document Set – MTOM/XOP [RAD‑68] Retrieve Imaging Document Set [RAD‑69]</td><td>Allegato 5 complemento 1 OCIP‑DFI, edizione 7</td></tr>
<tr><td>XDS Metadata Update</td><td>IHE IT Infrastructure Technical Framework, Supplement XDS Metadata Update, Revision 1.13, June 17, 2022</td><td>Document Administrator Document Registry</td><td>Update Document Set [ITI‑57]</td><td>Allegato 5 complemento 1 OCIP‑DFI, edizione 7</td></tr>
<tr><td>XUA</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>X-Service User X-Service Provider X-Assertion Provider User Authentication Provider</td><td>Authenticate User Get X‑User Assertion Provide X‑User Assertion [ITI‑40]</td><td>Allegato 5 complemento 1 OCIP‑DFI, edizione 7</td></tr>
</table>

[^annex5-lvlu1-lvl1-2]: Il contenuto dell’allegato 5 complemento 1 può essere consultato all’indirizzo: [https://fedlex.data.admin.ch/eli/oc/2024/194](https://fedlex.data.admin.ch/eli/oc/2024/194) &gt; Informazioni generali &gt; Portata della pubblicazione &gt; Pubblicazione di una parte di testo mediante rimando.
[^annex5-lvlu1-lvl1-3]: Il contenuto dell’allegato 5 complemento 2.2 può essere consultato all’indirizzo: [https://fedlex.data.admin.ch/eli/oc/2024/194](https://fedlex.data.admin.ch/eli/oc/2024/194) &gt; Informazioni generali &gt; Portata della pubblicazione &gt; Pubblicazione di una parte di testo mediante rimando.

### 2 Profili d’integrazione nazionali

<table>
<tr><th>Profilo d’integrazione</th><th>Documento tecnico</th><th>Attori</th><th>Transazioni</th></tr>
<tr><td>CH:ADR</td><td>Allegato 5 complemento 2.1[^annex5-lvlu1-lvl2-1] OCIP‑DFI, profilo d’integrazione Authorization Decision Request (CH:ADR), edizione 6</td><td>Authorization Decision Provider Authorization Decision Consumer</td><td>Authorization Decision Request (CH:ADR)</td></tr>
<tr><td>CH:ATC</td><td>Allegato 5 complemento 2.2 OCIP‑DFI, profilo d’integrazione Audit Trail Consumption (CH:ATC), edizione 5</td><td>Patient Audit Consumer Patient Audit Record Repository</td><td>Retrieve ATNA Audit Event [ITI‑81]</td></tr>
<tr><td>CH:CPI</td><td>Allegato 5 complemento 2.3[^annex5-lvlu1-lvl2-2] OCIP‑DFI, profilo d’integrazione Community Portal Index (CH:CPI), edizione 6</td><td>CH:CPI Consumer CH:CPI Provider</td><td>Community Information Query (CH:CIQ) Community Information Delta Download (CH:CIDD)</td></tr>
<tr><td>CH:PPQ</td><td>Allegato 5 complemento 2.1 OCIP‑DFI, profilo d’integrazione Privacy Policy Query (CH:PPQ), edizione 6</td><td>Policy Source Policy Repository Policy Consumer</td><td>Privacy Policy Feed (CH:PPQ‑1) Privacy Policy Retrieve (CH:PPQ‑2)</td></tr>
</table>

[^annex5-lvlu1-lvl2-1]: Il contenuto dell’allegato 5 complemento 2.1 può essere consultato all’indirizzo: [https://fedlex.data.admin.ch/eli/oc/2024/194](https://fedlex.data.admin.ch/eli/oc/2024/194) &gt; Informazioni generali &gt; Portata della pubblicazione &gt; Pubblicazione di una parte di testo mediante rimando.
[^annex5-lvlu1-lvl2-2]: Il contenuto dell’allegato 5 complemento 2.3 può essere consultato all’indirizzo: [https://fedlex.data.admin.ch/eli/oc/2024/194](https://fedlex.data.admin.ch/eli/oc/2024/194) &gt; Informazioni generali &gt; Portata della pubblicazione &gt; Pubblicazione di una parte di testo mediante rimando.

Allegato 6

(art. 6)

## Valutazione e ricerca

### 1 Disposizioni generali

- 1\.1

  I metadati di cui all’allegato 3 devono essere utilizzati per:

  - a. il tipo di organizzazione della struttura sanitaria (n. 2.3);
  - b. la classe di documenti (n. 2.5);
  - c. il tipo di documenti (n. 2.6);
  - d. il ruolo della persona responsabile della messa a disposizione iniziale (n. 2.14).

- 1\.2 Sono applicate le classi di età quinquennali (0–4; 5–9; 10–14 … 95–99; 100+ anni).

### 2 Dati che devono essere raccolti dalle comunità

- 2\.1

  Numero dei documenti messi a disposizione attraverso la cartella informatizzata del paziente, suddivisi per:

  - a. tipo di organizzazione della struttura sanitaria;
  - b. classe di documenti;
  - c. tipo di documenti;
  - d. ruolo della persona responsabile della messa a disposizione iniziale.

- 2\.2 Numero dei documenti registrati in un formato standardizzato di scambio secondo l’allegato 4, suddivisi per tipo di struttura sanitaria.
- 2\.3

  Numero dei documenti per grado di riservatezza secondo l’articolo 1 OCIP, suddivisi per:

  - a. tipo di organizzazione della struttura sanitaria;
  - b. classe di documenti;
  - c. tipo di documenti;
  - d. ruolo della persona responsabile della messa a disposizione iniziale.

- 2\.4

  Numero delle consultazioni dei documenti messi a disposizione, suddivise per:

  - a. numero di accessi in situazioni di emergenza medica;
  - b. tipo di organizzazione della struttura sanitaria che accede ai documenti;
  - c. ruolo della persona responsabile della messa a disposizione iniziale che accede ai documenti.

### 3 Dati supplementari che devono essere raccolti dalle comunità di riferimento

- 3\.1

  Numero delle persone che dispongono di una cartella informatizzata del paziente, suddivise per:

  - a. Cantone;
  - b. sesso in combinazione con la classe di età.

- 3\.2

  Numero di revoche dei consensi per la tenuta di una cartella informatizzata del paziente, suddivise per:

  - a. Cantone;
  - b. sesso in combinazione con la classe di età.

- 3\.3

  Numero degli adeguamenti ai diritti d’accesso, suddivisi per sesso in combinazione con la classe di età del paziente, effettuati per:

  - a. stabilire il grado di riservatezza da attribuire ai nuovi dati medici registrati secondo l’articolo 4 lettera a OCIP;
  - b. negare ai singoli professionisti della salute l’accesso alla sua cartella informatizzata secondo l’articolo 4 lettera b OCIP;
  - c. essere informati sull’adesione di professionisti della salute ai gruppi secondo l’articolo 4 lettera c OCIP;
  - d. fissare la scadenza dei diritti d’accesso secondo l’articolo 4 lettera d OCIP;
  - e. estendere il diritto d’accesso in caso di situazioni di emergenza medica al grado di riservatezza «limitatamente accessibile» secondo l’articolo 4 lettera e OCIP;
  - f. negare l’accesso in caso di situazioni di emergenza medica secondo l’articolo 4 lettera e OCIP;
  - g. autorizzare un professionista della salute della sua comunità di riferimento a trasferire i diritti d’accesso ad esso accordati secondo l’articolo 4 lettera g OCIP ad altri professionisti della salute o gruppi di professionisti della salute.

- 3\.4 Numero di pazienti che non hanno effettuato adeguamenti ai diritti d’accesso, suddivisi per sesso in combinazione con la classe di età.
- 3\.5 Numero dei professionisti della salute e gruppi di professionisti della salute con diritti d’accesso, suddivisi per cartella informatizzata del paziente.
- 3\.6 Numero delle persone che hanno nominato un rappresentante secondo l’articolo 4 lettera f OCIP, suddivise per sesso in combinazione con la classe di età.
