Black Box Network Penetration Testing: Methodology and Findings

Project Overview:
This project involved a Black Box penetration test on multiple external IP addresses to assess the network security posture without any prior internal knowledge. The objective was to simulate a real-world attacker’s perspective and uncover exploitable vulnerabilities using both manual and automated techniques.

Duration:
January 2025 to February 2025

Tools Used:
Nmap, Metasploit, RouterSploit, Wireshark, Hydra, SNMP-check

Key Objectives:
Identify as many vulnerabilities as possible through external Black Box testing  
Evaluate risks using CVSS scores and map findings to CWE, CVE, and OWASP  
Document Proof of Concepts (PoCs) and provide mitigation strategies  
Deliver a structured and technical report to guide future remediation efforts

Results:
Multiple vulnerabilities discovered across various severity levels  
Critical: BlueKeep, Samba RCE, SNMPv1, OpenSSH vulnerabilities  
High: Admin login exposure, VSFTPD DoS, Anonymous File Upload  
Medium: MySQL privilege escalation, OpenSSH command injection, SMTP flaw  
Low: Anonymous FTP access  

Conclusion:
This assessment revealed serious risks caused by outdated software, service misconfigurations, and insecure protocols. Each vulnerability was validated with a proof of concept and mapped to industry standards. The project provided valuable hands-on experience in real-world network penetration testing and demonstrated the importance of secure configurations and regular updates.
