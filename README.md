# 🔐 Microsoft Azure Master Lab Project  

![Azure](https://img.shields.io/badge/Azure-Sentinel-blue?logo=microsoftazure)  
![Defender](https://img.shields.io/badge/Microsoft-Defender-blueviolet?logo=microsoft)  
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)  

A complete **hands-on SOC lab** for preparing for the **Microsoft SC-200: Security Operations Analyst Associate** exam.  
This project contains **10 mini-projects** that simulate real-world security operations tasks using:  
- 🛡️ Microsoft Sentinel (SIEM + SOAR)  
- 🖥️ Microsoft 365 Defender / Defender for Endpoint  
- ☁️ Azure Defender for Cloud (Secure Score)  
- 👤 Entra ID (Identity Protection)  

---

## 📖 Table of Contents
- [Overview](#-overview)  
- [Projects](#-projects)  
- [Skills Demonstrated](#-skills-demonstrated)  
- [Repo Structure](#-repo-structure)  
- [How to Use](#-how-to-use)  
- [Notes](#-notes)  

---

## 📖 Overview
The SC-200 exam measures your ability to:  
- **Manage a security operations environment (20–25%)**  
- **Configure protections and detections (15–20%)**  
- **Manage incident response (25–30%)**  
- **Manage security threats (15–20%)**  

This repo covers all objectives through **guided projects** with KQL queries, dashboards, playbooks, and incident drills.  

---

## 🚀 Projects

| # | Project | Description | SC-200 Mapping |
|---|---------|-------------|----------------|
| 01 | **Data Connectors** | Connect Microsoft 365, Defender, Entra ID, and Syslog/AWS logs into Sentinel | Security Operations Env |
| 02 | **Analytics Rules (KQL)** | Create custom rules for brute force, impossible travel, mass downloads | Protections & Detections |
| 03 | **Automated Playbooks (SOAR)** | Build Logic App playbooks (isolate device, block IP, notify Teams) | Incident Response |
| 04 | **Workbooks & Dashboards** | Build dashboards for incidents, MITRE ATT&CK mapping, and alert trends | Incident Response |
| 05 | **Threat Hunting** | Use KQL to hunt brute force, persistence, lateral movement | Manage Threats |
| 06 | **Identity Protection** | Enable Entra ID Identity Protection, simulate risky sign-ins | Protections & Threats |
| 07 | **Incident Lifecycle Drill** | Simulate detection → investigation → remediation → closure | Incident Response |
| 08 | **Defender for Cloud** | Enable Secure Score, remediate findings, ingest alerts | Protections & Threats |
| 09 | **Non-Azure Logs** | Ingest AWS, GCP, or firewall logs into Sentinel | Security Operations Env |
| 10 | **Incident Report** | Write structured reports with lessons learned | Incident Response |

---

## 🛠️ Skills Demonstrated
- 🔎 **KQL (Kusto Query Language)** — analytics rules & hunting  
- 📊 **Microsoft Sentinel** — SIEM setup, automation, dashboards  
- 🤖 **SOAR (Playbooks)** — automated remediation  
- 🖥️ **Microsoft 365 Defender** — endpoint & email detections  
- ☁️ **Azure Defender for Cloud** — posture & secure score  
- 🎯 **Threat Hunting** — MITRE ATT&CK alignment  
- 🔐 **Identity Protection** — risky users & conditional access  
- 📑 **Incident Response Lifecycle** — detection → triage → investigation → remediation  

---

## 📂 Repo Structure
