# DVWA Network Reconnaissance & Port Scanning

## 📌 Project Overview
This project demonstrates network reconnaissance and port scanning using Nmap against a DVWA (Damn Vulnerable Web Application) lab environment.

## 🎯 Objective
- Identify open ports
- Detect running services
- Analyze potential security risks

## 🛠️ Tools Used
- Nmap

## 🌐 Target
192.168.114.131

## ⚡ Commands Used

### Basic Scan
nmap 192.168.114.131

### Service Version Detection
nmap -sV 192.168.114.131

### Aggressive Scan
nmap -A 192.168.114.131

## 📊 Scan Results
Open ports identified:
- 21 (FTP)
- 22 (SSH)
- 23 (Telnet)
- 80 (HTTP)
- 3306 (MySQL)
- 8180 (Tomcat)

## 🔍 Key Findings
- FTP service running (vsftpd 2.3.4)
- SSH service detected
- Apache web server exposed
- Multiple services increase attack surface

## ⚠️ Security Risks
- Outdated services may contain vulnerabilities
- Telnet is insecure (plaintext communication)
- Multiple open ports increase risk of attack

## 🛡️ Recommendations
- Disable unnecessary services
- Use SSH instead of Telnet
- Update outdated software
- Implement firewall rules

## 📷 Screenshot
See ``

## 📚 Learning Outcome
- Hands-on experience with Nmap
- Understanding of network exposure
- Basic vulnerability identification

