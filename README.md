# SA Ransomware Tabletop Kit

A facilitated tabletop exercise for a ransomware incident at a fictional Cape Town financial services firm. You can run it in one sitting of 2 to 3 hours. No software, lab, or virtual machine is required.

This kit is a portfolio project by Mosa Mofokeng (GitHub [Sasa021](https://github.com/Sasa021)). The scenario, roles, injects, question sets, notification checklist, and communication templates are here so she can facilitate the exercise herself. The results are not. Outcomes, participant comments, and lessons learned stay blank until she runs the room and writes them in her own words.

**This kit is not legal advice.** Notification duties change when a commencement date is proclaimed, when a Minister prescribes a form, or when a regulator issues a new notice. Read the source, then check it with legal counsel before you rely on it in a real incident. Sources are cited in [regulatory/breach-notification-guide.md](regulatory/breach-notification-guide.md).

## What this proves

A completed run of this kit shows that you can:

- Design and facilitate a ransomware tabletop from first detection through extortion and recovery.
- Describe what defenders see, and map those observations to MITRE ATT&CK technique names, without turning the room into an attack tutorial.
- Separate three South African duties that are often collapsed into one conversation: POPIA section 22, the Cybercrimes Act 19 of 2020 section 54 reporting duty for electronic communications service providers and financial institutions, and notification under FSCA and Prudential Authority Joint Standard 2 of 2024.
- Draft holding lines, an internal note, a customer notice, and a media question set that match what the room actually knows.
- Run the room with an eye on stress, roles, and psychological safety.
- Keep a scribe log that distinguishes what was said from what was decided, and turn that log into an after action report.

The proof is the completed scribe log, the after action report, and the results section below. An unread kit is a plan, not a result.

## Audience

- Hiring managers in a security operations centre, incident response, governance, risk and compliance, or security awareness, who want to see how you run a room.
- Peers, a student society, or a small team sitting the exercise. Four to eight people is a comfortable room. You can run it with three if one person holds two roles.
- You, if you walk it alone with the facilitator guide. A solo pass is a rehearsal. It is not a substitute for the notes a real room produces.

## The fictional firm

Harbourline Discretionary (Pty) Ltd is a fictional discretionary financial services provider on the Foreshore in Cape Town. It is not a licensed firm and it is not based on a real business. No client, staff member, or supplier in the brief is a real person.

Harbourline is written as a discretionary FSP so that three questions can come up in one afternoon: POPIA, because the firm holds personal information; Joint Standard 2 of 2024, because a discretionary FSP is in the list of financial institutions in that Standard; and Cybercrimes Act section 54, because a financial institution is one of the two kinds of organisation that section names. The guide is explicit about what is in force, what is still to be proclaimed, and what you must verify.

## How to run a 2 to 3 hour exercise

You need a room or a video call, a timer, one printed or shared copy of the participant handbook per person, the company brief, the eight injects, the scribe log, and this kit's facilitator guide. Keep [decision-points.md](decision-points.md) with the facilitator. Do not send the later injects in advance.

Suggested clock for about 2 hours 50 minutes:

| Exercise clock | Block | Minutes |
| --- | --- | --- |
| 0:00 | Open, roles, company brief | 15 |
| 0:15 | Inject 1, detection | 15 |
| 0:30 | Inject 2, spread and backups | 15 |
| 0:45 | Inject 3, accounts | 15 |
| 1:00 | Inject 4, extortion | 20 |
| 1:20 | Break | 10 |
| 1:30 | Inject 5, SAPS and regulators | 20 |
| 1:50 | Inject 6, staff, clients, and media | 20 |
| 2:10 | Inject 7, recovery | 20 |
| 2:30 | Inject 8 and hot wash | 20 |

A 2 hour sitting drops the break, shortens the open to 10 minutes, and folds inject 8 into a 10 minute hot wash. Give injects 4, 5, and 6 the time if you have to cut. Those three carry the pay or not pay decision, the reporting decision, and the customer communication.

Step by step:

1. Read [facilitator-guide.md](facilitator-guide.md) the day before.
2. Ask people to read [participant-handbook.md](participant-handbook.md) and [scenario/company-brief.md](scenario/company-brief.md). Ask them not to open the inject files.
3. Assign an incident lead, a scribe, a communications lead, a technical lead, and a person who holds the Information Officer role. The remaining people play client services, compliance, and the managed service provider.
4. Start the timer. Read each inject aloud from `scenario/inject-01` through `scenario/inject-08`. Pause for the questions in [decision-points.md](decision-points.md).
5. The scribe uses [templates/scribe-log.md](templates/scribe-log.md). Decisions, owners, and open questions go in the log. Speeches do not need to be verbatim.
6. Close with what the room decided, what it left open, and a check that nobody is leaving worried about a real incident at work or at home.
7. Within a day, draft [templates/after-action-report.md](templates/after-action-report.md) from the scribe log. Then fill **Results and lessons learned** below with what actually happened. Photographs or notes of the sitting go through [docs/screenshot-checklist.md](docs/screenshot-checklist.md) and [evidence/README.md](evidence/README.md).

There is no scoring sheet and no model answer pack. A confident wrong decision, recorded with the reason, teaches more than a scripted "correct" call.

## Repo structure

```
.
├── README.md
├── LICENSE
├── facilitator-guide.md
├── participant-handbook.md
├── decision-points.md
├── human-factors.md
├── scenario/
│   ├── README.md
│   ├── company-brief.md
│   ├── mitre-map.md
│   └── inject-01 to inject-08
├── regulatory/
│   └── breach-notification-guide.md
├── comms/
│   └── crisis-communications-plan.md
├── templates/
│   ├── after-action-report.md
│   └── scribe-log.md
├── docs/
│   └── screenshot-checklist.md
└── evidence/
    └── README.md
```

| Path | What it is for |
| --- | --- |
| [scenario/](scenario/README.md) | The firm and eight timed injects, plus a defender's MITRE ATT&CK map |
| [facilitator-guide.md](facilitator-guide.md) | How to set the room, keep time, and handle silence, argument, and distress |
| [participant-handbook.md](participant-handbook.md) | Rules, roles, and what participants may know at the start |
| [decision-points.md](decision-points.md) | Discussion questions for each inject, including pay or not pay, law enforcement, backups, and customer communications |
| [regulatory/breach-notification-guide.md](regulatory/breach-notification-guide.md) | POPIA, the Information Regulator's process, Cybercrimes Act section 54, and Joint Standard 2 of 2024, with a who, what, when checklist |
| [comms/crisis-communications-plan.md](comms/crisis-communications-plan.md) | Holding statements, internal message, customer notice, media questions, and a stakeholder map |
| [human-factors.md](human-factors.md) | Decision making under stress, roles, and psychological safety |
| [templates/](templates/after-action-report.md) | Blank after action report and scribe log |
| [docs/screenshot-checklist.md](docs/screenshot-checklist.md) | What to photograph or write down when you run the exercise |
| [evidence/README.md](evidence/README.md) | Where those notes live, and what must stay out of the repository |

## Results and lessons learned

Complete this section after you facilitate the exercise. Do not invent a sitting you have not run. If you have not run it yet, leave the lines blank.

- Date and place of the sitting:
- Who was in the room, by role (names only with their consent):
- Length of the sitting:
- Decision on payment:
- Decision on reporting to SAPS, the Information Regulator, and the responsible authority:
- Decision on which backup to trust:
- What you sent, or would have sent, to staff and to clients:
- What worked in the room:
- What you would change in the kit or in the facilitation:
- Link to the completed scribe log and after action report:

Participant comments, if people agreed they could be quoted:

> 

## About me

Rewrite this section in your own words before you treat the repository as finished portfolio work.

- Name: Mosa Mofokeng
- GitHub: [github.com/Sasa021](https://github.com/Sasa021)
- LinkedIn: replace this with your profile URL, [LinkedIn](https://www.linkedin.com/)
- Base: Cape Town, South Africa

Starter facts to confirm or rewrite: junior Cyber Security Analyst, ISC2 Certified in Cybersecurity (CC), Microsoft Security Operations Analyst (SC-200), academic background in Industrial and Organisational Psychology, Head of Public Relations at a student organisation, and scribe at an ITWeb ransomware workshop. Say what you did in the room when you ran this exercise, and what that sitting showed you. Leave the results section for the sitting itself.

## Licence

[MIT License](LICENSE). Copyright (c) 2026 Mosa Mofokeng.
