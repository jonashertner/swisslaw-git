---
sr: "211.432.11"
title: Ordinanza tecnica del DFGP e del DDPS del 28 dicembre 2012 sul registro fondiario (OTRF)
short: OTRF
eli: "https://fedlex.data.admin.ch/eli/cc/2013/3"
language: it
version: 2013-02-01
adopted: 2012-12-28
in_force: 2013-02-01
source: "https://fedlex.data.admin.ch/filestore/fedlex.data.admin.ch/eli/cc/2013/3/20130201/it/xml/fedlex-data-admin-ch-eli-cc-2013-3-20130201-it-xml-1.xml"
url: "https://www.fedlex.admin.ch/eli/cc/2013/3/20130201/it"
---

> Riproduzione non ufficiale della versione consolidata (Fedlex). Fa stato la pubblicazione nella Raccolta ufficiale (art. 15 LPubb, RS 170.512).

# Ordinanza tecnica del DFGP e del DDPS sul registro fondiario

(OTRF)

del 28 dicembre 2012 (Stato 1° febbraio 2013)

Il Dipartimento federale di giustizia e polizia (DFGP) e il Dipartimento federale della difesa, della protezione della popolazione e dello sport (DDPS),

visto l’articolo 949*a* capoverso 3 del Codice civile[^ingress-1] (CC); visti gli articoli 19 capoverso 4, 40 capoverso 2 e 41 capoverso 1 dell’ordinanza del 23 settembre 2011[^ingress-2] sul registro fondiario (ORF); visto l’articolo 6*a* capoverso 2 dell’ordinanza del 18 novembre 1992[^ingress-3] concernente la misurazione ufficiale (OMU),

ordinano:

