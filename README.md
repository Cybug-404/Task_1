# Task 1 – Nmap Scanning

## 🔍 Objective
To perform a basic network scan using `nmap` to discover open ports and services on a target machine.

## 🛠 Tools Used
- Nmap
- Bash terminal
- Linux OS (Kali/Debian)

## 🧪 Steps Performed
1. Identified the target IP address: `192.168.1.10`
2. Performed a full TCP port scan using:
   ```bash
   nmap -sS -p- 192.168.1.10
