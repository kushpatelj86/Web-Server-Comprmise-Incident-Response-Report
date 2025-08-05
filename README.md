# SecureTech Cybersecurity Incident Response

**Phishing-Based Credential Theft Simulation — April 2025**  
**Course:** CPSC 455 – Web Security (Spring 2025)

This project simulates a real-world cybersecurity incident involving a phishing-based credential theft attack on the Networks and Servers of SecureTech Solutions, leading to a User's account being compromised and resulting in a social engineering attack within the Company. The project was completed individually for academic purposes.

---

## Main Deliverable

**`IncidentResponseForm.docx`** – An executive-level incident report detailing:

-  Attack timeline  
-  Indicators of compromise (IOCs)
-  Findings
-  Financial impact (~$466,700)  
-  Response actions taken  
-  Lessons learned(Successes)
-  Opportunities for Improvement  

Designed for executive leadership, legal teams, Auditors, Incident Response Analysts and IT security management.

---

## Scenario Overview

I am a SOC analyst at SecureTech Solutions. An employee reports a suspicious email:
From: Jason Robinson jrobinson@securetech.com
To: Stephanie Morgan smorgan@securetech.com
Subject: "You have one (1) new message"
Link: srv-61.kim.johnson.biz/login

---

### Provided Resources

- `http.log` – HTTP metadata (web server logs)  
- `mail.log` – Email logs  
- `inventory.csv` – Mapping of internal users, devices, and IP addresses

### My Objectives

- Analyze logs and metadata to determine what happened  
- Write a detailed incident report  
- Create a technical investigation log documenting your methods

---

## Supporting Files (`/Web Compromise` folder)

### 🔍 Provided Logs

- `http.log` – Tracks web-based access behavior  
- `mail.log` – Identifies email communication and delivery  
- `inventory.csv` – Maps usernames to devices and IPs  

### Investigation Artifact

- `Investigation Log.pdf` – Includes:
  - Log queries and pattern recognition  
  - Timeline reconstruction  
  - HTTP and IP behaviour tracking
  - Activity from every user that sent and received a message on the network
  - Tracks all mail communication between all clients
  - Logged any suspicious and malicious activity
  - Logged certain patterns and similar emails to those of the attacker
  - Looked at the attacker's IP addresses
  - Looked at all the websites with the same domain or DNS server as "srv-61.kim.johnson.biz"
---


## Skills Demonstrated

- Log and metadata analysis  
- Incident response planning and containment  
- Web-layer threat detection (e.g., phishing, HTTP misuse)  
- Executive documentation
- Technical Documentation 
- Analytical thinking
- Investigative Workflow 
- Threat Hunting
- DNS Analysis
- Network Forensics
- Endpoint Detection
- Security Awareness & User Behaviour Analysis
- Web Traffic & Behaviour Analysis
- HTTP Method Analysis
- Malicious Infrastructure Mapping
- Behavioural Correlation
- Credential Hygiene Monitoring
- Anomaly Detection
- Risk Mitigation Planning
- Phishing Campaign Recognition

---



## Note

This project was designed to simulate a real-world security incident and demonstrate the end-to-end workflow of a SOC analyst

- Evidence gathering
- Forensics
- Log Analysis
- Threat Detection
- Incident Timeline Construction
- Risk Assessment




## Disclaimer

This is a **fictional academic simulation**.  
All IP addresses, email addresses, and URLs (e.g., `srv-61.kim.johnson.biz`) are **entirely fictional** and created for instructional use only.

> **Do not** visit any links or interact with any domains referenced in the report. They may be inactive or unsafe.

---

 Developed individually for **CPSC 455 – Web Security (Spring 2025)**  
