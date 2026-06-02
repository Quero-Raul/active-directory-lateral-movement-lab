# Findings

## Finding 01: Exposed FTP Service with Weak Access Control

**Severity:** High  
**Category:** Initial Access  
**Impact:** Unauthorized access to internal resources.

### Description

An exposed FTP service allowed access with weak or misconfigured authentication. This provided an initial foothold into the lab environment.

### Business Impact

An attacker could use this access to upload or retrieve files, enumerate internal information and prepare further attacks.

### Evidence

Sanitized screenshots can be included in:

```text
/screenshots/sanitized/

Recommendation
Disable anonymous access.
Enforce strong authentication.
Restrict FTP access by network segment.
Replace FTP with secure alternatives such as SFTP.


Luego repites el mismo formato para:

```text
Finding 02: Poor Network Segmentation
Finding 03: Credential Exposure
Finding 04: Excessive User Privileges
Finding 05: Lateral Movement Possible Between Hosts
Finding 06: Domain Controller Compromise
