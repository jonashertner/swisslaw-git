---
sr: "172.010.59"
title: Ordinanza del 19 ottobre 2016 sui sistemi di gestione delle identità e sui servizi di elenchi della Confederazione (OIAM)
short: OIAM
eli: "https://fedlex.data.admin.ch/eli/cc/2016/610"
language: it
version: 2024-01-01
adopted: 2016-10-19
in_force: 2017-01-01
source: "https://fedlex.data.admin.ch/filestore/fedlex.data.admin.ch/eli/cc/2016/610/20240101/it/xml/fedlex-data-admin-ch-eli-cc-2016-610-20240101-it-xml-2.xml"
url: "https://www.fedlex.admin.ch/eli/cc/2016/610/20240101/it"
---

> Riproduzione non ufficiale della versione consolidata (Fedlex). Fa stato la pubblicazione nella Raccolta ufficiale (art. 15 LPubb, RS 170.512).

# Ordinanza sui sistemi di gestione delle identità e sui servizi di elenchi della Confederazione

(OIAM)

del 19 ottobre 2016 (Stato 1° gennaio 2024)

Il Consiglio federale svizzero,

visti gli articoli 26 e 84 capoverso 1 della legge del 18 dicembre 2020[^ingress-1] sulla sicurezza delle informazioni (LSIn); vista la legge federale del 17 marzo 2023[^ingress-2] concernente l’impiego di mezzi elettronici per l’adempimento dei compiti delle autorità (LMeCA); vista la legge del 21 marzo 1997[^ingress-3] sull’organizzazione del Governo e dell’Amministrazione (LOGA); visto l’articolo 27 capoversi 5 e 6 della legge del 24 marzo 2000[^ingress-4] sul personale federale; visto l’articolo 186 della legge federale del 3 ottobre 2008[^ingress-5] sui sistemi d’informazione militari e su altri sistemi d’informazione nel DDPS,[^ingress-6]

ordina:

