# UDP Flood Attack Detection using SNORT

![Copy of Log ana (4)](https://github.com/emeka789/NetworkMonitoring/assets/99328320/a80c574b-acdc-42bd-9f86-9877691b2592)

## Introduction
In this project, an intrusion detection solution, Snort, was implemented on a Linux system to monitor inbound network traffic and detect potential malicious activity. The Linux system was then exposed to a DoS attack (UDP Flood) where large numbers of UDP packets were sent by an attacker to the target in order to overwhelm the target system's capacity, making it unresponsive to legitimate network traffic. Often times these packets can contain spoofed IP address data making it diffcult to pinpoint the origin of the attack. 
After this, network traffic was analyzed and monitored to evaluate the environment's security posture and incident response effectiveness.

## Technologies Used
- Virtual Machines (Linux/Windows)
- Linux CLI
- Snort

## Snort Rules Implemented
- SSH Authenication Attemps
- ICMP Ping
