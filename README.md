# Hello, I'm Paul Koumedzro
<a href="https://www.linkedin.com/in/paul-koumedzro/"><img src="https://img.shields.io/badge/-LinkedIn-0072b1?&style=for-the-badge&logo=linkedin&logoColor=white" /></a>    <a href="https://medium.com/@paulkoumedzro"><img src="https://img.shields.io/badge/-Medium-12100E?&style=for-the-badge&logo=medium&logoColor=white" /></a>
</br>


I'm a cybersecurity specialist focused on protecting digital environments through strategic defense and continuous learning. Rigorous academic training and practical experience have shaped my path, giving me a strong foundation in security principles, threat analysis, and incident response. I approach each challenge with analytical precision and a commitment to excellence, driven by a passion for staying ahead of the evolving cybersecurity landscape.


# Objective
With a passion for cybersecurity developed through diverse educational paths and hands-on experience, I aim to showcase practical projects that highlight my strong skills in threat detection and response. My journey led me to transition into cybersecurity, specifically targeting a role in a Security Operations Domain.
# Project


| Lab                                        | Associated Project         |
|-----------------------------------------------|----------------------------|
| Malware Analysis with YARA        | <a href="https://tinyurl.com/YARA-for-Malware">YARA For Malware Analysis Lab</a>|
| SSH Brute-Force Investigation with Splunk          | <a href="https://tinyurl.com/splunk-investigations">SSH brute-force investigation Lab</a> 
| Phishing Email Analysis   | <a href="https://tinyurl.com/phishing-Email-analysis">Phishing Email Lab</a>|
| Malicious Document Analysis            | <a href="https://tinyurl.com/Malicious-Document-Analysis">Malicious Document Analysis Lab</a>|
| Data Exfiltration | <a href="https://tinyurl.com/Data-Exfiltration">Data Exfiltration Lab</a>|


# Network & Security: TCP/IP, Ports, and Protocols

*Port ranges: 0–1023 well-known (system) · 1024–49151 registered · 49152–65535 dynamic/ephemeral. Rule of thumb: close or filter anything you don't need, and prefer encrypted protocols.*

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






# Tools

### Network
<div>
    <img src="https://img.shields.io/badge/-Wireshark-1679A7?&style=for-the-badge&logo=Wireshark&logoColor=white" />
    <img src="https://img.shields.io/badge/-Suricata-EF3B2D?&style=for-the-badge&logo=Suricata&logoColor=white" />
    <img src="https://img.shields.io/badge/-Zeek-777BB4?&style=for-the-badge&logo=Zeek&logoColor=white" />
</div>

### Endpoint
<div>
    <img src="https://img.shields.io/badge/-Microsoft_Defender_for_Endpoint-00A4EF?&style=for-the-badge&logo=Microsoft&logoColor=white" />
</div>

### SIEM
<div>
    <img src="https://img.shields.io/badge/-Splunk-000000?&style=for-the-badge&logo=Splunk&logoColor=white" />
</div>

## Certifications

<div>
<img src="https://img.shields.io/badge/-Security%2B-FF0000?&style=for-the-badge&logo=CompTIA&logoColor=white" />
<img src="https://img.shields.io/badge/-PenTest%2B-DC143C?&style=for-the-badge&logo=CompTIA&logoColor=white" />
<img src="https://img.shields.io/badge/-Qualys%20VMDR-005C99?&style=for-the-badge&logo=qualys&logoColor=white" />
<img src="https://img.shields.io/badge/-AWS-FF9900?&style=for-the-badge&logo=amazonaws&logoColor=white" />
</div>

## Projects
- Malware Analysis with YARA 
- SSH Brute-Force Investigation with Splunk
- Phishing Email Analysis
- Malicious Document Analysis
- Data Exfiltration

