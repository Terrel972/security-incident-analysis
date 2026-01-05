# Detection Phase – Suspicious PowerShell Activity

## Detection Context
The Security Operations Center (SOC) detected unusual PowerShell activity
on a Windows endpoint during routine monitoring.

The alert was triggered due to abnormal PowerShell execution patterns
that deviated from the baseline behavior observed on similar systems.

## Detection Source
- Monitoring type: Endpoint telemetry
- Data sources:
  - PowerShell execution logs
  - Process creation events
  - Command-line arguments

## Alert Characteristics
- Process: powershell.exe
- Execution context: User-level
- Behavior observed:
  - Encoded or obfuscated command usage
  - Unusual command-line parameters
  - Execution outside standard administrative workflows

## Analyst Action
The alert was flagged for further analysis and escalated to the triage phase
to determine whether the activity was benign or malicious.

## Detection Status
- Detection confirmed
- Escalated to triage phase
