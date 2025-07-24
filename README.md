# SME Network Penetration Test – Ethical Hacking Project

This repository documents a black-box penetration test on a simulated Small and Medium Enterprise (SME) network. The goal of this project was to identify vulnerabilities, exploit misconfigurations, and recommend remediation strategies using ethical hacking techniques.

> ⚠️ **Disclaimer:** This project was conducted entirely in a **controlled lab environment** using virtual machines (Kali Linux & Metasploitable 2). No real-world systems were targeted or harmed. This is strictly for educational purposes.



🧪 Project Overview

- **Target Machine:** Metasploitable 2 (192.168.1.5)
- **Attack Machine:** Kali Linux 2025.4
- **Testing Type:** Black-box penetration testing
- **Testing Date:** July 23, 2025
- **Student:** Rohan Pise



🔧 Tools Used

- Nmap 7.93 – for network scanning and enumeration
- Metasploit Framework – for vulnerability exploitation
- Nikto – for web server scanning
- Custom Bash commands for post-exploitation
- smbclient, netcat, whois, and more...



📄 What’s Inside

| File/Folder         | Description                                       |
|---------------------|---------------------------------------------------|
| `report/`           | Full PDF report with findings and screenshots     |
| `screenshots/`      | Evidence of scans, exploits, and post-exploitation|
| `tools-used.md`     | Versions of tools used in this project            |
| `commands-used.txt` | Useful commands and payloads used                 |
| `notes/`            | References and personal notes                     |



🧠 Key Learning

This project helped me:
- Understand the end-to-end process of penetration testing
- Practice real exploitation using Metasploit modules
- Identify risks in outdated or misconfigured services
- Learn how to document and report vulnerabilities professionally



✅ Sample Vulnerabilities Identified

- `vsftpd 2.3.4` backdoor – CVSS 10.0
- Samba usermap script – Remote Code Execution
- SSH default credentials – Privilege Escalation
- Apache outdated version – Info disclosure



📚 References

- [Offensive Security](https://www.offensive-security.com/metasploit-unleashed/)
- [OWASP Testing Guide](https://owasp.org/www-project-web-security-testing-guide/)
- [Nmap Documentation](https://nmap.org/book/)
- CVE Database: [https://cve.mitre.org](https://cve.mitre.org)



🔒 Ethics Reminder

Do **not** attempt penetration testing on live or unauthorized systems. Always get written permission. Follow ethical hacking guidelines and laws in your country.


