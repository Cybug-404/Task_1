# Task 1 – Nmap TCP SYN Scan

## 🔍 Objective
Learn to discover open ports on devices in your local network to understand network exposure.

## 🛠 Tools Used
- Nmap
- Wireshark
- linux (OS)

## 🧪 Steps Performed
1. Installed Nmap using command **sudo apt install nmap** on the terminal
2. Installed Wireshark from https://www.wireshark.org/
3. Opened Wireshark on packet capture mode on the interface
4. Performed a full TCP SYN port scan using nmap on the localhost

## 📊 Output
- Open ports: 22,23,445,5900
- OS: Linux

## 🧠 Learnings
   PORTS     SERVICE           DESCRIPTION                                            VULNERABILITY
   
-  22        SSH               Remote login (encrypted)and command execution          Brute-force attacks, misconfigured keys
-  23        Telnet            Remote login (Plaintext)                               Man-in-the-middle attacks(MITM)
-  445       SMB               File and printer sharing (Windows)                     RCE via EternalBlue (MS17-010), credential leakage
-  5900      VNC               Remote desktop GUI access                              Brute-force attacks, weak or missing authentication 
