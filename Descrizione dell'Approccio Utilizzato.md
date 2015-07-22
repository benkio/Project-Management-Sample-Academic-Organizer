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
- **Corso**: Insieme di lezioni che trattano lo stesso argomento e culminano nello stesso esame

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
Essendo questo un esercizio didattico sul management si e' comunque deciso di individuare solo i rischi di malfunzionamento principali al fine di snellire la trattazione e concentrarsi adeguatamente anche sulle successive parti dell'elaborato. Tutto questo deve quindi essere considerato come un semplice esempio di una vera analisi dei rischi, che pero' segue in ogni caso la metodologia che viene illustrata, in quando realmente applicata anche in contesti reali.

### Failure Mode, Effects, and Criticality Analysis ###
Per l'individuazione dei rischi si e' deciso di utilizzare un semplice approccio molto conosciuto per svolgere questa analisi che coincide semplicemente nel:

1.  Identificazione tutti i possibili malfunzionamenti o difetti dei componenti del prodotto.
2.  Per ogni modo di malfunzionamento/difetto dei componenti descrizione degli effetti e delle possibili cause.
3.  Per ogni modo di malfunzionamento/difetto ricerca delle azioni possibili per ridurne gli effetti.
4.  Definizione delle scale di punteggio dei tre parametri: 
  *  Probabilità di accadimento del malfunzionamento/difetto base
  *  Severità degli effetti del malfunzionamento/difetto base
  *  Rilevabilità del malfunzionamento/difetto base.
5.  Attribuzione dei punteggi ai parametri.
6.  Valutare e decidere gli interventi da intraprendere.

#### Identificazione Malfunzionamenti ####
Vengono qui illustrati dei macro rischi (Effetti e cause) che sono strettamente correlati ai COS e che quindi possono fortente portare a una insoddisfazione degli stessi, qui di seguito i due principali rischi: 

1. *Problemi di Rete*: Il rischio che il sistema del cliente si ritrovi isolato dal mondo esterno e quindi non e' in grado fisicamente di raggiungere l'applicativo.
2. *Guasti Hardware*: Si vuole analizzare il caso in cui l'application server e il database server subisca dei guasti in modo da rendere inutilizzabile il sistema.
3. *Necessita' Improvvisa di Acquisto*: Ci si rende conto che e' necessario per il corretto funzionamento del sistema un acquisto di hardware e software. 
4. *Necessita' di personale*: Ci si rende conto che e' necessario assumere nuovo personale in corso d'opera.
5. *Problemi sulle Stime*: Risultano errate per via della poca esperienza, per dell'incertezza del compito stesso o per fattori tecnici

#### Effetti dei Malfunzionamenti ####
I COS effettivamente influenzati da questi problemi sono: 
* *Performance*
* *Completamento Pianificazione Entro le Tempistiche*.

Inoltre risultano influenzati tutti i punti relativi allo *Scope Triangle* in particolare il fattore tempo.
Di seguito elenchiamo i possibili effetti che hanno sul sistema:
1. Il sistema e' inutilizzabile (soprattutto perche' e' concepito come interamente web) e quindi effettivamente si ha un blocco completo dei lavori. Questo ha un forte impatto sul requisito delle tempistiche.
2. Anche in questo caso il sistema risente di un impatto sulle tempistiche rendendo l'applicativo di fatto inutilizzabile, inoltre se questo rischio si verifica si ha anche un conseguente impatto sui costi di riparazione/sostituzione.
3. Questo problema ha anch'esso un effetto sui costi e sulle risorse dovendo portare ad un utilizzo di maggior hardware o all'acquisto di eventuali licenze per velocizzare li lavoro. Inoltre il tutto dovra' anche essere integrato con il sistema.
4. La necessita' sopra indicata, se non prevista, puo' portare a problematiche di tempo, in quanto il neo assunto va formato e introdotto al dominio applicativo, e di risorse, in quanto delle risorse vanno impiegate per integrare il nuovo arrivato nel team e renderlo di fatto operativo.
5. L'impatto principale si ha senza dubbio sui tempi in quanto stime errate possono facilmente portare fuori schedula tutto il progetto.

#### Possibili Azioni per Mitigare le Problematiche ####
Prendendo in esame ogni singolo rischio verra' mostrata una lista delle possibili contromisure che si possono intraprendere:
1. Creazione di un clone del sistema interno alla rete del cliente che viene mantenuto automaticamente in sincrono tramite un job notturno con l'ambiente di produzione in modo che, in causa di guasti sia possibile lavorare su quello. L'integrazione puo' basarsi su un log che semplicemente da prevalenza alle modifiche piu' recenti.
2. Per risolvere questo problema e anche l'acquisto di nuovo hardware in maniera improvvisa si puo' decidere di utilizzare una soluzione cloud che offre scalabilita' e fault tollerance
3. Per mitigare questa problematica si puo' pensare di intraprendere fin da subito contatti e partnership con eventuali agenzie di reclutamento per lavori a progetto in grado di coprire le eventuali necessita'. Oppure considerare la possibilita' di negoziare personale da altri progetti, meglio se particolarmente specializzato nel compito da svolgere (ad esempio un dipendente di un altro progetto che gia' ha preso parte alla creazione di sistemi di reportistica) per avere un aiuto e quindi sopperire al rischio.
4. In questo caso e' fondamentale considerare la presenza di un time bank adeguato in base all'incertezza/inesperienza del personale alla realizzazione del task. Essendo il PMLC individuato come incrementale e quindi alla fine di ogni ciclo di esecuzione anche la revisione e il rilascio di una nuova milestone, si puo' pensare di calcolare per ogni pianificazione il time bank per le stime di quel ciclo in modo da mitigare adeguatamente eventuali ritardi.

