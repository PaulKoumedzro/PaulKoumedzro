# Hello, I'm Paul Koumedzro
<a href="https://www.linkedin.com/in/paul-koumedzro/"><img src="https://img.shields.io/badge/-LinkedIn-0072b1?&style=for-the-badge&logo=linkedin&logoColor=white" /></a>    <a href="https://medium.com/@paulkoumedzro"><img src="https://img.shields.io/badge/-Medium-12100E?&style=for-the-badge&logo=medium&logoColor=white" /></a>
</br>


I'm a cybersecurity specialist focused on protecting digital environments through strategic defense and continuous learning. Rigorous academic training and practical experience have shaped my path, giving me a strong foundation in security principles, threat analysis, and incident response. I approach each challenge with analytical precision and a commitment to excellence, driven by a passion for staying ahead of the evolving cybersecurity landscape.


# Objective
With a passion for cybersecurity shaped by diverse education and hands-on experience, I aim to showcase practical projects that highlight my strong threat detection and response skills. My journey led me to transition into cybersecurity, specifically targeting a role in a Security Operations Domain.
# Project


| Lab                                        | Associated Project         |
|-----------------------------------------------|----------------------------|
| Malware Analysis with YARA        | <a href="https://tinyurl.com/YARA-for-Malware">YARA For Malware Analysis Lab</a>|
| SSH Brute-Force Investigation with Splunk          | <a href="https://tinyurl.com/splunk-investigations">SSH brute-force investigation Lab</a> 
| Phishing Email Analysis   | <a href="https://tinyurl.com/phishing-Email-analysis">Phishing Email Lab</a>|
| Malicious Document Analysis            | <a href="https://tinyurl.com/Malicious-Document-Analysis">Malicious Document Analysis Lab</a>|
| Data Exfiltration | <a href="https://tinyurl.com/Data-Exfiltration">Data Exfiltration Lab</a>|


# Network & Security: TCP/IP, Ports, and Protocols

A list of commonly used ports and protocols in networking by security  and network professionals to assist with configuration or investigation.

| Protocol | Port(s) | Transport | Purpose | Security note |
| --- | --- | --- | --- | --- |
| **Application layer** | | | | |
| **HTTP** | 80 | TCP | Web traffic | Plaintext; sniffable. Redirect to HTTPS |
| **HTTPS** | 443 | TCP (QUIC: UDP) | Web traffic over TLS | Encrypted; check certs and TLS version |
| **SSH / SFTP / SCP** | 22 | TCP | Encrypted remote shell and file transfer | Use keys, disable root and password login |
| **Telnet** | 23 | TCP | Legacy remote shell | Plaintext credentials; replace with SSH |
| **FTP** | 20, 21 | TCP | File transfer | Plaintext; use SFTP or FTPS instead |
| **SMTP / IMAP / POP3** | 25, 587 / 143, 993 / 110, 995 | TCP | Send and retrieve email | Prefer TLS ports; watch for open relays and spoofing |
| **DNS** | 53 | UDP (TCP for large) | Name to IP resolution | Cache poisoning, tunneling; use DNSSEC and filtering |
| **DHCP** | 67, 68 | UDP | Automatic IP assignment | Rogue DHCP servers; use DHCP snooping |
| **SNMP** | 161, 162 | UDP | Device monitoring and management | v1/v2c send community strings in clear; use v3 |
| **LDAP / LDAPS** | 389 / 636 | TCP | Directory services (e.g. Active Directory) | Enumeration and injection; require LDAPS or StartTLS |
| **SMB** | 445 | TCP | Windows file and printer sharing | Lateral movement, EternalBlue; never expose to internet |
| **RDP** | 3389 | TCP | Remote desktop | Brute force, ransomware entry; use VPN and MFA |
| **Transport layer** | | | | |
| **TCP** | n/a | n/a | Reliable, ordered; 3-way handshake (SYN, SYN-ACK, ACK) | SYN floods, session hijacking; scans use SYN/FIN flags |
| **UDP** | n/a | n/a | Connectionless, low overhead | Spoofable; reflection and amplification attacks |
| **Internet / network layer** | | | | |
| **IPv4 / IPv6** | n/a | n/a | Logical addressing and routing | Source spoofing, fragmentation tricks; ingress/egress filtering |
| **ICMP** | n/a | IP proto 1 | Ping, traceroute, error reporting | Recon and ping floods; limit but do not blindly block |
| **IPsec (IKE, ESP, AH)** | 500, 4500 | UDP / IP proto 50, 51 | VPN encryption and authentication | Weak pre-shared keys and old IKEv1 modes |
| **Link layer** | | | | |
| **Ethernet / Wi-Fi, ARP** | n/a | n/a | MAC addressing; ARP maps IP to MAC | ARP poisoning, MAC flooding; use port security and WPA3 |








