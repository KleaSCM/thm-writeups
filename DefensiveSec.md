<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=00FF99&center=true&width=500&lines=Defensive+Security+by+CyDieLia;Detection+%7C+Monitoring+%7C+SIEM+Workflows;Blue+Team+Built+on+Logs+%26+Logic+%F0%9F%93%9A" alt="Typing SVG" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Goblin_Mode-Defensive-%2300C8A0?style=for-the-badge&logo=gnome&logoColor=white" />
  <img src="https://img.shields.io/badge/TryHackMe-CyDieLia-red?style=for-the-badge&logo=tryhackme&logoColor=white" />
  <img src="https://img.shields.io/badge/Detection-In_Progress-%230089CA?style=for-the-badge&logo=splunk&logoColor=white" />
  <img src="https://img.shields.io/badge/Editor-VSCodium-blue?style=for-the-badge&logo=vscodium&logoColor=white" />
</p>

---

# 🛡️ Defensive Security – Blue Team Ops with CyDieLia

Welcome to my **Defensive Security repository** — a growing toolkit of logging configs, detection strategies, SIEM rules, and scripts built to detect, trace, and respond to threats across Linux, Windows, and cloud systems.

---

## 🌒 Dark Mode Preview

> Markdown and screenshots optimized for GitHub dark mode.  
> SIEM outputs and logs color-coded where applicable.

---

## 🧠 What I’m Learning

| Area                        | Topics                                                                 |
|-----------------------------|------------------------------------------------------------------------|
| **SIEM & Logging**          | Splunk, Elastic, Sigma rules, log correlation                         |
| **Windows Blue Team**       | Sysmon, Event Logs, WEF, registry monitoring                          |
| **Linux Blue Team**         | Auditd, journald, file integrity monitoring, rootkit detection        |
| **Cloud Detection**         | AWS CloudTrail, Azure Defender, logging architecture                  |
| **Incident Response**       | Timeline building, IOC tracking, alert tuning                         |
| **MITRE ATT&CK Mapping**    | Detection coverage, log enrichment, behavioral signatures             |

---

## ✍️ Featured Repos

| Repo | Description |
|------|-------------|
| [**Blue Sentinel**](https://github.com/CediLia/blue-sentinel) *(coming soon)* | Modular incident triage scripts, SIEM queries, and alert templates |
| [**SysWatch**](https://github.com/CediLia/syswatch) *(planned)* | Lightweight host monitor with alerting and integrity checks |
| [**AD Logs & Detections**](https://github.com/CediLia/ad-logs-detections) *(planned)* | Windows Event Log detection logic for Active Directory attacks |
| [**Goblin Tools**](https://github.com/CediLia/goblin-tools) | Some scripts are shared between red and blue ops (e.g., recon monitoring) |

---

## ✅ TryHackMe Blue Team Progress

- [x] Blue Primer  
- [x] Windows Event Logging  
- [ ] SOC Level 1 Path  
- [ ] Investigating with Splunk  
- [ ] Detection Engineering Labs

---

## 🧰 Defensive Toolsets

---

### 🧠 SIEM / Analysis Tools

`Splunk` • `Elastic/Kibana` • `Sigma` • `Arkime`  
`Sysmon` • `LogonTracer` • `Sigma2Splunk` • `Kusto/KQL`  
`Auditd` • `osquery` • `Wireshark` • `Zeek`

---

### 🛡️ Detection + Monitoring Scripts

| Tool / Repo | Type |
|-------------|------|
| [**SysWatch**](https://github.com/CediLia/syswatch) *(planned)* | Host-level monitoring (audit logs, file integrity) |
| [**LogSifter**](https://github.com/CediLia/logsifter) *(planned)* | Python-based log parser for quick IOC detection |
| [**Blue Sentinel**](https://github.com/CediLia/blue-sentinel) *(coming soon)* | Central IR helper: alert builder + detection pack |
| [**AD Logs & Detections**](https://github.com/CediLia/ad-logs-detections) *(planned)* | Defensive logic for AD attacks, persistence spotting |

---

### ⚙️ Blue Team Scripts

#### PowerShell

| Script | Description |
|--------|-------------|
| `Invoke-SysmonConfig.ps1` | Deploys sysmon.xml with event forwarding |
| `Watch-AD-Auth.ps1` *(planned)* | Detects brute force, ticket reuse, anomalous logons |

#### Bash / Linux

| Script | Description |
|--------|-------------|
| `auditd-init.sh` | Hardens auditd logging rules and rotates logs |
| `cronmon.sh` *(planned)* | Monitors new or modified cron jobs, systemd timers |

#### Python

| Script | Description |
|--------|-------------|
| `logalert.py` | Keyword alert system for new logs (files or stdin) |
| `ioc-harvester.py` *(planned)* | Parses multiple log types for matches against IOC lists |

---

## 🧪 Detection Philosophy

- Start with logs → build visibility → expand coverage  
- Understand attacker methods by writing detections for them  
- I map all detections to MITRE techniques using `attack-navigator`

> Blue team isn’t just defense — it’s cyber forensics, behavioral profiling, and attack prediction.

---

## 📚 Learning Paths & Goals

- [x] Blue Primer & basic log analysis  
- [ ] Build custom Sysmon configs  
- [ ] Sigma to Splunk alert chains  
- [ ] Build a multi-host WEF test lab  
- [ ] Simulate and detect common attack chains  
- [ ] Track and visualize attacker movement using logs alone

---

## 🧙 About Me

- GitHub: [CediLia](https://github.com/CediLia)  
- TryHackMe: [CyDieLia](https://tryhackme.com/p/CyDieLia)  
- Cybersecurity student focused on threat detection & response  
- Building a dual skillset — attacker mindset, defender’s vision

---

> 📖 _“Every shell leaves a trace. The question is — did you notice?”_  
> 🗓️ Last updated: March 25, 2025
