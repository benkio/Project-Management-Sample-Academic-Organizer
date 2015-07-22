Risk Management
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

