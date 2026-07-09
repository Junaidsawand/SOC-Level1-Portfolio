# Junaid Ahmed  | Defensive Security & Forensics Portfolio

Welcome to my engineering logs. This repository documents my hands-on experience building defensive security architectures, analyzing host/network telemetry, and conducting deep-dive digital forensic investigations. 

My focus is on moving past foundational theory to architect production-grade detection pipelines, implement automated incident containment, and reconstruct granular compromise timelines.

---

## 🛠️ Core Tech Stack & Tools

*   **SIEM / Log Management:** Wazuh SIEM, Elastic Stack, Logstash
*   **Intrusion Detection:** Suricata Network IDS
*   **Endpoint Security:** File Integrity Monitoring (FIM), System Audit Logging, Host-Based Firewalls
*   **Digital Forensics & Incident Response (DFIR):** FTK Imager, Autopsy, EZ Tools Suite (PECmd, LECmd, RECmd, Registry Explorer), log2timeline/plaso
*   **Network Triage:** Wireshark, tcpdump

---

## 📁 Repository Structure & Engineering Roadmap

### 🔵 SOC-Track (Phase 1 — Security Operations & Threat Detection Engineering)
*   [x] **Week 1: SOC Foundations & Lab Architecture** | Engineered a dual-adapter isolated testing infrastructure using VMware Workstation Pro. Deployed a localized attack platform (Kali Linux), a centralized SIEM hub (Ubuntu Server hosting the Wazuh Manager, Indexer, and Dashboard), and a monitored enterprise target (Windows 10 Pro).
*   [ ] **Week 2: File Integrity Monitoring (FIM) & Automated Active Response** | Configured real-time cross-platform directory watching engines (`syscheck`). Engineered multi-stage custom XML detection signatures (IDs > 100000) for unauthorized user account creations, threshold-based SSH brute-force actions, and Windows USB device placements. Implemented dynamic host containment actions via stateful firewall scripts.
*   [ ] **Week 3: Network Intrusion Detection Engine Integration** | Integrating Suricata IDS to merge network-layer signature events and live packet capture inspection streams directly into the centralized SIEM telemetry pipeline.
*   [ ] **Week 4: Threat Intelligence Automation & Enrichment** | Building automated API enrichment lookups leveraging OSINT threat intelligence feeds (VirusTotal, Abuse.ch) to auto-triage indicators of compromise.
*   [ ] **Week 5: Log Aggregation, Normalization & Parsers** | Custom log ingestion engineering, configuring advanced parsers, and standardizing high-volume telemetry fields across heterogeneous operating systems.
*   [ ] **Week 6: Behavioral Malware Triage & Incident Playbooks** | Conducting static and dynamic analysis of malicious execution paths and compiling structured incident response containment playbooks.

### 🔴 DFIR-Track (Phase 2 — Digital Forensics & Incident Response)
*   [ ] **Week 7: Forensic Imaging & Evidence Preservation** | Provisioning bit-stream forensic copies, executing strict cryptographic verification hashing, and mapping formal chain of custody data logs.
*   [ ] **Week 8: Windows Host Artifact Triage** | Deep data carving of native Windows Event logs, parsing application execution traces (Prefetch, Amcache, Shimcache), and reconstructing active system execution baselines.
*   [ ] **Week 9: Memory Forensics & Browser History Analysis** | Carving volatile memory dumps and parsing browsing history streams, active session cookies, and local download registers across modern web clients.
*   [ ] **Week 10: User Activity Timeline Reconstruction** | Tracing chronological human actions through automated parsing of shell items, jump lists, `.lnk` metadata files, and external storage device system interactions.
*   [ ] **Week 11: Windows Registry Forensics** | Uncovering advanced persistence mechanisms, user profile modifications, installed applications, and hidden malware configuration hives.
*   [ ] **Week 12: Comprehensive Incident Investigation Capstone** | Full-scale forensic analysis of a complex network breach and intellectual property theft scenario, culminating in an executive-ready technical brief.

---

## 🚀 Key Achievements & Applied Learning
*   **TryHackMe SOC Level 1 Certification Path:** Completed over 20+ hands-on defensive security labs focusing on log analysis, packet analysis, and tactical alert triage.

---

## 📫 Professional Connections
*   **LinkedIn:** [linkedin.com/in/junaidsawand](https://www.linkedin.com/in/junaidsawand/)
*   **TryHackMe Portfolio:** [tryhackme.com/p/junaidsawand](https://tryhackme.com/p/junaidsawand)
