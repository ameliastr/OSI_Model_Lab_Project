# OSI Model Lab Project

This project documents hands-on practice with all seven layers of the OSI Model using a virtualized IT lab environment. The exercises cover key concepts and practical skills in networking and systems administration, such as packet analysis, routing tables, file encryption, and DNS lookups.

---

## 🧪 Lab Environment

- **ACIDC01** – Windows Server 2022 (Domain Controller)
- **ACIDM01** – Windows Server 2022 (Domain Member Server)
- **ACIWIN11** – Windows 11 PRO (Domain Workstation)
- **ACIALMA** – Alma Linux 9.3 (Standalone Workstation)
- **ACIPFSENSE** – pfSense v2.7.2 (Virtual Router)

---

## ✅ Skills Practiced

- NIC Inspection (Layer 1)
- ARP Table & Interface Statistics (Layer 2)
- Routing Table Analysis (Layer 3)
- TCP Packet Capture & Stream Analysis (Layers 4–5)
- File Compression & Encryption (Layer 6)
- DNS Queries with Nslookup (Layer 7)

---

## 📁 Exercises Summary

### 🔹 Exercise 1 – OSI Layers 1 to 3

- **Tools used**: Device Manager, `ipconfig`, `arp -a`, `route print`
- **Skills**:
  - Identified and examined NIC settings (Layer 1)
  - Viewed ARP entries and interface stats (Layer 2)
  - Reviewed local routing table (Layer 3)

### 🔹 Exercise 2 – OSI Layers 4 and 5

- **Tools used**: Wireshark, Nmap
- **Skills**:
  - Captured a TCP handshake using Wireshark
  - Followed a TCP stream on port 80

### 🔹 Exercise 3 – OSI Layer 6

- **Tools used**: Windows File Explorer, Terminal
- **Skills**:
  - Compressed and encrypted files on Windows 11
  - Verified attribute changes via command line

### 🔹 Exercise 4 – OSI Layer 7

- **Tools used**: `nslookup`
- **Skills**:
  - Queried local and external DNS servers
  - Retrieved authoritative nameservers for domain

---

## 📸 Additional Files

- `lab_report.md`: A detailed, step-by-step walkthrough of each exercise.
- `screenshots/`: (Optional) Captures of commands, tools, and outputs.
- `configs/`: (Optional) Terminal outputs or network config files.

---

## 💼 Relevance to My Career

This project demonstrates practical, real-world skills relevant to:

- Networking Fundamentals
- Systems Administration
- Cybersecurity
- IT Support & Troubleshooting

By completing this module, I’ve gained technical experience in protocol behavior, system diagnostics, and secure file handling—skills critical to an IT role.

---

## 🔗 License

This project is for educational and portfolio use. No commercial or production systems were involved.
