Risk Analysis
================

Legenda
----------------

|                                               Rating                                               | Insignificant | Minor  | Moderate | Major   | Catastrophic |
|:--------------------------------------------------------------------------------------------------:|---------------|--------|----------|---------|--------------|
| *Almost certain* - controls unsatisfactory to mitigate the risk                                    | HIgh          | HIgh   | Extreme  | Extreme | Extreme      |
| *Likely* - Controls inadequate to mitigate the risk and require improvement                        | Medium        | HIgh   | HIgh     | Extreme | Extreme      |
| *Possible* - Controls reasonable / adequate to mitigate the risk but may still require improvement | Low           | Medium | HIgh     | Extreme | Extreme      |
| *Unlikely* - Controls robust and adequate to mitigate the risk                                     | Low           | Medium | Medium   | HIgh    | Extreme      |
| *Rare* - Controls strong to mitigate the risk                                                      | Low           | Low    | Medium   | HIgh    | HIgh         |

| Rating        |                                                        Description                                                       |
|---------------|:------------------------------------------------------------------------------------------------------------------------:|
| Insignificant | Impact can be easily absorbed without requiring management effort                                                        |
| Minor         | Impact can be readily absorbed but some management effort is required                                                    |
| Moderate      | Impact cannot be managed under normal operating conditions;,requiring moderate level of resource and management input    |
| Major         | Impact requires a high level of management attention / effort and resources to rectify                                   |
| Catastrophic  | Disaster with potential to lead to business collapse and requiring almost total management attention / effort to rectify |


Risk Identification and Assissment
----------------

|            Risk Summary           | Description                                                                                              | Preliminary Risk Rating | Risk Mitigation Description                                                                                                                                                                                            | Residual Risk Rating |
|:---------------------------------:|----------------------------------------------------------------------------------------------------------|-------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------|
| Problemi di Rete                  | il sistema si ritrovi isolato dal mondo esterno, quindi non raggiungibile                                | Extreme                 | Clone del sistema interno alla rete del cliente che viene mantenuto automaticamente in sincrono tramite un job notturno                                                                                                | Medium               |
| Guasti Hardware                   | Uno tra l'application server e il database server risulta non piu utilizzabile                           | Extreme                 | Sia hardware che software per via di richieste tecniche o per far fronte a carichi notevoli di lavoro.                                                                                                                 | Low                  |
| Necessita' Improvvisa di Acquisto | Sia hardware che software per via di richieste tecniche o per far fronte a carichi notevoli di lavoro.   | High                    | Soluzione cloud per la parte hardware. Per la parte software e' necessario un procurement analysis che puo' essere fatta ad ogni ciclo di pianificazione.                                                              | Low                  |
| Necessita' di personale           | A fronte di un maggiore carico di lavoro o di inesperienza in alcune implementazioni tecniche.           | Medium                  | Prestito di personale qualificato da altri progetti. Effettuare gia' una prima indagine sul mercato per le figure professionali attualmente presenti. Rapporti con agenzie di collocamento etc etc.                    | Low                  |
| Problemi sulle Stime              | Stime errate per via della poca esperienza, per dell'incertezza del compito stesso o per fattori tecnici | High                    | Time bank adeguato in base alle attivita' da intraprendere nel ciclo di vita del progetto al momento in esame, calcolato in base all'incertezza del compito, l'esperienza del team e eventuali problematiche tecniche. | Medium               |

Explanation of Risks
---------------------------------------

### Identificazione Malfunzionamenti ###
Vengono qui illustrati dei macro rischi (Effetti e cause) che sono strettamente correlati ai COS e che quindi possono fortente portare a una insoddisfazione degli stessi, qui di seguito i due principali rischi:

1. *Problemi di Rete*: Il rischio che il sistema del cliente si ritrovi isolato dal mondo esterno e quindi non e' in grado fisicamente di raggiungere l'applicativo.
2. *Guasti Hardware*: Si vuole analizzare il caso in cui l'application server e il database server subisca dei guasti in modo da rendere inutilizzabile il sistema.
3. *Necessita' Improvvisa di Acquisto*: Ci si rende conto che e' necessario per il corretto funzionamento del sistema un acquisto di hardware e software.
4. *Necessita' di personale*: Ci si rende conto che e' necessario assumere nuovo personale in corso d'opera.
5. *Problemi sulle Stime*: Risultano errate per via della poca esperienza, per dell'incertezza del compito stesso o per fattori tecnici

### Effetti dei Malfunzionamenti ###
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

### Possibili Azioni per Mitigare le Problematiche ###
Prendendo in esame ogni singolo rischio verra' mostrata una lista delle possibili contromisure che si possono intraprendere:

1. Creazione di un clone del sistema interno alla rete del cliente che viene mantenuto automaticamente in sincrono tramite un job notturno con l'ambiente di produzione in modo che, in causa di guasti sia possibile lavorare su quello. L'integrazione puo' basarsi su un log che semplicemente da prevalenza alle modifiche piu' recenti.
2. Per risolvere questo problema e anche l'acquisto di nuovo hardware in maniera improvvisa si puo' decidere di utilizzare una soluzione cloud che offre scalabilita' e fault tollerance
3. Per mitigare questa problematica si puo' pensare di intraprendere fin da subito contatti e partnership con eventuali agenzie di reclutamento per lavori a progetto in grado di coprire le eventuali necessita'. Oppure considerare la possibilita' di negoziare personale da altri progetti, meglio se particolarmente specializzato nel compito da svolgere (ad esempio un dipendente di un altro progetto che gia' ha preso parte alla creazione di sistemi di reportistica) per avere un aiuto e quindi sopperire al rischio.
4. In questo caso e' fondamentale considerare la presenza di un time bank adeguato in base all'incertezza/inesperienza del personale alla realizzazione del task. Essendo il PMLC individuato come incrementale e quindi alla fine di ogni ciclo di esecuzione anche la revisione e il rilascio di una nuova milestone, si puo' pensare di calcolare per ogni pianificazione il time bank per le stime di quel ciclo in modo da mitigare adeguatamente eventuali ritardi.