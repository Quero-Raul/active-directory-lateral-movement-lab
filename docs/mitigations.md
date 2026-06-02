# Mitigations

## Access Control

- Disable anonymous or guest access.
- Enforce strong password policies.
- Implement multi-factor authentication where possible.
- Apply least privilege to users and service accounts.

## Network Segmentation

- Restrict communication between VLANs.
- Limit administrative protocols such as RDP, SMB and WinRM.
- Use firewall rules between internal segments.
- Monitor east-west traffic.

## Active Directory Hardening

- Protect privileged accounts.
- Disable unused accounts.
- Rotate exposed credentials.
- Review group memberships regularly.
- Apply tiered administration model.

## Monitoring and Detection

- Monitor failed and successful authentication events.
- Detect lateral movement behavior.
- Alert on suspicious use of administrative tools.
- Monitor abnormal RDP, SMB and Kerberos activity.

## System Hardening

- Remove unnecessary services.
- Patch vulnerable systems.
- Restrict file upload paths.
- Apply endpoint protection.
- Enable centralized logging.

## MITRE ATT&CK Mapping

| Tactic | Technique |
|---|---|
| Initial Access | Valid Accounts / Exploitation of Public-Facing Application |
| Discovery | Network Service Discovery |
| Credential Access | OS Credential Dumping |
| Lateral Movement | Remote Services |
| Privilege Escalation | Exploitation for Privilege Escalation |
| Defense Evasion | Use of Legitimate Tools |