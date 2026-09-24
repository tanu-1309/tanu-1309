<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/ledger-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/ledger-light.svg">
  <img alt="Tanu Sree Reddy Gavinnolla. I find the gaps, then make sure they actually get closed. Findings ledger: 75 to 80 vulnerability assessments closed; EDR agent baselines standardised across 500+ endpoints; MITRE ATT&CK detection logic, about 20% better fidelity; automated revocation and host isolation, about 30% lower MTTR; IDS and firewall tuning, 35% higher accuracy. Next role: open to opportunities." src="assets/ledger-light.svg" width="100%">
</picture>

I'm a cyber security engineer in the Master of Applied Computing co-op at the University of Windsor. As a security intern at BlueCloud Softech I worked the whole loop on a vulnerability: scan it, triage it, write it up, and chase the fix until it closed.

My work sits where tooling meets process. Qualys and Nmap findings that become tracked remediation, MITRE ATT&CK detection logic, FortiGate and FortiMail hardening, and Python and PowerShell automation that takes hours out of incident response.

**[tanusreereddy.com](https://tanusreereddy.com)** · [LinkedIn](https://www.linkedin.com/in/TanusreeReddy) · [gavinno@uwindsor.ca](mailto:gavinno@uwindsor.ca)

## Experience

**Cyber Security Intern, BlueCloud Softech Solutions** (2025)

A 15-person security team, covering vulnerability management, detection engineering and incident response.

- Ran 75–80 vulnerability assessments with Qualys VMDR and Nmap, tracking findings, remediation timelines and audit evidence through to closure.
- Standardised EDR agent baselines across 500+ endpoints.
- Built MITRE ATT&CK-aligned detection logic that lifted lateral-movement and process-anomaly detection fidelity by about 20%.
- Automated credential revocation and host isolation in Python and PowerShell against firewall and threat-intel APIs, contributing to about 30% lower MTTR.
- Supported forensic analysis and containment on a compromised AWS EC2 instance, and hardened FortiGate rules plus SPF, DKIM and DMARC on FortiMail.

**Virtual Intern, Palo Alto Networks** (2024, virtual job simulation)

- Tuned intrusion detection and firewall policy, raising threat-identification accuracy by 35%.
- Consolidated 10 threat-intelligence APIs into a single interface, halving analysis time.

**Education.** Master of Applied Computing (co-op), University of Windsor, 2026 to present. B.Tech in Computer Science and Engineering (Cyber Security), CVR College of Engineering, 2021–2025, CGPA 9.17/10.

## Selected work

| Repository | What it does |
| --- | --- |
| [vuln-priority-engine](https://github.com/tanu-1309/vuln-priority-engine) | Ranks scanner output by how likely a CVE is to be exploited, not by CVSS alone. Enriches findings with EPSS, CISA KEV and asset criticality, then produces an SLA-bucketed remediation queue. Runs offline on bundled sample data. |
| [sentinel-triage](https://github.com/tanu-1309/sentinel-triage) | SIEM alert triage. Clusters events by entity and time window, matches Sigma rules mapped to MITRE ATT&CK, and has an LLM summarise each incident with citations that must point to real event IDs. Includes an analyst review queue and a precision/recall harness. |
| [iocextract](https://github.com/tanu-1309/iocextract) | Pulls IPs, domains, URLs, emails and file hashes out of logs and reports, rejects version-string false positives, and defangs indicators so they're safe to paste into a ticket. Python, stdlib plus pydantic. |
| [soc-automation-lab](https://github.com/tanu-1309/soc-automation-lab) | An automated SOC workflow on local VMs: Wazuh detects, The Hive tracks cases, Shuffle orchestrates, and VirusTotal enriches alerts. |
| [elk-siem-dashboard](https://github.com/tanu-1309/elk-siem-dashboard) | A SIEM on the ELK stack in Docker, with Filebeat and Logstash parsing, GeoIP enrichment, Kibana dashboards and alert rules. |
| [ai_soc](https://github.com/tanu-1309/ai_soc) | Local-first, AI-assisted SOC research: trained intrusion-detection models, alert triage on a local Ollama LLM, Wazuh integration and response planning. |

**Coursework and research**

- **Digital forensics lab.** Staged a breach in an isolated VM lab, then reconstructed it: disk with Autopsy, memory with Volatility 3, network with Wireshark, with chain-of-custody records and SHA-256 evidence hashing.
- **Cryptographic key management system.** Python and Flask, with AES-GCM, RSA-OAEP and PBKDF2 for key storage, plus key rotation, revocation, audit logging and role-based access.
- **Cloud storage security on blockchain.** Elliptic-curve encryption with Ethereum smart contracts for hash-based integrity checks.
- **Published paper (co-author).** Botnet detection on the Bot-IoT dataset with Decision Tree, Random Forest and 1D-CNN models, in the International Journal of Research Publication and Reviews (IJRPR).

## Toolbox

| Area | Tools |
| --- | --- |
| Assess and detect | Qualys VMDR, Nmap, Wireshark, EDR platforms, MITRE ATT&CK |
| Investigate | Autopsy, Volatility 3, FTK Imager, Windows registry analysis, chain of custody |
| Harden and automate | FortiGate, FortiMail (SPF, DKIM, DMARC), Python, PowerShell, Bash |
| Govern | Security audits, risk management, security documentation and policies |
| Also | Java, C, JavaScript, Flask, Git, AWS and Azure fundamentals |

I'm open to opportunities. Email is the quickest way to reach me.