[^ingress-1]: [RS 128](https://fedlex.data.admin.ch/eli/cc/2022/232)
[^ingress-2]: [RS 172.019](https://fedlex.data.admin.ch/eli/cc/2023/682)
[^ingress-3]: [RS 172.010](https://fedlex.data.admin.ch/eli/cc/1997/2022_2022_2022)
[^ingress-4]: [RS 172.220.1](https://fedlex.data.admin.ch/eli/cc/2001/123)
[^ingress-5]: [RS 510.91](https://fedlex.data.admin.ch/eli/cc/2009/823)
[^ingress-6]: Nuovo testo giusta il n. I dell’O dell’8 nov. 2023, in vigore dal 1° gen. 2024 ([RU 2023 738](https://fedlex.data.admin.ch/eli/oc/2023/738)).

## Sezione 1: Disposizioni generali

#### Art. 1

**Oggetto**

La presente ordinanza disciplina le competenze, il trattamento e la comunicazione di dati personali e i requisiti in materia di sicurezza delle informazioni per i sistemi di gestione delle identità (sistemi IAM[^1-1]), i servizi di elenchi e l’archivio centralizzato delle identità della Confederazione.

[^1-1]: IAM = *Identity and Access Management*

#### Art. 2

**Campo d’applicazione**[^2-1]

<sup>1</sup>

Gli articoli 24 e 25 LSIn e la presente ordinanza si applicano:

- a. alle unità amministrative dell’Amministrazione federale centrale secondo l’articolo 7 dell’ordinanza del 25 novembre 1998[^2-2] sull’organizzazione del Governo e dell’Amministrazione (OLOGA);
- b. all’esercito.

<sup>2</sup> L’applicabilità della presente ordinanza alle unità amministrative dell’Amministrazione federale decentralizzata secondo l’articolo 2 capoverso 3 LOGA e alle organizzazioni secondo l’articolo 2 capoverso 4 LOGA si fonda sull’articolo 2 capoverso 2 lettera b e 3 dell’ordinanza dell’8 novembre 2023[^2-3] sulla sicurezza delle informazioni (OSIn).

[^2-1]: Nuovo testo giusta il n. I dell’O dell’8 nov. 2023, in vigore dal 1° gen. 2024 ([RU 2023 738](https://fedlex.data.admin.ch/eli/oc/2023/738)).
[^2-2]: [RS 172.010.1](https://fedlex.data.admin.ch/eli/cc/1999/170)
[^2-3]: [RS 128.1](https://fedlex.data.admin.ch/eli/cc/2023/735)

## Sezione 2: Scopo e funzione principale dei sistemi

#### Art. 3

**Sistemi IAM**

<sup>1</sup> Lo scopo di un sistema IAM consiste nell’amministrare in modo raggruppato i dati sull’identità e sui diritti di persone, macchine e sistemi per metterli a disposizione, su richiesta, di sistemi a valle e di altri sistemi IAM.

<sup>2</sup> I sistemi a valle sono applicazioni specifiche oppure sistemi che consentono di accedere a informazioni, strumenti informatici, locali e altre infrastrutture.

<sup>3</sup> In quanto sistema a monte, il sistema IAM verifica l’identità e determinate caratteristiche, rilevanti ai fini dei diritti, di persone, macchine e sistemi che vogliono accedere a un sistema a valle e ne trasmette il risultato al sistema d’informazione a valle affinché possa accertare tali diritti.

#### Art. 4

**Servizi di elenchi**

Lo scopo di un servizio di elenchi consiste nel gestire informazioni sugli utenti delle infrastrutture della Confederazione al fine di identificare le persone e amministrare i dispositivi, le connessioni, i dati relativi ai contatti e simili a loro assegnati.

## Sezione 3: Organi responsabili

#### Art. 5

**Sistemi IAM**[^5-1]

<sup>1</sup>

I seguenti organi federali sono responsabili dei sottostanti sistemi IAM dell’Amministrazione federale centrale:

- a.

  il settore Trasformazione digitale e governance delle TIC della Cancelleria federale (settore TDT della CaF) per:

  - 1\. tutti i sistemi IAM offerti come servizi standard o esplicitamente attribuiti al settore TDT della CaF inclusa la relativa messa a disposizione dei Cantoni e dei Comuni nonché delle organizzazioni e delle persone di diritto pubblico o privato conformemente all’articolo 11 capoverso 3 LMeCA,
  - 2\. tutti i sistemi IAM dei processi di supporto legati a finanze, acquisti, immobili e logistica, compresi i collegamenti cloud;

- b. la Direzione delle risorse del Dipartimento federale degli affari esteri (DFAE) per il sistema IAM gestito dall’unità Informatica DFAE;
- c. la Segreteria generale del Dipartimento federale della difesa, della protezione della popolazione e dello sport per i sistemi IAM gestiti dall’Aggruppamento Difesa (Aggruppamento D);
- d. l’Amministrazione federale delle finanze per il sistema IAM gestito in seno all’Ufficio centrale di compensazione per il trattamento dei sistemi di assicurazioni sociali del 1° pilastro e il relativo supporto ai processi;
- e. la Segreteria generale del Dipartimento federale dell’economia, della formazione e della ricerca (DEFR) per il sistema IAM gestito presso il Centro servizi informatici DEFR (CSIeco);
- f. l’Ufficio federale delle strade per il suo sistema IAM destinato all’esercizio degli equipaggiamenti di esercizio e sicurezza delle strade nazionali.

<sup>2</sup> Provvedono affinché la liceità del trattamento dei dati personali nei sistemi IAM dei quali sono responsabili sia verificata almeno ogni quattro anni da un servizio esterno.

<sup>3</sup>

I seguenti organi federali sono responsabili dei sottostanti sistemi IAM:

- a. l’Aggruppamento D per i sistemi IAM dell’esercito;
- b. le rispettive unità amministrative per i sistemi IAM dell’Amministrazione federale decentralizzata;
- c. le rispettive organizzazioni per i sistemi IAM delle organizzazioni secondo l’articolo 2 capoverso 4 LOGA.

<sup>4</sup> Le autorità assoggettate secondo l’articolo 2 capoverso 1 lettere a e c–e LSIn, alle quali la presente ordinanza si applica secondo l’articolo 84 capoverso 3 LSIn, stabiliscono quali sono gli organi federali responsabili nel loro settore.

<sup>5</sup> La responsabilità del sistema a valle, in particolare dell’accesso ad esso, rimane al servizio tecnico cui spetta la relativa competenza.

[^5-1]: Nuovo testo giusta il n. I dell’O dell’8 nov. 2023, in vigore dal 1° gen. 2024 ([RU 2023 738](https://fedlex.data.admin.ch/eli/oc/2023/738)).

#### Art. 6

**Servizi di elenchi**

Gli organi federali responsabili dei servizi di elenchi esterni ai sistemi IAM sono:

- a. il settore TDT della CaF[^6-1] per i servizi standard;
- b.

  per gli altri elenchi, i fornitori di prestazioni informatiche che gestiscono tali sistemi, più precisamente:

  - 1\. l’unità Informatica DFAE della Direzione delle risorse del DFAE,
  - 2\. il Centro servizi informatici del Dipartimento federale di giustizia e
  - 3\.[^6-2] l’Aggruppamento D,
  - 4\. l’Ufficio federale dell’informatica e della telecomunicazione (UFIT),
  - 5\. il CSIeco.

[^6-1]: Nuova espressione giusta l’all. n. 8 dell’O del 25 nov. 2020 sulla trasformazione digitale e l’informatica, in vigore dal 1° gen. 2021 ([RU 2020 5871](https://fedlex.data.admin.ch/eli/oc/2020/988)). Di detta mod. è tenuto conto in tutto il presente testo.
[^6-2]: Nuovo testo giusta il n. I dell’O dell’8 nov. 2023, in vigore dal 1° gen. 2024 ([RU 2023 738](https://fedlex.data.admin.ch/eli/oc/2023/738)).

#### Art. 7

**Esercizio dei diritti**

Le persone interessate fanno valere i propri diritti relativi ai sistemi IAM e ai servizi di elenchi presso i seguenti servizi:

- a. diritto di lettura: presso gli organi responsabili;
- b.[^7-1]

  diritto di correzione e cancellazione dei dati:

  - 1\. presso il servizio del personale della loro unità amministrativa od organizzazione oppure presso il servizio competente per l’aggiornamento dei loro dati,
  - 2\. nel caso di cui all’articolo 9 lettera b: presso gli organi responsabili.

[^7-1]: Nuovo testo giusta il n. I dell’O dell’8 nov. 2023, in vigore dal 1° gen. 2024 ([RU 2023 738](https://fedlex.data.admin.ch/eli/oc/2023/738)).

## Sezione 4: Dati trattati, ottenimento dei dati e termine di conservazione

#### Art. 8

**Persone registrate in sistemi IAM e in servizi di elenchi**

<sup>1</sup>

Nei sistemi IAM e nei servizi di elenchi possono essere trattati dati relativi alle seguenti persone:

- a. collaboratori dell’Amministrazione federale centrale secondo l’articolo 7 OLOGA[^8-1];
- b. collaboratori dell’Amministrazione federale decentralizzata secondo l’articolo 7*a* OLOGA;
- c. membri dell’Assemblea federale e collaboratori dei Servizi del Parlamento secondo il titolo quarto, capitolo 7 della legge del 13 dicembre 2002[^8-2] sul Parlamento;
- d. persone elette dall’Assemblea federale secondo l’articolo 168 della Costituzione federale[^8-3];
- e. collaboratori del Tribunale federale, del Tribunale amministrativo federale, del Tribunale penale federale e del Tribunale federale dei brevetti, sempre che la legislazione non preveda diversamente;
- f. collaboratori del Ministero pubblico della Confederazione secondo gli articoli 7–22 della legge del 19 marzo 2010[^8-4] sull’organizzazione delle autorità penali (LOAP);
- g. collaboratori della segreteria dell’autorità di vigilanza sul Ministero pubblico della Confederazione secondo l’articolo 27 capoverso 2 LOAP;
- h.[^8-5] militari e militi della protezione civile.

<sup>2</sup>

Inoltre possono essere trattati dati di collaboratori delle seguenti imprese a condizione che essi siano regolarmente in contatto con i servizi di cui al capoverso 1:

- a. Ferrovie federali svizzere;
- b. La Posta Svizzera;
- c. RUAG;
- d. Istituto nazionale svizzero di assicurazione contro gli infortuni.

<sup>3</sup>

Nei sistemi IAM e nei servizi di elenchi possono essere inoltre trattati dati sulle seguenti persone:

- a. persone esterne che svolgono attività per i servizi di cui ai capoversi 1 o 2;
- b. persone esterne che per altri motivi hanno accesso a informazioni, strumenti informatici, locali e altre infrastrutture dell’Amministrazione federale.

[^8-1]: [RS 172.010.1](https://fedlex.data.admin.ch/eli/cc/1999/170)
[^8-2]: [RS 171.10](https://fedlex.data.admin.ch/eli/cc/2003/510)
[^8-3]: [RS 101](https://fedlex.data.admin.ch/eli/cc/1999/404)
[^8-4]: [RS 173.71](https://fedlex.data.admin.ch/eli/cc/2010/444)
[^8-5]: Introdotta dal n. I dell’O del 14 nov. 2018, in vigore dal 1° gen. 2019 ([RU 2018 4739](https://fedlex.data.admin.ch/eli/oc/2018/752)).

#### Art. 9

**Persone registrate nei sistemi IAM**

Oltre ai dati di cui all’articolo 8, nei sistemi IAM possono essere trattati dati delle persone seguenti:

- a. collaboratori di autorità cantonali o comunali se queste persone utilizzano sistemi informatici messi a disposizione dalla Confederazione;
- b.[^9-1] privati e rappresentanti di organizzazioni che accedono a sistemi informatici, come le applicazioni per il Governo elettronico, messi a disposizione dalla Confederazione o, per l’esecuzione del diritto cantonale, dai Cantoni e dai Comuni nonché dalle organizzazioni e dalle persone di diritto pubblico o privato.

[^9-1]: Nuovo testo giusta il n. I dell’O dell’8 nov. 2023, in vigore dal 1° gen. 2024 ([RU 2023 738](https://fedlex.data.admin.ch/eli/oc/2023/738)).

#### Art. 10

**Persone registrate nei servizi di elenchi**

Oltre ai dati di cui all’articolo 8, nei servizi di elenchi possono essere trattati dati di collaboratori di autorità cantonali o comunali nonché di altre imprese vicine alla Confederazione diverse da quelle menzionate nell’articolo 8 capoverso 2, che utilizzano un certificato digitale della Confederazione.

#### Art. 11

**Categorie di dati personali**

<sup>1</sup> Nei sistemi IAM, nei servizi di elenchi e nell’archivio centralizzato delle identità di cui all’articolo 13 possono essere trattati dati personali conformemente all’allegato.

<sup>2</sup> In questi sistemi non può essere effettuata alcuna profilazione secondo l’articolo 5 lettere f e g della legge federale del 25 settembre 2020[^11-1] sulla protezione dei dati.[^11-2]

<sup>3</sup> In assenza di una base legale specifica in materia, in questi sistemi non possono essere trattati dati personali degni di particolare protezione. È fatto salvo il trattamento di dati biometrici con sistemi IAM per l’identificazione delle persone in funzione dei rischi secondo gli articoli 8 e 9 lettera a (art. 20 cpv. 2 LSIn).[^11-3]

<sup>4</sup> I dati riguardanti persone secondo l’articolo 8 che nell’allegato sono contrassegnati con un asterisco possono essere pubblicati in un elenco di persone accessibile a tutti coloro che vi sono riportati.

[^11-1]: [RS 235.1](https://fedlex.data.admin.ch/eli/cc/2022/491)
[^11-2]: Nuovo testo giusta il n. I dell’O dell’8 nov. 2023, in vigore dal 1° gen. 2024 ([RU 2023 738](https://fedlex.data.admin.ch/eli/oc/2023/738)).
[^11-3]: Nuovo testo giusta il n. I dell’O dell’8 nov. 2023, in vigore dal 1° gen. 2024 ([RU 2023 738](https://fedlex.data.admin.ch/eli/oc/2023/738)).

#### Art. 12

**Ottenimento di dati personali**

<sup>1</sup> I sistemi IAM e i servizi di elenchi possono ottenere automaticamente dati delle persone registrate nel sistema d’informazione per la gestione dei dati del personale (SIGDP) conformemente all’articolo 34 dell’ordinanza del 22 novembre 2017[^12-1] sulla protezione dei dati personali del personale federale.[^12-2]

<sup>2</sup> Possono ottenere automaticamente dai rispettivi servizi di cui all’articolo 8 dati di persone non registrate in SIGDP[^12-3], a condizione che il gruppo di persone interessato necessiti di principio l’accesso a sistemi d’informazione o ad altre risorse della Confederazione.

<sup>3</sup> Possono ottenere automaticamente dai singoli sistemi d’informazione dati di persone esterne che accedono regolarmente alle risorse della Confederazione.

<sup>4</sup> Possono ottenere automaticamente dati di persone esterne dai sistemi IAM esterni collegati ai sistemi IAM della Confederazione secondo gli articoli 21–24.[^12-4]

[^12-1]: [RS 172.220.111.4](https://fedlex.data.admin.ch/eli/cc/2017/793)
[^12-2]: Nuovo testo giusta l’all. 8 n. II 1 dell’O del 22 nov. 2017 sulla protezione dei dati personali del personale federale, in vigore dal 1° gen. 2018 ([RU 2017 7271](https://fedlex.data.admin.ch/eli/oc/2017/793)).
[^12-3]: Nuova espr. giusta l’all. 8 n. II 1 dell’O del 22 nov. 2017 sulla protezione dei dati personali del personale federale, in vigore dal 1° gen. 2018 ([RU 2017 7271](https://fedlex.data.admin.ch/eli/oc/2017/793)). Di detta mod. è tenuto conto in tutto il presente testo.
[^12-4]: Introdotto dal n. I dell’O dell’8 nov. 2023, in vigore dal 1° gen. 2024 ([RU 2023 738](https://fedlex.data.admin.ch/eli/oc/2023/738)).

#### Art. 13

**Archivio centralizzato delle identità per la distribuzione di dati**

<sup>1</sup> L’UFIT gestisce un archivio centralizzato delle identità per distribuire dati degli utenti ai diversi sistemi IAM e ai servizi di elenchi. In questo archivio possono essere trattati tutti i dati personali conformemente all’allegato. L’organo federale responsabile è il settore TDT della CaF.

<sup>2</sup> La SIGDP trasmette regolarmente, se disponibili, i dati conformemente all’allegato all’archivio centralizzato delle identità. Tutti i dati personali ottenuti automaticamente dalla SIGDP sono distribuiti mediante questo archivio. Fanno eccezione i dati personali di base nel sistema SAP standard ottenuti direttamente per i sistemi SAP autorizzati.

<sup>3</sup> I dati personali secondo l’articolo 8 capoverso 1 lettera c e capoverso 3 sono messi a disposizione dei Servizi del Parlamento affinché possano essere ripresi e armonizzati.

<sup>4</sup>

I dati possono essere messi a disposizione automaticamente di altri sistemi d’informazione interni alla Confederazione per essere ripresi e armonizzati a condizione che il sistema interessato:

- a.[^13-1] sia dotato di una base legale che prevede il trattamento dei dati da mettere a disposizione e di un regolamento per il trattamento secondo l’articolo 6 dell’ordinanza del 31 agosto 2022[^13-2] sulla protezione dei dati (OPDa); e
- b. sia notificato all’Incaricato federale della protezione dei dati e della trasparenza secondo l’articolo 12 capoverso 4 della legge federale del 25 settembre 2020[^13-3] sulla protezione dei dati (LPD).[^13-4]

<sup>4bis</sup> Il numero AVS è messo a disposizione a condizione che la sua utilizzazione sia annunciata all’Ufficio centrale di compensazione secondo l’articolo 134<sup>ter</sup> dell’ordinanza del 31 ottobre 1947[^13-5] sull’assicurazione per la vecchiaia e per i superstiti.[^13-6]

<sup>5</sup> I dati necessari per la pubblicazione nell’Annuario federale secondo l’articolo 5 dell’ordinanza del 29 ottobre 2008[^13-7] sull’organizzazione della Cancelleria federale sono trasmessi regolarmente alla Cancelleria federale.

[^13-1]: Nuovo testo giusta il n. I dell’O dell’8 nov. 2023, in vigore dal 1° gen. 2024 ([RU 2023 738](https://fedlex.data.admin.ch/eli/oc/2023/738)).
[^13-2]: [RS 235.11](https://fedlex.data.admin.ch/eli/cc/2022/568)
[^13-3]: [RS 235.1](https://fedlex.data.admin.ch/eli/cc/2022/491)
[^13-4]: Nuovo testo giusta l’all. 2 n. II 18 dell’O del 31 ago. 2022 sulla protezione dei dati, in vigore dal 1° set. 2023 ([RU 2022 568](https://fedlex.data.admin.ch/eli/oc/2022/568)).
[^13-5]: [RS 831.101](https://fedlex.data.admin.ch/eli/cc/63/1185_1183_1185)
[^13-6]: Introdotto dal n. I dell’O del 4 mag. 2022, in vigore dal 1° giu. 2022 ([RU 2022 282](https://fedlex.data.admin.ch/eli/oc/2022/282)).
[^13-7]: [RS 172.210.10](https://fedlex.data.admin.ch/eli/cc/2008/719)

#### Art. 14

**Termine di conservazione di dati personali**

<sup>1</sup> Se una persona non rientra più nel campo d’applicazione della presente ordinanza, i suoi dati nei sistemi IAM e nei servizi di elenchi sono distrutti al più tardi dopo due anni.

<sup>2</sup> Sono fatte salve le disposizioni sulla distruzione dei dati biometrici secondo l’articolo 20 capoverso 2 LSIn.[^14-1]

[^14-1]: Introdotto dal n. I dell’O del 14 nov. 2018 ([RU 2018 4739](https://fedlex.data.admin.ch/eli/oc/2018/752)). Nuovo testo giusta il n. I dell’O dell’8 nov. 2023, in vigore dal 1° gen. 2024 ([RU 2023 738](https://fedlex.data.admin.ch/eli/oc/2023/738)).

## Sezione 5: Comunicazione di dati in relazione ai sistemi IAM

#### Art. 15

**Comunicazione di dati in caso di collegamento di un sistema d’informazione a un sistema IAM**

<sup>1</sup> Se un sistema d’informazione in precedenza autonomo viene connesso a un sistema IAM e se a quest’ultimo viene affidata la verifica delle identità e di determinate proprietà personali rilevanti ai fini dei diritti, i relativi dati personali possono essere importati nel sistema IAM.

<sup>2</sup> Nel sistema IAM, per ogni sistema d’informazione a valle deve essere tenuto un elenco dei dati personali che possono essere comunicati al sistema d’informazione a valle in base alla presente ordinanza e alle basi legali del sistema a valle.

#### Art. 16

**Comunicazione di dati in caso di un singolo accesso**

Il sistema IAM autentica persone, macchine o sistemi che richiedono l’accesso a un sistema d’informazione a valle, verifica i dati necessari concernenti l’identità e le altre proprietà e attestazioni necessarie e trasmette al sistema a valle il risultato di tale verifica con i dati concernenti l’identità, le proprietà e le attestazioni rilevati.

#### Art. 17

**Comunicazione di dati personali a un gestore esterno**

<sup>1</sup> Se un sistema d’informazione della Confederazione è gestito su mandato di quest’ultima da un gestore esterno oppure se persone di cui all’articolo 8 capoversi 1 o 3 lettera a devono accedere a sistemi d’informazione esterni, i dati personali necessari a tale fine possono essere comunicati in modo automatizzato al gestore esterno a partire da sistemi d’informazione concernenti il personale, dall’archivio centralizzato delle identità o da sistemi IAM.

<sup>2</sup> A tal fine il servizio competente del sistema d’informazione gestito esternamente o che necessita l’accesso al sistema d’informazione esterno formula una richiesta scritta, specificando le persone interessate, e la invia tramite il consulente per la protezione dei dati competente all’organo federale responsabile del sistema d’informazione che fornisce i dati richiesti.[^17-1]

<sup>3</sup> Nella richiesta il servizio responsabile secondo il capoverso 2 si impegna per scritto a rispettare la legislazione federale sulla protezione dei dati, a utilizzare i dati esclusivamente per lo scopo previsto e a proteggerli conformemente allo stato della tecnica. All’organo federale responsabile del sistema d’informazione che fornisce i dati richiesti deve essere accordato un diritto di ispezione.

<sup>4</sup> Le persone interessate devono essere previamente informate.

[^17-1]: Nuovo testo giusta l’all. 2 n. II 18 dell’O del 31 ago. 2022 sulla protezione dei dati, in vigore dal 1° set. 2023 ([RU 2022 568](https://fedlex.data.admin.ch/eli/oc/2022/568)).

## Sezione 6: Misure di protezione dei sistemi IAM e dei servizi di elenchi

[^sec6-1]

[^sec6-1]: Nuovo testo giusta il n. I dell’O dell’8 nov. 2023, in vigore dal 1° gen. 2024 ([RU 2023 738](https://fedlex.data.admin.ch/eli/oc/2023/738)).

#### Art. 18

**Requisiti in materia di sicurezza delle informazioni**

<sup>1</sup> I gestori interni ed esterni di componenti di un sistema IAM e di un servizio di elenchi devono disporre di direttive scritte sulla sicurezza delle informazioni e sulla gestione dei rischi. In particolare, ogni organo responsabile secondo la presente ordinanza di un sistema o di un servizio di elenchi emana un regolamento per il trattamento secondo l’articolo 6 OPDa[^18-1].[^18-2]

<sup>2</sup> I sistemi IAM e i servizi di elenchi che non sono gestiti da servizi secondo l’articolo 2 o su loro mandato, possono essere collegati a sistemi IAM o servizi di elenchi interni alla Confederazione soltanto se soddisfano i requisiti minimi in materia di sicurezza delle informazioni.[^18-3]

<sup>3</sup> Per accedere a determinati sistemi d’informazione il servizio competente o il settore TDT della CaF possono esigere il rispetto di requisiti più severi e la presenza di determinate certificazioni.

<sup>4</sup> Il settore TDT della CaF disciplina in istruzioni i requisiti in materia di sicurezza e le procedure da rispettare.

[^18-1]: [RS 235.11](https://fedlex.data.admin.ch/eli/cc/2022/568)
[^18-2]: Nuovo testo giusta il n. I dell’O dell’8 nov. 2023, in vigore dal 1° gen. 2024 ([RU 2023 738](https://fedlex.data.admin.ch/eli/oc/2023/738)).
[^18-3]: Nuovo testo giusta il n. I dell’O dell’8 nov. 2023, in vigore dal 1° gen. 2024 ([RU 2023 738](https://fedlex.data.admin.ch/eli/oc/2023/738)).

#### Art. 19

**Trattamento dei dati nell’emissione di strumenti di identificazione elettronici**

<sup>1</sup> Per verificare l’identità del richiedente, l’emittente di uno strumento di identificazione può esigere l’esibizione del passaporto, della carta d’identità svizzera o di un documento d’identità riconosciuto per l’ingresso in Svizzera.

<sup>2</sup> Può registrare una foto o una firma del richiedente oppure può utilizzare foto o firme già memorizzate nel sistema per confrontarle con il documento d’identità.

<sup>3</sup> I dati utilizzati per l’identificazione sono salvati insieme a quelli relativi allo strumento di identificazione. Se i requisiti in materia di sicurezza concernenti lo strumento di identificazione interessato lo esigono, può essere salvata anche una copia dei documenti d’identità utilizzati per l’identificazione.

## Sezione 7: Rete di sistemi IAM

#### Art. 20

**Sistema globale IAM**[^20-1]

I sistemi IAM della Confederazione possono essere collegati tra loro e con i sistemi IAM esterni di cui all’articolo 21 al fine di costituire un sistema globale.

[^20-1]: Nuovo testo giusta il n. I dell’O dell’8 nov. 2023, in vigore dal 1° gen. 2024 ([RU 2023 738](https://fedlex.data.admin.ch/eli/oc/2023/738)).

#### Art. 21

**Condizioni per il collegamento di sistemi IAM esterni**

I seguenti sistemi esterni IAM possono essere collegati ai sistemi IAM della Confederazione per consentire l’accesso delle persone ivi registrate alle risorse della Confederazione, sempre che siano soddisfatte le condizioni e le procedure secondo gli articoli 22 e 23 e i loro gestori s’impegnino a rispettare la presente ordinanza e le direttive emanate in virtù della stessa oppure, nel caso dei Cantoni, tali sistemi garantiscano una sicurezza delle informazioni almeno equivalente:[^21-1]

- a.[^21-2] sistemi IAM comprendenti collaboratori cantonali e comunali secondo l’articolo 9 lettera a e i sistemi IAM del Principato del Liechtenstein;
- b. sistemi IAM riconosciuti dal settore TDT della CaF previsti per la rete per le identificazioni nell’ambito del Governo elettronico;
- c. sistemi IAM esteri o reti estere per le identificazioni il cui collegamento è previsto in un trattato internazionale; oppure
- d. registri degli attributi che mettono a disposizione per l’utilizzo dati relativi alle funzioni professionali conformemente alla lettera b dell’allegato.

[^21-1]: Nuovo testo giusta il n. I dell’O dell’8 nov. 2023, in vigore dal 1° gen. 2024 ([RU 2023 738](https://fedlex.data.admin.ch/eli/oc/2023/738)).
[^21-2]: Nuovo testo giusta il n. I dell’O dell’8 nov. 2023, in vigore dal 1° gen. 2024 ([RU 2023 738](https://fedlex.data.admin.ch/eli/oc/2023/738)).

#### Art. 22

**Richiesta di collegamento di sistemi IAM esterni**

<sup>1</sup> Il servizio competente invia la richiesta di collegamento di un sistema IAM esterno a un sistema IAM della Confederazione all’organo federale responsabile secondo l’articolo 5.

<sup>2</sup>

La richiesta contiene in particolare:

- a. lo scopo del collegamento;
- b. le basi legali e le altre regolamentazioni relative al sistema da collegare;
- c. una descrizione tecnica del sistema da collegare;
- d. i documenti che comprovano il rispetto dei requisiti in materia di sicurezza dell’informazione secondo l’articolo 18 capoverso 2 o 3;
- e. un parere favorevole del dipartimento competente;
- f. il parere a sostegno espresso da almeno un servizio responsabile di un sistema a valle al quale si intende accedere attraverso il sistema IAM da collegare.

#### Art. 23

**Decisione in merito al collegamento di sistemi IAM esterni**

<sup>1</sup> La decisione in merito alla richiesta di collegamento spetta all’organo federale responsabile del sistema IAM della Confederazione interessato.

<sup>2</sup> Se il sistema IAM esterno deve essere collegato, oltre al sistema IAM direttamente collegato, anche ad altri sistemi IAM della Confederazione, per l’approvazione della richiesta è necessario il consenso del settore TDT della CaF.

<sup>3</sup> L’organo federale responsabile stipula l’accordo con il servizio richiedente, ne informa il settore TDT della CaF e conferisce il mandato per il collegamento al fornitore di prestazioni competente.

<sup>4</sup> Le richieste di modiche o disattivazioni sono trattate analogamente alle richieste di collegamento.

#### Art. 24

**Collegamento di sistemi IAM della Confederazione a sistemi IAM esterni**

<sup>1</sup>

I sistemi IAM della Confederazione possono essere collegati, in qualità di fornitori di informazioni inerenti all’identificazione e all’autenticazione, a un sistema IAM esterno o a una rete esterna per le identificazioni alle seguenti condizioni:

- a.[^24-1]

  il collegamento serve a concedere alle persone di cui agli articoli 8 o 9 l’accesso:

  - 1\. ai sistemi d’informazione gestiti da un gestore esterno su mandato della Confederazione o a sistemi d’informazione terzi ai quali devono accedere per poter eseguire i loro compiti legali, oppure
  - 2\. ai sistemi d’informazione, come le applicazioni per il Governo elettronico, messi a disposizione per l’esecuzione del diritto cantonale dai Cantoni e dai Comuni nonché dalle organizzazioni e dalle persone di diritto pubblico o privato;

- b. tra la Confederazione e il gestore del sistema d’informazione beneficiario esiste un accordo che disciplina il rapporto sotto il profilo legale, organizzativo e tecnico;
- c. il collegamento è configurato in modo da permettere unicamente un accesso a sistemi d’informazione predefiniti.

<sup>2</sup> Il settore TDT della CaF disciplina in istruzioni i requisiti da soddisfare in materia di sicurezza, d’intesa con l’organo responsabile per il corrispondente sistema IAM, e periodicamente ne verifica il rispetto.

<sup>3</sup> È altresì possibile partecipare a una rete internazionale per le identificazioni sulla base di un trattato internazionale a condizione che sia garantito il rispetto dei requisiti in materia di sicurezza delle informazioni.

[^24-1]: Nuovo testo giusta il n. I dell’O dell’8 nov. 2023, in vigore dal 1° gen. 2024 ([RU 2023 738](https://fedlex.data.admin.ch/eli/oc/2023/738)).

## Sezione 8: Verbalizzazione, statistiche e documentazione

#### Art. 25

**Verbalizzazione nei sistemi IAM**

<sup>1</sup> Il sistema IAM verbalizza le autenticazioni e la comunicazione di dati concernenti l’identità solo per il tempo e nella misura necessari per consentire una gestione sicura e ordinata dei propri sistemi e dei sistemi a valle.

<sup>2</sup> I dati verbalizzati sono conservati separatamente dal sistema in cui sono trattati i dati personali e distrutti entro due anni. Essi non sono archiviati.[^25-1]

<sup>3</sup> È fatta salva una verbalizzazione più dettagliata, una conservazione prolungata o un’archiviazione dei dati protocollati concernenti gli accessi a un determinato sistema d’informazione se lo prevede su una base legale particolare.

[^25-1]: Nuovo testo giusta l’all. 2 n. II 18 dell’O del 31 ago. 2022 sulla protezione dei dati, in vigore dal 1° set. 2023 ([RU 2022 568](https://fedlex.data.admin.ch/eli/oc/2022/568)).

#### Art. 26

**Trasmissione di dati verbalizzati da sistemi IAM**

<sup>1</sup> I gestori di sistemi IAM della Confederazione possono trasmettere al servizio competente del sistema a valle i dati verbalizzati inerenti all’autenticazione e alla comunicazione di dati concernenti l’identità.

<sup>2</sup> A tal fine, tramite il consulente per la protezione dei dati, deve essere inviata all’organo responsabile del sistema IAM una richiesta scritta in cui vengono indicati lo scopo e la base legale. La trasmissione può essere concordata in maniera analoga anche nell’accordo di gestione stipulato tra l’organo responsabile e il gestore del sistema IAM.[^26-1]

<sup>3</sup> In base ai principi vigenti per l’ottenimento di servizi informatici in seno alla Confederazione la trasmissione può essere soggetta a pagamento.

[^26-1]: Nuovo testo giusta l’all. 2 n. II 18 dell’O del 31 ago. 2022 sulla protezione dei dati, in vigore dal 1° set. 2023 ([RU 2022 568](https://fedlex.data.admin.ch/eli/oc/2022/568)).

#### Art. 27

**Statistiche riguardanti i sistemi IAM**

Per far fronte alle esigenze del servizio competente del sistema IAM o del sistema d’informazione a valle possono essere elaborate statistiche sugli accessi. I dati personali devono essere resi anonimi.

#### Art. 28

**Inventario e documentazione**

<sup>1</sup>

Ogni organo che secondo la presente ordinanza è responsabile di un sistema IAM, un servizio di elenchi o un altro sistema d’informazione tiene un inventario su:

- a. i propri sistemi IAM e i propri servizi di elenchi;
- b. i sistemi d’informazione da cui sono ottenuti automaticamente dati;
- c. i sistemi d’informazione i cui dati sono messi a disposizione automaticamente;
- d. tutti i sistemi IAM con cui è collegato il proprio sistema IAM.

<sup>2</sup> I documenti e i giustificativi importanti, in particolare le richieste secondo la presente ordinanza, devono essere conservati almeno finché sono validi.

## Sezione 9: Disposizioni finali

#### Art. 29

**Esecuzione**

Il settore TDT della CaF emana le istruzioni amministrative e tecniche per realizzare e gestire i sistemi IAM della Confederazione.

#### Art. 30

**Abrogazione di un altro atto normativo**

L’ordinanza del 6 dicembre 2013[^30-1] sui servizi di elenchi della Confederazione è abrogata.

[^30-1]: [[RU 2013 4553](https://fedlex.data.admin.ch/eli/oc/2013/811)]

#### Art. 31

**Entrata in vigore**

La presente ordinanza entra in vigore il 1° gennaio 2017.

Allegato[^t-1]

(art. 11 e 13 cpv. 1 e 2)

## Categorie di dati

[^t-1]: Nuovo testo giusta il n. II dell’O dell’8 nov. 2023, in vigore dal 1° gen. 2024 ([RU 2023 738](https://fedlex.data.admin.ch/eli/oc/2023/738)).

Osservazione preliminare: per il significato degli asterischi (\*) si veda l’articolo 11 capoverso 4.

<table>
<tr><th></th><th>Servizi di elenchi</th><th>Sistemi IAM con persone secondo gli art. 8 e 9 lett. a</th><th>Sistemi IAM con persone secondo l’art. 9 lett. b</th></tr>
<tr><td>a. Dati personali</td><td>[tab]</td><td>[tab]</td><td>[tab]</td></tr>
<tr><td>1. Cognome\*</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>2. Nomi\*</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>3. Data di nascita</td><td></td><td>x</td><td>x</td></tr>
<tr><td>4. Luogo di nascita</td><td></td><td></td><td>x</td></tr>
<tr><td>5. Nazionalità</td><td></td><td></td><td>x</td></tr>
<tr><td>6. Sesso</td><td></td><td>x</td><td>x</td></tr>
<tr><td>7. Appellativo\*</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>8. Titolo\*</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>9. Iniziali\*</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>10. Identificativi personali locali</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>11. Denominazione della professione\*</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>12. Lingua per la corrispondenza\*</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>13. Particolari caratteristiche biometriche personali, segnatamente scansione dell’iride, retina, scansione delle vene, impronte digitali, impronta della mano, caratteristiche della forma del viso e profilo vocale</td><td></td><td>x</td><td></td></tr>
<tr><td>14. Immagine del viso</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>15. Numero AVS</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>b. Dati relativi al rapporto con il datore di lavoro/mandante</td><td></td><td></td><td></td></tr>
<tr><td>1. Rapporto di lavoro (interno/esterno)\*</td><td>x</td><td>x</td><td></td></tr>
<tr><td>2. Informazioni concernenti l’organizzazione e i posti in organico\*</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>3. Futura attribuzione a un’unità organizzativa</td><td>x</td><td>x</td><td></td></tr>
<tr><td>4. Categoria di personale</td><td></td><td>x</td><td></td></tr>
<tr><td>5. Numero personale (anche cantonale)</td><td>x</td><td>x</td><td></td></tr>
<tr><td>6. Funzione\*</td><td>x</td><td>x</td><td></td></tr>
<tr><td>7. Designazione del posto\*</td><td>x</td><td>x</td><td></td></tr>
<tr><td>8. Identificazione del sistema d’informazione concernente il personale (fonte)</td><td>x</td><td>x</td><td></td></tr>
<tr><td>9. Data di entrata / data di partenza</td><td>x</td><td>x</td><td></td></tr>
<tr><td>10. Numero del documento d’identità e/o del badge</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>c. Dati di contatto</td><td></td><td></td><td></td></tr>
<tr><td>1. Luogo di lavoro e indirizzo postale professionale\*</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>2. Indirizzo postale privato</td><td></td><td></td><td>x</td></tr>
<tr><td>3. Numero dell’ufficio\*</td><td>x</td><td>x</td><td></td></tr>
<tr><td>4. Elementi dell’indirizzo professionale\* come indirizzo di posta elettronica\*, numeri di telefono\*, numero di fax\*, indirizzo VOIP\*</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>5. Elementi dell’indirizzo esterno\* (per collaboratori e incaricati\*) o elementi dell’indirizzo privato</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>d. Dati sulle funzioni professionali</td><td></td><td></td><td></td></tr>
<tr><td>1. Iscrizioni registrate in albi professionali ufficiali (medico, pubblico ufficiale rogatore, avvocato ecc.)</td><td></td><td>x</td><td>x</td></tr>
<tr><td>2. Funzioni secondo il registro di commercio e altri registri di rappresentanza</td><td></td><td>x</td><td>x</td></tr>
<tr><td>e. Dati tecnici</td><td></td><td></td><td></td></tr>
<tr><td>1. Dispositivi, collegamenti, sistemi, applicazioni ecc. attribuiti</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>2. Elementi dell’indirizzo, numeri d’identificazione ecc.</td><td>x</td><td></td><td></td></tr>
<tr><td>3. Linguaggio di sistema dei dispositivi, dei collegamenti ecc.</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>4. Chiave pubblica dei certificati digitali\*</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>5. Gruppi di autorizzazioni</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>6. Nomi per la registrazione nei sistemi IT</td><td>x</td><td>x</td><td>x</td></tr>
<tr><td>7. Password (protette crittograficamente)</td><td></td><td>x</td><td>x</td></tr>
<tr><td>8. Ultimo login</td><td></td><td>x</td><td>x</td></tr>
<tr><td>9. Tentativi di login falliti</td><td></td><td>x</td><td>x</td></tr>
<tr><td>10. Status (attivo/passivo)</td><td></td><td>x</td><td>x</td></tr>
<tr><td>11. Qualità dell’autenticazione</td><td></td><td>x</td><td>x</td></tr>
<tr><td>f. Dati sui controlli di sicurezza relativi alle persone, se l’esito di quest’ultimi è una dichiarazione di sicurezza senza riserve o se l’autorità decisionale ha emanato una decisione positiva.</td><td></td><td></td><td></td></tr>
<tr><td>1. Livello di controllo</td><td></td><td>x</td><td></td></tr>
<tr><td>2. Durata di validità della dichiarazione di sicurezza</td><td></td><td>x</td><td></td></tr>
</table>