Project Overview Statement
--------------------------
Per la stesura del POS si e' proceduto per gradi: mano in mano che il processo di scoping progrediva e venivano svolte le riunioni che andavano a consolidare le condition of satisfaction e la struttura gerarchica dei requisiti(RBS) il POS veniva aggiornato in modo da rispecchiare il piu' fedelmente possibile il procedere dei lavori. Una volta che tutte le fasi precedenti sono terminate, la versione finale e' stata sottoposta al senior management per l'approvazione.
Gli aspetti principali che si sono considerati per la creazione del documento sono stati:
* Un'attenzione particolare alla misurazione dei criteri di successo e delle richieste del cliente evidenziando come fare per verificare la riuscita del progetto al fine di tutelarsi per eventuali problematiche future.
* L'aggiunta di quelli che possono essere i vantaggi per l'azienda nell'intraprendere il progetto in esame.
* L'intenzione di voler evidenziare fin da subito quali sono le varie parti che dovranno comporre il sistema in modo da rinforzare l'idea della compartimentazione e soprattutto la scelta del ciclo di vita che si e' introdotto nella sezione precedente.

Planning
=======


Policies e Varie (da sistemare)
=======

Descrizione Del Team
----------
Per la realizzazione di questa simulazione di project management si e' pensato a un team di una piccola azienda e quindi composto prettamente da 5 risorse:

 - Due Senior Developer
 - Un DBA
 - Un Junior developer
 - Un Sistemista

In particolare, lo sviluppatore con piu esperienza all'interno del team sara' quello che effettivamente si trovera' a capo del progetto e che quindi avra' la responsabilita' di prendere le decisioni riguardanti soprattutto l'architettura del progetto. Per quanto riguarda la gestione della parte amministrativa, questa viene affidata al DBA essendo anche l'ipotetico responsabile della gestione della qualita' e che quindi puo' tenere meglio sotto controllo che tutti i processi aziendali vengano correttamente rispettati.
Infine, per quanto riguarda il testing e la documentazione viene designato come responsabile il secondo senior Developer, si faccia riferimento alla parte relativa. sempre interna a questa sezione.

Testing e Documentazione
-------
Essendo un prodotto software enterprise, e' necessaria la presenza di un manuale che viene costantemente mantenuto aggiornato ogni volta che vengono effettuate delle modifiche all'interfaccia, sia lato utente che lato software e nel caso siano presenti delle API relative a web service che fanno riferimento al prodotto stesso. Inoltre ci si avvale anche della generazione automatica di documentazione tecnica grazie all'utilizzo di tool di generazione automatica ad ogni milestone.
In fase di analisi si e' anche pensato ad una forma *snella* di documentazione in modo che, nel caso fossero necessarie nuove risorse da inserire nel progetto, queste possano avere subito una rapida visione di quello che riguarda il progetto, in termini di: scopo, funzionalita' principali, metodologie di riferimento per il testing e monitoring, contesto incui il programma dovra' operare etc. Tutto questo non dovra' superare le 15 pagine. Anche la lettura di questo documento diventa fondamentale.
Per quanto riguarda il testing invece si e' deciso di adottare, dove possibile, la presenza di test unitari che verranno implementati prima dello sviluppo del componente stesso e da uno sviluppatore diverso da quello che effettivamente sviluppera' il componente. Infine, durante la parte di collaudo verranno inoltre ideati anche dei test con dati fittizi che serviranno per controllare l'integrazione delle varie parti del prodotto nonche' le sue performance e controllo qualita' nei termini prestabiliti con il cliente.

 Comunicazioni (Meetings)
-------
Le comunicazioni interne e i meetings che avvengono tra i membri del team sono principalmente 2:

 - **Meeting Informale Mattiniero**(Stand-Up): anche se il progetto non sara' gestito in maniera agile si e' considerato comunque utile utilizzare la riunione informale mattiniera tipica di questa metodologia per informare gli altri membri del team dei progressi sulle attivita' assegnate, dei problemi e quindi aiutare i project manager a riassegnare eventualmente le risorse in base ad eventuali imprevisti. Effuttuando anche poi le dovute modifiche alla documentazione di progetto per mantenerne il controllo. Queste riunioni *devono essere brevi* affinche' non costituiscano un impedimento alla produttivita' di tutto il team. Servano soprattutto in casi gravi come primo campanello di allarme per il team, che acconsenta al capo progetto di decidere se la problematica e' da affrontare in una sede a parte. Con una riunione formale come quella seguente.
 - **Meeting Formale**(Riunione Classica): utilizzata nel caso di problemi che necessitano un approfondimento, per informare il team su quello che viene richiesto nel progetto o per altri scopi riguardanti l'analisi ad esempio. Sono riunioni strutturate e pianificate dove chi comanda la riunione deve illustrare per prima cosa quali sono gli argomenti che verranno trattati e quanto tempo impieghera' la riunione nella sua totalita'. Ogniuna di queste riunioni deve avere un'impatto sulla documentazione del progetto o produrre un report da poter consultare in futuro per avere subito chiaro quali sono gli argomenti trattati e i risultati della riunione. Tipicamente si e' deciso che si effettuera' una di queste riunioni a settimana, il Venerdi' pomeriggio, dove vengono illustrati lo stato del progetto e gli sviluppi/evoluzioni futuri.