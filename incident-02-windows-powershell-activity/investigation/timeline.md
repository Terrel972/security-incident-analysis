# Incident Timeline – Suspicious RDP Activity

## Summary
A successful remote authentication followed by an interactive RDP session was observed on the Administrator account.

## Timeline
| Time | Event | Details |
|------|-------|---------|
| 17:01:13 | Logon Type 3 | Network authentication from 10.80.108.111 |
| 17:01:15 | Logon Type 10 | RDP session established on Administrator |

## Analysis
No post-authentication process execution (Event ID 4688) was observed during the analysis window.

## Status
Suspicious activity – monitored
