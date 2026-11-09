# Company brief: Harbourline Discretionary (Pty) Ltd

**This firm is fictional.** Harbourline is not a licensed financial services provider, and it is not modelled on a real Cape Town business. Every person named below is invented. Use the facts in this brief. Do not add clients, rand amounts, or systems that are not written here. If a fact is missing, say that the room does not know it.

## What the firm is

Harbourline Discretionary (Pty) Ltd trades as Harbourline. It is a small discretionary financial services provider. In this scenario it sits in paragraph (f) of the definition of "financial institution" in FSCA and Prudential Authority Joint Standard 2 of 2024: a discretionary FSP as defined in the relevant codes of conduct. The responsible authority for its financial sector law is the Financial Sector Conduct Authority, not the Prudential Authority. Confirm that split if you use this scenario to talk about a real licence. The brief states it so the room has a clear notification path to discuss.

The office is on the Foreshore in Cape Town. Staff also visit clients in the northern suburbs and in Stellenbosch. There is no second office.

The book is a set of discretionary portfolios for families and family trusts in the Western Cape. The exact rand value of the book is not in this brief. Do not invent one. What matters for the exercise is that a day without the portfolio system stops instructions, withdrawals, and client reporting.

About 28 people work at Harbourline. About 1,400 clients are on the books. Those numbers are scenario facts so the room can talk about scale. They are not a census of a real firm.

## Personal information the firm holds

As a responsible party under the Protection of Personal Information Act 4 of 2013 (POPIA), Harbourline holds:

- Client and trustee names and contact details
- Identity numbers and tax reference numbers
- Bank account numbers used for contributions and withdrawals
- FICA documents and proof of address
- Beneficiary details and, in a few files, information about a child's guardianship
- Staff records on the same file server, including payslips

Harbourline does not hold medical aid records. Do not add that category during the exercise.

## People in the story

| Name | Role in the story | In the room you may play |
| --- | --- | --- |
| Amina Fourie | Managing director and Information Officer | Incident lead, or Information Officer |
| Thabo Meyer | Compliance manager and Deputy Information Officer | Compliance and the section 22 question |
| Lerato Jacobs | The only in-house IT lead | Technical lead |
| Johan Pietersen | Head of client services | Client calls and the customer notice |
| Dr Naledi September | Non-executive board chair, not in the office today | The person the lead must brief by phone |
| BaySwitch Technology (Pty) Ltd | Fictional managed service provider and operator under POPIA | The outsourced technical voice |

BaySwitch hosts the portfolio system and watches the office systems under a written contract. The contract says BaySwitch must tell Harbourline at once if it believes personal information has been accessed by an unauthorised person. That sentence tracks POPIA section 21(2). The notification to the Information Regulator and to clients remains Harbourline's duty under section 22.

External counsel is on a panel. No firm is named, and no one is on the clock until the managing director calls them. The cyber insurance quote requested in March was never bound. There is no cyber policy in force on the morning of the incident. Do not invent a claim that pays out.

## Systems, in plain language

- Email and calendars are on a cloud suite used by all staff. Email is still up at the start of the story.
- **LedgerQuay** is the portfolio and client-record system. BaySwitch hosts it. Advisers use it all day.
- **QUAY-FS01** is the office file server. Client working papers and staff files sit on it.
- A backup job copies QUAY-FS01 to a disk on the same office network every night.
- A separate offline copy goes to **Salt River Vault Storage**, a fictional storage room Harbourline rents. The last set that BaySwitch collected and stored offline is 11 days old.
- BaySwitch also runs a cloud backup of LedgerQuay. The job that finished on Sunday night has not been restored in a test this year.
- Harbourline has not written down a recovery point objective or a recovery time objective. Joint Standard 2 of 2024 expects a financial institution to set both in line with its size and risk. The gap is intentional. The room has to choose a recovery point in inject 7 and live with what clients lose.
- The client portal, a simple login on top of LedgerQuay, shows balances and accepts a withdrawal request. It is up at 07:40. It is not up by inject 3.

Multi-factor authentication is on email. It is not on the portal and not on the administrator accounts BaySwitch uses for QUAY-FS01. That is a known weakness Lerato has raised twice. It has not been funded.

## What "normal Monday" looks like

Advisers arrive from 07:30. A weekly investment meeting starts at 09:00. Client reporting for the month is due on Friday. Johan has already promised three families a withdrawal instruction this week. Those three instructions are the concrete client harm the room can talk about. Do not invent a run on the firm or a loss of client money unless a later inject says so. This story is about systems and personal information, not a hole in the client bank accounts.

## What you know about preparation

Harbourline has a two-page incident note written by Thabo last year. It says: tell Amina, call BaySwitch, and do not speak to the press. It does not name a scribe, a communications owner, or the Information Regulator. It has never been exercised. This sitting is the first time the firm walks through a cyber incident. In the language of Joint Standard 2 of 2024 paragraph 7.5, the firm does not yet have a tested cyber incident response plan. Participants may recommend what the plan should contain. They may not pretend the plan already worked.

## Rules for facts

- If the brief and the injects are silent, the answer is "we do not know yet".
- Do not look up real criminal groups, real leak sites, or real payment methods during the sitting.
- Do not use a real client's story as colour. Stay inside Harbourline.
