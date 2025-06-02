# Lab Report – OSI Model Practical Exercises

---

## Overview

This lab focused on practical, hands-on tasks covering all layers of the OSI Model, using a virtual network of Windows, Linux, and pfSense systems. The goal was to observe how protocols operate at each layer using system tools, CLI commands, and packet analyzers.

---

## Exercise 1 – OSI Layers 1 to 3

### Powered-on Machines:
- ACIDC01 (Windows Server 2022 - DC)
- ACIWIN11 (Windows 11 PRO)
- ACIPFSENSE (pfSense Router)

### Tasks Performed:

**Layer 1 – Physical (NIC Inspection)**  
- Opened Device Manager on Windows 11  
- Reviewed physical properties of the NIC  

**Layer 2 – Data Link (ARP Table & Stats)**  
- Ran: "ipconfig /all"
- Ran: "arp -a" to view ARP table  

**Layer 3 – Network (Routing Table)**  
- Ran: "ipconfig" to check interface IPs  
- Ran: "route print" to examine routing table  

---

## Exercise 2 – OSI Layers 4 and 5

### Powered-on Machines:
- ACIDC01 (Windows Server 2022 - DC)
- ACIWIN11 (Windows 11 PRO)
- ACIALMA (Alma Linux 9.3)
- ACIPFSENSE (pfSense Router)

### Tasks Performed:

**Layer 4 – Transport (TCP Analysis)**  
- Captured traffic in Wireshark  
- Opened Terminal on Windows:  
  "nmap -Pn 192.168.0.4"  
- In Wireshark: filtered using "tcp.port == 22"  
- Observed TCP handshake packets

**Layer 5 – Session (TCP Stream)**  
- In Wireshark: filtered using "tcp.port == 80"  
- Opened 192.168.0.4 in Microsoft Edge  
- Right-clicked packet and selected "Follow > TCP Stream"

---

## Exercise 3 – OSI Layer 6

### Powered-on Machines:
- ACIDC01 (Windows Server 2022 - DC)
- ACIWIN11 (Windows 11 PRO)
- ACIPFSENSE (pfSense Router)

### Tasks Performed:

**Layer 6 – Presentation (Compression & Encryption)**  
- Opened a folder in Terminal and ran "dir" 
- Right-clicked a file > Properties > Advanced  
- Enabled "Compress contents to save disk space" 
- Enabled "Encrypt contents to secure data"  
- Verified file attributes after compression/encryption  

---

## Exercise 4 – OSI Layer 7

### Powered-on Machines:
- ACIDC01 (Windows Server 2022 - DC)
- ACIWIN11 (Windows 11 PRO)
- ACIPFSENSE (pfSense Router)

### Tasks Performed:

**Layer 7 – Application (DNS Queries)**  
- Ran in Terminal:
  - "nslookup acidc01"
  - "nslookup -type=NS aciplab.com"  
- Observed DNS resolution and authoritative server responses  

---

## Final Thoughts

This lab helped solidify my understanding of the OSI Model not just in theory but in real-world contexts. The use of CLI tools, GUI-based settings, and packet analysis provided a comprehensive look into how different layers interact and how to troubleshoot them effectively.

