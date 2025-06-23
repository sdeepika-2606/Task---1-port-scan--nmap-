# Task---1-port-scan--nmap

# Task 1 – Network Port Scanning using Nmap

## 🎯 Objective
To scan the local network and identify open ports using Nmap to understand network exposure and potential security risks.

---

## 🛠 Tools Used
- [Nmap - Kali Linux Tools](https://www.kali.org/tools/nmap/) – A powerful tool for scanning networks and identifying open ports and services.
- Command Prompt (Windows)
- (Optional) Wireshark – For analyzing packet captures

---

## 📍 Step-by-Step Progress

### ✅ Step 1: Task Understanding
Understood that the task involves using Nmap to perform a local network scan and analyze open ports to learn about basic network reconnaissance.

### ✅ Step 2: Installed Nmap
Downloaded and installed Nmap from the official Kali Linux tools page and made sure it was added to the system PATH.

### ✅ Step 3: Found My IP Range
Used the command: ipconfig

Found my local IP: `192.168.1.9`  
Used network range: `192.168.1.0/24`

### ✅ Step 4: Performed TCP SYN Scan
Ran the command: nmap -sS 192.168.1.0/24

This scanned for live hosts and their open ports.

### ✅ Step 5: Saved Scan Result
Saved the output in a text file using: nmap -sS 192.168.1.0/24 > scan_result.txt

### ✅ Step 6: Used Wireshark (Optional)
Captured traffic during the scan to observe SYN, SYN-ACK, and RST packets.

### ✅ Step 7: Analysis
Identified devices and open ports. Researched common services (e.g., port 22 = SSH, port 80 = HTTP) and reviewed potential security risks.

---

## 📁 Output File
The full scan result is available in [`scan_result.txt`](scan_result.txt)

---

## 📚 Key Learnings
- How to identify and scan IP ranges
- TCP SYN scanning with Nmap
- Observing packet flow using Wireshark
- The purpose and risks of open ports
- Basics of network security and reconnaissance

---

## 🧠 Key Topics Covered
- Port Scanning  
- TCP SYN Scan  
- IP Ranges  
- Network Reconnaissance  
- Open Ports  
- Network Security Basics

---

## 🔗 Reference
- [Nmap - Kali Linux Tools](https://www.kali.org/tools/nmap/)

