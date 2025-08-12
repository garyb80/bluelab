# BlueLab – My Cybersecurity Home Lab

**Author:** garyb80  
**Objective:** Build a self-contained Blue Team lab to practice SOC analysis, threat hunting, incident response, vulnerability management, IAM, and sysadmin skills — all in one evolving environment.

---

## 📜 Overview

This repository documents the creation and continuous improvement of **BlueLab**, a simulated enterprise environment designed for **hands-on cybersecurity practice**.  

The lab evolves month by month:
- Starts with basic **Windows + Linux hosts**
- Grows into a full **Active Directory domain** with SIEM integration
- Expands to include **cloud logging, IAM security, and vulnerability management**
- Supports **Blue Team & Threat Intelligence workflows** with ATT&CK mapping

Every skill and tool I learn will be applied **multiple times** to reinforce retention and produce **job-ready portfolio artifacts**.

---

## 🛠 Current Lab Setup (Month 1)

| Component      | Version/Details                          | Purpose |
|----------------|------------------------------------------|---------|
| Host Platform  | VirtualBox (v7.x)                        | VM management |
| Windows Client | Windows 11 (Evaluation)                  | Endpoint for user simulation & event logs |
| Linux Server   | Ubuntu Server 22.04 LTS                  | Log collection, sysadmin practice |
| Logging Agent  | Sysmon w/ custom config                  | Endpoint telemetry |
| Network        | NAT + Host-Only                          | Controlled lab traffic |

---

## 📂 Repository Structure

bluelab/
│
├── 01-foundation/ # Lab setup notes, diagrams, basic logging
│ ├── lab-setup-notes.md
│ ├── week3-logs.md
│
├── sysadmin-fundamentals/ # Windows & Linux admin skills
│ ├── week2-user-mgmt.md
│
├── detections/ # Detection logic & test cases
│ ├── powershell-encodedcommand.md
│
└── CHANGELOG.md # Weekly updates & progress tracking


---

## 📈 Skills Practiced (Month 1)
- Git & GitHub basics
- Virtual machine creation
- Windows & Linux user management
- Basic networking (IP, DNS, ping)
- Sysmon installation & configuration
- Event log navigation & parsing
- Writing simple detection logic

---

## 🧠 Learning Goals
1. Reinforce **foundational IT skills** (networking, sysadmin tasks)
2. Develop **SOC analyst workflows** (log analysis, detection tuning)
3. Build **threat intelligence-driven detections**
4. Simulate **real-world incidents** for practice
5. Create a **job-ready portfolio** with reusable projects

---

## 📅 Timeline & Progress

| Month | Focus Area                           | Key Deliverables |
|-------|---------------------------------------|------------------|
| 1     | Foundation + GitHub habits           | Initial lab setup, first detection |
| 2     | Active Directory core + Vuln Mgmt     | AD config, vuln scan & remediation |
| 3     | SIEM integration + IAM basics         | Forwarding logs, IAM lifecycle docs |
| ...   | ...                                   | ... |

---

## 📌 Notes
- All work is done in an **isolated lab environment** — no production systems are affected.
- Sensitive data is sanitized before committing to GitHub.
- Logs and detections are based on **safe simulations**.

---

## 🏁 How to Reproduce (Basic)
1. Install [VirtualBox](https://www.virtualbox.org/) or VMware Workstation Player.
2. Download Windows 11 evaluation ISO and Ubuntu Server LTS ISO.
3. Create VMs with NAT networking and install OS.
4. Install Sysmon on Windows with a security-focused config.
5. Start collecting logs and follow along with the repository updates.

---

## 📬 Contact
- **LinkedIn:** www.linkedin.com/in/garybrown80
- **Email:** garyb80@gmail.com  

---
