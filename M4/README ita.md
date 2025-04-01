# 🔐 README – Modulo 4: Sfruttamento delle Vulnerabilità e Attacchi alle Web App

## 🔍 Temi Trattati

Nel **Modulo 4**, abbiamo esplorato tecniche reali per sfruttare vulnerabilità di sistema e applicazioni web, tra cui:

## 🚧 Sfruttamento delle Vulnerabilità con Metasploit

Comprendere come utilizzare il **Metasploit Framework** per identificare e sfruttare debolezze a livello di sistema, ottenendo una shell remota tramite payload come **Meterpreter**.

## 🔢 Attacchi SQL Injection

Simulazione e mitigazione delle vulnerabilità **SQLi** in moduli e applicazioni web per recuperare dati da database backend.

## 🔋 Attacchi Brute-force con Hydra

Utilizzo di **Hydra** per automatizzare attacchi brute-force contro servizi come SSH, FTP e login web.

## 🌐 Analisi di Cross-Site Scripting (XSS)

Analisi delle vulnerabilità **XSS** nei siti web e difese contro injection di script che compromettono le sessioni utente.

---

## 📄 Progetto Capstone 4: Exploit Java_RMI con Metasploit

Questo progetto è strutturato in:

### 📂 File 1: Introduzione al Progetto M4 – Exploit JAVA_RMI – contesto teorico e razionale.

### 📂 File 2: Progetto Capstone completo – fase di exploit con remediation.

### 📎 Report Nessus: Nessus Metasploitable Scan – utilizzato per validare la vulnerabilità.

## 🎯 Obiettivo

Dimostrare lo sfruttamento di un servizio **Java RMI** vulnerabile su una macchina **Metasploitable 2**, ottenendo una sessione **Meterpreter**, raccogliendo informazioni di sistema e implementando una difesa efficace.

## 🛠️ Strumenti Utilizzati

- 🔍 **Nmap** – Scansione delle porte e rilevamento dei servizi
- 🛡️ **Metasploit Framework** – Sfruttamento e rilascio dei payload
- 🐧 **Kali Linux** – Ambiente attaccante
- 🔌 **UFW (Uncomplicated Firewall)** – Meccanismo di remediation
- 📄 **Report Nessus** – Validazione esterna dei servizi esposti

## ⚠️ Fasi Chiave dell’Exploit

1. Identificata la porta TCP `1099` aperta con servizio **Java RMI** usando **Nmap**.
2. Avviato **Metasploit**, selezionato e configurato il modulo `java_rmi_server`.
3. Regolato il parametro `HTTPDELAY` per evitare timeout e ottenuta shell **Meterpreter**.
4. Eseguiti comandi per raccogliere:
   - Configurazione rete (`ifconfig`, `route`)
   - Info di sistema (`sysinfo`, `ps`)
   - File sensibili (`cat /etc/shadow`)
5. Dimostrate capacità di post-exploitation: accesso tabella ARP, esplorazione del filesystem.

## 🛠️ Azione di Remediation

Per mettere in sicurezza il sistema:

- Applicate regole firewall con **UFW**:
  - `sudo ufw deny 1099` – blocco totale delle connessioni alla porta vulnerabile
  - oppure accesso ristretto solo a IP autorizzati

Questo riflette un approccio reale di patching e controllo accessi.

## ✅ Risultato

- ✅ Exploit riuscito del servizio Java RMI
- 📊 Raccolta di informazioni critiche di rete e sistema
- 🔐 Applicazione di contromisure difensive per chiudere il vettore d'attacco

## 🧠 Conclusione

Questo progetto ha evidenziato i rischi dei servizi esposti e non protetti come **Java RMI**. Ha mostrato non solo la fase offensiva (exploit), ma anche la necessità della **remediation immediata**, offrendo una visione completa delle buone pratiche di cybersecurity.

> 📊 Conoscenze offensive + contromisure difensive = maturità completa in cybersecurity.

---
