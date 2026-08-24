# SOC Home Lab — Wazuh Learning Journey

## Project Description

A self-built SOC home lab using Wazuh SIEM to practice detection engineering end-to-end — from raw endpoint telemetry to MITRE ATT&CK-mapped alerts. Includes SIEM deployment, Windows/Linux agent onboarding, Sysmon telemetry, and real triggered detections, documented daily as SOC Analyst L1 prep.

Each day of work is logged individually, capturing what was built and what was learned — including detection logic, Windows Event ID analysis, and MITRE ATT&CK mapping. The intent is for this repo to double as both a personal learning record and a portfolio artifact demonstrating practical, hands-on security engineering and analysis skills.

## 🎯 Goals

- Build a functioning SIEM environment from the ground up
- Generate and analyze real endpoint telemetry across both Windows and Linux
- Practice mapping detections to **Windows Event IDs** and the **MITRE ATT&CK** framework
- Maintain daily consistency — even a single alert triaged or one new concept learned counts as progress worth logging

## 🧰 Lab Environment

| Component | Details |
|---|---|
| SIEM Platform | Wazuh 4.14.7 (Manager, Indexer, Dashboard) |
| Manager Host | Ubuntu Server (VM) |
| Monitored Endpoint 1 | Windows 10 Pro (VM) — agent `WindowsVM` |
| Monitored Endpoint 2 | Ubuntu 24.04 LTS (VM) — agent `Shubh-Linux` |
| Telemetry Source | Sysmon (installed on both Windows and Linux endpoints) |
| Hypervisor | VirtualBox |

## 📁 Repository Structure

```
soc-home-lab/
├── README.md                # This file — project overview and index
├── day-logs/                # Chronological daily journal entries
├── detections/               # Standalone write-ups per detection, organized by topic (not date)
└── resources/                 # Running reference material (Event ID cheat-sheet, MITRE mapping log)
```

## 📅 Daily Logs

| Day | Focus | Link |
|---|---|---|
| Day 1 | 3-VM lab setup (Wazuh manager + Windows + Linux endpoints), Wazuh SIEM deployment, agent onboarding, Sysmon install, first alert investigation (user creation → permission change → deletion) | [day-logs/day-01.md](day-logs/day-01.pdf) |

*(Updated daily — new entries added as the lab progresses.)*

## 📚 Resources

- [Windows Event ID Reference](resources/windows-event-ids.md) — running cheat-sheet of Event IDs encountered
- [MITRE ATT&CK Mapping Log](resources/mitre-attack-mapping.md) — techniques actually triggered and analyzed in this lab

## 📌 Notes

Any auth keys or credentials referenced in this lab are excluded via `.gitignore` and never committed. Shared for educational/portfolio purposes only.

---

*Following along as I build this out. Feedback and suggestions from fellow SOC/DFIR folks are welcome.*
