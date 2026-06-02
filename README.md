# Active Directory & Lateral Movement Lab

## Overview

This project documents a controlled penetration testing lab focused on lateral movement, pivoting and Active Directory compromise.

The objective was to simulate an internal attack path starting from an initial foothold and progressing through multiple network segments until reaching the domain controller.

> All work was performed in a private lab environment. Sensitive data, IP addresses, credentials and bootcamp-specific material have been removed or anonymized.

## Objectives

- Discover hosts and exposed services.
- Gain initial access to a Linux machine.
- Perform pivoting between network segments.
- Enumerate Windows systems and Active Directory.
- Identify credential exposure.
- Perform lateral movement.
- Demonstrate domain compromise.
- Document mitigations and hardening recommendations.

## Tools Used

- Kali Linux
- Nmap
- Dirsearch
- Proxychains
- Chisel
- CrackMapExec / NetExec
- xfreerdp
- PowerView
- Mimikatz
- Hashcat

## Attack Path Summary

1. Network discovery and service enumeration.
2. Initial access through exposed/misconfigured service.
3. Linux host enumeration.
4. Pivoting into an internal network.
5. Windows host discovery.
6. Credential harvesting and validation.
7. Active Directory enumeration.
8. Lateral movement.
9. Domain Controller compromise.

## Key Learnings

- Importance of network segmentation.
- Risks of reused or exposed credentials.
- Dangers of weak privilege boundaries.
- Need for monitoring lateral movement techniques.
- Importance of hardening Active Directory environments.

## Mitigations

- Enforce strong password policies and rotation.
- Disable unnecessary services.
- Restrict lateral communication between hosts.
- Apply least privilege to users and services.
- Monitor authentication events.
- Detect tools and techniques mapped to MITRE ATT&CK.
- Protect privileged accounts.
- Review and harden Active Directory configurations.

## Disclaimer

This project is for educational and portfolio purposes only. No real systems were attacked, and no sensitive information is included.
