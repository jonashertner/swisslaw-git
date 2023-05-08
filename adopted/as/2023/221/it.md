---
status: "beschlossen, noch nicht in Kraft"
reference: AS 2023 221
title: Ordinanza del DFI sulla cartella informatizzata del paziente (OCIP-DFI)
language: it
adopted: 2023-05-04
published: 2023-05-09
in_force: ["2023-06-01"]
url: "https://www.fedlex.admin.ch/eli/oc/2023/221/it"
---

> Riproduzione non ufficiale della Raccolta ufficiale (RU). L’atto è pubblicato ma non ancora in vigore; fa stato la pubblicazione nella RU (art. 15 LPubb, RS 170.512).

# Ordinanza del DFI sulla cartella informatizzata del paziente

(OCIP-DFI)

Modifica del 4 maggio 2023

Il Dipartimento federale dell’interno (DFI)

ordina:

## I

L’ordinanza del DFI del 22 marzo 2017[^lvlI-1] sulla cartella informatizzata del paziente è modificata come segue:

*Art. 8c* Disposizione transitoria della modifica del 4 maggio 2023

Fino al 31 maggio 2024 le comunità e le comunità di riferimento non sono tenute ad attuare la modifica del 4 maggio 2023.

[^lvlI-1]: [RS 816.111](https://fedlex.data.admin.ch/eli/cc/2017/205)

## II

<sup>1</sup> Gli allegati 2–4, 8 e 9 sono modificati[^lvlII-1].

<sup>2</sup> L’allegato 5 è sostituito dalla versione qui annessa.

[^lvlII-1]: Il contenuto di questi allegati è pubblicato nella RU e nella RS soltanto mediante rimando. Può essere consultato all’indirizzo: [https://fedlex.data.admin.ch/eli/oc/2023/221](https://fedlex.data.admin.ch/eli/oc/2023/221) &gt; Informazioni generali &gt; Portata della pubblicazione &gt; Pubblicazione di una parte di testo mediante rimando.

## III

La presente ordinanza entra in vigore il 1° giugno 2023.

<table>
<tr><td>4 maggio 2023</td><td>Dipartimento federale dell’interno: Alain Berset</td></tr>
</table>

Allegato 5

(art. 5)

## Profili d’integrazione

### 1 Profili d’integrazione IHE

[^annex5-lvlu1-lvl1-1]

[^annex5-lvlu1-lvl1-1]: Integrating the Healthcare Enterprise.

<table>
<tr><th>Profilo d’integrazione</th><th>Documento tecnico</th><th>Attori</th><th>Transazioni</th><th>Adeguamenti nazionali</th></tr>
<tr><td>ATNA</td><td>IHE IT Infrastructure Technical Framework, Volume 2a (ITI TF-2a), Revision 15.0, July 24, 2018</td><td>Secure Application Secure Node Audit Record Repository</td><td>Authenticate Node [ITI-19] Record Audit Event [ITI-20]</td><td>Allegato 5 complemen-to 1[^annex5-lvlu1-lvl1-2] OCIP‑DFI, edizione 6</td></tr>
<tr><td></td><td>IHE IT Infrastructure Technical Framework Supplement, Add RESTful ATNA (Query and Feed), Revision 3.3, July 2, 2021</td><td>Audit Consumer Audit Record Repository</td><td>Retrieve ATNA Audit Event [ITI-81]</td><td>Allegato 5 complemento 2.2[^annex5-lvlu1-lvl1-3] OCIP-DFI, profilo d’integrazione Audit Trail Consumption (CH:ATC), edizione 4</td></tr>
<tr><td>CT</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Time Client Time Server</td><td>Maintain Time [ITI‑1]</td><td>No</td></tr>
<tr><td>HPD</td><td>IHE IT Infrastructure Technical Framework, Supplement Healthcare Provider Directory (HPD), Revision 1.8, August 28, 2020</td><td>Provider Information Source Provider Information Consumer Provider Information Directory</td><td>Provider Information Query [ITI‑58] Provider Information Feed [ITI-59] Provider Information Delta Download (CH:PIDD)</td><td>Allegato 5 complemen-to 1 OCIP-DFI, edizione 6</td></tr>
<tr><td>IUA</td><td>IHE IT Infrastructure Technical Framework, Supplement Internet User Authorization (IUA), Revision 2.2, June 17, 2022</td><td>Authorization Client Resource Server</td><td>Incorporate Authorization Token [ITI-72]</td><td>No</td></tr>
<tr><td>PDQV3</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Patient Demographics Consumer Patient Demographics Supplier</td><td>Patient Demographics Query HL7 V3 [ITI-47]</td><td>Allegato 5 complemen-to 1 OCIP-DFI, edizione 6</td></tr>
<tr><td>PIXV3</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Patient Identity Source Patient Identifier Cross- reference Consumer Patient Identifier Cross-reference Manager</td><td>Patient Identity Feed HL7 V3 [ITI‑44] PIXV3 Query [ITI‑45] PIXV3 Update Notification [ITI-46]</td><td>Allegato 5 complemen-to 1 OCIP-DFI, edizione 6</td></tr>
<tr><td>RMU</td><td>IHE IT Infrastructure Technical Framework, Supplement Restricted Metadata Update (RMU), Revision 1.3, July 2, 2021</td><td>Update Initiator Update Responder</td><td>Restricted Update Document Set [ITI‑92]</td><td>Allegato 5 complemen-to 1 OCIP-DFI, edizione 6</td></tr>
<tr><td>SVS</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Value Set Consumer Value Set Repository</td><td>Retrieve Value Set [ITI-48]</td><td>No</td></tr>
<tr><td>XCA</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Initiating Gateway Responding Gateway</td><td>Cross Gateway Query [ITI-38] Cross Gateway Retrieve [ITI-39]</td><td>Allegato 5 complemen-to 1 OCIP-DFI, edizione 6</td></tr>
<tr><td>XCA-I</td><td>IHE Radiology Technical Framework, Volume 3 (RAD‑TF-3), Cross-Transaction Specifications and Content Specifications, Revision 20.0, March 10, 2022</td><td>Initiating Imaging Gateway Responding Imaging Gateway</td><td>Cross Gateway Retrieve Image Document Set [RAD-75]</td><td>No</td></tr>
<tr><td>XCPD</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Initiating Gateway Responding Gateway</td><td>Cross Gateway Patient Discovery [ITI-55]</td><td>Allegato 5 complemen-to 1 OCIP-DFI, edizione 6</td></tr>
<tr><td>XDM</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Portable Media Creator Portable Media Importer</td><td>Distribute Document Set on Media [ITI‑32]</td><td>No</td></tr>
<tr><td>XDS</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>Document Consumer Document Source Document Repository Document Registry Patient Identity Source</td><td>Registry Stored Query [ITI-18] Provide and Register Document Set-b [ITI-41] Register Document Set-b [ITI-42] Retrieve Document Set [ITI-43] Patient Identity Feed HL7v3 [ITI-44]</td><td>Allegato 5 complemen-to 1 OCIP-DFI, edizione 6</td></tr>
<tr><td>XDS-I.b</td><td>IHE Radiology Technical Framework, Volume 3 (RAD‑TF-3), Cross-Transaction Specifications and Content Specifications, Revision 20.0, March 10, 2022</td><td>Imaging Document Source Imaging Document Consumer</td><td>Provide & Register Imaging Document Set – MTOM/XOP [RAD-68] Retrieve Imaging Document Set [RAD-69]</td><td>Allegato 5 complemen-to 1 OCIP-DFI, edizione 6</td></tr>
<tr><td>XDS Metadata Update</td><td>IHE IT Infrastructure Technical Framework, Supplement XDS Metadata Update, Revision 1.13, June 17, 2022</td><td>Document Administrator Document Registry</td><td>Update Document Set [ITI-57]</td><td>Allegato 5 complemen-to 1 OCIP-DFI, edizione 6</td></tr>
<tr><td>XUA</td><td>IHE IT Infrastructure Technical Framework, Volume 2, Revision 19.0, June 17, 2022</td><td>X-Service User X-Service Provider X-Assertion Provider User Authentication Provider</td><td>Authenticate User Get X-User Assertion Provide X-User Assertion [ITI-40]</td><td>Allegato 5 complemen-to 1 OCIP-DFI, edizione 6</td></tr>
</table>

[^annex5-lvlu1-lvl1-2]: Il contenuto dell’allegato 5 complemento 1 può essere consultato all’indirizzo: [https://fedlex.data.admin.ch/eli/oc/2023/221](https://fedlex.data.admin.ch/eli/oc/2023/221) &gt; Informazioni generali &gt; Portata della pubblicazione &gt; Pubblicazione di una parte di testo mediante rimando.
[^annex5-lvlu1-lvl1-3]: Il contenuto dell’allegato 5 complemento 2.2 può essere consultato all’indirizzo: [https://fedlex.data.admin.ch/eli/oc/2023/221](https://fedlex.data.admin.ch/eli/oc/2023/221) &gt; Informazioni generali &gt; Portata della pubblicazione &gt; Pubblicazione di una parte di testo mediante rimando.

### 2 Profili d’integrazione nazionali

<table>
<tr><th>Profilo d’integrazione</th><th>Documento tecnico</th><th>Attori</th><th>Transazioni</th></tr>
<tr><td>CH:ADR</td><td>Allegato 5 complemento 2.1[^annex5-lvlu1-lvl2-1] OCIP-DFI, profilo d’integrazione Authorization Decision Request (CH:ADR), edizione 5</td><td>Authorization Decision Provider Authorization Decision Consumer</td><td>Authorization Decision Request (CH:ADR)</td></tr>
<tr><td>CH:ATC</td><td>Allegato 5 complemento 2.2 OCIP-DFI, profilo d’integrazione Audit Trail Consumption (CH:ATC), edizione 4</td><td>Patient Audit Consumer Patient Audit Record Repository</td><td>Retrieve ATNA Audit Event [ITI-81]</td></tr>
<tr><td>CH:CPI</td><td>Allegato 5 complemento 2.3[^annex5-lvlu1-lvl2-2] OCIP-DFI, profilo d’integrazione Community Portal Index (CH:CPI), edizione 5</td><td>CH:CPI Consumer CH:CPI Provider</td><td>Community Information Query (CH:CIQ) Community Information Delta Download (CH:CIDD)</td></tr>
<tr><td>CH:PPQ</td><td>Allegato 5 comple-mento 2.1 OCIP-DFI, profilo d’integrazione Privacy Policy Query (CH:PPQ), edizione 5</td><td>Policy Source Policy Repository Policy Consumer</td><td>Privacy Policy Feed (CH:PPQ-1) Privacy Policy Retrieve (CH:PPQ-2)</td></tr>
</table>

[^annex5-lvlu1-lvl2-1]: Il contenuto dell’allegato 5 complemento 2.1 può essere consultato all’indirizzo: [https://fedlex.data.admin.ch/eli/oc/2023/221](https://fedlex.data.admin.ch/eli/oc/2023/221) &gt; Informazioni generali &gt; Portata della pubblicazione &gt; Pubblicazione di una parte di testo mediante rimando.
[^annex5-lvlu1-lvl2-2]: Il contenuto dell’allegato 5 complemento 2.3 può essere consultato all’indirizzo: [https://fedlex.data.admin.ch/eli/oc/2023/221](https://fedlex.data.admin.ch/eli/oc/2023/221) &gt; Informazioni generali &gt; Portata della pubblicazione &gt; Pubblicazione di una parte di testo mediante rimando.
