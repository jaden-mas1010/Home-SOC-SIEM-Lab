# 🏠 Home SOC & SIEM Lab  
A self‑built, fully isolated SOC environment designed to replicate real Security Operations workflows. This lab collects rich endpoint telemetry using **Sysmon (SwiftOnSecurity configuration)** and ingests it into **Splunk Enterprise**, enabling hands‑on experience with log analysis, detection engineering, and incident triage.

---

## 📛 Badges  
![Status: Active](https://img.shields.io/badge/Status-Active-brightgreen)  
![Splunk](https://img.shields.io/badge/SIEM-Splunk-orange)  
![Sysmon](https://img.shields.io/badge/Telemetry-Sysmon-blue)  
![Windows](https://img.shields.io/badge/OS-Windows%202022%20%7C%2010-lightgrey)  
![VMware](https://img.shields.io/badge/Virtualization-VMware_Workstation-purple)

---

## 🔧 Lab Architecture  
<img width="766" height="501" alt="image" src="https://github.com/user-attachments/assets/1ff86714-73bb-4859-b565-ad4357d0e9fc" />


---

## 🧰 Tools & Technologies  
- **Splunk Enterprise** — SIEM for log ingestion, dashboards, detections, correlation searches  
- **Sysmon (SwiftOnSecurity config)** — detailed process, network, registry, and file monitoring  
- **Windows Server 2022** — domain controller + event generation  
- **Windows 10 Endpoint** — Sysmon‑monitored workstation  
- **VMware Workstation** — isolated virtualization platform  
- **PowerShell & Sysinternals Suite** — attack simulation + forensic tooling  

---

---

## 🛡️ SOC Triage Workflow  
1. **Alert Review**  
2. **Log Enrichment**  
3. **Initial Investigation**  
4. **MITRE Mapping**  
5. **Decision Making**  
6. **Documentation**

---

## 🛠️ Detection Engineering Overview  
Detection engineering focuses on identifying malicious or suspicious activity through well‑designed SIEM rules. This lab includes custom SPL detections built from Sysmon telemetry and mapped to MITRE ATT&CK techniques.

### 🔹 Workflow  
- Telemetry review  
- Use case development  
- SPL rule creation  
- Testing & validation  
- Tuning & false positive reduction  
- Documentation

### 🔹 Example Use Cases  
- Suspicious PowerShell execution (T1059.001)  
- Credential access attempts (T1003)  
- Persistence mechanisms (T1547)  
- Network anomalies (TA0011)

---

## 📊 Splunk Dashboards

Below is an example of the dashboards built in this SOC lab, showcasing endpoint telemetry visibility, detection coverage, and SOC triage metrics.

### 🔹 Sysmon Visibility Dashboard  
Shows high‑volume telemetry including process creation, network connections, registry changes, and file events.

### 🔹 Detection Coverage Dashboard  
- Techniques tested: 20  
- Techniques detected: 16  
- Coverage: 80%  

### 🔹 Endpoint Activity Overview  
Displays process activity and network connections for `WIN10-ENDPOINT`.

### 🔹 SOC Triage Summary Dashboard  
Summarizes SOC alert handling:
- Alerts reviewed: 58  
- Alerts escalated: 12  
- Alerts closed: 46  

---



## 🎯 Lab Objectives  
This lab is built to practice and demonstrate core SOC analyst capabilities:

### 🔹 SOC Analyst Skills Practiced  
- Endpoint telemetry analysis (Sysmon)  
- SIEM log ingestion & parsing (Splunk)  
- SPL‑based detection engineering  
- MITRE ATT&CK technique mapping  
- Incident triage & documentation  
- Windows event analysis  
- Attacker chain reconstruction  

### 🔹 Why This Lab Matters  
This environment demonstrates the ability to:

- Build and operate a functional SOC lab  
- Understand how endpoint telemetry flows into a SIEM  
- Write and test real detection rules  
- Investigate suspicious activity using Splunk  
- Document incidents like a SOC analyst  
- Analyse attacker behaviour on Windows systems  

---

## 📈 Outcomes  
This lab showcases:

- **Hands‑on SIEM experience**  
- **Practical detection engineering**  
- **Realistic incident investigation workflows**  
- **Strong understanding of Sysmon telemetry**  
- **Ability to analyse Windows security events**  
- **SOC triage methodology and reporting**  

---

## 📘 Repository Contents  
- **/detections** — SPL rules and detection logic  
- **/investigations** — incident write‑ups and triage notes  
- **/config** — Sysmon + Splunk configuration references  
- **/docs** — architecture, methodology, and SOC workflows  

---

## 📄 About This Project  
This Home SOC & SIEM Lab is part of my ongoing SOC analyst development, focused on building practical, real‑world detection and investigation skills using enterprise‑grade tools.

