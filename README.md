<div align="center">

# Cybersecurity | SOC & Blue Team | Infrastructure Security

**Cybersecurity learner focused on Security Operations, threat detection, digital forensics, incident response, and secure IT infrastructure.**

`Windows & Active Directory` · `Linux` · `Networking` · `SIEM` · `DFIR` · `Python` · `Cloud Security`

</div>

---

## About Me

I'm building a hands-on cybersecurity portfolio based on a multidisciplinary training program spanning **10 technical modules**: computer networks, Windows and Linux security, network defense, security monitoring, scripting, ethical hacking, digital forensics, IoT/container security, and AWS cloud security.

My primary career objective is to develop as a **Junior SOC Analyst / Security Analyst (Blue Team)**, with strong foundations in infrastructure, networking, threat investigation, and security automation. I also explore vulnerability assessment and offensive security to better understand attack techniques and defensive controls.

> **Portfolio transparency:** This profile summarizes topics covered and practical assignments included in my training. Not every tool listed represents production experience, and course assignments are not equivalent to independently verified professional engagements. The DFIR investigation described below is supported by project documentation. Individual labs will be linked as their own evidence, configurations, screenshots, and write-ups are published.

## Core Skills

| Area | Technologies / Practical Focus |
| --- | --- |
| **SOC & security monitoring** | Splunk SIEM, SPL searches, log parsing, dashboards, Snort, Suricata, alerts, detection fundamentals |
| **Digital forensics & incident response** | Wireshark, Zeek, PCAP investigation, Windows artifacts, Sysinternals, file hashes, timeline reconstruction, evidence handling |
| **Windows security** | Windows Server, Active Directory, Group Policy, DNS, DHCP, RDP, PowerShell, BitLocker, AppLocker, Windows Firewall, auditing |
| **Linux security** | Debian, Bash, SSH, file permissions, sudo, PAM, GRUB, iptables, systemd, Apache, ModSecurity, OpenSSL |
| **Networking & network security** | TCP/IP, OSI, Cisco IOS, VLANs, OSPF, RIP, ACLs, AAA, RADIUS, TACACS+, 802.1X, pfSense, VPN |
| **Programming & automation** | Python, PowerShell, Bash; file processing, exception handling, TCP sockets, log parsing, ARP monitoring |
| **Endpoint & threat detection** | YARA, ClamAV, VirusTotal, honeypots (Dionaea, MHN, Valhalla), DLP fundamentals |
| **Vulnerability assessment** | Nmap, Masscan, Metasploit, Burp Suite, web security concepts (XSS, LFI, SQL injection) in authorized labs |
| **Cloud & containers** | AWS EC2, IAM, VPC, Security Groups, Inspector, Organizations, WAF, Docker, Docker Compose |
| **IoT & wireless fundamentals** | MQTT, RFID/NFC, SDR, GNU Radio, GQRX, HackRF, IoT attack-surface analysis |

## Training Modules

These are the **10 modules** covered in my learning pathway. Each module combines theory with technical exercises, demonstrations, or projects as documented in the training materials.

<details>
<summary><strong>01 — Computer Networking</strong></summary>

**Focus:** Network fundamentals, switching, routing, configuration, and troubleshooting.

- **Topics:** OSI/TCP-IP, Ethernet, IPv4/IPv6, subnetting, CIDR/VLSM, static routing, RIPv2, OSPFv2, VLANs, 802.1Q trunking, SSH, port security, ACL, NTP, Syslog; DHCP/NAT theory.
- **Tools:** Cisco Packet Tracer, Cisco IOS CLI, Wireshark, Windows network utilities.
- **Lab scope:** 17 exercises including device configuration, routing, VLANs, secure access, traffic analysis, and ACLs.
- **Portfolio themes:** Cisco LAN topology, segmented networks, routing verification, network troubleshooting.

</details>

<details>
<summary><strong>02 — Network Security</strong></summary>

**Focus:** Defense of enterprise networks and investigation of suspicious traffic.

- **Topics:** DMZ, network segmentation, AAA, RADIUS, TACACS+, 802.1X, ARP spoofing, DHCP snooping, switch hardening, firewalls/NAT, IPsec/OpenVPN, IDS/IPS, SNMP.
- **Tools:** Wireshark, pfSense, Cisco Packet Tracer, Suricata, Nagios, NetworkMiner.
- **Lab scope:** 25 exercises covering traffic investigation, network access control, firewall configuration, VPNs, monitoring, and intrusion detection.
- **Portfolio themes:** Packet analysis, switch hardening, pfSense rules, VPN, Suricata monitoring.

</details>

<details>
<summary><strong>03 — Microsoft Security</strong></summary>

**Focus:** Windows administration, domain infrastructure, and system hardening.

