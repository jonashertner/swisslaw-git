---
sr: "818.101.25"
title: Ordinanza del 24 giugno 2020 sul sistema di tracciamento della prossimità per il coronavirus SARS-CoV-2 (OSTP)
eli: "https://fedlex.data.admin.ch/eli/cc/2020/468"
language: it
version: 2021-03-18
adopted: 2020-06-24
in_force: 2020-06-25
source: "https://fedlex.data.admin.ch/filestore/fedlex.data.admin.ch/eli/cc/2020/468/20210318/it/xml/fedlex-data-admin-ch-eli-cc-2020-468-20210318-it-xml-1.xml"
url: "https://www.fedlex.admin.ch/eli/cc/2020/468/20210318/it"
---

> Riproduzione non ufficiale della versione consolidata (Fedlex). Fa stato la pubblicazione nella Raccolta ufficiale (art. 15 LPubb, RS 170.512).

# Ordinanza sul sistema di tracciamento della prossimità per il coronavirus SARS-CoV-2

(OSTP)

del 24 giugno 2020 (Stato 18 marzo 2021)

Il Consiglio federale svizzero,

visto l’articolo 60*a* capoverso 7 della legge del 28 settembre 2012[^ingress-1] sulle epidemie (LEp),

ordina:

[^ingress-1]: [RS 818.101](https://fedlex.data.admin.ch/eli/cc/2015/297)

#### Art. 1

**Oggetto**

La presente ordinanza disciplina i dettagli dell’organizzazione, dell’esercizio e del trattamento dei dati del sistema di tracciamento della prossimità per il coronavirus SARS-CoV-2 (sistema TP) di cui all’articolo 60*a* LEp.

#### Art. 2

**Struttura**

<sup>1</sup>

Il sistema TP include i seguenti componenti:

- a. un sistema di gestione dei dati relativi alla prossimità (sistema GP), costituito da un’applicazione installata dai partecipanti sul proprio telefono cellulare (app SwissCovid) e da un back end (back end GP);
- b. un sistema di gestione dei codici di attivazione delle informazioni (sistema di gestione dei codici), costituito da un *front end* basato sulla rete e da un back end.

<sup>2</sup> Il back end GP e il sistema di gestione dei codici sono gestiti come server centrali dall’Ufficio federale della sanità pubblica (UFSP).

#### Art. 3

**Volontarietà**

<sup>1</sup> L’installazione e l’utilizzazione dell’app SwissCovid sono volontarie.

<sup>2</sup> I partecipanti che sono stati potenzialmente esposti al coronavirus sono informati soltanto con il consenso esplicito della persona infetta.

#### Art. 4

**Organo federale responsabile**

L’UFSP è l’organo federale responsabile degli aspetti legali di protezione dei dati di tutti i componenti del sistema TP.

#### Art. 5

**Modalità di funzionamento di base**

<sup>1</sup>

Nel funzionamento di base il back end GP mette a disposizione delle app SwissCovid il suo contenuto mediante procedura di richiamo. Il contenuto consiste in un elenco con i seguenti dati:

- a. le chiavi private dei partecipanti infetti che erano di attualità nel periodo in cui altri partecipanti erano potenzialmente esposti al coronavirus (periodo rilevante);
- b. la data di ogni chiave.

<sup>2</sup>

Mediante l’utilizzazione di un’interfaccia verso il sistema operativo del telefono cellulare, l’app SwissCovid adempie le seguenti funzioni:

- a. genera almeno una volta al giorno una nuova chiave privata che non permette di risalire all’app SwissCovid, al telefono cellulare e al partecipante;
- b. scambia un codice d’identificazione che cambia almeno una volta ogni mezz’ora con tutte le app compatibili che si trovano entro la portata di Bluetooth. Il codice d’identificazione è ricavato dalla chiave privata attualmente in uso, ma non può essere ricondotto a questa chiave e non permette di risalire all’app SwissCovid, al telefono cellulare e al partecipante;
- c. memorizza i codici d’identificazione ricevuti, la potenza del segnale, la data e la durata stimata della prossimità;
- d. richiama periodicamente dal back end GP l’elenco delle chiavi private dei partecipanti contagiati e controlla se i loro codici d’identificazione memorizzati localmente sono stati generati con una chiave privata dell’elenco;
- e.[^5-1] se riscontra che almeno uno dei codici di identificazione memorizzati localmente è stato generato con una delle chiavi private dell’elenco e se sono soddisfatte le condizioni di prossimità di cui all’allegato numero 1, l’app SwissCovid invia l’informazione; la distanza della prossimità è stimata in base alla potenza del segnale ricevuto.

<sup>3</sup> Le funzioni dei sistemi operativi utilizzate tramite l’interfaccia devono adempiere le prescrizioni di cui all’articolo 60*a* LEp e alla presente ordinanza; è fatta salva la disposizione sul codice sorgente di cui all’articolo 60*a* capoverso 5 lettera e LEp. L’UFSP si assicura che queste prescrizioni siano rispettate, in particolare richiedendo le necessarie garanzie.

<sup>4</sup> ...[^5-2]

[^5-1]: Nuovo testo giusta il n. I dell’O del 18 nov. 2020, in vigore dal 19 nov. 2020 ([RU 2020 4733](https://fedlex.data.admin.ch/eli/oc/2020/852)).
[^5-2]: Abrogato dal n. I dell’O del 18 nov. 2020, con effetto dal 19 nov. 2020 ([RU 2020 4733](https://fedlex.data.admin.ch/eli/oc/2020/852)).

#### Art. 6

**Modalità di funzionamento dopo un’infezione**

<sup>1</sup> Se un’infezione è confermata, un servizio autorizzato può, con il consenso della persona infetta, richiedere un codice di attivazione unico e limitato nel tempo al sistema di gestione dei codici; a tale scopo, trasmette a quest’ultimo la data in cui si sono manifestati i primi sintomi o, se la persona infetta non presenta sintomi, la data in cui è stato effettuato il test.[^6-1]

<sup>2</sup> Il servizio autorizzato comunica il codice di attivazione alla persona infetta.[^6-2] Quest’ultima lo può immettere nella sua app SwissCovid.

<sup>3</sup> Il back end del sistema di gestione dei codici conferma all’app SwissCovid la validità del codice immesso. Dalla data registrata sottrae il numero di giorni secondo l’allegato numero 2.[^6-3] Il back end del sistema di gestione dei codici trasmette questa data all’app SwissCovid della persona infetta.

<sup>4</sup> L’app SwissCovid della persona infetta trasmette al back end GP le chiavi private che erano di attualità nel periodo rilevante unitamente alla data corrispondente.

<sup>5</sup> Il back end GP inserisce nel suo elenco le chiavi private ricevute unitamente alle date corrispondenti.

<sup>6</sup> Dopo la trasmissione delle chiavi private, l’app SwissCovid genera una nuova chiave privata. Da quest’ultima non è possibile risalire a precedenti chiavi private.

[^6-1]: Nuovo testo giusta il n. I dell’O del 18 nov. 2020, in vigore dal 19 nov. 2020 ([RU 2020 4733](https://fedlex.data.admin.ch/eli/oc/2020/852)).
[^6-2]: Nuovo testo giusta il n. I dell’O del 18 nov. 2020, in vigore dal 19 nov. 2020 ([RU 2020 4733](https://fedlex.data.admin.ch/eli/oc/2020/852)).
[^6-3]: Nuovo testo del per. giusta il n. I dell’O del 18 nov. 2020, in vigore dal 19 nov. 2020 ([RU 2020 4733](https://fedlex.data.admin.ch/eli/oc/2020/852)).

#### Art. 7

**Contenuto dell’informazione**

<sup>1</sup>

L’informazione include:

- a. l’informazione che il partecipante è stato potenzialmente esposto al coronavirus;
- b.[^7-1] l’indicazione dei giorni in cui lo è stato;
- c. l’informazione che l’UFSP gestisce una linea di consulenza telefonica gratuita;
- d. le raccomandazioni di comportamento dell’UFSP.

<sup>2</sup> Il sistema TP non dà istruzioni ai partecipanti.

[^7-1]: Nuovo testo giusta il n. I dell’O del 18 nov. 2020, in vigore dal 19 nov. 2020 ([RU 2020 4733](https://fedlex.data.admin.ch/eli/oc/2020/852)).

#### Art. 8

**Contenuto del sistema di gestione dei codici**

<sup>1</sup>

Il sistema di gestione dei codici contiene i seguenti dati:

- a. i codici di attivazione;
- b. la data in cui si sono manifestati i primi sintomi o, se la persona infetta non presenta sintomi, la data in cui è stato effettuato il test;
- c. la data di distruzione dei dati di cui alle lettere a e b.

<sup>2</sup> Questi dati non permettono di risalire ai partecipanti.

#### Art. 8a

**Modalità di accesso al sistema di gestione dei codici**[^8a-1]

L’accesso al sistema di gestione dei codici può avvenire mediante:

- a. uno specialista del servizio autorizzato attraverso il *front end*; oppure
- b. un’interfaccia tra il sistema di gestione dei codici e un sistema del servizio autorizzato.

[^8a-1]: Introdotto dal n. I dell’O del 18 nov. 2020, in vigore dal 19 nov. 2020 ([RU 2020 4733](https://fedlex.data.admin.ch/eli/oc/2020/852)).

#### Art. 9

**Accesso al sistema di gestione dei codici attraverso il *front end*[^9-1]**

<sup>1</sup>

Possono richiedere il codice di attivazione attraverso il *front end* le seguenti persone che agiscono per conto del servizio autorizzato interessato:[^9-2]

- a. i medici cantonali;
- b. il medico in capo dell’esercito;
- c. altri collaboratori dei servizi medici cantonali o del servizio medico militare dell’esercito;
- d. i terzi incaricati dai servizi medici cantonali o dal servizio medico militare dell’esercito;
- e.[^9-3] i collaboratori di studi medici;
- f.[^9-4] i collaboratori dei laboratori titolari di un’autorizzazione secondo l’articolo 16 LEp;
- g.[^9-5] i collaboratori delle strutture di cui all’articolo 24 capoverso 1 lettera b dell’ordinanza 3 COVID-19 del 19 giugno 2020[^9-6];
- h.[^9-7] i collaboratori della linea telefonica di cui all’articolo 7 capoverso 1 lettera c.

<sup>2</sup> La registrazione nel sistema di gestione dei codici avviene mediante il sistema centrale di accesso e autorizzazione dell’Amministrazione federale per le applicazioni di rete. Sono applicabili le disposizioni dell’ordinanza del 19 ottobre 2016[^9-8] sui sistemi di gestione delle identità e sui servizi di elenchi della Confederazione.

<sup>3</sup> L’UFSP concede e amministra i diritti di accesso al sistema di gestione dei codici. Può autorizzare i medici cantonali e il medico in capo dell’esercito o singoli loro assistenti a concedere i diritti di accesso ad assistenti.

[^9-1]: Nuovo testo giusta il n. I dell’O del 18 nov. 2020, in vigore dal 19 nov. 2020 ([RU 2020 4733](https://fedlex.data.admin.ch/eli/oc/2020/852)).
[^9-2]: Nuovo testo giusta il n. I dell’O del 18 nov. 2020, in vigore dal 19 nov. 2020 ([RU 2020 4733](https://fedlex.data.admin.ch/eli/oc/2020/852)).
[^9-3]: Nuovo testo giusta il n. I dell’O del 18 nov. 2020, in vigore dal 19 nov. 2020 ([RU 2020 4733](https://fedlex.data.admin.ch/eli/oc/2020/852)).
[^9-4]: Introdotta dal n. I dell’O del 18 nov. 2020, in vigore dal 19 nov. 2020 ([RU 2020 4733](https://fedlex.data.admin.ch/eli/oc/2020/852)).
[^9-5]: Introdotta dal n. I dell’O del 18 nov. 2020, in vigore dal 19 nov. 2020 ([RU 2020 4733](https://fedlex.data.admin.ch/eli/oc/2020/852)).
[^9-6]: [RS 818.101.24](https://fedlex.data.admin.ch/eli/cc/2020/438)
[^9-7]: Introdotta dal n. I dell’O del 18 nov. 2020, in vigore dal 19 nov. 2020 ([RU 2020 4733](https://fedlex.data.admin.ch/eli/oc/2020/852)).
[^9-8]: [RS 172.010.59](https://fedlex.data.admin.ch/eli/cc/2016/610)

#### Art. 9a

**Accesso al sistema di gestione dei codici attraverso l’interfaccia**[^9a-1]

L’UFSP consente ai servizi autorizzati secondo l’articolo 9 capoverso 1 di collegare il loro sistema a quello di gestione dei codici attraverso l’interfaccia, purché il sistema in questione garantisca un livello di sicurezza adeguato.

[^9a-1]: Introdotto dal n. I dell’O del 18 nov. 2020, in vigore dal 19 nov. 2020 ([RU 2020 4733](https://fedlex.data.admin.ch/eli/oc/2020/852)).

#### Art. 10

**Prestazioni di terzi**

<sup>1</sup> L’UFSP può incaricare terzi di mettere a disposizione delle app SwissCovid mediante procedura di richiamo l’elenco dei dati necessari per le informazioni.

<sup>2</sup> Può conferire a terzi la concessione dei diritti di accesso al sistema di gestione dei codici. I terzi incaricati devono garantire un controllo affidabile e giuridicamente corretto delle autorizzazioni degli specialisti.

<sup>3</sup> I terzi incaricati devono impegnarsi contrattualmente a rispettare le prescrizioni dell’articolo 60*a* LEp e della presente ordinanza; è fatta salva la disposizione sul codice sorgente di cui all’articolo 60*a* capoverso 5 lettera e LEp. L’UFSP controlla il rispetto delle prescrizioni.

#### Art. 11

**Registro degli accessi**

<sup>1</sup> Alla memorizzazione e all’analisi dei registri degli accessi al back end GP e al sistema di gestione dei codici, nonché all’elenco di cui all’articolo 10 capoverso 1 sono applicabili gli articoli 57*i*–57*q* della legge del 21 marzo 1997[^11-1] sull’organizzazione del Governo e dell’Amministrazione e l’ordinanza del 22 febbraio 2012[^11-2] sul trattamento di dati personali derivanti dall’utilizzazione dell’infrastruttura elettronica della Confederazione.

<sup>2</sup> Oltre a questi registri e alla registrazione delle prossimità, il sistema TP non tiene registri delle attività del *front end* del sistema di gestione dei codici e delle app SwissCovid.

[^11-1]: [RS 172.010](https://fedlex.data.admin.ch/eli/cc/1997/2022_2022_2022)
[^11-2]: [RS 172.010.442](https://fedlex.data.admin.ch/eli/cc/2012/160)

#### Art. 12

**Comunicazione per scopi statistici**

L’UFSP mette periodicamente a disposizione dell’Ufficio federale di statistica (UST) per valutazioni statistiche la raccolta dei dati disponibili in quel momento nei due back end in forma completamente anonimizzata.

#### Art. 13

**Distruzione dei dati**

<sup>1</sup> I dati del sistema GP sono distrutti sia sul telefono cellulare sia nel back end GP 14 giorni dopo la loro registrazione.

<sup>2</sup> I dati del sistema di gestione dei codici sono distrutti 24 ore dopo la loro registrazione.

<sup>3</sup> I dati dei registri di terzi incaricati ai sensi dell’articolo 10 capoverso 1 sono distrutti 7 giorni dopo la loro registrazione.

<sup>4</sup> Per il rimanente, la distruzione dei dati dei registri è retta dall’articolo 4 capoverso 1 lettera b dell’ordinanza del 22 febbraio 2012[^13-1] sul trattamento di dati personali derivanti dall’utilizzazione dell’infrastruttura elettronica della Confederazione.

<sup>5</sup> Anche i dati messi a disposizione dell’UST sono distrutti conformemente al presente articolo.

[^13-1]: [RS 172.010.442](https://fedlex.data.admin.ch/eli/cc/2012/160)

#### Art. 14

**Controllo del codice sorgente**

<sup>1</sup> L’UFSP pubblica i dati necessari per controllare se i programmi leggibili dalle macchine di tutti i componenti del sistema TP sono stati creati sulla base del codice sorgente pubblico.

<sup>2</sup> Effettua il controllo anche in modo autonomo.

#### Art. 15

**Disattivazione dell’app SwissCovid e rapporto**

<sup>1</sup> Al momento dell’abrogazione della presente ordinanza, l’UFSP disattiva l’app SwissCovid e chiede ai partecipanti di disinstallarla dal loro telefono cellulare.

<sup>2</sup> Entro sei mesi dall’abrogazione l’UFSP fa rapporto al Consiglio federale.

#### Art. 15a

**Collegamento del sistema TP a sistemi esteri corrispondenti**[^15a-1]

<sup>1</sup> Il sistema TP può essere collegato a un sistema estero (art. 62*a* LEp) soltanto se questo soddisfa le condizioni di cui all’articolo 60*a* capoverso 5 lettere a–d LEp.

<sup>2</sup> Per il collegamento, il back end GP e il sistema estero sono collegati a un sistema di collegamento per la trasmissione reciproca delle chiavi private dei partecipanti infetti.

<sup>3</sup>

Il sistema di collegamento sottostà alle seguenti regole:

- a. è gestito dall’UFSP o dal servizio estero competente;
- b. al codice sorgente e alle specifiche tecniche dei sistemi di collegamento gestiti dall’UFSP si applicano l’articolo 60*a* capoverso 5 lettera e LEp e l’articolo 14 della presente ordinanza;
- c. gli scopi dell’elaborazione sono retti dall’articolo 60*a* capoverso 2 LEp;
- d. i dati del sistema possono essere resi noti all’UST e al servizio estero competente a scopi statistici in forma completamente anonimizzata;
- e. i dati del sistema sono distrutti non appena non sono più necessari per l’informazione dei partecipanti, ma al più tardi 14 giorni dopo la loro trasmissione al sistema.

<sup>4</sup>

Se il sistema TP è collegato a un sistema estero, oltre alle modalità di funzionamento del sistema TP di cui agli articoli 5 e 6 vale quanto segue:

- a. nel funzionamento di base, il back end GP richiama dal sistema di collegamento le chiavi private dei partecipanti infetti del sistema estero nonché la data di queste chiavi e le inserisce nel suo elenco;
- b. dopo un’infezione, il back end GP trasmette la chiave privata della persona infetta con la rispettiva data al sistema estero mediante il sistema di collegamento.

[^15a-1]: Introdotto dal n. I dell’O del 12 mar. 2021, in vigore dal 18 mar. 2021 ([RU 2021 144](https://fedlex.data.admin.ch/eli/oc/2021/144)).

#### Art. 16

**Abrogazione di un altro atto normativo**

L’ordinanza COVID-19 test pilota di tracciamento di prossimità del 13 maggio 2020[^16-1] è abrogata.

[^16-1]: [[RU 2020 1589](https://fedlex.data.admin.ch/eli/oc/2020/324)]

#### Art. 16a

**Aggiornamento dell’allegato**[^16a-1]

Il Dipartimento federale dell’interno (DFI) aggiorna l’allegato alla presente ordinanza secondo lo stato attuale della scienza.

[^16a-1]: Introdotto dal n. I dell’O del 18 nov. 2020, in vigore dal 19 nov. 2020 ([RU 2020 4733](https://fedlex.data.admin.ch/eli/oc/2020/852)).

#### Art. 17

**Entrata in vigore e durata di validità**

La presente ordinanza entra in vigore il 25 giugno 2020 alle ore 00.00 e si applica fino al 30 giugno 2022.

Allegato*[^t-1]*

(art. 5 cpv. 2 lett. e e 6 cpv. 3)

## Condizioni di prossimità epidemiologiche e periodo rilevante

[^t-1]: Nuovo testo giusta il n. II dell’O del 18 nov. 2020, in vigore dal 19 nov. 2020 ([RU 2020 4733](https://fedlex.data.admin.ch/eli/oc/2020/852)).

### 1. Condizioni di prossimità epidemiologiche

Le condizioni di prossimità epidemiologiche sono soddisfatte se:

- a. vi è stata una prossimità fisica di 1,5 metri o meno con il telefono cellulare di almeno un partecipante infetto;
- b. la somma della durata di tutte le prossimità secondo la lettera a raggiunge o supera i 15 minuti in una giornata.

### 2. Inizio del periodo rilevante sotto il profilo epidemiologico

Numero di giorni da sottrarre: due.
