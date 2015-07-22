Condition of Satisfaction
=======

Requisiti Espressi Direttamente dall'Utente
-------

 1. Il prodotto deve consentire di pianificare l'orario universitario consentendo al personale attualmente addetto a tale compito di concludere il lavoro con un 30% in meno a livello di tempistiche, conseguentemente questo coincide con 1 mese e mezzo di lavoro, con una tolleranza di 10 giorni lavorativi. Il fornitore puo' valutare le tempistiche calcolando dal momento in cui avviene l'assegnamento della prima lezione per un corso di laurea fino a quando l'ultima lezione viene direttamente pubblicata agli studenti. Allo stesso modo questo verra' effettuato dal personale addetto in modo da verificare che effettivamente le date coincidano. Si e' deciso inoltre che tale valutazione sara' effettiva solamente dopo che sono trascorsi 6 mesi dall'eventuale corso di formazione o quando il numero di richieste di chiarimento da parte del personale all'area di supporto sara' inferiore a 10 al mese. Le statistiche che devono essere raccolte a riguardo devono contenere:
	 2. Tempo totale impiegato per la costruzione dell'orario
	 3. Corso di riferimento. Ogni corso avra' la sua statistica
	 4. Data Iniziale
	 5. Data Finale
 2. Il prodotto deve ridurre il numero di errori di pianificazione delle lezioni e delle sue risorse, compresa l'organizzazione dei docenti che eseguiranno le lezioni ad un massimo di un errore su sei lezioni correttamente pianificate. Per fare cio' il personale potra' ricevere i feedback dei docenti in modo da sapere in quali casi ci sono stati degli errori e avvalersi di snapshot dell'applicativo per accertare che questo ha avuto un comportamento anomalo, fatto cio' dovra' subito inviarlo al team di supporto che verifichera' l'eventuale anomalia. Naturalmente la lezione incriminata non dovra' essere modificata al fine di effettuare la verifica durante il collaudo. Purtroppo qui non si ha modo di evitare in maniera rigorosa eventuali falsificazioni da entrambe le parti, quindi ci si basera' sul buon senso e il margine di tolleranza sara' piu' ampio: 15 errori. Gli errori in esame consistono in:
	 3.  Controllo che ogni lezione abbia almeno un'corso e un'aula associata 
	 4. Controllo che non ci sia sovrapposizione temporale di risorse 
 3. Gestione degli stati di una lezione, quindi possibilita' di cambiare stato a piu' lezioni contemporaneamente.
 4. Possibilita' di associazione tra lezione e risorse (aula, docente, altre)
 5. Profilazione degli utenti
 6. Associazione degli utenti a gruppi logici (insieme di corsi, docenti e risorse che questi possono gestire) e quindi impedire a utenti appartenenti ad un certo gruppo logico di visualizzare lezioni o risorse esterne a questo.
 7. Performance dell'applicativo rapidi. Per fare cio' e' stato discusso con il committente che il tempo di risposta massimo per una determinata funzionalita' deve essere di 10 secondi. Eventualmente se si devono intraprendere operazioni che possono implicare tempistiche maggiori (operazioni di I/O, import, richieste attraverso la rete etc.) queste devono essere gestite in background consentendo all'utilizzatore di visualizzarnelo stato in un secondo momento e in ogni caso di continuare a lavorare normalmente.
 7. Import dei dati riguardanti le risorse del committente direttamente nel sistema. L'import deve consentire la possibilita' di inserire dati attraverso fogli excel e attraverso un apposito web service che consente di gestire i dati delle risorse, ma non delle lezioni, e solo dietro previa autenticazione.

Requisiti di Secondaria Importanza
-------
 1. Sistema di Reportistica che consenta all'utente di ottenere la versione esportabile dell'orario secondo certe tipologie da concordarsi che riguarderanno il raggruppamento in base alla risorsa in esame (raggruppato per aula, raggruppato per corso, raggruppato per docente e) con relativo intervallo di date, oppure un report sommario che indica tutte le lezioni in un dato periodo di tempo (giorno, settimana, mese).
 2. Possibilita' di visualizzare un determinato periodo di tempo su uno schermo pubblico con le opzioni di visualizzazione gia' considerate nel punto precedente.
 3. Ricerca di lezioni per: corso, risorse, docenti, data, intevallo di date.
 4. Espandere i valori attualmente presenti per le risorse con dati riferiti alla topologia degli edifici, dipartimento dei docenti o altro da concordare.
 5. Look and Feel Moderno. Attraverso i mockup si puo' definire gia' in fase di analisi dei requisiti come deve essere l'aspetto del prodotto.
 6. Presenza di una documentazione non tecnica, non necessariamente il manuale, anche se e' consigliato, in modo che il personale possa avere uno strumento per colmare eventuali dubbi sul progetto.