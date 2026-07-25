# Clarke Confectionary – Black-Box Penetration Test

Full black-box penetration test of a simulated Windows enterprise network, including exploitation of EternalBlue (MS17-010), post-exploitation, credential dumping and professional reporting.

**Full Project Report (PDF):** [Add link to your PDF here]

## Overview

This project documents a black-box penetration test conducted against a fictional organisation (Clarke Confectionary) as part of a university ethical hacking module. The engagement covered reconnaissance, vulnerability assessment, exploitation, post-exploitation and professional reporting with remediation recommendations.

## Key Achievements

- Conducted a full black-box assessment of a simulated Windows enterprise network
- Identified and exploited EternalBlue (MS17-010 / CVE-2017-0143) to gain remote code execution
- Achieved SYSTEM-level privilege escalation
- Extracted NTLM hashes and LSA secrets, then cracked 6 of 7 passwords using Hashcat and John the Ripper
- Demonstrated lateral movement and unauthorised access (including anonymous FTP)
- Delivered a professional penetration testing report with risk ratings and remediation recommendations

## Methodology

1. **Reconnaissance** – Network and service enumeration
2. **Vulnerability Analysis** – Scanning and identification of critical weaknesses
3. **Exploitation** – Gaining initial access via EternalBlue
4. **Post-Exploitation** – Privilege escalation, credential dumping and lateral movement
5. **Reporting** – Professional documentation of findings and remediation advice

## Tools Used

| Stage                 | Tools                                      |
|-----------------------|--------------------------------------------|
| Reconnaissance        | Nmap                                       |
| Vulnerability Scanning| OpenVAS                                    |
| Exploitation          | Metasploit                                 |
| Post-Exploitation     | Impacket, Mimikatz/Kiwi, Hashcat, John the Ripper |
| Privilege Escalation  | Windows Exploit Suggester                  |

## Key Findings

- Critical SMBv1 / EternalBlue vulnerability allowing remote code execution
- Successful SYSTEM privilege escalation
- Credential dumping from SAM and LSA secrets
- Weak passwords cracked via dictionary and rule-based attacks
- Anonymous FTP access exposing sensitive files
- Lack of network segmentation and insecure service configurations

## Notes

This assessment was conducted in a controlled virtual lab environment as part of a university module. It does not represent a real-world attack and was performed in accordance with ethical hacking principles.
