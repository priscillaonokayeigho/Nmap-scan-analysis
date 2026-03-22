# Nmap-scan-analysis
# Network Scan Report – scanme.nmap.org

## Overview
This project demonstrates my ability to perform network scans, analyze open ports, identify potential security risks, and document findings – skills relevant to SOC and cybersecurity analyst roles.

## Tools Used
- Nmap (Zenmap GUI)
- TCP Scan (-T4)

## Findings
- Port 21: FTP (restricted)
- Port 22: SSH (remote access)
- Port 80: HTTP (web service)
- Port 9929: Network testing service
- Port 31337: Filtered/unknown service

## Risks Identified
- Open ports increase attack surface
- SSH may be targeted by brute-force attacks
- HTTP traffic is unencrypted
- Unknown ports may expose hidden services

## Recommendations
- Close unused ports
- Use HTTPS instead of HTTP
- Implement strong authentication for SSH
- Monitor unusual ports (e.g., 31337
