# 🚨 SOC Incident Response Playbook: Ransomware (NIST Aligned)

## 📝 Overview
This repository contains a strategic **Incident Response (IR) Playbook** designed to guide a Security Operations Center (SOC) through a P1 Critical Ransomware event. 

The core objective of this project is to demonstrate the ability to bridge **Technical Triage (Blue Team/DFIR)** with **Corporate Compliance and Legal Escalation (GRC)**. The playbook is structured around the globally recognized **NIST SP 800-61 Rev. 2** standard.

---

## 🏗️ Frameworks & Standards Applied
* **Incident Handling:** NIST SP 800-61 Rev. 2 (Computer Security Incident Handling Guide)
* **Information Security Management:** ISO 27001:2022 (Control A.5.24)
* **Data Privacy Regulations:** Turkish KVKK (Personal Data Protection Law) & GDPR

---

## 🛑 Phase 1 & 2: Detection, Analysis, and Containment
The initial phases focus on identifying the "blast radius" and stopping lateral movement without destroying crucial forensic evidence. 

**Key Directives:**
* Verification of SIEM/EDR alerts (e.g., shadow copy deletion).
* **Strict Network Isolation:** Disconnecting endpoints from the network switch rather than powering them down, ensuring live RAM can be captured for memory forensics.

![playbook_phase1](https://github.com/user-attachments/assets/88a58547-486d-4512-90bd-d264ccc3cdb6)

*Extract from the playbook detailing the NIST Detection and Containment phases.*

---

## ⚖️ Phase 3: Eradication, Recovery, and GRC Escalation
A critical, often overlooked phase of Incident Response is managing the legal and regulatory fallout of a data breach. This playbook specifically maps technical recovery to corporate compliance requirements.

**Key Directives:**
* Secure restoration from immutable, offline backups.
* **The 72-Hour Notification Rule:** Immediate escalation to the Legal department to comply with **KVKK Article 12/5** and GDPR requirements in the event of double-extortion data exfiltration.
* Documenting the event for future **ISO 27001** audits.

![playbook_phase2_kvkk](https://github.com/user-attachments/assets/41b09996-7123-430c-8e2c-e620e4a62113)

*Extract demonstrating the integration of technical recovery with KVKK and ISO 27001 compliance mandates.*

---

## 🎓 Conclusion
Effective Incident Response is a business function, not just an IT function. This playbook demonstrates my capability to act not only as a technical SOC Analyst but also as an Incident Commander who understands the critical intersection of cybersecurity operations, risk management, and legal compliance (GRC).