- **Topics:** Windows clients and servers, AD DS, domain controllers, organizational units, users/groups, GPO, DNS, DHCP, SMB/NTFS shares, DFS, RDP, PowerShell, BitLocker, AppLocker, auditing.
- **Tools:** Windows Server, Active Directory Users and Computers, Server Manager, Group Policy Management, PowerShell, VirtualBox.
- **Lab scope:** Windows/AD infrastructure and security configuration across 10 topic areas; detailed lab documentation is maintained separately.
- **Portfolio themes:** `cyber.local` training domain, AD identity management, GPO, endpoint controls, security policy auditing.

</details>

<details>
<summary><strong>04 — Linux Security</strong></summary>

**Focus:** Linux administration, service protection, and Bash automation.

- **Topics:** Debian installation, CLI, filesystem, accounts/groups, permissions, SUID/SGID, SSH, FTP/Samba, Apache, Bash, Cron, backups, integrity monitoring, GRUB, PAM, firewall rules, HTTPS.
- **Tools:** Debian, Bash, systemd, OpenSSH, iptables, ModSecurity, OpenSSL.
- **Lab scope:** 29 numbered exercises plus an additional Cron-security exercise.
- **Portfolio themes:** Linux service hardening, Bash backup and monitoring scripts, secure web-server configuration.

</details>

<details>
<summary><strong>05 — Cybersecurity Infrastructure & Technology</strong></summary>

**Focus:** Security operations technology and centralized threat monitoring.

- **Topics:** Endpoint detection, signatures and YARA, honeypots, DLP/regex, email security, SIEM, Splunk SPL, dashboards, SOAR concepts, IoT/ICS threats, secure architecture.
- **Tools:** Splunk, Snort, YARA, ClamAV, VirusTotal, Dionaea, MHN, Valhalla, OpenDLP, Demisto (historical training platform), Shodan.
- **Lab scope:** 34 exercises covering signatures, sensors, data exposure, event searches, dashboards, and security research.
- **Portfolio themes:** Splunk log analysis, YARA detection rules, honeypot monitoring, SOC dashboards.

</details>

<details>
<summary><strong>06 — Python Security</strong></summary>

**Focus:** Scripting fundamentals and security-oriented automation.

- **Topics:** Data structures, control flow, functions, recursion, OOP, file handling, error handling, filesystem automation, TCP client/server sockets.
- **Tools:** Python 3, PyCharm, standard-library `os`, `sys`, `socket`.
- **Lab scope:** 35 learning exercises and a final ARP Spoof Detector assignment.
- **Portfolio themes:** IP-to-binary converter, service/port dictionary, TCP client-server application, ARP-table monitoring and event logging.

</details>

<details>
<summary><strong>07 — Ethical Hacking</strong></summary>

**Focus:** Authorized security assessment and understanding attacker techniques.

- **Topics:** Reconnaissance, port scanning, on-path attacks, password security, social engineering, infrastructure vulnerabilities, Windows/Linux privilege escalation, HTTP, XSS, file inclusion, SQL injection, penetration-test reporting.
- **Tools:** Kali Linux, Nmap, Masscan, Zenmap, Bettercap, Wireshark, Metasploit, SearchSploit, BloodHound, Burp Suite, bWAPP.
- **Training scope:** 12 chapters, with 21 lab references identified in the textbook; a separate complete lab-solutions file was not provided.
- **Portfolio themes:** Authorized reconnaissance, vulnerability assessment, web-app security testing, professional reporting.

</details>

<details>
<summary><strong>08 — Digital Forensics & Incident Response (DFIR)</strong></summary>

**Focus:** Investigation of incidents and analysis of digital evidence.

- **Topics:** Incident-response lifecycle, acquisition, chain of custody, live/dead forensics, Windows/Linux artifacts, memory analysis, malware analysis, threat hunting, network forensics, persistence and timelines.
- **Tools:** Wireshark, Zeek, FTK Imager, Autopsy, Volatility, Rekall, Sysinternals, HxD, VirusTotal, SIFT, REMnux.
- **Documented project:** A 19-step investigation recorded in a 10-page report, combining PCAP analysis, Zeek file logs, suspicious file/hash inspection, Windows startup artifacts, UPX indicators, account artifacts, and binary-file examination.
- **Portfolio themes:** Evidence-based network investigation, Windows artifact triage, file analysis, investigative reporting.

</details>

<details>
<summary><strong>09 — Internet of Things, RF & Container Security</strong></summary>

**Focus:** Embedded/wireless technologies together with cloud and container fundamentals.

- **Topics:** IoT layers and attack surface, MQTT pub/sub, RFID/NFC, infrared, replay risk, SDR, AWS introduction, cloud security, Docker security, CI/CD concepts, Redis/MongoDB and NoSQL injection.
- **Tools covered:** Mosquitto, HackRF, RTL-SDR, GQRX, GNU Radio, RTL_433, AWS, Docker, Docker Compose, Git, Jenkins.
- **Training scope:** 174-page course presentation with demonstrations; no separate numbered lab-assignment file.
- **Portfolio themes:** IoT protocol risk analysis, SDR signal analysis, MQTT architecture, container hardening.

