# Windows Event ID Reference

A running cheat-sheet of Windows Security Event IDs encountered during lab exercises, with their MITRE ATT&CK mapping as observed in Wazuh.

| Event ID | Description | MITRE Technique | MITRE Tactic(s) | First Seen |
|---|---|---|---|---|
| 4733 | A member was removed from a security-enabled local group | T1098, T1531 | Persistence, Impact | Day 1 |
| 4726 | A user account was deleted | T1484 | Defense Evasion, Privilege Escalation | Day 1 |
| 4720 | A user account was created | T1136 | Persistence | Day 2 |
| 4722 | A user account was enabled | T1098 | Persistence, Privilege Escalation | Day 2 |
| 4723 | An attempt was made to change an account's password | T1098 | Persistence, Privilege Escalation | Day 2 |
| 4724 | An attempt was made to reset an account's password | T1098 | Persistence, Privilege Escalation | Day 2 |
| 4725 | A user account was disabled | T1531 | Impact | Day 2 |
| 4732 | A member was added to a security-enabled local group | T1098.007 | Persistence, Privilege Escalation | Day 2 |
| 4738 | A user account was changed | T1098 | Persistence, Privilege Escalation | Day 2 |


*(Add rows as new events are encountered in future days.)*
