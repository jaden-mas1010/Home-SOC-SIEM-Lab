# Investigation: Suspicious PowerShell Activity

## Alert Summary
Splunk flagged encoded PowerShell commands executed from `winword.exe`.

## Evidence
- Sysmon EventCode 1: PowerShell spawned by Office
- Encoded command detected
- Network beacon to external IP

## MITRE Mapping
- T1059.001 — PowerShell
- T1204 — User Execution

## Analyst Decision
Malicious — escalate to IR.
