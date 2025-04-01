# 🔐 README – Modulo 3: Network scan | Vulnerability Assessment

### 🔍 Temi trattati

Questo modulo esplora competenze fondamentali per l'analisi della sicurezza di rete e l'identificazione delle vulnerabilità

### 🛡️ Metodologie di Penetration Testing

Comprensione degli approcci strutturati per simulare attacchi reali e scoprire debolezze di sistema.

### 🌐 Nmap per la scansione di rete

Mappatura di host e servizi attivi, analisi delle porte aperte e scoperta di potenziali vettori d'attacco.

### 🧪 Configurazione di Nessus e gestione delle vulnerabilità

Installazione e utilizzo di Nessus Essentials, scoring CVSS e proposta di strategie di mitigazione realistiche.

## 📄 Progetto Capstone: Vulnerability Assessment Report

 ### 🎯  Obiettivo

Identificare e valutare vulnerabilità critiche in un sistema deliberatamente vulnerabile (Metasploitable 2) e proporre soluzioni concrete.


### 🛠️ Strumenti utilizzati

🔍 Nmap per la scoperta di porte e servizi

🛡️ Nessus Essentials 10.8.3 per lo scanning e scoring CVSS

🐧 Kali Linux come ambiente operativo

| Porta | Servizio     | Vulnerabilità                 | Rischio                  |
|-------|--------------|-------------------------------|--------------------------|
| 8009  | ajp13        | Ghostcat – Esecuzione remota  | 🔴 Remote Code Execution |
| 8180  | HTTP         | Apache Tomcat obsoleto        | 🔶 Aggiornamento urgente |
| 1524  | wild_shell   | Servizio backdoor sconosciuto | 🔴 Compromissione OS     |
| 5900  | VNC          | Accesso con password debole   | 🟠 Rischio credenziali   |
| 6667  | IRC          | Backdoor UnrealIRCd           | 🔴 Esecuzione codice     |

### 🛠 Soluzioni proposte

Aggiornamento delle versioni vulnerabili (Tomcat, VNC, IRC)

Verifica dell'integrità software con hash

Reinstallazione dei sistemi compromessi

### ✅ Risultato

Ho prodotto un report completo per il cliente fittizio JetStorm S.p.A. che include:

📑 Sommario esecutivo per decision maker

🧾 Report tecnico dettagliato per analisti

💡 Azioni di remediation mirate per ogni vulnerabilità

### 🧠 Conclusione

Questo terzo capstone ha evidenziato il ruolo cruciale del vulnerability assessment nella difesa informatica. Combinando strumenti come Nmap e Nessus, ho maturato esperienza pratica nell’identificazione, classificazione e gestione delle minacce in un ambiente controllato.

