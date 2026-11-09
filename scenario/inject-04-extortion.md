# Inject 4. Extortion

**Scenario time:** Monday 11:40
**Exercise aim:** Decide whether the firm will pay, and what "pay" is even allowed to mean in this room.

## Read this aloud

A second note arrives by email to Amina and to info@harbourline.example, a fictional address. The message claims that copies of client files were taken before the encryption, including identity documents and bank details, and that the copies will be published if Harbourline does not pay. It says a sample can be provided. No sample is attached. The facilitator will not invent a sample, a leak site, or a price.

BaySwitch says they can see a large outbound transfer in last night's firewall summary, to a destination they have not identified. They cannot yet say whether the transfer was client files, a backup, or something else. The summary is not shown in this pack. Nobody is asked to interpret a real log.

Amina asks the room, in one sentence: "Do we pay?"

The firm's bank has a relationship manager who will want a written instruction from a mandated official before sending any unusual payment. No mandate for a ransomware payment exists, because the firm has never discussed one. There is no cyber insurance policy to phone.

## Facts the room may use

- There is a claim of theft of client identity documents and bank details, plus a threat to publish.
- There is an unexplained outbound transfer. Content unknown.
- There is no sample in the exercise.
- Payment would need a mandated official and the bank. Neither has been set up for this.
- Paying is a decision the room may take. This kit does not explain how to pay, who to contact, or how to move funds.

## What you do not know yet

- Whether any personal information was actually taken.
- Whether publication is imminent or is a standard threat.
- Whether a payment, even if it were lawful and funded, would produce a decryption key or a deletion of copies.

## Reveal after the discussion

| ID | Technique | Why it is on the table |
| --- | --- | --- |
| T1486 | Data Encrypted for Impact | The extortion sits on top of the encryption already seen. |
| T1567 | Exfiltration Over Web Service | Unconfirmed. A large outbound transfer is reported. Destination and content are unknown. |

Treat the data-theft claim as a reason to start the POPIA assessment in the next inject. Do not treat it as proof.