</details>

<details>
<summary><strong>10 — Cloud Security</strong></summary>

**Focus:** AWS administration and security controls.

- **Topics:** Cloud models, shared responsibility, IAM, EC2, security groups, virtual appliances, SDN/SDP, CASB, vulnerability assessment, AWS Organizations, S3/CloudFront fundamentals and WAF.
- **Tools:** AWS EC2, IAM, Inspector, Organizations, WAF, Security Groups, VirtualBox, Sysprep, BGInfo, OVA/OVF.
- **Lab scope:** 8 exercises, including instance setup, billing alerts, IAM, virtual-appliance export/import, network access rules, Inspector, Organizations, and WAF.
- **Portfolio themes:** Cloud IAM, EC2 network access, AWS vulnerability findings, web application protection.

</details>

## Portfolio Projects & Lab Write-ups

| Project / Lab collection | Practical scope | Documentation |
| --- | --- | --- |
| **DFIR Investigation** | PCAP analysis with Wireshark/Zeek, network artifact identification, Windows startup and file investigation, reporting | **Documented project** — link to published repository/report when available |
| **Microsoft Security Lab Environment** | Training domain `cyber.local`, Windows Server, AD DS, DNS/DHCP, GPO, PowerShell, endpoint security | **Lab documentation repository** — add GitHub URL |
| **Python ARP Spoof Detector** | ARP table extraction, IP/MAC change checks, event logging, test scenario | **Course final project assignment** — add implementation URL/evidence |
| **Splunk / SIEM Labs** | Event searches, log parsing, SPL, dashboards, Snort data and SOAR integration concepts | **Training labs** — add published write-ups |
| **Cisco & Network Security Labs** | VLANs, routing, AAA, 802.1X, ACLs, pfSense and IDS/IPS | **Training labs** — add published configurations |
| **AWS Cloud Security Labs** | EC2, IAM, Security Groups, Inspector, Organizations and WAF | **Training labs** — add published write-ups |
| **Linux Security & Automation Labs** | SSH and web-server hardening, Bash backup, file-integrity monitoring, PAM, firewall | **Training labs** — add published scripts and evidence |

**Publishing principle:** Each lab repository should include its goal, architecture, tools, configuration, test procedure, actual results, screenshots with sensitive information redacted, lessons learned, and a remediation/security section.

## Tools & Technologies

<!-- The following are technologies covered in coursework; not a claim of professional proficiency with every product. -->

**Network analysis & monitoring**

![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![Zeek](https://img.shields.io/badge/Zeek-304A66?style=flat-square)
![Suricata](https://img.shields.io/badge/Suricata-EF3B2D?style=flat-square)
![Snort](https://img.shields.io/badge/Snort-E5422B?style=flat-square)
![pfSense](https://img.shields.io/badge/pfSense-1D5A97?style=flat-square)
![Cisco](https://img.shields.io/badge/Cisco_IOS-1BA0D7?style=flat-square&logo=cisco&logoColor=white)

**SIEM, detection & investigation**

![Splunk](https://img.shields.io/badge/Splunk-111111?style=flat-square&logo=splunk&logoColor=white)
![YARA](https://img.shields.io/badge/YARA-6750A4?style=flat-square)
![ClamAV](https://img.shields.io/badge/ClamAV-CC0000?style=flat-square)
![VirusTotal](https://img.shields.io/badge/VirusTotal-394EFF?style=flat-square)
![Volatility](https://img.shields.io/badge/Volatility-506070?style=flat-square)
![Autopsy](https://img.shields.io/badge/Autopsy-505F72?style=flat-square)

**Systems & scripting**

![Windows Server](https://img.shields.io/badge/Windows_Server-0078D4?style=flat-square&logo=windows&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**Cloud & infrastructure**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![VirtualBox](https://img.shields.io/badge/VirtualBox-183A61?style=flat-square&logo=virtualbox&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

## Career Focus

I am primarily interested in **SOC Analyst (L1), Junior Security Analyst, and Blue Team** opportunities where I can apply network traffic analysis, security event investigation, Windows/Linux administration, scripting, and incident-response fundamentals.

I am continuing to develop practical evidence through reproducible labs, security documentation, and small tools. Additional interests include **DFIR, threat hunting, vulnerability assessment, and cloud security**.

## Certifications & Learning

My current portfolio documents **coursework, laboratories, and projects**. Certifications will be listed here only after they have been earned and verified.

## Contact

- **LinkedIn:** Add my real LinkedIn profile URL here.
- **GitHub projects:** Browse the repositories on this profile.
- **Contact:** Add a professional email address if desired.

---

<div align="center">

*Built around hands-on learning, reproducible labs, clear technical documentation, and responsible security research.*

</div>
