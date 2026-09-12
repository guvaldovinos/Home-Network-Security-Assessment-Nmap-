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
<img width="1999" height="494" alt="ipconfig_" src="https://github.com/user-attachments/assets/ad42036b-6532-4c02-863b-acc0887ddf1e" />
Caption: Here we ran "nmap --version" on PowerShell to confirmed what version we of Nmap we have installed in our device. 
<img width="1386" height="1039" alt="network_scan" src="https://github.com/user-attachments/assets/97fbd41c-7c26-4280-a82f-f018d6b33aa4" />

<img width="2063" height="580" alt="Screenshot 2026-09-11 175227" src="https://github.com/user-attachments/assets/d77cfb66-5951-4bc1-9edb-70c4bdaa92d3" />

<img width="967" height="178" alt="Screenshot 2026-09-12 151530" src="https://github.com/user-attachments/assets/5acf1ca8-8d80-4fce-8695-5d64a90bc7c5" />

<img width="2031" height="890" alt="Screenshot 2026-09-11 175710" src="https://github.com/user-attachments/assets/f5135078-7a66-4e45-9cbc-692c384dfe8e" />

<img width="1909" height="534" alt="Screenshot 2026-09-11 181812" src="https://github.com/user-attachments/assets/a1ca2f72-e99d-4d9f-afad-3ec8e3c4147c" />
<img width="459" height="157" alt="Screenshot 2026-09-12 152853" src="https://github.com/user-attachments/assets/3c503fa4-08d0-4f61-a885-8b85ad944a75" />

<img width="2360" height="920" alt="Screenshot 2026-09-11 183412" src="https://github.com/user-attachments/assets/75bbab9a-fe3c-4dd9-87d2-0eeb3c3a7c30" />

<img width="928" height="414" alt="Screenshot 2026-09-11 192443" src="https://github.com/user-attachments/assets/cce117a5-7efe-4ee4-a0f8-b47cdeac5de5" />


<img width="1362" height="434" alt="Screenshot 2026-09-11 192619" src="https://github.com/user-attachments/assets/59be4dfb-8759-4ee9-9dd6-2d03e118327f" />

<img width="836" height="261" alt="Screenshot 2026-09-11 200145" src="https://github.com/user-attachments/assets/8794d9e3-ca94-4295-a08b-4aa0f0522704" />
udp scan
<img width="937" height="459" alt="Screenshot 2026-09-11 200542" src="https://github.com/user-attachments/assets/44fd521e-3162-43a6-acbc-9933a8828ae2" />

<img width="1149" height="1092" alt="Screenshot 2026-09-11 212517" src="https://github.com/user-attachments/assets/f9a39a6b-b422-42e8-bcb4-5f9e0a4aa0b9" />










