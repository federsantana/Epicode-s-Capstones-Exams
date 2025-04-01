# 🔐 README – Modulo 6: Splunk, Intelligenza Artificiale e Analisi Malware

## 🔍 Temi Trattati

Nel **Modulo 6**, abbiamo esplorato come unire la gestione dei log, il supporto dell’intelligenza artificiale e l’analisi malware in un flusso operativo completo:

## 📊 Utilizzo di Splunk per l’Analisi dei Log  
Installazione, configurazione e scrittura di query in Splunk Enterprise per identificare accessi falliti, attività SSH, errori 500 e tentativi di forza bruta.

## 🤖 Intelligenza Artificiale in Cybersecurity  
Utilizzo di ChatGPT per validare le query e ottenere insight analitici dai file di log.

## 🧬 Analisi Malware  
Introduzione all’analisi statica/dinamica del malware e utilizzo di VirusTotal, con attenzione ai virus polimorfici.

---

## 📄 Progetto Capstone 6: Analisi del Malware e Splunk

### 📂 Panoramica del progetto

Progetto finale realizzato in gruppo da:
- **Federico Presti** – Introduzione e contesto teorico  
- **Guyphard Ndombasi** – Struttura e impaginazione  
- **Alfredo Verduci** & **Jimsop Dario Garcia Burgos** – Query e logica di indagine

> Questo approccio ha evidenziato **collaborazione, coordinamento tecnico ed efficienza** in uno scenario simile a un SOC.

### 🧠 Obiettivo

Analizzare un grande archivio di log di sistema tramite Splunk e SPL (Search Processing Language) per:

- Identificare accessi SSH falliti e riusciti
- Tracciare IP con accessi sospetti
- Monitorare errori 500 (Internal Server Error)
- Evidenziare anomalie critiche
- Applicare un’analisi assistita da AI tramite ChatGPT

---

## 🛠️ Strumenti Utilizzati

- 🕵️‍♂️ **Splunk Enterprise 9.4.0**
- 📁 **Tutorialdata.zip** (dataset dei log)
- 🤖 **ChatGPT** per supporto analitico
- 📊 **Regex + Query SPL**
- 🧠 **Revisione IOC manuale**

---

## ⚙️ Query Principali e Use Case

1. **Accessi SSH Falliti**  
   → Estrazione IP, username, timestamp e motivazione errore

2. **Sessioni SSH riuscite (utente `djohnson`)**  
   → Verifica UID e provenienza

3. **Accessi sospetti da IP** `86.212.199.60`  
   → Ricostruzione di un attacco brute-force

4. **IP con oltre 5 tentativi falliti**  
   → Prevenzione di attacchi futuri

5. **Errori 500 (Internal Server Error)**  
   → Analisi URI e pattern comportamentali

---

## ✅ Risultato

- ✅ Dataset interrogato completamente tramite SPL
- 🔍 Riconosciuti pattern sospetti e comportamenti anomali
- 🧠 Analisi supportata da ChatGPT per insight approfonditi
- 🔐 Proposte misure difensive (firewall, MFA, controllo API)
- 🤝 Forte collaborazione in team da quattro membri

---

## 🧠 Conclusione

Questo progetto finale ha racchiuso l’intero percorso formativo, combinando:

- Query reali in ambiente Splunk
- Lavoro collaborativo in un SOC simulato
- Estrazione di intelligence dai log
- Difese preventive e strategie reattive

> 🚨 AI + Log Analysis + Teamwork = Operazioni di Sicurezza Next-Gen

---

🔗 Collegati con me su [LinkedIn](https://www.linkedin.com/in/federico-presti/)  
👨‍💻 **Federico Presti**  
*Cybersecurity Analyst in formazione*
