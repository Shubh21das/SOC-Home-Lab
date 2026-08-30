# MITRE ATT&CK Technique Log

A running log of MITRE ATT&CK techniques observed and mapped to real alerts generated in this lab (not just read about — actually triggered and analyzed).

| Technique ID | Technique Name | Tactic(s) | Triggered By | Day |
|---|---|---|---|---|
| T1098 | Account Manipulation | Persistence, Privilege Escalation | Windows Event 4733 (group member removed) | Day 1 |
| T1531 | Account Access Removal | Impact | Windows Event 4733 (group member removed) | Day 1 |
| T1484 | Domain Policy Modification | Defense Evasion, Privilege Escalation | Windows Event 4726 (account deleted) | Day 1 |
| T1136 | Create Account | Persistence | Windows Event 4720 (account created) | Day 2 |
| T1098 | Account Manipulation | Persistence, Privilege Escalation | Windows Event 4722 (account enabled) | Day 2 |
| T1098 | Account Manipulation | Persistence, Privilege Escalation | Windows Event 4723 (password change attempt) | Day 2 |
| T1098 | Account Manipulation | Persistence, Privilege Escalation | Windows Event 4724 (password reset attempt) | Day 2 |
| T1531 | Account Access Removal | Impact | Windows Event 4725 (account disabled) | Day 2 |
| T1098.007 | Account Manipulation: Additional Local or Domain Groups | Persistence, Privilege Escalation | Windows Event 4732 (member added to local security group) | Day 2 |
| T1098 | Account Manipulation | Persistence, Privilege Escalation | Windows Event 4738 (account modified) | Day 2 |


*(Add rows as new techniques are triggered and analyzed in future days.)*
