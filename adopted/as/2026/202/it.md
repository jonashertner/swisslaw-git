---
status: "beschlossen, noch nicht in Kraft"
reference: AS 2026 202
title: Ordinanza del DFI sulla cartella informatizzata del paziente (OCIP-DFI)
language: it
adopted: 2026-04-30
published: 2026-05-08
in_force: ["2026-06-01"]
url: "https://www.fedlex.admin.ch/eli/oc/2026/202/it"
---

> Riproduzione non ufficiale della Raccolta ufficiale (RU). L’atto è pubblicato ma non ancora in vigore; fa stato la pubblicazione nella RU (art. 15 LPubb, RS 170.512).

# Ordinanza del DFI sulla cartella informatizzata del paziente

(OCIP-DFI)

Modifica del 30 aprile 2026

Il Dipartimento federale dell’interno (DFI)

ordina:

## I

L’ordinanza del DFI del 22 marzo 2017[^lvlI-1] sulla cartella informatizzata del paziente è modificata come segue:

***Art. 8f* Disposizione transitoria della modifica del 30 aprile 2026**

Fino al 31 maggio 2027 gli emittenti di strumenti d’identificazione, le comunità e le comunità di riferimento non sono tenuti ad attuare la modifica del 30 aprile 2026.

[^lvlI-1]: [RS 816.111](https://fedlex.data.admin.ch/vocabulary/legal-taxonomy/9642)

## II

<sup>1</sup> Gli allegati 2, 4, 8 e 9[^lvlII-1] *(concerne soltanto il testo francese)* sono modificati.

<sup>2</sup> L’allegato 5 è sostituito dalla versione qui annessa.

[^lvlII-1]: Il contenuto dei presenti allegati è pubblicato nella RU e nella RS soltanto mediante rimando. Può essere consultato all’indirizzo: [https://fedlex.data.admin.ch/eli/oc/2026/202](https://fedlex.data.admin.ch/eli/oc/2026/202) &gt; Informazioni generali &gt; Portata della pubblicazione &gt; Pubblicazione di una parte di testo mediante rimando.

## III

La presente ordinanza entra in vigore il 1° giugno 2026.

<table>
<tr><td>30 aprile 2026</td><td>Dipartimento federale dell’interno: Elisabeth Baume-Schneider</td></tr>
</table>

Allegato 5

(art. 5)

## Profili d’integrazione

### 1 Profili d’integrazione IHE

[^annex5-lvlu1-lvl1-1]

[^annex5-lvlu1-lvl1-1]: Integrating the Healthcare Enterprise.

<table>
<tr><th>Profilo d’integrazione</th><th>Documento tecnico</th><th>Attori</th><th>Transazioni</th><th>Adeguamenti nazionali</th></tr>
<tr><td>ATNA</td><td>IHE IT Infrastructure Technical Framework[^annex5-lvlu1-lvl1-2], Volume 1, Revision 20.0, August 4, 2023 IHE IT Infrastructure Technical Framework, Volume 2, Revision 20.0, August 4, 2023 (ITI-19), and Revision 20.1, December 12, 2024 (ITI-20)</td><td>Secure Application Secure Node Audit Record Repository</td><td>Authenticate Node [ITI-19] Record Audit Event [ITI-20]</td><td>Allegato 5 complemento 1[^annex5-lvlu1-lvl1-3] OCIP-DFI, edizione 9 RESTful ATNA, CH EPR FHIR (R4)[^annex5-lvlu1-lvl1-4], RESTful ATNA Implementation Guide, Version 5.0.0, 2025-12-18</td></tr>
<tr><td>CT</td><td>IHE IT Infrastructure Technical Framework, Volume 1, Revision 20.0, August 4, 2023 IHE IT Infrastructure Technical Framework, Volume 2, Revision 20.0, August 4, 2023</td><td>Time Client Time Server</td><td>Maintain Time [ITI-1]</td><td>No</td></tr>
<tr><td>HPD</td><td>IHE IT Infrastructure Technical Framework, Supplement Healthcare Provider Directory (HPD), Revision 1.8, August 28, 2020</td><td>Provider Information Source Provider Information Consumer Provider Information Directory</td><td>Provider Information Query [ITI-58] Provider Information Feed [ITI-59] Provider Information Delta Download (CH:PIDD)</td><td>Allegato 5 complemento 1 OCIP-DFI, edizione 9</td></tr>
<tr><td>IUA</td><td>IHE IT Infrastructure Technical Framework, Supplement Internet User Authorization (IUA), Revision 2.3, May 24, 2024</td><td>Authorization Server Authorization Client Resource Server</td><td>Get Access Token [ITI-71] Incorporate Authorization Token [ITI-72] Get Authorization Server Metadata [ITI-103]</td><td>Internet User Authorization (IUA), CH EPR FHIR (R4) Implementation Guide, Version 5.0.0, 2025-12-18</td></tr>
<tr><td>mCSD</td><td>IHE IT Infrastructure Technical Framework, Mobile Care Services Discovery (mCSD) Implementation Guide, Version 4.0.0, 2025-05-21</td><td>Query Client Update Client Data Source Directory</td><td>Find Matching Care Services [ITI-90] Care Services Feed [ITI-130]</td><td>Mobile Care Services Discovery (mCSD), CH EPR FHIR (R4) Implementation Guide, Version 5.0.0, 2025-12-18</td></tr>
<tr><td>MHD</td><td>IHE IT Infrastructure Technical Framework, Mobile access to Health Documents (MHD) Implementation Guide, Version 4.2.2, 2024-05-18</td><td>Document Source Document Recipient Document Consumer Document Responder</td><td>Provide Document Bundle [ITI-65] Find Document References [ITI-67] Retrieve Document [ITI-68] Update Document Metadata [CH:MHD-1]</td><td>Mobile Access to Health Documents (MHD) with XDS on FHIR, CH EPR FHIR (R4) Implementation Guide, Version 5.0.0, 2025-12-18</td></tr>
<tr><td>PCC</td><td>IHE Patient Care Coordination (PCC) Technical Framework, Volume 1, Revision 11.1, November 11, 2016 IHE Patient Care Coordination (PCC) Technical Framework, Volume 2, Revision 11.1, April 14, 2021</td><td>Content Creator Content Consumer</td><td></td><td>Allegato 5 complemento 1 OCIP-DFI, edizione 9</td></tr>
<tr><td>PDQV3</td><td>IHE IT Infrastructure Technical Framework, Volume 1, Revision 20.0, August 4, 2023 IHE IT Infrastructure Technical Framework, Volume 2, Revision 20.1, December 12, 2024</td><td>Patient Demographics Consumer Patient Demographics Supplier</td><td>Patient Demographics Query HL7 V3 [ITI-47]</td><td>Allegato 5 complemento 1 OCIP-DFI, edizione 9</td></tr>
<tr><td>PDQm</td><td>IHE IT Infrastructure Technical Framework, Patient Demographics Query for Mobile (PDQm) Implementation Guide, Version 3.1.0, 2024-12-12</td><td>Patient Demographics Consumer Patient Demographics Supplier</td><td>Patient Demographics Match [ITI-119]</td><td>Patient Demographics Query for Mobile (PDQm), CH EPR FHIR (R4) Implementation Guide, Version 5.0.0, 2025-12-18</td></tr>
<tr><td>PIXV3</td><td>IHE IT Infra-structure Technical Framework, Volume 1, Revision 20.0, August 4, 2023 IHE IT Infrastructure Technical Framework, Volume 2, Revision 20.0, August 4, 2023</td><td>Patient Identity Source Patient Identifier Cross- reference Consumer Patient Identifier Cross- reference Manager</td><td>Patient Identity Feed HL7 V3 [ITI-44] PIXV3 Query [ITI-45]</td><td>Allegato 5 complemento 1 OCIP-DFI, edizione 9</td></tr>
<tr><td>PIXm</td><td>IHE IT Infrastructure Technical Framework, Patient Identifier Cross-referencing for Mobile (PIXm) Implementation Guide, Version 3.0.4, 2024-02-23</td><td>Patient Identity Source Patient Identifier Cross- reference Consumer Patient Identifier Cross- reference Manager</td><td>Mobile Patient Identifier Cross- reference Query [ITI-83] Patient Identity Feed FHIR [ITI-104]</td><td>Patient Identifier Cross-referencing for mobile (PIXm), CH EPR FHIR (R4) Implementation Guide, Version 5.0.0, 2025-12-18</td></tr>
<tr><td>RMU</td><td>IHE IT Infrastructure Technical Framework, Supplement Restricted Metadata Update (RMU), Revision 1.3, July 2, 2021</td><td>Update Initiator Update Responder</td><td>Restricted Update Document Set [ITI‑92]</td><td>Allegato 5 complemento 1 OCIP-DFI, edizione 9</td></tr>
<tr><td>SVS</td><td>IHE IT Infra-structure Technical Framework, Volume 1, Revision 20.0, August 4, 2023 IHE IT Infrastructure Technical Framework, Volume 2, Revision 20.0, August 4, 2023</td><td>Value Set Consumer Value Set Repository</td><td>Retrieve Value Set [ITI-48]</td><td>No</td></tr>
<tr><td>XCA</td><td>IHE IT Infra-structure Technical Framework, Volume 1, Revision 20.1, December 12, 2024 IHE IT Infrastructure Technical Framework, Volume 2, Revision 20.0, August 4, 2023 (ITI-39), and Revision 20.1, December 12, 2024 (ITI-38)</td><td>Initiating Gateway Responding Gateway</td><td>Cross Gateway Query [ITI-38] Cross Gateway Retrieve [ITI-39]</td><td>Allegato 5 complemento 1 OCIP-DFI, edizione 9</td></tr>
<tr><td>XCA-I</td><td>IHE Radiology Technical Framework, Volume 1 (RAD‑TF‑1), Integration Profiles, Revision 23.0, August 8, 2025 IHE Radiology Technical Framework, Volume 2 (RAD-TF-2), Transactions, Revision 23.0, August 8, 2025</td><td>Initiating Imaging Gateway Responding Imaging Gateway</td><td>Cross Gateway Retrieve Image Document Set [RAD-75]</td><td>No</td></tr>
<tr><td>XCPD</td><td>IHE IT Infra-structure Technical Framework, Volume 1, Revision 20.0, August 4, 2023 IHE IT Infrastructure Technical Framework, Volume 2, Revision 20.1, December 12, 2024</td><td>Initiating Gateway Responding Gateway</td><td>Cross Gateway Patient Discovery [ITI-55]</td><td>Allegato 5 complemento 1 OCIP-DFI, edizione 9</td></tr>
<tr><td>XDM</td><td>IHE IT Infra-structure Technical Framework, Volume 1, Revision 20.1, December 12, 2024 IHE IT Infrastructure Technical Framework, Volume 2, Revision 20.1, December 12, 2024</td><td>Portable Media Creator Portable Media Importer</td><td>Distribute Document Set on Media [ITI-32]</td><td>No</td></tr>
<tr><td>XDS</td><td>IHE IT Infra-structure Technical Framework, Volume 1, Revision 20.1, December 12, 2024 IHE IT Infrastructure Technical Framework, Volume 2, Revision 20.0, August 4, 2023 (ITI-42, ITI-43, ITI-44), and Revision 20.1, December 12, 2024 (ITI-18, ITI-41) IHE IT Infra-structure Technical Framework, Volume 3, Revision 20.1, December 12, 2024</td><td>Document Consumer Document Source Document Repository Document Registry Patient Identity Source</td><td>Registry Stored Query [ITI-18] Provide and Register Document Set-b [ITI-41] Register Document Set-b [ITI-42] Retrieve Document Set [ITI-43] Patient Identity Feed HL7v3 [ITI-44]</td><td>Allegato 5 complemento 1 OCIP-DFI, edizione 9</td></tr>
<tr><td>XDS-I.b</td><td>IHE Radiology Technical Framework, Volume 1 (RAD‑TF‑1), Integration Profiles, Revision 23.0, August 8, 2025 IHE Radio-logy Technical Framework, Volume 2 (RAD-TF-2), Transactions, Revision 23.0, August 8, 2025</td><td>Imaging Document Source Imaging Document Consumer</td><td>Provide & Register Imaging Document Set – MTOM/XOP [RAD-68] Retrieve Imaging Document Set [RAD-69]</td><td>Allegato 5 complemento 1 OCIP-DFI, edizione 9</td></tr>
<tr><td>XDS Metadata Update</td><td>IHE IT Infrastructure Technical Framework, Supplement XDS Metadata Update, Revision 1.14, August 4, 2023</td><td>Document Administrator Document Registry</td><td>Update Document Set [ITI-57]</td><td>Allegato 5 complemento 1 OCIP-DFI, edizione 9</td></tr>
<tr><td>XUA</td><td>IHE IT Infra-structure Technical Framework, Volume 1, Revision 20.0, August 4, 2023 IHE IT Infrastructure Technical Framework, Volume 2, Revision 20.1, December 12, 2024</td><td>X-Service User X-Service Provider X-Assertion Provider User Authentication Provider</td><td>Authenticate User Get X-User Assertion Provide X-User Assertion [ITI-40]</td><td>Allegato 5 complemento 1 OCIP-DFI, edizione 9</td></tr>
</table>

[^annex5-lvlu1-lvl1-2]: L’IHE Technical Framework può essere consultato gratuitamente all’indirizzo: www.ihe.net.
[^annex5-lvlu1-lvl1-3]: Il contenuto dell’allegato 5 complemento 1 può essere consultato all’indirizzo: [https://fedlex.data.admin.ch/eli/oc/2026/202](https://fedlex.data.admin.ch/eli/oc/2026/202) &gt; Informazioni generali &gt; Portata della pubblicazione &gt; Pubblicazione di una parte di testo mediante rimando.
[^annex5-lvlu1-lvl1-4]: Gli adeguamenti nazionale dello standard FHIR possono essere consultati gratuitamente all’indirizzo: www.fhir.ch.

### 2 Profili d’integrazione nazionali

<table>
<tr><th>Profilo d’integrazione</th><th>Documento tecnico</th><th>Attori</th><th>Transazioni</th></tr>
<tr><td>CH:ADR</td><td>Allegato 5 complemento 2.1[^annex5-lvlu1-lvl2-1] OCIP‑DFI, profilo d’integrazione Authorization Decision Request (CH:ADR), edizione 8</td><td>Authorization Decision Provider Authoriza-tion Decision Consumer</td><td>Authorization Decision Request (CH:ADR)</td></tr>
<tr><td>CH:ATC</td><td>Audit Trail Consumption (CH:ATC), CH EPR FHIR (R4) Implementation Guide, Version 5.0.0, 2025-12-18</td><td>Patient Audit Consumer Patient Audit Record Repository</td><td>Retrieve ATNA Audit Event [ITI-81]</td></tr>
<tr><td>CH:CPI</td><td>Allegato 5 complemento 2.3[^annex5-lvlu1-lvl2-2] OCIP‑DFI, profilo d’integrazione Community Portal Index (CH:CPI), edizione 8</td><td>CH:CPI Consumer CH:CPI Provider</td><td>Community Information Query (CH:CIQ) Community Information Delta Download (CH:CIDD)</td></tr>
<tr><td>CH:PPQ</td><td>Allegato 5 complemento 2.1 OCIP‑DFI, profilo d’integrazione Privacy Policy Query (CH:PPQ), edizione 8</td><td>Policy Source Policy Repository Policy Consumer</td><td>Privacy Policy Feed (CH:PPQ-1) Privacy Policy Retrieve (CH:PPQ-2)</td></tr>
<tr><td>CH:PPQm</td><td>Privacy Policy Query for Mobile (CH:PPQm), CH EPR FHIR (R4) Implementation Guide, Version 5.0.0, 2025-12-18</td><td>Policy Repository Policy Source Policy Consumer</td><td>Mobile Privacy Policy Feed (PPQ-3) Mobile Privacy Policy Bundle Feed (PPQ-4) Mobile Privacy Policy Retrieve (PPQ-5)</td></tr>
</table>

[^annex5-lvlu1-lvl2-1]: Il contenuto dell’allegato 5 complemento 2.1 può essere consultato all’indirizzo: [https://fedlex.data.admin.ch/eli/oc/2026/202](https://fedlex.data.admin.ch/eli/oc/2026/202) &gt; Informazioni generali &gt; Portata della pubblicazione &gt; Pubblicazione di una parte di testo mediante rimando.
[^annex5-lvlu1-lvl2-2]: Il contenuto dell’allegato 5 complemento 2.3 può essere consultato all’indirizzo: [https://fedlex.data.admin.ch/eli/oc/2026/202](https://fedlex.data.admin.ch/eli/oc/2026/202) &gt; Informazioni generali &gt; Portata della pubblicazione &gt; Pubblicazione di una parte di testo mediante rimando.
