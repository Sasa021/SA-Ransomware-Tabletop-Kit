# Inject 2. Spread and backups

**Scenario time:** Monday 08:25
**Exercise aim:** Draw a boundary around what is affected, and find out which copy of the data you might trust later.

## Read this aloud

Lerato is in the office. BaySwitch is on a call. Their technician says the same note is on the file server and on two adviser laptops, one of which is at a client's house in Stellenbosch. The laptop is on the guest Wi-Fi there and is still signed in to email.

The nightly disk copy of QUAY-FS01, the one that sits on the office network, cannot be read. BaySwitch will not say whether that disk was encrypted or simply failed. They will say the last offline set at Salt River Vault Storage was collected 11 days ago and has not been connected to the office network since.

Lerato remembers an email from last Thursday. An adviser forwarded a message that looked like a supplier invoice. The adviser opened the attachment. Lerato quarantined the mailbox on Friday morning and did not finish the check. The attachment is not available to the room. Nobody may describe how to build one.

LedgerQuay is slow. It is still up. Amina wants the 09:00 investment meeting to go ahead "so we do not alarm the staff".

## Facts the room may use

- The note is on the file server, on two office PCs, and on a laptop outside the office.
- The network backup of the file server is unreadable. Cause unknown.
- An offline copy exists and is 11 days old.
- A suspicious attachment was opened on Thursday. The check was not finished.
- The 09:00 meeting is in 35 minutes. Most staff do not know there is an incident. They do know there is a WhatsApp photo.

## What you do not know yet

- Whether the Thursday attachment has anything to do with Monday morning.
- Whether the offline set is complete, or whether it includes LedgerQuay.
- Whether BaySwitch's own management accounts were used.

## Reveal after the discussion

| ID | Technique | Why it is on the table |
| --- | --- | --- |
| T1486 | Data Encrypted for Impact | The note is now on the server and on a remote laptop. |
| T1490 | Inhibit System Recovery | The on-network backup is unreadable. You do not yet know if that was deliberate. |
| T1566 | Phishing | Suspected only. An invoice attachment was opened on Thursday. Link unproven. |
| T1204 | User Execution | Suspected only. A person opened that attachment. Link unproven. |
