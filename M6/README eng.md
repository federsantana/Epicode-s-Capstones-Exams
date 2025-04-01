# 🔐 README – Module 6: Splunk, AI & Malware Analysis

## 🔍 Topics Covered

In **Module 6**, we explored how to combine log management, AI support, and malware analysis into an effective security workflow:

## 📊 Using Splunk for Log Analysis  
Installation, configuration, and query writing with Splunk Enterprise to detect login failures, SSH activity, internal server errors, and brute-force patterns.

## 🤖 Artificial Intelligence in Cybersecurity  
Leveraging ChatGPT to assist in query validation and to extract security insights from full log datasets.

## 🧬 Malware Analysis  
Introduction to malware behavior through static/dynamic analysis and VirusTotal queries, including polymorphic threats.

---

## 📄 Capstone Project 6: Advanced Log Threat Detection with Splunk

### 📂 Project Overview

Final group project developed by:
- **Federico Presti** – Project introduction and context  
- **Guyphard Ndombasi** – Structure and formatting  
- **Alfredo Verduci** & **Jimsop Dario Garcia Burgos** – Core queries and investigation logic

> This collaborative approach demonstrates **teamwork, technical coordination, and efficiency** in a SOC-like environment.

### 🧠 Objective

Analyze a large system log archive using Splunk and Splunk SPL (Search Processing Language) to:

- Identify failed and successful SSH logins
- Detect repeated login attempts from a single IP
- Track Internal Server Errors (500)
- Highlight critical access anomalies
- Apply AI-based review with ChatGPT

---

## 🛠️ Tools Used

- 🕵️‍♂️ **Splunk Enterprise 9.4.0**
- 📁 **Tutorialdata.zip** (Log dataset)
- 🤖 **ChatGPT** for log interpretation
- 📊 **Regex + SPL Queries**
- 🧠 **Manual IOC review**

---

## ⚙️ Key Queries & Use Cases

1. **Failed SSH Attempts**  
   → Extraction of IP, username, timestamps, and failure reason

2. **Successful SSH Sessions by User**  
   → Detection of access for `djohnson` and evaluation of UID source

3. **Targeted Access from IP** `86.212.199.60`  
   → Evaluation of brute-force signatures

4. **IPs with Over 5 Failed Logins**  
   → Identification of sources for possible attack prevention

5. **Internal Server Errors (500)**  
   → URI mapping and behavioral pattern analysis

---

## ✅ Outcome

- ✅ Queried and analyzed a full dataset using SPL
- 🔍 Detected brute-force patterns and risky user behaviors
- 🧠 Used ChatGPT for AI-assisted log interpretation
- 🔐 Suggested defensive countermeasures (firewalls, MFA, API controls)
- 🤝 Demonstrated strong collaboration across a four-member team

---

## 🧠 Conclusion

This final project encapsulated our learning across the entire course, combining:

- Real-world query design with Splunk
- Collaborative teamwork in a simulated SOC
- Threat intelligence extraction
- Preventive and responsive defense strategies

> 🚨 AI, Logs, and Team Coordination = Next-Gen Security Operations

---
