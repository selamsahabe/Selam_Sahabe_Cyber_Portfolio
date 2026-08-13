# Selam_Sahabe_Cyber_Portfolio

## Hi there, I'm a Cyber Security Analyst! 👋

Welcome to my cybersecurity portfolio. I am passionate about Threat Hunting, Incident Response, and Blue Teaming. Here, I document my hands-on experience solving complex security incidents and analyzing real-world cyber threats.

---

## 🛡️ Featured SOC Investigation Write-ups

Here are detailed breakdowns of security alerts I investigated and remediated on **LetsDefend (VIP+)**:

### 🌐 [SOC169 - Possible IDOR Attack Detected](https://github.com/selamsahabe/LetsDefend-SOC169-IDOR-Attack-Analysis)
* **Category:** Web Application Security / IDOR
* **Verdict:** `True Positive (Successful)`
* **Core Skills:** Web log analysis, HTTP response code auditing, payload impact analysis.
* **Brief:** Investigated consecutive POST requests targeting a user info endpoint. Confirmed data breach and unauthorized data access by analyzing varying HTTP response sizes and a 200 OK status code trend.

### ✉️ [SOC326 - Impersonating Domain MX Record Change Detected](https://github.com/selamsahabe/LetsDefend-SOC326-Impersonating-Domain-MX-Record-Change-Analysis)
* **Category:** Threat Intelligence / Email Security
* **Verdict:** `True Positive`
* **Core Skills:** Typosquatting analysis, mail exchange (MX) verification, proxy log correlation.
* **Brief:** Remedated a highly targeted phishing campaign involving an organizational lookalike domain (`letsdefwnd[.]io`), leading to automated email purging and compromised endpoint isolation.

### 🎯 [SOC163 - Suspicious Certutil.exe Usage](https://github.com/selamsahabe/LetsDefend-SOC163-Certutil-Analysis)
* **Category:** Endpoint Security / Living off the Land (LOLBins)
* **Verdict:** `True Positive`
* **Core Skills:** Command-line forensics, threat actor timeline reconstruction, network isolation.
* **Brief:** Investigated a live hands-on-keyboard attack where an adversary utilized `certutil.exe` to bypass execution policies, download Nmap, and perform active internal network enumeration.
---

## 🧰 Skills & Tools

* **SIEM & Log Management:** Log Analysis, Event Correlation, Network/Proxy Logs.
* **Endpoint Protection:** EDR Alerts, Process Monitoring, Host Isolation.
* **Threat Intel & OSINT:** VirusTotal, AbuseIPDB, URLScan, Sandbox Analysis (Any.Run).
* **Frameworks:** MITRE ATT&CK Mapping, Incident Response Playbooks.

---

## 📈 Platform Profiles

* 🟦 **LetsDefend:** //[My Profile]()
* 💼 **LinkedIn:** //[Connect with me](https://www.linkedin.com/in/selam-sahabe-karadag/)

*“Continuous monitoring, immediate containment, thorough investigation.”*
