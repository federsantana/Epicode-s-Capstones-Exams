# 🔐 README – Module 3: Network Scan | Vulnerability Assessment

## 🔍 Topics Covered

This module explores core skills for analyzing network security and identifying vulnerabilities:

### 🛡️ Penetration Testing Methodologies  
Understanding structured approaches to simulate real-world attacks and uncover system weaknesses.

### 🌐 Nmap for Network Scanning  
Mapping active hosts and services, analyzing open ports, and discovering potential attack vectors.

### 🧪 Nessus Configuration & Vulnerability Management  
Installing and using Nessus Essentials, applying CVSS scoring, and proposing realistic mitigation strategies.

---

## 📄 Capstone Project: Vulnerability Assessment Report

### 🎯 Objective  
Identify and evaluate critical vulnerabilities in a deliberately vulnerable system (Metasploitable 2) and propose actionable solutions.

---

### 🛠️ Tools Used

- 🔍 **Nmap** for port and service discovery  
- 🛡️ **Nessus Essentials 10.8.3** for scanning and CVSS scoring  
- 🐧 **Kali Linux** as the operating environment

---

### ⚠️ Key Vulnerabilities Identified

| Port | Service     | Vulnerability                 | Risk                  |
|------|-------------|-------------------------------|-----------------------|
| 8009 | ajp13       | Ghostcat – Remote execution   | 🔴 Remote Code Execution |
| 8180 | HTTP        | Outdated Apache Tomcat        | 🔶 Upgrade required      |
| 1524 | wild_shell  | Unknown backdoor service      | 🔴 OS Compromise         |
| 5900 | VNC         | Weak password access          | 🟠 Credential risk       |
| 6667 | IRC         | UnrealIRCd backdoor           | 🔴 Code execution        |

---

### 🛠 Proposed Solutions

- Upgrade vulnerable software versions (Tomcat, VNC, IRC)  
- Verify software integrity using hash checks  
- Reinstall compromised systems as necessary

---

## ✅ Outcome

I produced a **comprehensive report** for the fictional client *JetStorm S.p.A.* including:

- 📑 Executive summary for decision-makers  
- 🧾 Detailed technical report for analysts  
- 💡 Targeted remediation actions for each identified vulnerability

---

## 🧠 Conclusion

This third capstone project highlighted the critical importance of **vulnerability assessment** in cybersecurity defense. By combining tools like **Nmap** and **Nessus**, I gained hands-on experience in identifying, classifying, and managing threats in a controlled environment.
