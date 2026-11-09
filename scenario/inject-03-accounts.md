# Inject 3. Accounts and the portal

**Scenario time:** Monday 09:40
**Exercise aim:** Decide what to isolate, who still has administrator rights, and what to tell the board chair.

## Read this aloud

The 09:00 meeting was cancelled because the file server is unusable. That decision, if the room made a different one, still stands in the story: staff were told "IT issues, meeting postponed", and nothing more.

BaySwitch now reports two account facts. A privileged account that BaySwitch uses on QUAY-FS01 signed in at 02:14 from a network location Harbourline does not recognise. A second administrator account, which Lerato does not remember creating, was created at 02:31. BaySwitch has not disabled either account. They are asking Amina for written permission because the contract says production changes need the client's approval. The office network is still up. The Stellenbosch laptop is still on guest Wi-Fi.

At 09:35 the client portal stops responding. Johan has four missed calls from clients who wanted a balance before a property transfer today. LedgerQuay itself is unreachable from the office. BaySwitch can still see the server that hosts it and says it is "not encrypted as far as we can tell". They have not proved that.

Dr Naledi September, the board chair, sends a one-line message: "Call me before this reaches clients."

## Facts the room may use

- Unusual use of a privileged account at 02:14, and a new administrator account at 02:31.
- Neither account has been disabled. The network has not been isolated.
- The portal and LedgerQuay are down from the users' point of view. Encryption of LedgerQuay is not established.
- Clients are already calling about today's balances.
- The board chair wants a call.

## What you do not know yet

- Whether the 02:14 sign-in and the new account belong to the same activity as the encrypted files.
- Whether mailbox contents, client records, or only file-server documents were touched.
- Whether BaySwitch still has a trustworthy administrator path.

## Reveal after the discussion

| ID | Technique | Why it is on the table |
| --- | --- | --- |
| T1078 | Valid Accounts | A known privileged account signed in from an unrecognised location. |
| T1136 | Create Account | A new administrator account appeared at 02:31. |
| T1021 | Remote Services | Suspected. The sign-in was remote. The room has no session detail. |
| T1489 | Service Stop | The portal and LedgerQuay are unavailable to users. Cause unproven. |
