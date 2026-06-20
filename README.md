Open-Source Cybersecurity Ecosystem
A comprehensive collection of industry-leading open-source tools for Security Operations Centers (SOC), Threat Intelligence, Digital Forensics, and AI-driven security automation.

Table of Contents
SOC Operations
Threat Intelligence (CTI)
Digital Forensics & Incident Response (DFIR)
Mobile Security
Endpoint Detection & Response (EDR)
AI Security & Automation
Network Security
OSINT & Recon
SOC Operations
Core Stack
| Purpose | Tool | | :--- | :--- | | SIEM | Wazuh | | Case Management | TheHive | | Threat Intelligence | MISP | | Threat Graph | OpenCTI | | IOC Enrichment | Cortex | | SOAR | Shuffle | | NIDS | Suricata | | Network Metadata | Zeek | | Search Platform | OpenSearch |

Incident Management & Workflows
IRIS: Case management and evidence tracking; alternative to ServiceNow SecOps.
SOCFortress: Integrated SOC stack with Wazuh and MISP.
Timesketch: Forensic timeline analysis by Google.
Hayabusa: Fast Windows event log hunting using Sigma rules.
Threat Intelligence (CTI)
Yeti: Platform for organizing IOCs, malware, and actor tracking.
IntelOwl: Automated IOC enrichment (VirusTotal, Hybrid Analysis).
ThreatBus: Real-time intelligence sharing bus between tools.
ATT&CK Navigator: Visualization and mapping of the MITRE ATT&CK framework.
Digital Forensics & Incident Response (DFIR)
Velociraptor: Advanced endpoint visibility and live response.
KAPE: Rapid forensic artifact acquisition.
Chainsaw: Windows event log and MFT hunting.
Plaso: Engine for creating super-timelines (log2timeline).
Autopsy: GUI-based disk forensic platform.
Mobile Security
Analysis & Reverse Engineering
MobSF: All-in-one static and dynamic analysis.
Androguard: Python-based APK reverse engineering.
JADX: Android decompiler.
Frida: Dynamic instrumentation toolkit.
Objection: Runtime mobile exploration (Frida wrapper).
Mobile Forensics
ALEAPP: Android Logs Events and Protobuf Parser.
AndroidQF: Quick forensic acquisition for Android.
Andriller: Decryption and acquisition for Android devices.
Endpoint Detection & Response (EDR)
FleetDM: Management for osquery at scale.
Osquery: SQL-based operating system instrumentation.
LimaCharlie: Cloud-native EDR agent and infrastructure.
OpenEDR: Complete open-source EDR solution.
HELK: Threat Hunting ELK stack with Sigma and Sysmon support.
AI Security & Automation
Local LLM & Frameworks
Open WebUI: Interface for local LLMs.
Ollama: Local LLM runner.
Open Interpreter: Local code interpreter.
CrewAI: Multi-agent orchestration.
LangGraph: Cyclic graph-based agent orchestration.
Modern AI SOC Architecture
Integration pattern for AI-assisted security: Wazuh + OpenCTI + TheHive + Ollama + Llama 3 + CrewAI

Network Security
Arkime: Full packet capture and indexing.
Malcolm: Integrated network traffic analysis (Zeek + Suricata + Arkime).
Brim: Desktop application for searching PCAP and Zeek logs.
RITA: Beaconing detection in network logs.
Stenographer: High-speed packet capture to disk.
OSINT & Recon
OSINT Tools
SpiderFoot: Modular OSINT automation.
Recon-ng: CLI-based OSINT framework.
Maigret: Username checking across social platforms.
theHarvester: Email, subdomain, and names harvester.
Recon Frameworks
OWASP Amass: In-depth DNS enumeration and mapping.
ProjectDiscovery Stack: subfinder, naabu, httpx, nuclei.
BBOT: OSINT and recon automation framework.
Contributing
Contributions are welcome. Please refer to the CONTRIBUTING.md for guidelines on adding new tools or updating existing documentation.

License
This list is distributed under the MIT License. See LICENSE for more information.
