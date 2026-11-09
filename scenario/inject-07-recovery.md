# Inject 7. Recovery

**Scenario time:** Tuesday 15:00
**Exercise aim:** Choose a recovery path, name what data you will lose, and refuse a path you cannot trust.

## Read this aloud

BaySwitch has spent the day on containment. If the room ordered accounts disabled and the office network isolated, BaySwitch followed that order at Monday 14:00. If the room did not, BaySwitch isolated the file server only, and says the rest was "left as you decided".

They now offer two restore options and one they refuse to recommend.

**Option A. Salt River Vault Storage.** The offline set from 11 days ago can be brought to the office on Wednesday morning. BaySwitch has not opened it. It cannot include any instruction, new client, or file saved in the last 11 days. It is the copy least likely to have sat on the network during the incident. "Least likely" is not a test result.

**Option B. Sunday cloud backup of LedgerQuay.** This copy is newer. It finished on Sunday night, after the 02:14 sign-in and before Monday's notes appeared. BaySwitch cannot say whether the copy contains anything harmful. They can restore it to a separate network on Wednesday and look at it. They will not restore it straight onto the live systems.

**Option C. A decryptor.** BaySwitch will not run an unknown decryptor, and this exercise does not provide one. If the room decided on Monday to pay, there is still no key in the story. Do not fast-forward to a successful decryption. The story does not contain that result.

Friday's client reporting pack cannot be produced from memory. Johan says three withdrawal instructions from last week are in email, which is still up, and the rest are in LedgerQuay.

Amina asks what Harbourline will tell clients about the missing 11 days if option A is the one that stands.

## Facts the room may use

- Option A is older and was offline. It is untested.
- Option B is newer and overlaps the suspicious sign-in. It can be inspected off to the side.
- Option C is not available in this scenario.
- Email still has some recent client instructions.
- Joint Standard 2 of 2024 expects backup media to be protected, and expects offline or offsite storage, and expects the firm to have set a recovery point objective and a recovery time objective. Harbourline has the offsite habit and has not set the two objectives.

## What you do not know yet

- Whether either backup will boot cleanly.
- How many client instructions live only in LedgerQuay.
- When the portal should be switched on again. "As soon as possible" is not a decision. Name a condition.

## Reveal after the discussion

| ID | Technique | Why it is on the table |
| --- | --- | --- |
| T1490 | Inhibit System Recovery | Still the right label for the unreadable on-network backup. The offline set is the control that survived. |

Recovery is a business decision informed by that technique. It is not a new attack step for the room to design.
