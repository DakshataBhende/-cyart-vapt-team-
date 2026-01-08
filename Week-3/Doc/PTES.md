# PTES Penetration Testing Report 

## 1. Executive Summary
This penetration testing engagement was conducted in a controlled laboratory environment to assess the security posture of intentionally vulnerable systems. The objective was to identify vulnerabilities, validate their exploitability, and assess potential impact using industry-standard tools and methodologies. The assessment followed the Penetration Testing Execution Standard (PTES) to ensure a structured and repeatable approach.

## 2. Assessment Approach
The engagement began with reconnaissance and service enumeration using Nmap to identify exposed services and potential attack vectors. Vulnerability assessment was performed using OpenVAS, which identified multiple high and critical severity issues. These findings were mapped to known weaknesses and prioritized based on risk and impact.

## 3. Findings and Exploitation
Successful exploitation was achieved using the Metasploit Framework, resulting in remote shell access to the target system. Web application testing conducted on DVWA revealed critical SQL Injection and reflected Cross-Site Scripting (XSS) vulnerabilities, indicating insufficient input validation and insecure application design. Post-exploitation activities confirmed the possibility of full system compromise.

## 4. Evidence and Reporting
Network traffic generated during exploitation was captured using Wireshark, and cryptographic hashing was applied to preserve evidence integrity.
