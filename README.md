Clarke Confectionary – Blackbox Penetration Test

University Assignment – COMP3011 Ethical Hacking
Overview

This project documents a blackbox penetration test conducted against a fictional company, Clarke Confectionary, as part of a university-level ethical hacking module. The engagement involved reconnaissance, vulnerability analysis, exploitation, and post-exploitation activities within a controlled lab environment. The findings were compiled into a professional penetration testing report with mitigation recommendations.
Objectives

    Identify and exploit vulnerabilities in the target system

    Gain initial access and escalate privileges

    Extract credentials and sensitive data

    Provide remediation guidance for each security issue

Methodology

The assessment followed a typical blackbox penetration testing process:

    Reconnaissance – Network and service enumeration

    Scanning & Analysis – Vulnerability discovery

    Exploitation – Gaining initial access via known exploits

    Post-Exploitation – Privilege escalation, credential dumping, and lateral movement

    Reporting – Documenting findings and mitigation strategies

Tools & Techniques

    Nmap – Service discovery and OS fingerprinting

    OpenVAS – Vulnerability scanning and analysis

    Metasploit Framework – Exploitation and post-exploitation

    Impacket (e.g., secretsdump.py, psexec.py) – Remote credential extraction and lateral movement

    Hashcat & John the Ripper – NTLM hash cracking

    Windows Exploit Suggester – Privilege escalation enumeration

Key Findings

    SMBv1 EternalBlue Exploit (MS17-010) – Remote code execution vulnerability

    Anonymous FTP Login – Sensitive files accessible without authentication

    Credential Dumping – NTLM hashes extracted from SAM and LSA secrets

    Privilege Escalation – SYSTEM-level access achieved

    Weak Passwords – Several cracked via dictionary and rule-based attacks

    Insecure Configurations – Lack of network segmentation, exposed services

Deliverables

📄 Penetration Testing Report (PDF)
📁 Tools, scripts, and output samples used during the engagement
Disclaimer

This project was conducted in a virtual lab environment as part of a university module. It does not represent a real-world attack and was performed in accordance with ethical hacking principles.
