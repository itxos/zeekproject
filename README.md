# zeekproject
Zeek Project
# OskiStealer Malware Incident Analysis Project

## PROJECT OBJECTIVE
The primary objective of this project was to develop and demonstrate proficiency in using Zeek (formerly known as Bro) for post-incident analysis of network traffic captures (PCAP files). The project focused on analyzing a security incident involving OskiStealer malware infection, utilizing Zeek's powerful network analysis capabilities to extract key forensic artifacts and indicators of compromise.

## TOOLS
- **Zeek (Version 7.0)**: Network Security Monitor
 - Used for analyzing PCAP files
 - Custom scripts developed for:
   - Victim identification
   - IOC detection
   - File download analysis
   - Network connection monitoring
   - HTTP traffic analysis
 
## SKILLS GAINED
1. **Zeek Script Development**
  - Creating custom detection modules
  - Pattern matching and event handling
  - File analysis and hash extraction
  - Protocol-specific analysis (HTTP, DNS, DHCP)

2. **Network Forensics**
  - PCAP analysis
  - Network traffic pattern recognition
  - Malware behavior analysis
  - IOC identification and extraction

3. **Incident Response**
  - Timeline reconstruction
  - Artifact collection
  - IOC documentation
  - Technical report writing

## OUTCOMES

### Incident Analysis Summary
- **Date**: 2022-01-07
- **Time**: 16:07 UTC
- **Incident**: OskiStealer malware infection
- **Affected User**: Steve Smith

### Victim Details
```yaml
MAC Address: 95:5c:8e:32:58:f9
IP Address: 192.168.1.216
Hostname: DESKTOP-GXMYNO2
User Account: steve.smith

```sh 
├── scripts/
│   ├── victim-details.zeek
│   ├── file-ioc.zeek
│   ├── manufacturing-detect.zeek
│   └── beacon-detect.zeek
├── docs/
│   └── incident-report.md
├── samples/
│   └── redacted-traffic.pcap
└── README.md

