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
- Ran OS detection against the target host, confirming a Linux-based OS consistent with a Fiberhome router/modem, then verified with a follow-up port/service scan to confirm no discrepancies.
- Ran a TCP SYN scan (`-sS`) — a fast, stealthy scan technique commonly used in security assessments — and saved output for review (`-oN`).
-  Ran a UDP scan (`-sU`) to identify open, filtered, and closed UDP services.
- an a TCP scan with the `--reason` flag to determine the exact network response behind each port's classification.
- Ran a vulnerability scan using `--script vuln` against discovered open ports.
- Documented findings and remediation recommendations in a structured report.

---

## 🧩 Key Skills Demonstrated
* Performing OS detection, TCP SYN scanning, UDP scanning, and vulnerability scanning with Nmap
* Understanding scan reason codes (SYN-ACK, RST, ICMP unreachable, no-response)
* Distinguishing confirmed findings from false positives using multi-source validation (version scan, vendor lookup, manual review)
* Documenting technical findings and remediation steps

 

---
## 📸 Screenshots
<img width="1999" height="494" alt="ipconfig_" src="https://github.com/user-attachments/assets/ad42036b-6532-4c02-863b-acc0887ddf1e" />
Caption: Ran "nmap --version" on PowerShell to confirmed what version we of Nmap we have installed in our device. 
<img width="1386" height="1039" alt="network_scan" src="https://github.com/user-attachments/assets/97fbd41c-7c26-4280-a82f-f018d6b33aa4" />
Caption: Performed a ping scan to find live hosts on my network

<img width="2063" height="580" alt="Screenshot 2026-09-11 175227" src="https://github.com/user-attachments/assets/d77cfb66-5951-4bc1-9edb-70c4bdaa92d3" />
Caption: Performed a Service/version detection scan 

<img width="2031" height="890" alt="Screenshot 2026-09-11 175710" src="https://github.com/user-attachments/assets/f5135078-7a66-4e45-9cbc-692c384dfe8e" />
Caption: Saved results on a file for reporting

<img width="967" height="178" alt="Screenshot 2026-09-12 151530" src="https://github.com/user-attachments/assets/5acf1ca8-8d80-4fce-8695-5d64a90bc7c5" />
Caption: Documented findings in an Excel sheet

<img width="1909" height="534" alt="Screenshot 2026-09-11 181812" src="https://github.com/user-attachments/assets/a1ca2f72-e99d-4d9f-afad-3ec8e3c4147c" /><img width="459" height="157" alt="Screenshot 2026-09-12 152853" src="https://github.com/user-attachments/assets/3c503fa4-08d0-4f61-a885-8b85ad944a75" />
Caption: Ran a OS detection scan & documented key information of the OS detection scan

<img width="2360" height="920" alt="Screenshot 2026-09-11 183412" src="https://github.com/user-attachments/assets/75bbab9a-fe3c-4dd9-87d2-0eeb3c3a7c30" />
Caption: Ran a quick port and service scan on host
<img width="928" height="414" alt="Screenshot 2026-09-11 192443" src="https://github.com/user-attachments/assets/cce117a5-7efe-4ee4-a0f8-b47cdeac5de5" /><img width="550" height="218" alt="Screenshot 2026-09-13 210953" src="https://github.com/user-attachments/assets/9fdc2ba1-5467-4965-a934-34348f9922e5" />

Caption: Ran a TCP SYN Scan on target Ip & documented findings in Excel sheet


<img width="836" height="261" alt="Screenshot 2026-09-11 200145" src="https://github.com/user-attachments/assets/8794d9e3-ca94-4295-a08b-4aa0f0522704" /><img width="554" height="59" alt="Screenshot 2026-09-13 210638" src="https://github.com/user-attachments/assets/18b942e0-3634-4968-a616-b4173f6601e1" />
Caption: Ran a UDP Scan on target ip & doucmented findings in Excel sheet

<img width="937" height="459" alt="Screenshot 2026-09-11 200542" src="https://github.com/user-attachments/assets/44fd521e-3162-43a6-acbc-9933a8828ae2" />


<img width="1149" height="1092" alt="Screenshot 2026-09-11 212517" src="https://github.com/user-attachments/assets/f9a39a6b-b422-42e8-bcb4-5f9e0a4aa0b9" />
Caption: Performed a lightweight vulnerability scan against target ip
<img width="697" height="501" alt="Screenshot 2026-09-13 211745" src="https://github.com/user-attachments/assets/aea37429-246b-4d8f-b70d-6fabf366af23" />
Caption: Documented vulnerability and remediation steps in Excel sheet








