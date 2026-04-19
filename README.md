# Blue Team Security Lab: Setup, Attack Simulation, and Detection

This project documents the end-to-end implementation of a localized Blue Team security laboratory. It covers environment virtualization, SIEM (Splunk) optimization, attack execution, and forensic analysis.

##  Tools & Technologies
- SIEM: Splunk Enterprise on Ubuntu CLI.
- Virtualization: VMware Workstation.
- Attacking Suite: Kali Linux (Metasploit Framework).
- Target OS: Windows 10 LTSC (instrumented with Sysmon & Splunk UF).
- Analysis: XML parsing using _spath, MITRE ATT&CK & D3FEND mapping.

##  Key Features
- Engineering Optimizations: Implemented Tiered Storage and customized XML log parsing for high-performance indexing.
- Attack Simulation: Executed persistence mechanisms (Registry Run Keys, Scheduled Tasks) and Reverse Shells.
- Detection Engineering: Developed search queries to identify Malicious PowerShell execution and C2 communication.

##  Project Documentation
You can find the full technical report with screenshots and detailed analysis here: [View Technical Report](./Haneen_Mallah_Technical_Report.pdf?raw=true)
