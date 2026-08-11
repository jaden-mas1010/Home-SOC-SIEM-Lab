# T1059 — Command and Scripting Interpreter

## Description
Detects suspicious command execution using PowerShell, CMD, or other interpreters.

## Detection Logic
- Sysmon EventCode 1 (Process Creation)
- Encoded commands
- Suspicious parent-child relationships

## SPL Rule
See: `/detections/splunk/process_creation_rules.spl`

## Triage Notes
- Check parent process lineage
- Review network connections
- Validate user context