[^ingress-1]: [RS 210](https://fedlex.data.admin.ch/eli/cc/24/233_245_233)
[^ingress-2]: [RS 211.432.1](https://fedlex.data.admin.ch/eli/cc/2011/667)
[^ingress-3]: [RS 211.432.2](https://fedlex.data.admin.ch/eli/cc/1992/2446_2446_2446)

## Sezione 1: Oggetto

#### Art. 1

La presente ordinanza disciplina:

- a. il modello di dati per il registro fondiario (eGRISMD; allegato 1);
- b. il modello di dati per lo scambio di dati tra la misurazione ufficiale e il registro fondiario (MDMURF; allegato 2);
- c. l’interfaccia per l’estrazione e lo scambio di dati del registro fondiario (IEDRF; allegato 3);
- d. l’interfaccia per lo scambio di dati tra la misurazione ufficiale e il registro fondiario (IMURF);
- e. l’identificazione federale dei fondi (E-GRID);
- f. i formati di dati dei documenti per la comunicazione elettronica con gli uffici del registro fondiario;
- g. le procedure di trasmissione alternative per la comunicazione elettronica (allegato 4);
- h. la salvaguardia a lungo termine.

## Sezione 2: Competenze

#### Art. 2

**DFGP**

<sup>1</sup>

Il DFGP definisce per il registro fondiario:

- a. l’eGRISMD e i requisiti che devono soddisfare i dati ivi tenuti e l’inizio della validità delle nuove versioni;
- b. il linguaggio di descrizione dei dati;
- c. l’IEDRF e l’inizio della validità delle nuove versioni nonché la scadenza della validità delle versioni precedenti;
- d. il catalogo di criteri per il riconoscimento di piattaforme alternative per la comunicazione elettronica con l’ufficio del registro fondiario.

<sup>2</sup> Riconosce piattaforme alternative per la comunicazione elettronica con l’ufficio del registro fondiario.

#### Art. 3

**DFGP e DDPS**

<sup>1</sup>

Per lo scambio di dati tra la misurazione ufficiale e il registro fondiario, il DFGP e il DDPS definiscono:

- a. il MDMURF e l’inizio della validità delle nuove versioni;
- b. il linguaggio di descrizione dei dati;
- c. l’IMURF.

<sup>2</sup> Definiscono l’E-GRID.

#### Art. 4

**Ufficio federale per il diritto del registro fondiario e del diritto fondiario**

<sup>1</sup> L’Ufficio federale per il diritto del registro fondiario e del diritto fondiario (UFRF) è incaricato di diffondere l’eGRISMD e l’IEDRF nonché la relativa documentazione.

<sup>2</sup> Con la collaborazione dei Cantoni, dei produttori del sistema e di altri partecipanti, l’UFRF elabora una pianificazione per lo sviluppo del registro fondiario informatizzato e il suo collegamento con altri sistemi. Adegua annualmente tale pianificazione.

#### Art. 5

**UFRF e Direzione federale delle misurazioni catastali**

<sup>1</sup> L’UFRF e la Direzione federale delle misurazioni catastali (D+M) sono incaricati di diffondere il MDMURF e l’IMURF nonché la relativa documentazione.

<sup>2</sup> Garantiscono lo sviluppo del MDMURF, con la collaborazione dei Cantoni e dei produttori del sistema.

#### Art. 6

**Cantoni**

<sup>1</sup> I Cantoni integrano nei loro sistemi del registro fondiario gli elementi dell’eGRISMD designati come obbligatori nell’allegato 1.

<sup>2</sup> Realizzano nei loro sistemi del registro fondiario gli elementi dell’IEDRF designati come obbligatori nell’allegato 3.

<sup>3</sup> Garantiscono lo scambio di dati tra il registro fondiario e la misurazione ufficiale nella misura prevista dal MDMURF.

## Sezione 3: Linguaggio di descrizione dei dati

#### Art. 7

<sup>1</sup> L’eGRISMD e il MDMURF sono descritti nel linguaggio di descrizione INTERLIS conformemente alla norma svizzera SN 612031, edizione 2006‑05[^7-1].

<sup>2</sup> L’IEDRF è descritto in XML.

[^7-1]: La norma può essere consultata gratuitamente od ottenuta a pagamento presso l’Associazione svizzera di normalizzazione (SNV), Sulzerallee 70, 8404 Winterthur; www.snv.ch.

## Sezione 4: Il modello di dati per il registro fondiario

#### Art. 8

<sup>1</sup> L’eGRISMD fissa i tipi di dati e il livello di dettaglio dei dati del registro fondiario nonché le relazioni tra i dati. Funge da base per l’IEDRF.

<sup>2</sup> Il livello di dettaglio degli elementi dell’eGRISMD designati come obbligatori nell’allegato 1 non può essere ristretto. Gli ampliamenti non possono sostituire gli elementi obbligatori esistenti.

<sup>3</sup>

L’eGRISMD comprende i modelli parziali seguenti:

- a.

  modelli parziali obbligatori:

  - 1\. libro mastro con le pertinenti tabelle dei codici,
  - 2\. libro giornale con le pertinenti tabelle dei codici;

- b.

  modelli parziali facoltativi:

  - 1\. dati personali di base,
  - 2\. note.

<sup>4</sup> Le parti obbligatorie dell’eGRISMD devono essere installate e messe a disposizione nella loro versione in vigore in tutti i sistemi del registro fondiario entro 24 mesi dall’entrata in vigore.

## Sezione 5: Il modello di dati per lo scambio di dati tra la misurazione ufficiale e il registro fondiario

#### Art. 9

<sup>1</sup> Il MDMURF descrive i dati che devono essere scambiati tra la misurazione ufficiale e il registro fondiario.

<sup>2</sup> Il livello di dettaglio del MDMURF non può essere ristretto. Gli ampliamenti non possono sostituire gli elementi esistenti.

<sup>3</sup> Gli ampliamenti del MDMURF non possono essere contrari al modello di dati della misurazione ufficiale (art. 6 OMU) e all’eGRISMD.

<sup>4</sup>

Il MDMURF è suddiviso nei seguenti modelli parziali:

- a. proprietà;
- b. descrizione del fondo;
- c. tabella di mutazione;
- d. oggetti legati all’esecuzione.

<sup>5</sup> Il MDMURF identifica i fondi mediante l’E-GRID.

<sup>6</sup> Il MDMURF deve essere installato e messo a disposizione nella sua versione in vigore in tutti i registri fondiari e nella misurazione ufficiale entro 24 mesi dall’entrata in vigore.

## Sezione 6: L’interfaccia per l’estrazione e lo scambio di dati del registro fondiario

#### Art. 10

<sup>1</sup>

L’IEDRF consente:

- a. il trasferimento dei dati giuridicamente efficaci e di quelli cancellati del libro mastro, del libro giornale e dei documenti giustificativi in una forma strutturata ed elettronicamente leggibile;
- b. l’allestimento dell’indice svizzero dei fondi secondo l’articolo 27 capoverso 3 ORF;
- c. l’esportazione dei dati giuridicamente efficaci e di quelli cancellati del libro mastro per la salvaguardia a lungo termine da parte della Confederazione;
- d. la comunicazione elettronica con gli uffici del registro fondiario.

<sup>2</sup> Per quanto concerne il contenuto e il livello di dettaglio, la struttura dei dati è retta dal modello di dati eGRISMD.

<sup>3</sup> L’UFRF o un’organizzazione da esso incaricata esterna all’Amministrazione federale può, con la collaborazione dei Cantoni, sviluppare l’IEDRF. A tal fine, l’UFRF può istituire un gruppo di accompagnamento composto di rappresentanti dei Cantoni, della misurazione ufficiale, dei produttori del sistema interessati e di altre cerchie di specialisti.

<sup>4</sup> I produttori del sistema ricevono le proposte di modifica, ne stilano un elenco epurato e lo sottopongono per adozione al gruppo di accompagnamento. Dopo attuazione delle proposte adottate, verifica pratica della nuova versione ed esame da parte del gruppo di accompagnamento, la nuova versione è sottoposta al DFGP per approvazione.

<sup>5</sup> L’IEDRF deve essere installata e messa a disposizione nella sua versione in vigore in tutti i sistemi del registro fondiario entro 24 mesi dall’entrata in vigore.

## Sezione 7: L’interfaccia per lo scambio di dati tra la misurazione ufficiale e il registro fondiario

#### Art. 11

**Definizione**

L’IMURF è definita mediante il MDMURF e il formato di trasferimento risultante dal MDMURF e dalla SN 612031, edizione 2006‑05[^11-1].

[^11-1]: La norma può essere consultata gratuitamente od ottenuta a pagamento presso l’Associazione svizzera di normalizzazione (SNV), Sulzerallee 70, 8404 Winterthur; www.snv.ch.

#### Art. 12

**Impiego**

<sup>1</sup> L’IMURF deve essere installata e messa a disposizione nella sua versione in vigore in tutti i sistemi del registro fondiario entro 24 mesi dall’entrata in vigore.

<sup>2</sup> Al posto dell’IMURF i Cantoni possono provvedere in altro modo affinché i dati della misurazione ufficiale definiti nel MDMURF siano trasferiti integralmente nel registro fondiario nell’ambito della gestione ordinaria.

## Sezione 8: Requisiti dei sistemi informatici

#### Art. 13

**Requisiti per la tenuta del registro fondiario**

I sistemi informatici impiegati per la tenuta del registro fondiario devono essere in grado di:

- a. fornire i dati mediante l’IEDRF;
- b. esportare i dati giuridicamente efficaci e quelli cancellati del libro mastro in un file IEDRF, ai fini della salvaguardia a lungo termine;
- c. creare e attribuire tutti gli identificatori obbligatori conformemente all’eGRISMD.

#### Art. 14

**Tenuta dei dati dei sistemi del registro fondiario**

<sup>1</sup> Per quanto concerne il contenuto, il livello di dettaglio e la completezza dei dati, la tenuta dei dati del registro fondiario è retta dall’eGRISMD.

<sup>2</sup> In occasione del passaggio dalla versione cartacea a quella informatizzata del registro fondiario devono essere ripresi tutti i dati giuridicamente efficaci delle singole rubriche. Non è necessario rilevare i dati cancellati e i rinvii ai documenti giustificativi corrispondenti.

#### Art. 15

**Requisiti della tenuta del registro fondiario e della misurazione ufficiale**

I sistemi informatici impiegati per la tenuta del registro fondiario e per la misurazione ufficiale devono essere in grado di estrarre e fornire dati dell’estensione e del livello di dettaglio del MDMURF.

## Sezione 9: Identificazione federale dei fondi

#### Art. 16

**Principi**

<sup>1</sup> L’E-GRID è univoca in tutta la Svizzera, non contiene elementi classificatori ed è attribuita una sola volta.

<sup>2</sup> Serve per identificare i fondi nel modello di dati della misurazione ufficiale, nell’eGRISMD e nel MDMURF.

<sup>3</sup> Costituisce la base per lo scambio di dati relativi ai fondi.

<sup>4</sup> Deve poter essere utilizzata come parola chiave di ricerca nei sistemi di informazione relativi ai fondi.

#### Art. 17

**Attribuzione ai fondi**

<sup>1</sup> L’E-GRID per gli immobili come pure per i diritti per sé stanti e permanenti limitati per superficie e per le miniere è allestita e attribuita dalla misurazione ufficiale. Per gli altri fondi è allestita e attribuita dall’ufficio del registro fondiario. I Cantoni possono emanare norme derogatorie.

<sup>2</sup> In caso di modifica dell’entità o del territorio dei Comuni, tutti i fondi interessati conservano la loro E-GRID.

<sup>3</sup> In caso di divisione di un fondo, una parte conserva di norma l’E-GRID esistente. In caso di riunione di vari fondi, l’E-GRID di uno dei fondi interessati è di norma riutilizzata per il nuovo fondo.

## Sezione 10: Formati di dati di documenti per la comunicazione elettronica con gli uffici del registro fondiario

#### Art. 18

**Richieste destinate all’ufficio del registro fondiario**

I formati di dati ammessi per le richieste destinate all’ufficio del registro fondiario sono:

- a. per le notificazioni dell’iscrizione nel registro fondiario che non sono già contenute nell’attestazione del titolo giuridico: PDF provvisto di firma elettronica qualificata ai sensi dell’articolo 14 capoverso 2<sup>bis</sup> del Codice delle obbligazioni[^18-1] (CO); i dati contenuti nella notificazione possono inoltre essere allegati in formato XML;
- b. per le attestazioni del titolo giuridico documentate da un atto pubblico: i formati secondo l’ordinanza del DFGP del 2 dicembre 2011[^18-2] sui formati elettronici riconosciuti nell’ambito degli atti pubblici in forma elettronica;
- c. per le attestazioni del titolo giuridico in forma scritta, allegati inclusi: PDF/A provvisto di firma elettronica qualificata ai sensi dell’articolo 14 capoverso 2<sup>bis</sup> CO;
- d. per le domande di rilascio di un estratto del registro fondiario o di un’attestazione dell’iscrizione: PDF provvisto di firma elettronica qualificata ai sensi dell’articolo 14 capoverso 2<sup>bis</sup> CO; sono fatte salve le domande di partecipanti autentificati nell’ambito di procedure alternative di trasmissione e di sistemi cantonali d’informazione del registro fondiario.

[^18-1]: [RS 220](https://fedlex.data.admin.ch/eli/cc/27/317_321_377)
[^18-2]: [[RU 2011 6265](https://fedlex.data.admin.ch/eli/oc/2011/882). [RU 2013 2347](https://fedlex.data.admin.ch/eli/oc/2013/495)art. 20 n. 1]. Vedi ora l’O del DFGP dell’8 dic. 2017 sulla realizzazione di atti pubblici e autenticazioni in forma elettronica ([RS 211.435.11](https://fedlex.data.admin.ch/eli/cc/2018/30)). RU 2018 107

#### Art. 19

**Notifiche dell’ufficio del registro fondiario**

I formati per le notifiche dell’ufficio del registro fondiario alle parti sono:

- a. per le attestazioni dell’iscrizione e gli avvisi delle operazioni effettuate nel registro fondiario: PDF/A o XML; su richiesta del destinatario il documento in formato PDF/A può essere provvisto di firma elettronica qualificata ai sensi dell’articolo 14 capoverso 2<sup>bis</sup> CO[^19-1]; al documento possono inoltre essere allegati dati in formato XML;
- b. per fissare i termini e per le decisioni di rifiuto: PDF/A provvisto di firma elettronica qualificata ai sensi dell’articolo 14 capoverso 2<sup>bis</sup> CO;
- c. per gli estratti del registro fondiario: PDF/A o XML; su richiesta del destinatario l’estratto può essere provvisto di firma elettronica qualificata ai sensi dell’articolo 14 capoverso 2<sup>bis</sup> CO; all’estratto possono inoltre essere allegati dati in formato XML.

[^19-1]: [RS 220](https://fedlex.data.admin.ch/eli/cc/27/317_321_377)

#### Art. 20

**Formati ammessi di dati**

<sup>1</sup> Le versioni ammesse del formato di dati PDF/A sono rette dall’allegato dell’ordinanza del DFGP del 2 dicembre 2011[^20-1] sui formati elettronici riconosciuti nell’ambito degli atti pubblici in forma elettronica.

<sup>2</sup> I formati PDF e XML possono essere utilizzati in tutte le versioni in uso.

[^20-1]: [[RU 2011 6265](https://fedlex.data.admin.ch/eli/oc/2011/882). [RU 2013 2347](https://fedlex.data.admin.ch/eli/oc/2013/495)art. 20 n. 1]. Vedi ora l’O del DFGP dell’8 dic. 2017 sulla realizzazione di atti pubblici e autenticazioni in forma elettronica ([RS 211.435.11](https://fedlex.data.admin.ch/eli/cc/2018/30)).

## Sezione 11: Procedure di trasmissione alternative

#### Art. 21

**Riconoscimento di piattaforme alternative**

Una piattaforma alternativa per la comunicazione elettronica con l’ufficio del registro fondiario è riconosciuta se:

- a. per la firma e il criptaggio applica certificati macchina (certificati SSL) che provengono da un prestatore di servizi di certificazione riconosciuto secondo la legge del 19 dicembre 2003[^21-1] sulla firma elettronica (prestatore riconosciuto);
- b. può attestare quali documenti sono stati trasmessi o sono stati utilizzati per il disbrigo dei compiti specificati;
- c. protegge adeguatamente le richieste e le notifiche dall’accesso non autorizzato da parte di terzi;
- d. è in grado di comunicare conformemente alle regole riconosciute in materia di trasmissione sicura; tiene conto dello stato della tecnica come espresso in particolare negli standard eCH[^21-2];
- e. possiede risorse o garanzie finanziarie sufficienti.

[^21-1]: [[RU 2004 5085](https://fedlex.data.admin.ch/eli/oc/2004/788), [2008 3437](https://fedlex.data.admin.ch/eli/oc/2008/447)II 55. [RU 2016 4651](https://fedlex.data.admin.ch/eli/oc/2016/752)all. n. I]. Vedi ora la L del 18 mar. 2016 ([RS 943.03](https://fedlex.data.admin.ch/eli/cc/2016/752)).
[^21-2]: www.eCH.ch

#### Art. 22

**Procedura di riconoscimento**

<sup>1</sup> Le domande di riconoscimento vanno presentate all’UFRF.

<sup>2</sup>

La domanda contiene informazioni concernenti:

- a. l’adempimento del catalogo di criteri, in particolare le misure tecniche e organizzative per garantire l’integrità, la protezione e la sicurezza dei dati durante la trasmissione e sulla piattaforma;
- b. la tracciabilità della trasmissione;
- c. la disponibilità del sistema.

<sup>3</sup>

Alla domanda vanno allegati:

- a. una descrizione del sistema;
- b. i risultati dei test e dei controlli effettuati.

<sup>4</sup> Per la verifica delle condizioni di riconoscimento, l’UFRF può fare capo a specialisti esterni all’Amministrazione. Le spese sono a carico del richiedente.

<sup>5</sup> Il DFGP revoca il riconoscimento se constata che le condizioni di riconoscimento non sono più adempiute.

<sup>6</sup> L’emolumento per la decisione è calcolato in base al dispendio di tempo; la tariffa oraria ammonta a 250 franchi. Per il rimanente, si applicano le disposizioni dell’ordinanza generale dell’8 settembre 2004[^22-1] sugli emolumenti.

[^22-1]: [RS 172.041.1](https://fedlex.data.admin.ch/eli/cc/2004/677)

## Sezione 12: Salvaguardia a lungo termine

#### Art. 23

<sup>1</sup> Ai fini della salvaguardia a lungo termine, i Cantoni consegnano all’Ufficio federale di giustizia (UFG) almeno una volta per anno civile, in un momento da loro liberamente scelto, l’integralità dei dati giuridicamente efficaci e dei dati cancellati del libro mastro, strutturati conformemente a quanto richiesto dall’IEDRF.

<sup>2</sup> La consegna comprende un file per tutto il Cantone oppure svariati file, ciascuno relativo a una parte del Cantone (p. es. circondario del registro fondiario).

<sup>3</sup> I file sono trasmessi mediante un collegamento sicuro con un programma informatico messo a disposizione dalla Confederazione, mediante un certificato qualificato ai sensi della legge del 19 dicembre 2003[^23-1] sulla firma elettronica e un certificato di autentificazione del medesimo prestatore.

<sup>4</sup> Per ciascuna unità del loro territorio, i Cantoni designano e notificano all’UFG una persona incaricata della salvaguardia a lungo termine dei dati, che trasmette alla Confederazione il file da essa firmato e conferma, con la sua firma, che si tratta dell’insieme di dati del sistema del registro fondiario da salvaguardare.

[^23-1]: [[RU 2004 5085](https://fedlex.data.admin.ch/eli/oc/2004/788), [2008 3437](https://fedlex.data.admin.ch/eli/oc/2008/447)II 55. [RU 2016 4651](https://fedlex.data.admin.ch/eli/oc/2016/752)all. n. I]. Vedi ora la L del 18 mar. 2016 ([RS 943.03](https://fedlex.data.admin.ch/eli/cc/2016/752)).

## Sezione 13: Requisiti minimi per la sicurezza d’esercizio dei sistemi del registro fondiario

#### Art. 24

<sup>1</sup> Il DFGP elabora, insieme a rappresentanti dei Cantoni e in base a una valutazione metodica dei rischi, un catalogo di criteri contenente misure adeguate, efficaci e formalmente verificabili per la gestione sicura di un sistema del registro fondiario.

<sup>2</sup> Il catalogo contiene requisiti relativi agli auditori, alla frequenza e alla modalità di verifica.

<sup>3</sup> È messo a disposizione dei Cantoni a titolo di raccomandazione.

## Sezione 14: Disposizioni finali

#### Art. 25

**Diritto previgente: abrogazione**

L’ordinanza tecnica del DFGP e del DDPS del 6 giugno 2007[^25-1] sul registro fondiario è abrogata.

[^25-1]: [[RU 2007 3353](https://fedlex.data.admin.ch/eli/oc/2007/408)]

#### Art. 26

**Disposizione transitoria**

<sup>1</sup>

I Cantoni devono rendere disponibili nei loro sistemi informatici entro il 1° gennaio 2014:

- a. per il registro fondiario e la misurazione ufficiale: l’IMURF o un metodo di trasmissione dei dati equivalente e l’E-GRID;
- b. per il registro fondiario: gli elementi obbligatori dell’eGRISMD e le parti informazione/estrazione di dati e salvaguardia a lungo termine dell’IEDRF.

<sup>2</sup> In casi motivati, il DFGP può prorogare i termini.

#### Art. 27

**Entrata in vigore**

La presente ordinanza entra in vigore il 1° febbraio 2013.

Allegato 1*[^t-1]*

(art. 1 lett. a, 2 cpv. 1 lett. a e art. 8)

## Descrizione in INTERLIS del modello di dati per il registro fondiario eGRISMD

[^t-1]: Il presente all. contiene il modello di dati nella versione eGRISMD11. Il testo dell’all. non è pubblicato né nella RU né nella RS. L’O con l’all. può essere consultata in Internet sul sito www.bj.admin.ch &gt; temi &gt; economia &gt; registro fondiario & registro del naviglio.

Allegato 2*[^t-2]*

(art. 1 lett. b, 3 cpv. 1 lett. a e art. 9)

## Descrizione in INTERLIS del modello di dati per lo scambio di dati tra la misurazione ufficiale e il registro fondiario MDMURF

[^t-2]: Il presente all. contiene il modello di dati nella versione MDMURF05. Il testo dell’all. non è pubblicato né nella RU né nella RS. L’ordinanza con l’all. può essere consultata in Internet sul sito www.bj.admin.ch &gt; temi &gt; economia &gt; registro fondiario & registro del naviglio.

Allegato 3*[^t-3]*

(art. 1 lett. c, 2 cpv. 1 lett. c e art. 10)

## Descrizione in XML dell’interfaccia per l’estrazione e lo scambio di dati del registro fondiario IEDRF

[^t-3]: Il presente all. contiene la versione 2.0.5 dell’interfaccia. Il testo dell’all. non è pubblicato né nella RU né nella RS. L’O con l’all. può essere consultata in Internet sul sito www.bj.admin.ch &gt; temi &gt; economia &gt; registro fondiario & registro del naviglio.

Allegato 4*[^t-4]*

(art. 1 lett. g e 2 cpv. 1 lett. d)

## Catalogo di criteri per il riconoscimento di piattaforme alternative

[^t-4]: Il testo dell’all. non è pubblicato né nella RU né nella RS. L’O con l’all. può essere consultata in Internet sul sito www.bj.admin.ch &gt; temi &gt; economia &gt; registro fondiario & registro del naviglio.
