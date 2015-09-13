Case Study: Academic Organizer
=======

Descrizione e Caratteristiche del Sistema
-------
Si vuole creare un prodotto in grado di facilitare la pianificazione della parte didattica delle universita' in modo da velocizzare il processo, che al momento richiede 2 mesi di lavoro, fornendo quindi anche piu' flessibilita' dei cambiamenti e controlli appositi per evitare piu' facilmente gli errori piu banali, che sono stimati essere all'incica 1 su 3 lezioni.
In particolare il cliente si aspetta di ridurre del 30% le tempistiche attuali per la creazione dell'orario universitario, nonche' ridurre significativamente il numero di errori commessi(aule/docenti gia' impegnate/i, risorse non disponibili..) della meta'.
Quindi si deve essere in grado di creare l'orario delle lezioni dei vari corsi presenti all'interno dell'universita' con gestione delle varie risorse, con particolare attenzione alle aule, ai docenti e alle risorse che possono essere utilizzate da parte della lezione stessa(es proiettori).
Per quanto riguarda la pianificazione delle lezioni:

 - Una lezione deve obbligatoriamente appartenere ad un corso e un'aula.
 - Ogniuna di queste deve avere un suo stato in modo da aiutare l'operatore nella pianificazione, questo infatti puo' pensare di abbozzare un primo orario con lezioni di un certo stato e poi, una volta deciso, andare a cambiare lo stato delle lezioni che effettivamente verranno effettuate.
 - L'operatore deve essere in grado in un secondo momento di cambiare gli stati delle lezioni in modo massivo.
	 - Quindi dare la possibilita' all'operatore di ricercare le lezioni in base allo stato o ad un'altra qualsiasi caratteristica di questa in modo da poi poter cambiare lo stato.

In questa prima fase non sono richieste la gestione di caratteristiche aggiuntive rispetto a quelle gia' presenti, pero' bisogna comunque mantenere un ampio margine per miglioramenti futuri.
Per quanto riguarda le risorse:

 - Dare la possibilita di associare ad ogni lezione una o piu risorse di quelle precedentemente introdotte.
 - Prevedere la presenza di attributi aggiuntivi per le risorse (come ad esempio per le aule la presenza di PC o di accesso ai disabili, edificio, citta'. Oppure per i docenti la matricola).
 - Dare la possibilita' di raggruppare le risorse per strutture (Dipartimenti, facolta', edifici...o in maniera personalizzata)

Si richiede inoltre che l'applicativo consenta di:

 - Visualizzare dei report per risorsa (es. impegni in un aula per la settimana/mese) *sistema di reportistica*
 - Controllare che non ci sia sovrapposizione di risorse. (es. aula/docente associata a due lezioni che avvengono nello stesso momento) o che ad una lezione manchi l'aula o l'associazione con il corso.
 - Profilare gli utenti che hanno accesso al sistema con un opportuno ruolo di accesso che ne limita le capacita'. *User Authentication and Authorization*
	 - Consentire varie tipologie di accesso: direttamente attraverso l'applicativo, attraverso l'SSO di ateneo, quando presente, o passando direttamente attraverso lo standard LDAP.
 - Creare piu' raggruppamenti logici che consentono di associare ad un gruppo di utenti la possibilita' di gestire solo certe risorse/corsi. Per far cio' si possono aggiungere aule appartenenti a strutture differenti, si veda l'ultimo punto riguardante alle risorse, effettuando una lista delle risorse che fanno parte dei raggruppamenti, oppure utilizzando direttamente le strutture gia' associate alle risorse.
 - Rendere risponibile una versione dell'orario da mostrare sugli schermi pubblici di ateneo. Anche in questo caso e' necessaria una vasta flessibilita' sul tipo di visualizzazione che si vuole mostrare.

Non ci sono preferenze dal punto di vista della piattaforma da utilizzare, pero' si consiglia di implementare il tutto come un portale web in modo da rendere il tutto piu flessibile.
