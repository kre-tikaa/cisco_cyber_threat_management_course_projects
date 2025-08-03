# 🛡️ Cisco Module 6: Digital Forensics and Incident Response – Lab Projects

This folder contains completed lab assignments for **Module 6: Digital Forensics and Incident Response** from the Cisco Cyber Threat Management course. These labs focus on malware analysis, incident response planning, system forensics, and recovery from major disruptions such as data breaches or system failures.

---

## ✅ Labs Included

### 🔹 Lab 1: Gather System Information After an Incident
- Collected live system data from a compromised virtual machine (CSE-LABVM)
- Used Linux commands to capture:
  - System info (`uname`)
  - Network interfaces (`ifconfig`)
  - Open connections (`netstat`)
  - Running processes (`ps`)
  - Routing table (`route`)
- Extracted login attempt logs from:
  - `/var/log/auth.log`
  - `/var/log/btmp`
  - `/var/log/wtmp`
- Saved everything into `report.txt` for forensic analysis before shutdown

### 🔹 Lab 2: Attack Analysis
- Used **ANY.RUN** sandbox and **MITRE ATT&CK Matrix**
- Investigated hash values of suspected malware
- Identified threats such as **ASYNC RAT** and **RedLine Stealer**
- Mapped behaviors to tactics like Execution, Persistence, and Credential Access
- Analyzed SHA256 values, process trees, ATT&CK techniques, and indicators of compromise (IOCs)

### 🔹 Lab 3: Incident Handling
- Practiced formulating incident response questions using two real-world scenarios:
  - Worm + DDoS infection at a small investment firm
  - Physical breach and unauthorized payroll access at a hospital
- Applied both the **Diamond Model** and **Kill Chain Model**
- Emphasized preparation, containment, detection, and post-incident activities
- Addressed CSIRC readiness, evidence gathering, and user awareness

### 🔹 Lab 4: Packet Tracer – Investigate Disaster Recovery
- Replaced a failed switch in a Packet Tracer environment
- Backed up startup-config and vlan.dat to a TFTP server
- Deployed a new switch and restored configuration
- Verified recovery using `show vlan`, `show ip interface brief`, and other diagnostic commands

### 🔹 Lab 5: Recommend Disaster Recovery Measures
- Addressed disaster scenarios like:
  - Natural disaster (damaged data center)
  - DDoS attack (inaccessible web services)
  - Data loss (human error)
- Recommended:
  - Offsite backups
  - RTO and RPO planning
  - DDoS mitigation tools (Cloudflare, AWS Shield)
  - Employee training, redundant infrastructure, and IR plans

---

## 🛠 Tools, Concepts & Frameworks

- **ANY.RUN**, **MITRE ATT&CK**, **Diamond Model**, **Kill Chain Model**
- **TFTP**, `startup-config`, `vlan.dat`, Linux shell tools
- **Logs**: `auth.log`, `btmp`, `wtmp`
- **Packet Tracer**
- **Incident Response Phases**: Preparation, Detection, Containment, Recovery, Post-Incident

---

## 📁 Files

- `Lab1_Gather_System_Information_After_an_Incident.pdf`
- `Lab2_Attack_Analysis.pdf`
- `Lab3_Incident_Handling.pdf`
- `Lab4_Packet_Tracer_Investigate_Disaster_Recovery.pdf`
- `Lab5_Recommend_Disaster_Recovery_Measures.pdf`

---

## 💡 Learning Outcomes

- Conduct forensic analysis and log collection
- Use threat intelligence platforms to classify malware behavior
- Understand frameworks for structured incident response
- Perform switch restoration in a simulated recovery environment
- Design practical disaster recovery measures based on business impact
