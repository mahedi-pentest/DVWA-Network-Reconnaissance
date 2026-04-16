# Reconnaissance Report

## Target
192.168.114.131

## Methodology
Performed network scanning using Nmap to identify open ports and services.

## Findings

| Port | Service | Version |
|------|--------|--------|
| 21   | FTP    | vsftpd 2.3.4 |
| 22   | SSH    | OpenSSH |
| 80   | HTTP   | Apache |
| 3306 | MySQL  | MySQL 5.0 |

## Risk Level
Medium to High

## Conclusion
The system exposes multiple services, increasing the attack surface and risk of exploitation.
