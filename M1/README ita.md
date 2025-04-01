  Il documento "esercitazione finale Modulo 1 signor Presti Federico" è focalizzato sull'implementazione di una comunicazione efficace tra due macchine virtuali, una su Kali Linux e l'altra su Windows 10 Home, utilizzando un'architettura client-server. Durante l'esercitazione, è stato utilizzato il software Inetsim per simulare richieste web e il tool Wireshark per intercettare e analizzare il traffico di rete.

- L'attività si è concentrata su diverse fasi:

Configurazione degli indirizzi IP statici e setup del nome DNS "epicode.internal" per facilitare la comunicazione tra le macchine.

Utilizzo di Inetsim per avviare un servizio HTTPS, seguito dall'analisi di errori di certificato che evidenziano l'importanza del protocollo HTTPS per la sicurezza delle comunicazioni.

Utilizzo di Wireshark per tracciare e analizzare i pacchetti di rete, identificare gli indirizzi MAC delle macchine virtuali e confrontare i dati delle sessioni HTTPS e HTTP.

- Le principali osservazioni includono:

Le differenze nella visibilità e leggibilità dei contenuti delle richieste, dove i contenuti HTTPS appaiono criptati a differenza delle richieste HTTP.

L'utilizzo di diversi numeri di pacchetti e protocolli durante le sessioni di comunicazione, con particolare attenzione al protocollo di sicurezza TLS impiegato nelle connessioni HTTPS per garantire una comunicazione cifrata e sicura.
