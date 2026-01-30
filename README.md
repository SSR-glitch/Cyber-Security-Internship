# Cyber Security Internship 

**Intern Name:** Satish Bukki
**Role:** Cyber Security Intern
**Host Company:** Codec Technologies
**Focus Area:** Network Security & VAPT

# Overview
Projects I completed during my internship. The work focuses on **Vulnerability Assessment** and ***Network Fundamentals**, demonstrating hands-on experience with industry-standard security tools.

## Project 1: Vulnerability Assessment and Penetration Testing (VAPT)

**Objective:** To conduct a comprehensive vulnerability scan on a target system to identify open ports, service versions, and potential security gaps.

### Tools Used
* **Nmap (Zenmap GUI):** For port scanning and service fingerprinting.
* **Target:** `scanme.nmap.org` (Authorized testing target).

### Execution Steps
1.  **Configuration:** Launched Zenmap and configured an **"Intense Scan"** profile (equivalent to `nmap -A`) to perform aggressive detection.
2.  **Scanning:** Executed the scan to enumerate the target's network services and operating system details.
3.  **Analysis:** The scan successfully identified critical open entry points:
    * **Port 80 (HTTP):** Detected Apache httpd 2.4.7.
    * **Port 22 (SSH):** Detected OpenSSH 6.6.1p1.
    * **OS Detection:** Identified the target as running Linux.

### Project Output
![Vulnerability Scan Screenshot](Project1_Zenmap_Scan.png)

## Project 2: Network Traffic Analysis (Network Fundamentals)

**Objective:** To capture and analyze live network traffic to understand TCP/IP handshakes and ICMP protocols.

### Tools Used
* **Wireshark:** For packet sniffing and protocol analysis.
* **Command Prompt:** For generating ICMP (Ping) traffic.

### Execution Steps
1.  **Setup:** Configured Wireshark to capture traffic on the active Wi-Fi network interface.
2.  **Traffic Generation:** Initiated a connectivity check using the command `ping 8.8.8.8` (Google DNS) to generate standardized **ICMP** packets.
3.  **Filtering & Analysis:** Applied the `icmp` display filter in Wireshark to isolate **"Echo Request"** and **"Echo Reply"** packets, confirming successful network communication and latency measurement.

### Project Output
![Network Analysis Screenshot](Project2_Wireshark_Analysis.png)

## Conclusion
These projects demonstrate the practical application of the **Defensive Security** lifecycle—identifying attack surfaces using Nmap and monitoring network integrity using Wireshark.
