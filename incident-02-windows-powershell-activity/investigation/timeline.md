# Incident Timeline – Suspicious RDP Activity

## Summary
A successful remote authentication followed by an interactive RDP session was observed on the local Administrator account, originating from an internal IP address.


## Timeline
| Time | Event | Details |
|------|-------|---------|
| 17:01:13 | Logon Type 3 | Network authentication from 10.80.108.111 |
| 17:01:15 | Logon Type 10 | interactive RDP session established on Administrator |

## Analysis
No post-authentication process execution (Event ID 4688) was observed during the analysis window,
limiting visibility on actions performed after the RDP session establishment.

## Status
Suspicious activity – monitored due to privileged account usage via RDP without observable post-authentication activity.

