# 🔍 Home-Network-Security-Assessment-Nmap
Nmap-based vulnerability assessment of a home network gateway, including manual verification and remediation recommendations. 
---

## 🧠 Description
This lab demonstrates a reconnaissance and vulnerability assessment performed against my own home network router using Nmap.
This task simulates a common SOC Analyst responsibility — scanning a network target, interpreting scan results, and validating automated findings before reporting them as real vulnerabilities.

---

## 🖥️ Environment
- **Tools:** Windows PowerShell, Nmap 
- **Target:** Home router (10.0.0.1) - own device, authorized for testing
- **Network Mode:** Local LAN scan 

---

## ⚙️ Steps Completed
1. Ran a TCP scan with the `--reason` flag to identify open/closed ports and the exact response behind each classification.
2. Ran a UDP scan to identify open, filtered, and closed UDP services.
3. Ran a vulnerability scan using `--script vuln` against discovered open ports.
4. Validated flagged findings using a version scan (`nmap -sV`), MAC address vendor lookup, and manual review of HTTP/HTTPS response headers.
5. Documented findings and remediation recommendations in a structured report.

---

## 🧩 Key Skills Demonstrated
- Running and interpreting Nmap TCP/UDP scans
- Understanding scan reason codes (SYN-ACK, RST, ICMP unreachable, no-response)
- Distinguishing confirmed findings from false positives using multi-source validation
-  Documenting technical findings and remediation in a clear, structured report

---
## 📸 Screenshots
<img width="1999" height="177" alt="nmap_confirmed" src="https://github.com/user-attachments/assets/516ce169-b3ea-4937-8165-971282ccbf29" />
Caption: Here we ran "nmap --version" on PowerShell to confirmed what version we of Nmap we have installed in our device. 
