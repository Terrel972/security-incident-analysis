# Triage Phase – Suspicious PowerShell Activity

## Triage Objective
Assess the severity, credibility, and potential impact of the detected
PowerShell activity in order to determine appropriate next actions.

## Initial Assessment
- Alert confirmed as legitimate
- Activity does not match standard user or administrative behavior
- No immediate evidence of false positive

## Observations
- PowerShell executed with unusual command-line parameters
- Execution occurred outside known maintenance or IT operations
- No immediate signs of system instability or service disruption

## Severity Assessment
- Severity level: Medium
- Justification:
  - Suspicious scripting activity observed
  - Limited scope (single endpoint)
  - No confirmed persistence or lateral movement at this stage

## Affected Assets
- Endpoint: Windows workstation
- User context: Standard user session
- Scope: Isolated to a single host

## Triage Decision
- Escalated to investigation phase
- No immediate containment required
- Endpoint remains under observation

## Next Steps
- Analyze PowerShell command content
- Review execution timeline
- Identify potential Indicators of Compromise (IOCs)
