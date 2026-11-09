# MITRE ATT&CK map (defender view)

This map names techniques that match what Harbourline's staff and BaySwitch report during Exercise Wharf Lantern. It is a vocabulary for the hot wash. It is not a finding that a named criminal group did these things, and it is not a set of steps anyone should reproduce.

Source of the names and IDs: MITRE ATT&CK Enterprise, https://attack.mitre.org/. Technique IDs are stable labels. Descriptions on the MITRE site are the reference if a participant wants the official sentence. Do not extend this table into commands, tools, or configuration changes during the sitting.

Status key:

- **Seen.** The inject describes the effect directly.
- **Suspected.** A fact is consistent with the technique. The room does not have forensic proof.

| Inject | ID | Name | Tactic | Status | What the room actually has |
| --- | --- | --- | --- | --- | --- |
| 1 | T1486 | Data Encrypted for Impact | Impact | Seen | Files will not open. A note claims encryption. |
| 2 | T1486 | Data Encrypted for Impact | Impact | Seen | The same note is on the server and on a laptop outside the office. |
| 2 | T1490 | Inhibit System Recovery | Impact | Suspected | The on-network backup is unreadable. Cause not shown. |
| 2 | T1566 | Phishing | Initial Access | Suspected | An invoice-style attachment was opened on Thursday. No link is proven. |
| 2 | T1204 | User Execution | Execution | Suspected | A person opened that attachment. |
| 3 | T1078 | Valid Accounts | Defense Evasion, Persistence, Privilege Escalation, Initial Access | Seen | A known privileged account signed in from an unrecognised location at 02:14. |
| 3 | T1136 | Create Account | Persistence | Seen | An administrator account the IT lead does not recognise was created at 02:31. |
| 3 | T1021 | Remote Services | Lateral Movement | Suspected | The sign-in was remote. No session detail is in the pack. |
| 3 | T1489 | Service Stop | Impact | Suspected | The portal and LedgerQuay are down for users. Cause not shown. |
| 4 | T1567 | Exfiltration Over Web Service | Exfiltration | Suspected | A large outbound transfer is reported. Content and destination are unknown. |
| 7 | T1490 | Inhibit System Recovery | Impact | Suspected | Same backup fact as inject 2. The offline set is the copy that was not on the network. |

Injects 5, 6, and 8 do not add technique IDs. They are decisions about notification, communication, and closure.

## How to use the map in the room

- At the end of an inject, ask: "Which of these have we seen, and which are still a story we are telling ourselves?"
- If someone proposes a technique that is not in the table, write it in the scribe log as a hypothesis with the fact that supports it. Do not argue from a blog post.
- Initial access stays unconfirmed on purpose. A tabletop that hands you the full intrusion path teaches attribution theatre. This one leaves a gap so the room can feel what an incomplete picture does to a payment decision and a client notice.

## What this map will not do

It will not tell you to pay, to stay silent, or to restore a backup. Those decisions sit in [decision-points.md](../decision-points.md). It will not name a real intrusion set or a real destination. Adding either would invent an outcome the injects do not contain.
