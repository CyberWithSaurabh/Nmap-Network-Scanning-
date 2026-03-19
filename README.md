Nmap – TryHackMe
📌 Overview

The Nmap Lab on TryHackMe focuses on network reconnaissance and port scanning techniques. This lab helps learners understand how to identify live hosts,
detect open ports, and discover services running on a target machine.

🎯 Objectives

Understand the basics of network scanning

Learn different Nmap scan techniques

Identify open ports and services

Perform service and version detection

Gain hands-on experience in enumeration

🛠️ Tools Used

Nmap

Linux Terminal

TryHackMe AttackBox / Kali Linux

🌐 What is Nmap?

Nmap (Network Mapper) is an open-source tool used for network discovery and security auditing. It is widely used by cybersecurity
professionals for scanning networks and identifying vulnerabilities.

⚡ Basic Nmap Commands
🔍 Scan a Single Target
nmap <target_ip>

🔍 Scan Multiple Targets
nmap <ip1> <ip2>

🔍 Scan a Range of IPs
nmap 192.168.1.1-100

🚀 Advanced Nmap Commands
🔸 SYN Scan (Stealth Scan)
nmap -sS <target_ip>

🔸 Service Version Detection
nmap -sV <target_ip>

🔸 OS Detection
nmap -O <target_ip>

🔸 Aggressive Scan
nmap -A <target_ip>

🔸 Scan Specific Ports
nmap -p 80,443 <target_ip>

📊 Common Scan Types
Scan Type	Command	Description
TCP Connect	-sT	Full TCP connection scan
SYN Scan	-sS	Stealth scan (half-open)
UDP Scan	-sU	Scan UDP ports
Ping Scan	-sn	Host discovery only

🧪 Lab Tasks Summary

Perform host discovery

Identify open ports

Detect running services

Analyze scan results

Understand enumeration techniques

📸 Screenshots
🔹 Nmap Scan Result
(Add your screenshot here)
Example: nmap scan output showing open ports

🔹 Service Detection
(Add your screenshot here)
Example: -sV scan output

🔹 Aggressive Scan
(Add your screenshot here)
Example: -A scan results

🧠 Key Learnings

Nmap is essential for reconnaissance

Different scan types serve different purposes

Open ports reveal attack surface

Service detection helps in vulnerability analysis

⚠️ Disclaimer

This lab is for educational purposes only. Always ensure you have permission before scanning any network or system.

📚 References

Nmap Official Documentation

TryHackMe Platform

⭐ Author  Saurabh

Cybersecurity Enthusiast 🔐
