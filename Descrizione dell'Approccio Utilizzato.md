**Table of Contents**  *generated with [DocToc](http://doctoc.herokuapp.com/)*

- [Descrizione Dell'Approccio Utilizzato](#)
	- [Introduzione](#)
	- [Glossario](#)
	- [Project Team](#)
- [Scoping](#)
	- [Meetings](#)
		- [Stesura del Report[Meeting Agenda]](#)
		- [Partecipanti](#)
		- [Lista dei Meetings](#)
	- [Conditions of Satisfaction](#)
	- [Requirements Breakdown Structure](#)
		- [Raccolta Dei Requisiti](#)
	- [Scelta del PMLC Model](#)
	- [Analisi dei Rischi (Risk Analysis)](#)
		- [Failure Mode, Effects, and Criticality Analysis](#)
	- [Project Overview Statement](#)
	- [Scelta del Core Team](#)
- [Planning](#)
		- [Deliverables](#)
		- [Project Definition Statement](#)
		- [Analisi Dei Rischi](#)
		- [Work Breakdown Statement](#)
		- [Stime Delle Attivita' e Dei Costi](#)
		- [Risorse Necessarie e Assegnamento](#)
		- [Project Network Diagram](#)
		- [Scope Bank](#)
- [Executing](#)
	- [Responsability Matrix](#)
	- [Problem Solving](#)
	- [Decision Making](#)
	- [Team Meetings](#)
	- [Change Request](#)
	- [Project Impact Statement](#)
	- [Altre Policies](#)
	- [Testing e Documentazione](#)
- [Monitoring & Control](#)
	- [Scope Bank](#)
	- [Issue Log](#)
- [Closing Project](#)
	- [Strategia di Implementazione e Collaudo](#)
	- [Documentazione](#)
	- [Accettazione da parte del Cliente](#)
	- [Installazione dei Deliverables](#)
	- [Lessons Learned](#)

Descrizione Dell'Approccio Utilizzato
=======

Introduzione
-------
In questo documento verranno riassunte e motivate tutte le scelte utilizzate all'interno del progetto. Inoltre verranno poi aggiunte anche tutte quelle parti che riguardano le convenzioni extra-progetto  e che quindi non rientrano nella documentazione del progetto stesso ma bensi' in quella che dovrebbero essere le norme generali che governano tutti i progetti intrapresi dall'ipotetica azienda incui questo progetto viene sviluppato. Si cerchera' di tralasciare tutti quegli aspetti che non riguardano il project management in modo da renderlo il piu' snello possibile.

Glossario
-------
- **Lezione**: Svolgimento effettivo dell'insegnamento
- **Aula**: Luogo effettivo della lezione
- **Docente**: Colui che svolge la lezione
- **Risorsa**: Si fa riferimento a qualsiasi cosa effettivamente associato ad una lezione, quindi anche il docente e' considerato nell'insieme quando si usa questo termine.
- **Altre Risorse**: Risorse coinvolte nella lezione (Proiettori, strumenti per dimostrazioni varie)
- **Studente**: Colui che segue le varie lezioni con lo scopo di apprendere la materia e superare l'esame.
- **Esame**: Verifica dell'apprendimento dello studente
- **Corso**: Insieme di lezioni che trattano lo stesso argomento e culminano
nello stesso esame

Project Team
-------
Questa parte sara' ricorrente durante tutto il progetto perche', in base alle fasi che si attraverseranno nella realizzazione del progetto sara' necessario andare a formalizzare i ruoli delle varie persone all'interno del progetto stesso. In particolare noi abbiamo individuato vari momenti che precedono le fasi piu' importanti del progetto nelle quali risulta importante andare a definire alcune figure chiave del team del progetto stesso.

Di conseguenza, inizialmente, prima del progetto di scoping e' necessario andare a definire **chi e' il project manager sia lato committente che lato fornitore** che si occupera' della gestione del progetto e quindi che ne assumera' le principali responsabilita'. Insieme a questi chiaramente anche i loro collaboratori, infatti si puo' gestire un progetto a livello strategico anche in piu' persone, magari con esperienza nel settore, che possono dare un valido contributo e un diverso punto di vista.

Scoping
=======
In questa sezione verranno racchiuse tutte le scelte relative alla parte di scoping. In particolare si e' deciso di suddividere i vari argomenti in base ai deliverables che i processi coinvolti dovranno produrre. In aggiunta viene discussa l'organizzazione dei meeting per ottenere i deliverables.

Meetings
-------
Si vogliono discutere i principali meetings necessari per il raggiungimento dei deliverables relativi allo scoping, chi sara' presente a questi meetings e soprattutto identificare in maniera rigorosa (ma non per questo immutabile) quelle che sono le tempistiche per quanto riguarda la conclusione della fase di scoping.
Nel caso sia necessario, nel corso del tempo, effettuare nuove riunioni al fine di raffinare qualche deliverables a fronte di cambiamenti di scope dettati da una qualsiasi causa (eg. richieste del committente, problematiche tecniche) e' necessario aggiungerla alla lista che si trova alla fine della sezione

###Stesura del Report[Meeting Agenda]###
Per quanto riguarda la stesura del report si vogliono solo indicare le informazioni principali che questi devono contenere:

 - Data
 - Luogo
 - Partecipanti
 - Durata complessiva
 - Titolo e descrizione piu' dettagliata delle motivazioni
 - Agenda della riunione (dove ogni sezione possibilmente e' scandita da una sua tempistica precisa)
 - Conclusioni tratte dalla riunione svolta
 - Indicazione per la prossima riunione se sono presenti i presupposti per pianificarla
 - Firma del responsabile della riunione e del dattilografo che ha stilato il report.

Si faccia riferimento al template indicato nei documenti di progetto. Si vuole far notare come nel template sia gia' presente una attivita' iniziale che serve per assicurarsi che siano presenti tutte le figure professionali richieste e per fare una ricapitolazione delle riunioni precedenti, se presenti.

###Partecipanti###
Di seguito viene indicata una lista delle figure professionali che devono essere presenti ai meeting di scoping. Chiaramente neanche questa e' fissata, questa parte vuole essere solo un invito per quelle che sono le figure piu' importanti:

 - Project Manager: di entrambe le parti (committente e fornitore)
 - Architetto e Core Team
 - Facilitatore
 - Redattore
 - Eventuali dirigenti [Senior Management]

In base allo scope della riunione i partecipanti possono cambiare, ad esempio se si deve parlare di questioni tecniche riguardanti il deploying e' consigliata la presenza di un tecnico sistemista.

###Lista dei Meetings###
Viene illustrata una lista dei meeting necessari in maniera ridotta. In particolare verranno indicate:

 - La data della riunione
 - Il motivo principale della riunione
 - Deliverables coinvolti dalla riunione
 - Riferimento al report dettagliato della riunione


----------

 1. 1/7/15 - "Riunione conoscitiva e di introduzione al progetto, glossario e descrizione dei processi del cliente" - [COS] - Report COS#001
 2. 8/7/15 - "Prima discussione delle Conditions of Satisfaction e requisiti principali"  - [COS] - Report COS#002
 3. 15/7/15 - "Raffinamento delle COS e dei requisiti principali" (dal committente)  - [COS + POS] - Report COS#003
 4. 16/7/15 - "Visione del processo attuale ed eventuali interviste agli operatori" (dal committente)  - [RBS, requirements] - Report RBS#001
 4. 22/7/15 - "Definizione Formalizzata delle COS e dei requisiti principali"  - [COS + POS] - Report COS#004
 5. 24/7/15 - "Consegna e discussione dei primi mockup dell'applicativo" - [RBS, requirements] - Report RBS#002
 6. 28/7/15 - "Revisione dei mockup e approvazione del cliente" - [RBS] - Report RBS#003
 7. 31/7/15 - "Definizione della RBS" - [RBS] - Report RBS#004
 8. 5/8/15 - "Analisi dei Rischi" - [Risk Analysis] - Report RA#001
 9. 7/8/15 - "Scelta del ciclo di sviluppo del progetto e Raffinamento del POS" - [PMLC Model + POS] - Report LCM#001
 10. 11/8/15 - "Versione finale del POS e presentazione dello stesso per il senior management" - [POS] - Report POS#001
 11. 20/08/15 - "JPPS - Planning Kickoff and PDS" - [PDS] - Report PDS#001 
 12. 25/08/15 - "Analisi Dei Rischi e WBS" - [Risk Analysis - WBS] - Report RAWBS#001
 13. 28/08/15 - "Completamento WBS e Stime" - [WBS - Stime] - Report WBSES#001
 14. 01/09/15 - "Completamento Stime e Gantt" - [Stime - Gantt] - Report ESGANTT#001
 15. 03/09/15 - "Completamento Gantt e Assegnamento Risorse - [Gantt - Assegnamento Risorse] - Report GANTT#001
 16. 07/09/15 - "Kickoff Meeting Execution" - [Operative Rules] - Report RULE#001
 
Conditions of Satisfaction
-------
Per la raccolta delle condition of satisfaction e' stato difficile trovare un vero e proprio template perche' spesso tutto viene direttamente riversato nella stesura stessa del POS e quindi non si ha un vero e proprio documento a riguardo.
Ad ogni modo, per rendere tutto piu chiaro, anche e soprattutto a me che devo sviluppare l'elaborato, si e' deciso di stillare comunque una lista ordinata per priorita' in modo da ordinare i vari requirements che sono presenti all'interno del progetto.
Si e' deciso quindi di dare maggiore importanza ai requisiti che direttamente interessano l'utente, come le performance e l'usabilita', cercando di trovare un modo corretto per poterle valutare, i requisiti minimi direttamente espressi dal committente e le funzionalita' principali che rendono il progetto utile. Si faccia riferimento al documento per ulteriori dettagli.

Requirements Breakdown Structure
--------------------------------
Per la creazione di questo deliverablesi si e' deciso di suddividere il tutto in varie fasi, in modo da facilitare la stesura del documento.
La costruzione della RBS ha inizio durante le ultimi raffinamenti delle condition of satisfaction in modo che, almeno le prime fasi di questo processo coincidano con le ultime di quello precedente. Facendo cio' anche le condition of satisfaction sono fortemente facilitate proprio dal fatto che queste sono intrinsecamente legate ai requisiti ad esempio.

###Raccolta Dei Requisiti###
Tra i metodi che si potevano adottare per la raccolta dei requisiti si e' deciso di utilizzarne vari in modo da ridurre eventuali problemi dovuti all'ulitizzo di un'unica metodologia e dare quindi un punto di vista piu' ampio sulla situazione attuale e su cosa vuole il cliente.
Nel dettaglio si e' scelto di effettuare una giornata dal committente in modo da avere una visione di quali sono i processi aziendali ed eventualmente, se qualcosa risultasse poco chiaro, effettuare qualche intervista ai principali operatori in modo da verificare se i bisogni coincidono con il risultato dell'analisi. In questo periodo, in particolare (estate) risulta essere il periodo migliore perche' il committente si sta preparando per la creazione dell'orario per il semestre successivo, quindi e' possibile osservare l'intero processo mentre questo viene eseguito.
In una secondo incontro invece il fornitore dovra' fornire dei mockup di come sara' l'aspetto dell'applicativo per avere un feedback dal committente e capire che cosa vada messo in primo piano e cosa invece vada nascosto. Questo consentira' eventualmente anche di capire che cosa e' effettivamente prioritario e cosa non lo e', inoltre evita che il fornitore debba effettivamente sviluppare una soluzione difficilmente integrabile nel prodotto finale e senza la dovuta documentazione.
Allo stesso tempo il committente invece puo' documentarsi del dettaglio per quanto riguarda gli use case del processo attualmente in atto in modo da creare una documentazione che potra' tornare utile anche come riferimento per sviluppi futuri o come punto di partenza per una discussione basata sulla reingegnerizzazione dei suoi processi. Inoltre risulta molto utile soprattutto se, in una prima soluzione, si e' deciso di escludere eventuali requisiti minori che poi potranno essere presi in considerazione in sviluppi futuri.

Scelta del PMLC Model
--------------------------
Per quanto riguarda la scelta del Modello per il ciclo di vita del progetto si e' deciso di attuare una modalita' *iterativa*.
Le motivazioni principali che hanno portato a questa scelta scaturiscono direttamente dal progetto e da come il committente si approccia ad esso.
E' apparso in fase di analisi che il committente fosse ben convinto per quanto riguarda la maggior parte dei requisiti principali presentati, ma che riservasse ancora dei dubbi su come questi devono essere realizzati. Inoltre e' ben chiaro anche quali siano le priorita' sui requisiti presentati.
Di conseguenza con questo approccio posso pensare di pianificare piu iterazioni, una per requisito, ordinate in base alla priorita' dei requisiti stessi e alla fine di ogni iterazione fornire una versione del prodotto, magari pianificando una milestone, che possa fornire al cliente un'idea su come procedono i lavori e di conseguenza agire direttamente sulle modifiche da apportare.
Quando infine il cliente si dira' soddisfatto del prodotto si procedera' con la fase di chiusura del progetto.

Analisi dei Rischi (Risk Analysis)
--------------------------
In questa sezione verranno presi in esame i rischi principali correlati con il progetto, di conseguenza saranno classificati per gravita e per la probabilita' che questi si verifichino. In questo modo si sara' in grado di stimare effettivamente quanto e' il rischio complessivo dell'intero progetto e quindi anche influenzare la prioritizzazione e realizzazione delle attivita' da svolgere relative ai requisiti al fine di ridurre al minimo la possibilita' di rischi, oppure influenzare effettivamente la scelta del senior management riguardo la partenza o meno dell'intero progetto.
Essendo questo un esercizio didattico sul management si e' comunque deciso di individuare solo i rischi di malfunzionamento principali al fine di snellire la trattazione e concentrarsi adeguatamente anche sulle successive parti dell'elaborato. Le motivazioni e le contromisure sono state direttamente spiegate all'interno del documento per far si di snellire questo documento e perche' puo' essere effettivamente utile avere all'interno del template una spiegazione discorsiva dell'analisi. Inoltre e' utile questa prima analisi dei rischi per due motivi:

*  Come template per l'analisi dei rischi che deve essere fatta in fase di planning per ogni iterazione.
*  Perche' i rischi principali che si possono riscontrare possono essere utili per la stesura del POS e possono anche portare a nuovi requisiti o ad un'estensione di quelli gia' presenti.

Tutto questo deve quindi essere considerato come un semplice esempio di una vera analisi dei rischi, che pero' segue in ogni caso la metodologia che viene illustrata, in quando realmente applicata anche in contesti reali.

### Failure Mode, Effects, and Criticality Analysis ###
Per l'individuazione dei rischi si e' deciso di utilizzare un semplice approccio molto conosciuto per svolgere questa analisi che coincide semplicemente nel:

1.  Identificazione tutti i possibili malfunzionamenti o difetti dei componenti del prodotto.
2.  Per ogni modo di malfunzionamento/difetto dei componenti descrizione degli effetti e delle possibili cause.
3.  Per ogni modo di malfunzionamento/difetto ricerca delle azioni possibili per ridurne gli effetti.
4.  Definizione delle scale di punteggio dei tre parametri:
  *  Probabilita' di accadimento del malfunzionamento/difetto base
  *  Severita' degli effetti del malfunzionamento/difetto base
  *  Rilevabilita' del malfunzionamento/difetto base.
5.  Attribuzione dei punteggi ai parametri.
6.  Valutare e decidere gli interventi da intraprendere.

-------
Per avere un esempio di Risk analysis si faccia riferimento al documento apposito.

Project Overview Statement
--------------------------
Per la stesura del POS si e' proceduto per gradi: mano in mano che il processo di scoping progrediva e venivano svolte le riunioni che andavano a consolidare le condition of satisfaction e la struttura gerarchica dei requisiti(RBS) il POS veniva aggiornato in modo da rispecchiare il piu' fedelmente possibile il procedere dei lavori. Una volta che tutte le fasi precedenti sono terminate, la versione finale e' stata sottoposta al senior management per l'approvazione.
Gli aspetti principali che si sono considerati per la creazione del documento sono stati:

* Un'attenzione particolare alla misurazione dei criteri di successo e delle richieste del cliente evidenziando come fare per verificare la riuscita del progetto al fine di tutelarsi per eventuali problematiche future.
* L'aggiunta di quelli che possono essere i vantaggi per l'azienda nell'intraprendere il progetto in esame.
* L'intenzione di voler evidenziare fin da subito quali sono le varie parti che dovranno comporre il sistema in modo da rinforzare l'idea della compartimentazione e soprattutto la scelta del ciclo di vita che si e' introdotto nella sezione precedente.

Scelta del Core Team
----------
Una volta conclusa la fase di scoping (raggiunti e consolidati tutti i suoi deliverables) e' necessario andare a individuare quello che e' il core team del progetto. Questo e' importante per sapere chi e' effettivamente all'interno delle risolrse che si possono utilizzare le progetto stesso e che quindi partecipano attivamente alla fase di planning. Chiaramente queste possono essere anche diverse da quelle che hanno partecipato allo scoping, anche se di solito viene condivisa la parte che riguarda chi gestisce il progetto e chi ha piu' esperienza sul campo.

In particolare, io preferisco cercare di scegliere tutto il team, anche quello che effettivamente andra' ad effettuare il progetto in questo momento del progetto stesso perche' mi da piu' sicurezza su quali e quante sono le risorse disponibili. Chiaramente quando e' possibile, altrimenti si possono utilizzare degli alias che non corrispondono fisicamente a nessuno di specifico, ma che mi danno la certezza che poi avro' una risorsa di quel tipo e che quindi sono in grado di pianificarla come dovuto.

Planning
=======
La gestione della parte di planning e' fortemente influenzata dalla scelta del ciclo di vita del progetto.(iterativa) Conseguentemente verra' preso in esame unicamente il primo requisito principale presente nella RBS risultante dalla fase di scope, come esempio, per tutti gli altri verranno solamente indicati i documenti risultanti dalla fase di scoping.
Questo consente di snellire in ogni caso questo documento ed eventualmente, se si ritiene necessario giustificare certe scelte particolari fatte per il planning delle attivita' di altri requisiti, queste saranno discusse in una sottosezione a parte.
Inoltre e' possibile adottare questo tipo di pianificazione perche' ogni requisito presente nella RBS viene trattato separatamente dagli altri e in maniera isolata. Questo consente una pianificazione piu mirata sul requisito stesso e la possibilita' di rilasciare alla fine del ciclo un prodotto al committente, in modo che questo possa valutarlo e collaudarlo, prima di passare al ciclo successivo.

Come caso di studio verra' affrontato il planning del primo requisito, quindi la realizzazione della pianificazione delle lezioni. 

###Deliverables###
Per maggior chiarezza vengono elencati i deliverables che la fase di planning deve produrre:

1. Project Definition Statement(PDS)
2. Analisi dei Rischi
3. Work Breakdown Statement(WBS)
4. Stima delle Attivita'
5. Risorse necessarie e assegnamento.
6. Dipendenza tra le attivita' (Project Network Diagram)

###Project Definition Statement###
All'interno del Project Definition Statement vengono raccolte in maniera dettagliata tutto quello che si e' deciso in fase di scoping, estendendo il POS. Cambia, oltre alla lunghezza del documento, anche il destinatario, che non sara' piu' il senior management ma pensi' il team aziendale. Questo fa si che si abbia un riferimento unico a tutto il team.

Il Project Definition Statement non e' un documento che viene rielaborato ad ogni iterazione ocme invece avviene per gli altri documenti della fase di planning.

###Analisi Dei Rischi###
Per l'analisi dei rischi e' stato preso il template gia' introdotto con il risk analiysis in fase di scoping ed e' stato effettuato in maniera peculiare per il requisito in esame. Si rimanda il lettore al documento associato, al suo intero sara' presente anche una spiegazione delle motivazioni percui si sono scelti certi rischi e le possibili contromisure. La presenza di un'analisi dei rischi a questo livello consente di individuare problematiche specifiche del requisito in esame e di prepararsi quindi nel caso qualcuno di quelli individuati si verifichi.

###Work Breakdown Statement###
La WBS verra' indicata separatamente, una per ogni requisito, in questo modo sara' possibile ridurre la complessita' della costruzione intera della WBS e concentrarsi direttamente sulle attivita' specifiche del singolo requisito in esame.
Per quanto riguarda le dipendenze delle varie attivita' che si possono avere, queste vengono analizzate alla fine del processo che le individua e le formalizza all'interno della WBS. In particolare, per questo caso incui si creeranno diverse WBS, una per ogni ciclo di iterazione, gia' dalla seconda prodotta si potra' andare ad analizzare e vedere se una delle attivita' da svolgere ha delle somiglianze con una gia' effettuata, in modo da avere un confronto in stime, costi, risorse e problematiche che hanno caratterizzato la precedente attivita'.
 
###Stime Delle Attivita' e Dei Costi###
Per le stime delle attivita' si e' deciso di utilizzare un consensus based seguendo una serie di round, da un minimo di 2 fino ad un massimo di 10 in modo da raggiungere una stima piu veritiera, il numero di round dipendera' prevalentemente dal come i valori del round precedente sono distanti tra di loro.

Coloro che parteciperanno alle stime sono:

* L'Architetto
* Gli sviluppatori del team
* Esperti aziendali (che gia' hanno sviluppato situazioni simili)
* Esperti aziendali della tecnologia utilizzata

Chiaramente i partecipanti possono variare in base a che tipo di attivita' va stimata, ad esempio nel caso della creazione di un database saranno necessari dei DBA piuttosto che sviluppatori software.

Per quanto riguarda i costi delle singole attivita' ci si basera' molto su:
* Esperienze Precedenti
* Risorse Particolari (licenze, consulenti..)
* Personale Coinvolto 
* Altro

Per quantizzare le stime del lavoro si e' deciso di utilizzare la classica misurazione giorni/uomo. In particolare nel documento della stima verra' mostrato il tempo necessario stimato con le risorse associate. Questo e' spesso ricavato da esperienze precedenti e similari; in questo caso si adatteranno le tempistiche effettivamente riscontrate nel caso storico effettuando una proporzione con le risorse che si hanno al momento per ricavare il dato del tempo. Il project manager poi puo' aggiungere o rimuovere del tempo in base al fatto che, nella realizzazione del compito, sia presente una risorsa junior piuttosto che senior o nel caso ci siano altri fattori che possano influenzare li tempo.

Al termine di ogni stima il tutto viene formalizzato attraverso l'apposito template che indichera' effettivamente il tempo che si e' deciso e il costo ad esso associato.

###Risorse Necessarie e Assegnamento###

Le risorse necessarie per ciascuna attivita' e il loro assegnamento e' stato riportato nel documento relativo alle stime. In particolare per questa fase si noti come molti compiti vengano fatti fare da sviluppatori senior piuttosto che junior perche', essendo la parte iniziale del progetto e' necessario che tutto venga impostato correttamente e che quindi si sfrutti personale con maggiore esperienza. In ogni caso se una attivita' non viene considerata come critica e possiede abbastanza margine da essere completata in sicurezza, senza quindi avere degli impatti sul tempo finale di realizzazione e rilascio della milestone che viene consegnata a fine di ogni ciclo incrementale, allora puo' esser svolta in coppia tra uno sviluppatore senior e uno junior in modo da aumentare l'esperienza di quest'ultimo, la formazione e gli stimoli che ne derivano.

###Project Network Diagram###
Una volta che si sono individuate le attivita' da effettuare e che queste sono state stimate, ora e' necessario individuare quali di queste sono dipendenti le une dalle altre, quali fanno quindi parte del percorso critico,le quali andranno gestite con particolare attenzione.

Per fare cio' si e' adottato il classico schema Gantt che si puo' trovare nei documenti di progetto. Per facilitare il lavoro si e' deciso di utilizzare il tool opensource: [Gantt Project](http://www.ganttproject.biz/)

Con questo tool si e' agevolati nella costruzione dello schema, nella costruzione del PERT risultante e delle risorse che sono associate alle singole attivita'.
Chiaramente la costruzione del Gantt e' fatta in concomitanza con le stime, questo rende possibile rivedere quanto scritto in base ad accorgimenti sulle risorse come sovraccarichi di lavoro o sottocarichi di lavoro. Quando il Gantt risulta corretto e le stime saranno sincronizzate con questo sara' possibile procedere con la fase di realizzazione della pianificazione.

Alcune attivita' nel Gantt sono state accorpate in 1 perche' il tempo minimo e' 1 giorno di durata.

###Scope Bank###
Si e' deciso di mantenere uno time bank di 2 settimane per questo primo requisito. Chiaramente il valore del time bank cambia dalla difficolta' del requisito stesso e dalla lunghezza complessiva che viene stimata per portarlo a termine. L'effettiva presenza del time bank si puo' ottenere dalle date di inizio/fine dei requisiti che si susseguono, all'interno dei vari Gantt

Executing
==============

Nella fase di executing si procede effettivamente con la fase di realizzazione del progetto e quindi si mettono in atto tutto cio' che e' stato deciso in fase di planning. Di novita' rispetto alle fasi precedenti vanno aggiunti alcuni template che introdurro' brevemente in seguito per gestire aspetti importanti che possono accadere in questa fase, come la gestione della responsabilita' riguardante le varie attivita' oppure il processo di decision making e problem solving che e' necessario standardizzare attraverso appunto appositi documenti.

Responsability Matrix
------------
Per l'assegnazione delle responsabilita' si e' deciso di utilizzare il classico template a matrice. Questo template e' stato inserito in questa fase perche' comunque si tratta di un documento interno e facile da gestire/costruire, ma a mio avviso la questione della responsabilita' delle varie attivita' puo' essere anche anticipato alla costruzione del gantt nella fase di planning, infatti lo strumento che si e' utilizzato in questo progetto per la costruzione del gantt gia' prevedeva la possibilita' di istituire uno o piu responsabili dell'attivita' quando a questa vengono assegnate le risorse.

In piu' pero' nel template della matrice devono essere anche segnate:
+ Le persone coinvolte 
* Quelle che devono essere informate
* Quelle che devono assitere il responsabile
* Quelle che devono approvare l'attivita' e il responsabile

Problem Solving
---------
Per affrontare i problemi e la loro risoluzione si e' utilizzato anche in questo caso un template standard che indica:
* Descrizione del problema
* Gestione delle cause del problema
* Raccolta di idee(brainstorming)
* Prioritizzazione delle idee
* Piano di azione

Questi sono i punti che abbiamo anche introdotto a lezione e che servono come guida per affrontare i problemi che possono capitare in fase di esecuzione. Chiaramente un ottimo documento che gia' abbiamo introdotto e affrontato e' l'analisi dei rischi che in maniera dettagliata dovrebbe gia' aver previsto quelli piu gravi e quindi, quelli che non sono presenti e gestiti in quella sede, dovrebbero essere problemi marginali e di piu' facile risoluzione.

risulta fondamentale mantenere sempre un *log dei problemi* che si sono affrontati all'interno del progetto stesso.

Decision Making
----------
Per quanto riguarda il decision making si e' deciso che, vista la coesione del gruppo, si puo' procedere con un'approccio di tipo *partecipativo*, ma nel caso non si riesca a convergere in tempo utile allora il responsabile dell'attivita' sulla quale e' stato sollevato il problema avra' la possibilita' di scegliere direttamente il da farsi.
Se invece la decisione riguarda tutto il progetto si e' deciso che il project manager avra' questa responsabilita'.

------
**Sia durante il decision making che il problem solving, per individuare le possibili soluzioni si fara' ricorso alla tecnica del brainstorming e quindi sara' necessaria uno o piu' meetings tra i membri del team**
------

Team Meetings
-------
Le comunicazioni interne e i meetings che avvengono tra i membri del team sono principalmente 3:

* **Meeting Informale Mattiniero**(Stand-Up): anche se il progetto non sara' gestito in maniera agile si e' considerato comunque utile utilizzare la riunione informale mattiniera tipica di questa metodologia per informare gli altri membri del team dei progressi sulle attivita' assegnate, dei problemi e quindi aiutare i project manager a riassegnare eventualmente le risorse in base ad eventuali imprevisti. Effuttuando anche poi le dovute modifiche alla documentazione di progetto per mantenerne il controllo. Queste riunioni *devono essere brevi* affinche' non costituiscano un impedimento alla produttivita' di tutto il team. Servano soprattutto in casi gravi come primo campanello di allarme per il team, che acconsenta al capo progetto di decidere se la problematica e' da affrontare in una sede a parte. Con una riunione formale come quella seguente.
* **Meeting Formale**(Riunione Classica): utilizzata nel caso di problemi che necessitano un approfondimento(*Problem Management Meeting*), per informare il team su quello che viene richiesto nel progetto o per altri scopi riguardanti l'analisi ad esempio. Sono riunioni strutturate e pianificate dove chi comanda la riunione deve illustrare per prima cosa quali sono gli argomenti che verranno trattati e quanto tempo impieghera' la riunione nella sua totalita'. Ogniuna di queste riunioni deve avere un'impatto sulla documentazione del progetto o produrre un report da poter consultare in futuro per avere subito chiaro quali sono gli argomenti trattati e i risultati della riunione. Tipicamente si e' deciso che si effettuera' una di queste riunioni a settimana, il Venerdi' pomeriggio, dove vengono illustrati lo stato del progetto e gli sviluppi/evoluzioni futuri.
* **Project Review Meetings**: Si tratta delle riunioni che si tengono a fine della milestone, che in questo caso coincide con la conclusione di uno dei requisiti del progetto stesso e punto centrale dell'iterazione. Durante questa rionione si fa il punto della situazione sul progetto con i project manager del committente, quelli del fornitore e i principali membri del team. In questo modo si ha anche un feedback su cio' che si e' raggiunto e su cosa invece va migliorato, anche a fronte del collaudo che avviene alla consegna di ogni milestone. In questo modo si possono pensare a delle azioni correttive che possano essere d'interesse per continuare il progetto stesso. Il deliverables di questi meetings e' quello di redigere il **Project Status Report**, template tipico di monitoraggio e controllo per avere un idea chiara dello stato del progetto. Dara' una visione sintetica di:
* Quali sono le cose che sono state fatte rispetto anche a quelle effettivamente pianificate.
* Quali sono quelle che devono essere fatte e che sono pianificate.
* I cambiamenti approvati e da esegiure
* Se il progetto e' in schedula oppure no
Si fa sempre riferimento anche ad altri documenti importani come la WBS.

Change Request
---------------
E' stato previsto un template per affrontare il change request, quindi se il cliente o qualcuno all'interno del team stesso si rende conto che sarebbe necessaria una modifica del progetto per diverse ragioni allora puo' sottoporre il template predisposto per essere approvato. Naturalmente dovra' indicare la causa del cambiamento, le motivazioni, con una propria descrizione.
Questa sara' presa in carica da chi effettivamente dovra' approvarla. La proposta di cambiamento sara' quindi accettata se la si considera pertinente e gistificata nel contesto del progetto stesso.
Una volta che viene approvata sara' pianificata e svolta. La sua pianificazione puo' essere considerata anche nel ciclo di interazione successivo seguendo la metodologia lean. Quindi puo' capitare che una milestone successiva alle prime inglobi sia un requisito minore che una revisione su uno passato. In casi estremi si puo' pensare a una milestone che riguarda unicamente il cambiamento e che quindi raggruppa tutte le richieste precedentemente approvate.

Project Impact Statement
------------------------

Verra' redatto dal project manager per ogni richiesta di cambiamento che verra' approvata e serve appunto a definirne l'impatto e a capire che cosa e' necessario per renderla possibile, nonche' un'indicazione chiara su come pianificare l'attivita'. Al suo interno saranno presenti varie alternative utili a dare al committente piu possibilita' di scelta su come operare il cambiamento.
Occupera' un ruolo fondamentale nella riunione successiva e relativa al cambiamento da effettuare che interessera' direttamente il committente in quanto avverra' una negoziazione con questo per scegliere come attuare il cambiamento.
Il tutto deve essere siglato con una firma del committente stesso in quanto un cambiamento del progetto indica sicuramente un cambiamento anche in risorse, costi o tempi (facendo riferimento allo scope triangle).

Altre Policies
---------

###Testing e Documentazione###

Essendo un prodotto software enterprise, e' necessaria la presenza di un manuale che viene costantemente mantenuto aggiornato ogni volta che vengono effettuate delle modifiche all'interfaccia, sia lato utente che lato software e nel caso siano presenti delle API relative a web service che fanno riferimento al prodotto stesso. Inoltre ci si avvale anche della generazione automatica di documentazione tecnica grazie all'utilizzo di tool di generazione automatica ad ogni milestone.
In fase di analisi si e' anche pensato ad una forma *snella* di documentazione in modo che, nel caso fossero necessarie nuove risorse da inserire nel progetto, queste possano avere subito una rapida visione di quello che riguarda il progetto, in termini di: scopo, funzionalita' principali, metodologie di riferimento per il testing e monitoring, contesto incui il programma dovra' operare etc. Tutto questo non dovra' superare le 15 pagine. Anche la lettura di questo documento diventa fondamentale. Come ulteriore supporto si puo' comunque fare riferimento anche ai documenti gia' presenti, come il POS e il PDS.
Per quanto riguarda il testing invece si e' deciso di adottare, dove possibile, la presenza di test unitari che verranno implementati prima dello sviluppo del componente stesso e da uno sviluppatore diverso da quello che effettivamente sviluppera' il componente. Infine, durante la parte di collaudo verranno inoltre ideati anche dei test con dati fittizi che serviranno per controllare l'integrazione delle varie parti del prodotto nonche' le sue performance e controllo qualita' nei termini prestabiliti con il cliente. E' previsto comunque anche una risorsa che dovra' effettivamente validare il prodotto, questa poi puo' essere anche del committente. 

Monitoring & Control
============
Nella fase di monitoraggio e controllo si ricapitolano tutti gli strumenti che sono utili per il controllo del progetto stesso, quindi per verificare se il progetto e' in schedula, come controllare che i requirements siano rispettati e su quale documentazione si fa riferimento.

In particolare il paragrafo che parla del meetings potrebbe tranquillamente rientrare in questo capitolo in quanto questi servono anche come controllo delle attivita' in particolare:
* *Daily Meetings*: hanno un ruolo tipicamente di controllo, in quanto serve per avere un feedback diretto del team su come procede il lavoro o se si devono prevedere dei ritardi o un riassegnamento delle risorse.
* *Project Review*: hanno un ruolo ricaptolativo sul progetto per avere una visione di insime su cosa si e' fatto, cosa si deve fare e i problemi che sono sorti fino adesso. Il tutto viene poi formalizzato nell'appsito template (*Project Status Report*)

Si e' deciso di non utilizzare un sistema di reporting apposito ma di basarsi sui documenti gia' precedentemente descritti, in particolare:
* Si cerca di mantenere il piu' possibile aggiornato il *Gantt* attraverso revisioni settimanali che possano andare a evidenziare problematiche nell'assegnamento delle risorse. Se poi avvengono cambiamenti notevoli direttamente da un daily meeting allora puo' essere utile intervenire tempestivamente sul gantt per verificare effettivamente il carico di lavoro sulle risorse.
* Tramite un'analisi dei *Project Status Report* si puo' istituire un *Cumulative Report*, ad esempio ogni due status reports, per  capire se l'andamento del progetto e' con tendenza negativa (es. aumento del cambiamento sopra il preventivato e ritardo conseguente) e quindi pensare a delle azioni correttive.

In ogni caso il tempo tipico con cui avviene il controllo del progetto e' al rilascio della milestone e quindi con una tempistica di un mese, anche meno in relazione al requisito.
Come strumento per il senior management e' anche richiesto la creazione di un report visuale di tipo *Earned Value* in modo da avere un feedback su quanto e' il business value fino ad ora realizzato. Si calcoleranno anche i due indici visti a lezione, rispettivamente sulla scedula e sui costi. Per quanto riguarda la schedula ci si aiutera' anche con il Gantt.
Vista la natura del progetto ci si aspetta una classica curva ad S visto che nelle fasi iniziali sono previste anche attivita' di analisi del mercato e quindi andare anche a verificare e adottare tecniche innovative e nuove. Queste possono portare sul lungo periodo un beneficio, ma le tempistiche anche di training del personale e' da mettere in conto e quindi possono aumentare il tempo di start-up. E' fortemente consigliato impostare uno scope bank piu ampio quindi per le prime fasi.

Scope Bank
------------
Riprendendo quanto gia' indicato in fase di planning lo scope bank per questo progetto viene gestito in modo anch'esso iterativo con il resto del progetto stesso in quanto, ad ogni ciclo di interazione viene ideato anche uno scope bank che in media coincidera' con 5-6 giorni lavorativi, in quanto in media la tempistica di una iterazione e' all'incirca quella mensile. Poi effettivamente la sua durata puo' essere variabile in base alla tipologia di requisito e alla sua difficolta' di realizzazione.
Viene decisa durante le riunioni che riguardano il Gantt e in particolare vengono visualizzate come il tempo che separa l'inizio di un Gantt con quello successivo.

Issue Log
----------
E' stato previsto un documento template per tenere traccia delle problematiche che sono sorte. In particolare in questo documento dovra' essere indicato se il problema riscontrato era stato previsto in un'analisi dei rischi e qundi inserire un'indentificativo che indichi effettivamente che tipo di rischio indentificato, se e' stata effettuata una richiesta di cambiamento apposita per il problema, anche qui con riferimento a quale richiesta si tratta.
Il template per l'issue log e' inserito all'interno dei documenti dell'executing.

Closing Project
==========
In questa sezione ci occuperemo di tutta la routine per la chiusura di progetto ipotizzando di essere riusciti ad arrivare a concludere tutti i requisiti in maniera soddisfacente e corretta.

In particolare ci occuperemo di ricapitolare come sono stati raggiunti i requisiti necessari per chiudere il progetto e i documenti necessari per farlo in maniera corretta.



Strategia di Implementazione e Collaudo
-------
Come gia' indicato nelle fasi precedenti si e' scelto di utilizzare una strategia a milestone separando i vari requisiti e impostando quindi un ciclo di iterazioni. Ogni ciclo mira ad una conclusione nel breve periodo e ad una seguente consegna del tutto al cliente in modo da rendere subito una parte del prodotto utilizzabile, abituare gli utilizzatori al prodotto e ottenere dei feedback in maniera rapita.

Per quanto riguarda il *collaudo* si hanno varie fasi di collaudo, ogniuno dei quali avviene alla consegna di una milestone e quindi il progetto viene mantenuto cosi maggiormente sotto controllo

Documentazione
---------------
Per quanto riguarda la documentazione si faccia riferimento al paragrafo relativo presente nella fase di executing.

In breve viene previsto la costruzione di un manuale utente che ogni attivita' deve aggiornare con le modifiche apportate. Per controllare ulteriormente il manuale, a fine milestone, viene pianificata un'attivita' di revisione dello stesso per accertarsi della correttezza e come controllo delle attivita' stesse che sono state svolte. Durante questa attivita' si puo' approfittare con l'aggiornamento di altri documenti come il *project status report* di fine milestone.
Inoltre e' presente anche una documentazione tecnica autogenerata che avviene durante la costruzione del codice stesso, ma non visibile all'utente per cercare di astrarsi dal codice e ottenere una descrizione discorsiva migliore.

Accettazione da parte del Cliente
-------------------------------------
Quando anche l'ultimo collaudo e' avvenuto con successo, il progetto verra' sottoposto alla approvazione del cliente che dovra' effettivamente firmare un documento apposito fornito dalla amministrazione che attesta che il progetto ha soddisfatto i requisiti necessari e che quindi ha soddisfatto il cliente. Questo e' necessario per procedere con la chiusura del progetto stessoe richiede semplicemente della firma del project manager del committente, si faccia riferimento direttamente al documento (*Project Acceptance*)

In particolare e' stato predisposto anche un template (*Project Closing Report*) che indica un riassunto di:
* Tutti i deliverables
* Lo scope e i suoi cambiamenti durante la realizzazione del progetto
* Eventuale manutenzione e i suoi costi
* Approvazione finale con firma

E' necessario anche organizzare correttamente il *project netbook* che conterra' tutti i documenti sopra citati e i report delle varie riunioni che sono state effettuate.

Installazione dei Deliverables
----------------------------------
Vista l'assenza di un prodotto precedente e la modalita di sviluppo scelta si e' deciso per un'installazione *phased approach* in quanto ad ogni milestone la funzionalita' sviluppata e collaudata veniva direttamente utilizzata dal cliente.

Lessons Learned
----------------
Infine viene istituito un template interno all'azienda e destinato al miglioramento e alla realizzazione di progetti futuri che riassume le problematiche principali con il committente e in generale che si sono ottenute dalla realizzazione del progetto, e le relative contromisure che si possono pensare per ridurle.

Questo documento e' molto importante perche' consente di mantenere traccia dell'esperienza acquisita all'interno del progetto e che questa rimanga appunto all'interno dell'azienda stessa.
