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