# SKILLS

### 📊 SIEM
![Splunk](https://img.shields.io/badge/-Splunk-000000?style=for-the-badge&logo=splunk&logoColor=white)
![SPL](https://img.shields.io/badge/-SPL-65A637?style=for-the-badge)
![Dashboards](https://img.shields.io/badge/-Dashboards-0072b1?style=for-the-badge)
![Alerts](https://img.shields.io/badge/-Alerts-C0392B?style=for-the-badge)

### 🛡️ Security Operations
![Alert Triage](https://img.shields.io/badge/-Alert_Triage-1F618D?style=for-the-badge)
![Log Analysis](https://img.shields.io/badge/-Log_Analysis-1F618D?style=for-the-badge)
![Incident Investigation](https://img.shields.io/badge/-Incident_Investigation-1F618D?style=for-the-badge)
![Threat Hunting](https://img.shields.io/badge/-Threat_Hunting-1F618D?style=for-the-badge)

### 📐 Frameworks
![MITRE ATT&CK](https://img.shields.io/badge/-MITRE_ATT%26CK-B03A2E?style=for-the-badge)
![Cyber Kill Chain](https://img.shields.io/badge/-Cyber_Kill_Chain-B03A2E?style=for-the-badge)
![CIA Triad](https://img.shields.io/badge/-CIA_Triad-B03A2E?style=for-the-badge)
![NIST 800-53](https://img.shields.io/badge/-NIST_800--53-B03A2E?style=for-the-badge)

### 🌐 Network
![Wireshark](https://img.shields.io/badge/-Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
![Suricata](https://img.shields.io/badge/-Suricata-EF3B2D?style=for-the-badge)
![Zeek](https://img.shields.io/badge/-Zeek-2E4053?style=for-the-badge)
![TCP/IP](https://img.shields.io/badge/-TCP%2FIP-5D6D7E?style=for-the-badge)
![DNS](https://img.shields.io/badge/-DNS-5D6D7E?style=for-the-badge)
![DHCP](https://img.shields.io/badge/-DHCP-5D6D7E?style=for-the-badge)

### 🦠 Malware Analysis
![Static Analysis](https://img.shields.io/badge/-Static_Analysis-6C3483?style=for-the-badge)
![Dynamic Analysis](https://img.shields.io/badge/-Dynamic_Analysis-6C3483?style=for-the-badge)
![YARA](https://img.shields.io/badge/-YARA-6C3483?style=for-the-badge)
![REMnux](https://img.shields.io/badge/-REMnux-6C3483?style=for-the-badge)
![FlareVM](https://img.shields.io/badge/-FlareVM-6C3483?style=for-the-badge)

### 📧 Email Security
![Phishing Detection](https://img.shields.io/badge/-Phishing_Detection-D68910?style=for-the-badge)
![Header Analysis](https://img.shields.io/badge/-Header_Analysis-D68910?style=for-the-badge)
![URL De-obfuscation](https://img.shields.io/badge/-URL_De--obfuscation-D68910?style=for-the-badge)
![M365](https://img.shields.io/badge/-M365-D83B01?style=for-the-badge)

### 💻 Virtualization
![VMware](https://img.shields.io/badge/-VMware-607078?style=for-the-badge&logo=vmware&logoColor=white)
![VirtualBox](https://img.shields.io/badge/-VirtualBox-183A61?style=for-the-badge&logo=virtualbox&logoColor=white)
# Certifications

<div>
<img src="https://img.shields.io/badge/-Security%2B-FF0000?&style=for-the-badge&logo=CompTIA&logoColor=white" />
<img src="https://img.shields.io/badge/-PenTest%2B-DC143C?&style=for-the-badge&logo=CompTIA&logoColor=white" />
<img src="https://img.shields.io/badge/-Qualys%20VMDR-005C99?&style=for-the-badge&logo=qualys&logoColor=white" />
<img src="https://img.shields.io/badge/-AWS-FF9900?&style=for-the-badge&logo=amazonaws&logoColor=white" />
</div>

## Contact
<b>Email:</b> <div font-color="white">paulkoumedzro@gmail.com</div>  </br><b>Tel:</b> +1 (612) 434-7961

