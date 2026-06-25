# Junaid Ahmed | Defensive Security & Forensics Portfolio

Welcome to my engineering logs. This repository documents my hands-on experience building defensive architectures, analyzing host/network telemetry, and conducting forensic investigations. 

I am currently documented my progress through the **Cyberster Blue Team Internship (Batch #02)** mentored by Abdullah Zia[cite: 2]. My focus is on moving past simple theory to build production-grade detection pipelines and comprehensive incident timelines[cite: 1, 2].

## 🛠️ Core Tech Stack & Tools
*   **SIEM / Log Management:** Wazuh SIEM[cite: 2]
*   **Intrusion Detection:** Suricata IDS[cite: 2]
*   **Forensics & Artifact Analysis:** FTK Imager, Autopsy, EZ Tools Suite[cite: 2]
*   **Network Analysis:** Wireshark, tcpdump[cite: 2]

---

## 📁 Repository Structure & Roadmap

### 🔵 01_SOC-Track (Phase 1: Weeks 1 - 6)
*   [x] **Week 1: SOC Foundations & Lab Setup** | Dual-adapter isolated network setup using VMware Workstation Pro. Deployed Kali Linux (Attacker), Ubuntu Server (Wazuh SIEM), and Windows 10 Pro (Monitored Endpoint)[cite: 1, 2].
*   [ ] **Week 2: Wazuh SIEM Compilation** | Setting up the indexer, server manager, and security dashboard components from the ground up[cite: 1].
*   [ ] **Week 3: Real-Time File Integrity Monitoring (FIM)** | Configuring directory watching and filtering system logging noise[cite: 1, 2].
*   [ ] **Week 4: Suricata IDS Integration** | Merging live network traffic detection rules into centralized SIEM alert feeds[cite: 2].
*   [ ] **Week 5: Threat Intelligence Automation** | Building automation lookups utilizing active OSINT feeds (VirusTotal, Abuse.ch)[cite: 2].
*   [ ] **Week 6: Applied Malware Analysis** | Investigating runtime executable execution paths and staging response plans[cite: 2].

### 🔴 02_DFIR-Track (Phase 2: Weeks 7 - 12)
*   [ ] **Week 7: Forensic Disk Imaging** | Creating bit-stream forensic copies, executing integrity checks, and logging strict chain of custody data[cite: 2].
*   [ ] **Week 8: Windows Host Artifacts** | Deep carving of Event Logs, parsing application Prefetch history, and system execution trace tracking[cite: 2].
*   [ ] **Week 9: Browser & Memory Forensics** | Recovering data streams, session state, and download histories from common web clients[cite: 2].
*   [ ] **Week 10: Shortcut & Device Analysis** | Reconstructing chronological user activity using Jump Lists, LNK metadata patterns, and external storage footprints[cite: 2].
*   [ ] **Week 11: Windows Registry Forensics** | Locating persistence footholds, checking configuration states, and parsing malware execution artifacts[cite: 2].
*   [ ] **Week 12: M57 Capstone Investigation** | Full-scale incident analysis on an intellectual property theft case resulting in a court-ready technical brief[cite: 2].

---

## 🚀 Key Achievements & Baseline Labs
*   **TryHackMe SOC Level 1 Path:** Completed 20+ dedicated defensive lab rooms focusing on log data review and security analysis processes.

## 📫 Professional Links
*   **LinkedIn:** https://www.linkedin.com/in/junaidsawand/
*   **TryHackMe Profile:** https://tryhackme.com/p/junaidsawand