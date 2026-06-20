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

### Hidden SOC Tools

#### [IRIS](https://github.com/dfir-iris/iris-web)
**Alternative to:** TheHive, ServiceNow SecOps.  
**Features:** Incident handling, Case management, Evidence tracking, IOC management.

#### [SOCFortress](https://github.com/socfortress)
**Provides:** Complete SOC stack, Wazuh integrations, MISP integrations, DFIR workflows.  
**Recommended for:** Students, Home labs.

#### [Timesketch](https://github.com/google/timesketch)
Google's forensic timeline platform.  
**Features:** Timeline analysis, Threat hunting, DFIR investigations.

#### [Hayabusa](https://github.com/Yamato-Security/hayabusa)
**Purpose:** Windows event log hunting, Sigma detection. Extremely fast.

---

## THREAT INTELLIGENCE

### Hidden CTI Platforms

#### [Yeti](https://github.com/yeti-platform/yeti)
Threat intelligence platform.  
**Useful for:** IOC storage, Malware tracking, Actor tracking.

#### [IntelOwl](https://github.com/intelowlproject/IntelOwl)
IOC enrichment automation.  
**Supports:** VirusTotal, URLHaus, MalwareBazaar, Hybrid Analysis.

#### [ThreatBus](https://github.com/tenzir/threatbus)
Real-time intelligence sharing.  
**Connects:** MISP, Zeek, Suricata, OpenCTI.

#### [ATT&CK Navigator](https://github.com/mitre-attack/attack-navigator)
Visualization platform for the MITRE ATT&CK framework.

---

## DIGITAL FORENSICS

### Hidden DFIR Tools

#### [Velociraptor](https://github.com/Velocidex/velociraptor)
Arguably one of the strongest DFIR platforms today.  
**Features:** Memory collection, Artifact collection, Live response, Threat hunting.

#### [KAPE](https://github.com/EricZimmerman/KapeFiles)
Fast artifact acquisition and processing.

#### [Chainsaw](https://github.com/WithSecureLabs/chainsaw)
Windows forensic hunting using Sigma and EVTX logs.

#### [Plaso](https://github.com/log2timeline/plaso)
Engine for timeline generation (log2timeline).

#### [Autopsy](https://github.com/sleuthkit/autopsy)
GUI-based disk forensics and digital investigation platform.

---

## MOBILE SECURITY

### Core Mobile Stack

#### [MobSF](https://github.com/MobSF/Mobile-Security-Framework-MobSF)
**Supports:** Static analysis, Dynamic analysis, Malware analysis, APK review.

#### [Androguard](https://github.com/androguard/androguard)
APK reverse engineering and analysis.

#### [JADX](https://github.com/skylot/jadx)
Android decompiler to produce Java source code from Android Dex and APK files.

#### [Frida](https://github.com/frida/frida)
Dynamic instrumentation toolkit for developers, reverse-engineers, and security researchers.

#### [Objection](https://github.com/sensepost/objection)
Runtime mobile exploration powered by Frida.

### Android Forensics

#### [ALEAPP](https://github.com/abrignoni/ALEAPP)
Android artifact parser supporting databases, logs, and application artifacts.

#### [AndroidQF](https://github.com/ydkhatri/AndroidQF)
Android forensic parsing and acquisition.

#### [Andriller](https://github.com/den4uk/andriller)
Commercial-grade style Android data acquisition and decoding.

---

## ENDPOINT DETECTION & RESPONSE

### Hidden EDR Tools

#### [FleetDM](https://github.com/fleetdm/fleet)
Enterprise osquery management and orchestration.

#### [Osquery](https://github.com/osquery/osquery)
Exposes operating system metrics as relational database tables.

#### [LimaCharlie Agent](https://github.com/refractionPOINT)
Cloud-native EDR/Endpoint security platform.

#### [OpenEDR](https://github.com/ComodoSecurity/openedr)
Full-featured open-source EDR.

#### [HELK](https://github.com/Cyb3rWard0g/HELK)
The Hunting ELK.  
**Supports:** Sigma, Sysmon, ATT&CK.

---

## AI SECURITY

### Local LLM Security Projects

#### [Open WebUI](https://github.com/open-webui/open-webui)
User-friendly web interface for local LLMs.

#### [Ollama](https://github.com/ollama/ollama)
Get up and running with large language models locally.

#### [Open Interpreter](https://github.com/OpenInterpreter/open-interpreter)
A natural language interface for computers to run code.

#### [CrewAI](https://github.com/crewAIInc/crewAI)
Framework for orchestrating role-playing, autonomous AI agents.

#### [LangGraph](https://github.com/langchain-ai/langgraph)
Agent orchestration for building complex stateful AI applications.

### AI + SOC
**Architecture:** Wazuh + OpenCTI + TheHive + Ollama + Llama 3 + CrewAI.

---

## NETWORK SECURITY

### Hidden Network Tools

#### [Arkime](https://github.com/arkime/arkime)
Open-source, indexed packet capture and search platform.

#### [Malcolm](https://github.com/idaholab/Malcolm)
**Combines:** Zeek, Suricata, Arkime.

#### [Brim](https://github.com/brimdata/brim)
Desktop app to efficiently search and analyze PCAP files and Zeek logs.

#### [RITA](https://github.com/activecm/rita)
Real Intelligence Threat Analytics for beacon detection.

#### [Stenographer](https://github.com/google/stenographer)
Packet capture solution designed to write large amounts of data to disk.

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
