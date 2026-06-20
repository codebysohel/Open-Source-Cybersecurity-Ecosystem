# Open-Source Cybersecurity Ecosystem

## SOC OPERATIONS

### Core Stack
| Purpose | Tool |
| :--- | :--- |
| SIEM | [Wazuh](https://github.com/wazuh/wazuh) |
| Case Management | [TheHive](https://github.com/TheHive-Project/TheHive) |
| Threat Intelligence | [MISP](https://github.com/MISP/MISP) |
| Threat Graph | [OpenCTI](https://github.com/OpenCTI-Platform/opencti) |
| IOC Enrichment | [Cortex](https://github.com/TheHive-Project/Cortex) |
| SOAR | [Shuffle](https://github.com/Shuffle/Shuffle) |
| NIDS | [Suricata](https://github.com/OISF/suricata) |
| Network Metadata | [Zeek](https://github.com/zeek/zeek) |
| Search Platform | [OpenSearch](https://github.com/opensearch-project/OpenSearch) |

---

## OSINT

### Hidden OSINT Tools

*   **[SpiderFoot](https://github.com/smicallef/spiderfoot)** - OSINT automation tool.
*   **[Recon-ng](https://github.com/lanmaster53/recon-ng)** - Full-featured Web Reconnaissance Framework.
*   **[Maigret](https://github.com/soxoj/maigret)** - Collect a dossier on a person by username.
*   **[Holehe](https://github.com/megadose/holehe)** - Check if an email is attached to an account on sites.
*   **[theHarvester](https://github.com/laramies/theHarvester)** - E-mail, subdomain and people names harvester.
*   **[Photon](https://github.com/s0md3v/Photon)** - Incredibly fast crawler designed for OSINT.
*   **[Datasploit](https://github.com/DataSploit/datasploit)** - Framework to perform various OSINT operations.
*   **[Social Analyzer](https://github.com/qeeqbox/social-analyzer)** - Analyze profiles across 1000+ social media platforms.

---

## RECON

### Hidden Recon Tools

*   **[OWASP Amass](https://github.com/owasp-amass/amass)** - In-depth Asset Discovery and Subdomain Enumeration.
*   **[Subfinder](https://github.com/projectdiscovery/subfinder)** - Subdomain discovery tool.
*   **[Naabu](https://github.com/projectdiscovery/naabu)** - Fast port scanner.
*   **[Katana](https://github.com/projectdiscovery/katana)** - Next-generation crawling and spidering framework.
*   **[httpx](https://github.com/projectdiscovery/httpx)** - Multi-purpose HTTP toolkit.
*   **[Nuclei](https://github.com/projectdiscovery/nuclei)** - Fast and customizable vulnerability scanner.
*   **[BBOT](https://github.com/blacklanternsecurity/bbot)** - Modular automated recon framework.

## SOC TOOLS

### SOC Platforms

* **[IRIS](https://github.com/dfir-iris/iris-web)** - Open-source incident response and case management platform. Supports incident handling, evidence tracking, IOC management, and investigation workflows.
* **[SOCFortress](https://github.com/socfortress)** - Complete SOC ecosystem with Wazuh integrations, MISP integrations, DFIR workflows, and blue-team automation capabilities.
* **[Timesketch](https://github.com/google/timesketch)** - Collaborative forensic timeline analysis platform developed by Google for threat hunting and DFIR investigations.
* **[Hayabusa](https://github.com/Yamato-Security/hayabusa)** - High-performance Windows event log hunting tool with Sigma rule support and rapid threat detection capabilities.

---

## THREAT INTELLIGENCE

### CTI Platforms

* **[Yeti](https://github.com/yeti-platform/yeti)** - Threat intelligence platform for IOC management, malware tracking, threat actor correlation, and intelligence enrichment.
* **[IntelOwl](https://github.com/intelowlproject/IntelOwl)** - Automated IOC enrichment framework integrating VirusTotal, URLHaus, MalwareBazaar, Hybrid Analysis, and other intelligence sources.
* **[ThreatBus](https://github.com/tenzir/threatbus)** - Real-time cyber threat intelligence sharing bus connecting MISP, Zeek, Suricata, OpenCTI, and other security platforms.
* **[ATT&CK Navigator](https://github.com/mitre-attack/attack-navigator)** - MITRE ATT&CK visualization and analysis tool for adversary mapping and defensive coverage assessments.

---

## DIGITAL FORENSICS

### DFIR Tools

* **[Velociraptor](https://github.com/Velocidex/velociraptor)** - Enterprise-grade DFIR and endpoint visibility platform supporting artifact collection, memory acquisition, live response, and threat hunting.
* **[KAPE](https://github.com/EricZimmerman/KapeFiles)** - Rapid evidence acquisition and forensic artifact collection framework designed for incident response investigations.
* **[Chainsaw](https://github.com/WithSecureLabs/chainsaw)** - Fast Windows forensic hunting tool leveraging Sigma rules and EVTX log analysis.
* **[Plaso](https://github.com/log2timeline/plaso)** - Log2Timeline engine for large-scale timeline generation and forensic event reconstruction.
* **[Autopsy](https://github.com/sleuthkit/autopsy)** - GUI-based digital forensics platform built on The Sleuth Kit for disk, file system, and artifact analysis.

---

## MOBILE SECURITY

### Core Mobile Security Tools

* **[MobSF](https://github.com/MobSF/Mobile-Security-Framework-MobSF)** - Automated mobile application security testing framework supporting static, dynamic, and malware analysis.
* **[Androguard](https://github.com/androguard/androguard)** - Reverse engineering and malware analysis toolkit for Android applications.
* **[JADX](https://github.com/skylot/jadx)** - Android decompiler that converts DEX and APK files into readable Java source code.
* **[Frida](https://github.com/frida/frida)** - Dynamic instrumentation toolkit for runtime analysis, reverse engineering, and application manipulation.
* **[Objection](https://github.com/sensepost/objection)** - Frida-powered runtime mobile application exploration and security assessment framework.

### Android Forensics

* **[ALEAPP](https://github.com/abrignoni/ALEAPP)** - Android artifact parser supporting application databases, logs, accounts, and forensic evidence extraction.
* **[AndroidQF](https://github.com/ydkhatri/AndroidQF)** - Android forensic acquisition and parsing framework for mobile investigations.
* **[Andriller](https://github.com/den4uk/andriller)** - Android forensic acquisition and decoding suite for extracting and analyzing device data.

---

## ENDPOINT DETECTION & RESPONSE

### EDR Platforms

* **[FleetDM](https://github.com/fleetdm/fleet)** - Enterprise-scale osquery management and endpoint orchestration platform.
* **[Osquery](https://github.com/osquery/osquery)** - SQL-powered operating system instrumentation framework exposing system data as relational tables.
* **[LimaCharlie Agent](https://github.com/refractionPOINT)** - Cloud-native EDR and security automation platform for endpoint visibility and response.
* **[OpenEDR](https://github.com/ComodoSecurity/openedr)** - Open-source endpoint detection and response solution with threat monitoring and remediation features.
* **[HELK](https://github.com/Cyb3rWard0g/HELK)** - Hunting ELK platform supporting Sigma, Sysmon, ATT&CK mapping, and advanced threat hunting operations.

---

## AI SECURITY

### Local LLM Security Projects

* **[Open WebUI](https://github.com/open-webui/open-webui)** - User-friendly web interface for managing and interacting with local large language models.
* **[Ollama](https://github.com/ollama/ollama)** - Lightweight framework for deploying and running large language models locally.
* **[Open Interpreter](https://github.com/OpenInterpreter/open-interpreter)** - Natural language interface enabling LLM-driven code execution and system interaction.
* **[CrewAI](https://github.com/crewAIInc/crewAI)** - Multi-agent orchestration framework for autonomous AI workflows and role-based agents.
* **[LangGraph](https://github.com/langchain-ai/langgraph)** - Stateful agent orchestration framework for complex AI and LLM applications.

### AI-Powered SOC

* **Wazuh + OpenCTI + TheHive + Ollama + Llama 3 + CrewAI** - Modern AI-driven SOC architecture combining detection, intelligence, incident response, local LLMs, and autonomous security agents.

---

## NETWORK SECURITY

### Network Visibility & Detection

* **[Arkime](https://github.com/arkime/arkime)** - High-performance packet capture, indexing, and network traffic search platform.
* **[Malcolm](https://github.com/idaholab/Malcolm)** - Integrated network monitoring stack combining Zeek, Suricata, Arkime, and traffic analysis components.
* **[Brim](https://github.com/brimdata/brim)** - Desktop application for rapid analysis of PCAP files, Zeek logs, and network telemetry.
* **[RITA](https://github.com/activecm/rita)** - Beacon detection and network threat hunting platform for identifying command-and-control activity.
* **[Stenographer](https://github.com/google/stenographer)** - Scalable full-packet capture solution designed for continuous network traffic recording and analysis.

---
Packet capture solution designed to write large amounts of data to disk.

