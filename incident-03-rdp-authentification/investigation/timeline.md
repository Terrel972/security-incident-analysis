# Incident Timeline – Remote RDP Session

## Summary
A successful remote authentication sequence resulted in an RDP session on host THM-PC.

## Timeline
| Time | Event | Details |
|------|-------|---------|
| 22:44:22 | Logon Type 3 | Network authentication initiated |
| 22:44:25 | Logon Type 2 | Interactive session created |
| 22:44:25 | Logon Type 10 | RDP session established – user THM-PCS from 10.80.115.83 |
| 22:44:28 | Logon Type 5 | Service logon triggered by session |

## Analysis
All events share Logon ID 0x44C70, confirming a single authentication chain leading to a remote desktop session.

No suspicious post-authentication execution was observed during the analysis window.

## Status
Remote access confirmed – activity documented
