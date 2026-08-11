# Investigation: Possible Lateral Movement

## Summary
Unusual SMB authentication attempts from workstation to domain controller.

## Evidence
- Sysmon EventCode 3: Outbound SMB traffic
- Multiple failed logons
- Process: `powershell.exe`

## MITRE Mapping
- T1021 — Remote Services

## Analyst Decision
Suspicious — escalate for deeper review.
