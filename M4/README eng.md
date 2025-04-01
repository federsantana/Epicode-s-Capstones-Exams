# 🔐 README – Module 4: Exploitation & Web Application Attacks

## 🔍 Topics Covered

In Module 4, we explored real-world techniques to exploit system and web application vulnerabilities, including:

## 🚧 Exploiting Vulnerabilities with Metasploit

Understanding how to use Metasploit Framework to identify and exploit system-level weaknesses, gaining remote shell access via payloads like Meterpreter.

## 🔢 SQL Injection Attacks

Simulating and mitigating SQLi vulnerabilities in web forms and applications to retrieve data from backend databases.

## 🔋 Brute-force Attacks with Hydra

Using Hydra to automate brute-force authentication attacks on various services like SSH, FTP, and web logins.

## 🌐 Cross-Site Scripting (XSS) Analysis

Analyzing XSS vulnerabilities in websites and learning to defend against script injection that compromises user sessions.

-

## 📄 Capstone Project 4: Exploiting Java_RMI with Metasploit

This project is structured into:

### 📂 File 1: Introduction to M4 Project – Exploit JAVA_RMI – theoretical context and rationale.

### 📂 File 2: Full Capstone Project – complete exploitation with remediation.

### 📎 Nessus Report: Nessus Metasploitable Scan – used to validate the vulnerability.

## 🎯 Objective

Demonstrate the exploitation of a vulnerable Java RMI service on a Metasploitable 2 virtual machine using Metasploit, establish a Meterpreter session, collect sensitive information, and implement a defense.

## 🛠️ Tools Used

 🔍 Nmap – Port scanning and service detection

 🛡️ Metasploit Framework – Exploitation and payload deployment
 
 🐧 Kali Linux – Attacker environment

 🔌 UFW (Uncomplicated Firewall) – Remediation mechanism

 📄 Nessus Scan Report – External validation of exposed services

## ⚠️ Key Exploitation Steps

 1. Identified open TCP port 1099 running Java RMI using Nmap.

 2. Started Metasploit, selected and configured the java_rmi_server exploit module.

 3. Increased HTTPDELAY to avoid timeouts and gained a Meterpreter shell.

 4. Executed commands to collect:

  - Network configuration (ifconfig, route)

  - System information (sysinfo, ps)

  - Credential files (cat /etc/shadow)

 5. Demonstrated post-exploitation capabilities such as ARP table access and filesystem traversal.

## 🛠️ Remediation Action

To secure the system:

- Applied UFW firewall rules:

- sudo ufw deny 1099 – block all connections to the vulnerable port

- or restrict access to trusted IPs only

This reflects a realistic patching and access control approach.

## ✅ Outcome

 ✅ Successfully exploited the Java RMI service

 📊 Collected system and network intelligence

 🔐 Applied effective countermeasures to close the attack vector

## 🧠 Conclusion

This capstone project highlighted the risks of exposed and unprotected services like Java RMI. It underlined not only the offensive phase (exploitation), but also the importance of immediate remediation, providing a complete view of professional cybersecurity practices.

📊 Offensive knowledge + defensive countermeasures = complete cybersecurity maturity.
