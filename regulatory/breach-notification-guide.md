# Breach notification guide

A reading note for Exercise Wharf Lantern. It covers three duties that the scenario can trigger at Harbourline Discretionary (Pty) Ltd, a fictional Cape Town discretionary financial services provider:

- Protection of Personal Information Act 4 of 2013 (POPIA) section 22, and the Information Regulator's security compromise process
- Cybercrimes Act 19 of 2020 section 54, the reporting duty aimed at electronic communications service providers and financial institutions
- FSCA and Prudential Authority Joint Standard 2 of 2024, cybersecurity and cyber resilience for financial institutions, including how a later notice sets the reporting template

**This is not legal advice.** It is a study aid for a tabletop. Statutes get amended, sections get commenced by proclamation, and regulators replace forms. Where this note is unsure of a date or a form, it says so. Before a real incident, read the current text and take advice from a lawyer who can look at your facts. A decision in the exercise is not a decision you can hand to a regulator.

Harbourline is fictional. The duties below are real. The firm is described as a discretionary FSP so the Joint Standard question can be asked. It is described as holding client personal information so the POPIA question can be asked. Whether a real firm falls inside each definition is a facts question. Do not copy Harbourline's label onto a real company without checking.

## How the three duties sit next to each other

They answer different questions. Doing one does not finish the others.

| Duty | Question it answers | Who it binds | A clock you can quote from the instrument itself |
| --- | --- | --- | --- |
| POPIA section 22 | Has an unauthorised person accessed or acquired personal information? | The responsible party. The operator must tell the responsible party. | "As soon as reasonably possible." No hour count in section 22. |
| Joint Standard 2 of 2024 paragraph 9 | Have we classified a cyber incident or an information security compromise as material? | A financial institution on that Standard's own list | The Standard says notify in the form, manner, and period the Authorities determine. The hour count, if you use one, has to come from the current notice and the template cover, not from paragraph 9. |
| Cybercrimes Act section 54 | Is our electronic communications service or network involved in a prescribed cyber offence? | An electronic communications service provider or a financial institution, and only for prescribed categories | The text says without undue delay and, where feasible, not later than 72 hours. That text is not a live clock until the section is in force and the Minister has prescribed the category, the form, and the manner. See the warning below. |

A voluntary report to the South African Police Service is available whether or not section 54 binds you. Reporting a crime and discharging a statutory duty are not the same act. The scribe should write which one the room means.

## POPIA section 22

Source: Protection of Personal Information Act 4 of 2013, section 22. A convenient consolidation is the one hosted by SAFLII: https://www.saflii.org/za/legis/consol_act/popia4o2013399/. Read the Act, not only this summary.

### Who

The **responsible party** must notify. At Harbourline that is the firm, and the brief makes Amina Fourie the Information Officer and Thabo Meyer the Deputy Information Officer. The Information Regulator's fact sheet on security compromises says the Information Officer or a Deputy Information Officer should make the report to the Regulator and to the data subjects. If your registration names someone else, use the person on the registration.

The **operator** is different. Section 21(2) says the operator must notify the responsible party immediately where there are reasonable grounds to believe that the personal information of a data subject has been accessed or acquired by any unauthorised person. BaySwitch is the operator in the story. Their mail to Lerato at 08:40 is the section 21 moment. It does not replace section 22. Harbourline still has to notify the Regulator and the data subjects.

A data subject who wants to complain uses the Regulator's complaints process. That is not the firm's notification. The fact sheet points a data subject to Form 5 and the complaints function. Do not mix the two forms up in the exercise.

### What counts

Section 22(1): where there are reasonable grounds to believe that the personal information of a data subject has been accessed or acquired by any unauthorised person, the responsible party must notify the Regulator and, subject to subsection (3), the data subject, unless the identity of the data subject cannot be established.

The Information Regulator's fact sheet states that POPIA does not set a risk threshold. On the Regulator's published view, security compromises are reported regardless of the level of risk the firm assigns, and the firm does not have a discretion about whether to report. If you want to argue for a threshold in a real matter, you are arguing against the Regulator's published position. Get counsel. Do not invent a "low risk" exception in this exercise.

The fact sheet also says you notify when you are reasonably sure a compromise has occurred, that the compromise does not have to be confirmed first, and that you do not need to finish the investigation first. If you were late, you explain the delay. If you do not yet have every detail, the fact sheet says to report on what you have and update the notification as you learn more.

In the story, the extortion email is a claim, and the outbound transfer is unexplained. Together with encrypted client folders, those facts are enough for the room to debate "reasonable grounds". The kit does not declare the debate over. It does say that "we are waiting to be certain" is a choice you must record, not a silent default.

### When

Section 22(2): the notification must be made as soon as reasonably possible after the discovery of the compromise, taking into account the legitimate needs of law enforcement or any measures reasonably necessary to determine the scope of the compromise and to restore the integrity of the responsible party's information system.

That sentence allows some time to understand scope and to restore systems, and it allows you to take law enforcement's legitimate needs into account. It does not state a number of hours. Do not write "72 hours" or "24 hours" next to POPIA. Those numbers belong to other instruments, and each of them has its own conditions.

Section 22(3) is the only delay rule for telling the data subject. The responsible party may delay that notification only if a public body responsible for the prevention, detection or investigation of offences, or the Regulator, determines that notification will impede a criminal investigation by the public body concerned. A preference for quiet, a journalist's deadline, or a hope that SAPS might call back is not that determination. If you do not have it, you do not have a section 22(3) delay.

### What the data subject must be told

Section 22(4): the notification to the data subject must be in writing and communicated by at least one of these:

- mailed to the last known physical or postal address
- sent by e-mail to the last known e-mail address
- placed in a prominent position on the website of the responsible party
- published in the news media
- as the Regulator directs

Section 22(5): the notification must give the data subject enough information to take protective measures. The Act lists:

- a description of the possible consequences of the security compromise
- a description of the measures the responsible party intends to take or has taken to address it
- a recommendation of measures the data subject can take to mitigate the possible adverse effects
- if known to the responsible party, the identity of the unauthorised person who accessed or acquired the personal information

The customer notice in the communications plan is built around those four points. If you do not know the identity of the unauthorised person, say you do not know. Do not invent a group name.

Section 22(6): the Regulator may direct a responsible party to publicise a compromise, in a manner the Regulator specifies, where the Regulator has reasonable grounds to believe publicity would protect a data subject.

### Where to send it

Use the channel the Information Regulator currently publishes. As described in the Regulator's fact sheet "New way to report security compromises!" (PDF on the Regulator's website, path under `/wp-content/uploads/2025/08/Fact-Sheet-on-security-compromises-2.pdf`):

- Notify the Regulator by logging the notification on the eServices portal.
- The portal page used for this is https://eservices.inforegulator.org.za/compromises/default.aspx. Access is limited to Information Officers, Deputy Information Officers, and Admin Officers linked to a registered organisation.
- Older material is still online, including Form SCN1 and the guidelines for completing a security compromise notification (linked from https://inforegulator.org.za/popia-forms/). The later fact sheet tells Information Officers to use the portal. If the portal and the PDF form disagree on the day you read this, follow the instruction the Regulator is giving Information Officers now, and keep a copy of that instruction with the notification.

The fact sheet's own sequence is: identify the compromise, tell the Information Officer or Deputy, mitigate, notify data subjects in writing, notify the Regulator on the portal, and, if you are the operator, tell the responsible party immediately. Then review the safeguards.

### How long a website notice stays up

The Act does not set a number of days. The same fact sheet says the period depends on how likely data subjects are to see the notice, and that thirty to ninety days is a general rule of thumb. Treat that as the Regulator's practical comment, not as section 22. Record why you chose a period. If the Regulator directs a different period, the direction wins.

### What failure can lead to

Non-compliance with section 22 is one of the things section 73(b) calls an interference with the protection of the personal information of a data subject. A person may complain to the Regulator under section 74. The Regulator can investigate and can issue an enforcement notice. Section 103(1) makes it an offence to fail to comply with an enforcement notice served under section 95. Section 107(a) sets the penalty for that offence at a fine or imprisonment for a period not exceeding 10 years, or both.

Section 109 lets the Regulator deliver an infringement notice where a responsible party is alleged to have committed an offence under the Act. The administrative fine in that notice may not exceed R10 million, subject to section 109(10). The person may pay, arrange instalments, or elect to be tried in court. Section 109 is tied to an alleged offence. It is not a tariff that says "late section 22 notice equals R10 million". Do not quote it that way.

Section 99 provides for civil remedies. The detail belongs with counsel if a data subject sues. This kit does not summarise the quantum of damages, because the Act does not set a single number.

Section 19 is the security-safeguards condition in the background: appropriate, reasonable technical and organisational measures, kept up to date. It is not a notification deadline. It is the duty people will ask about when they ask whether the compromise should have been harder to cause.

## Information Regulator: practical checklist

- [ ] Information Officer and Deputy identified, and the eServices access checked before you need it
- [ ] Operator contract requires the section 21(2) call, and the call has a named inbox that is read
- [ ] You can say, in one paragraph, why you do or do not yet have reasonable grounds
- [ ] Regulator notification lodged on the current channel, with a reference number saved
- [ ] Data subjects notified in writing by a section 22(4) method, unless a section 22(3) determination exists and you have a copy
- [ ] The notice covers consequences, measures taken, recommended steps, and the identity of the unauthorised person if known
- [ ] Updates sent when the early report was incomplete
- [ ] Website notice period chosen and recorded, if you used the website
- [ ] Reason for any delay written down at the time, not reconstructed a month later

## Cybercrimes Act section 54

Source: Cybercrimes Act 19 of 2020, section 54. The Act was published in Government Gazette 44651 on 1 June 2021. Section 54 sits in Chapter 8, "Reporting obligations and capacity building".

### The duty, as written

Section 54(1): an electronic communications service provider or financial institution that is aware, or becomes aware, that its electronic communications service or electronic communications network is involved in the commission of any category or class of offences provided for in Part I of Chapter 2 **and which is determined in terms of subsection (2)**, must:

- without undue delay and, where feasible, not later than 72 hours after having become aware of the offence, report the offence in the prescribed form and manner to the South African Police Service; and
- preserve any information which may be of assistance to the South African Police Service in investigating the offence.

Section 54(2): the Cabinet member responsible for policing, in consultation with the Cabinet member responsible for the administration of justice, must by notice in the Gazette prescribe the category or class of offences that must be reported, and the form and manner of the report.

Section 54(3): failure to comply with subsection (1) is an offence, liable on conviction to a fine not exceeding R50 000.

Section 54(4): subject to any other law or obligation, subsection (1) must not be read as requiring the provider or institution to monitor the data it transmits or stores, or to actively seek facts or circumstances indicating unlawful activity. The subsection uses the words "electronic service provider". Subsection (1) uses "electronic communications service provider". Do not build a clever argument on that difference without a lawyer.

Section 54(5): the section does not apply to a financial sector regulator, or to a function performed by the South African Reserve Bank under section 10 of the South African Reserve Bank Act, 1989.

### Who is an electronic communications service provider

Section 1 defines it in two limbs. The first is a person who provides an electronic communications service under an Electronic Communications Act licence, or who is deemed licensed or exempted. The second is a person with lawful authority to control a private electronic communications network used primarily for the owner's own use, where that network is exempted from licensing. A normal advisory firm is not, just by having email, an electronic communications service provider. Read both limbs before you apply them to a real network operator. BaySwitch might or might not fall inside the definition. The brief does not give BaySwitch's licence status. In the exercise, say "not established" unless you are discussing the definition itself.

### Who is a financial institution for section 54

Section 1 says a financial institution as defined in section 1 of the Financial Sector Regulation Act 9 of 2017. That definition is the FSR Act's, and it is not the same list as the definition inside Joint Standard 2 of 2024. The Joint Standard says "notwithstanding" the Act's definition and then lists who it covers. A firm can raise a section 54 question without being inside the Joint Standard, and the reverse also needs a check.

Harbourline is written as a discretionary FSP so participants have a serious section 54 conversation. Before you treat a real FSP as a "financial institution" under section 54, read the current FSR Act definition.

### When the 72 hours is not yet your clock

Two separate uncertainties sit on top of the "where feasible, not later than 72 hours" wording. Do not skip them.

**Commencement.** Section 60 of the Act lets the President fix different dates for different provisions. Proclamation R42, published in Government Gazette 45562 of 30 November 2021, brought large parts of the Act into operation on 1 December 2021 and excluded section 54. The proclamation brings Chapter 8 into operation "with the exclusion of section 54". The Government Gazette copy used here is https://www.gov.za/sites/default/files/gcis_document/202112/45562re11363proc42.pdf. A publicly circulated consolidation of the Act, marked as incorporating changes to 11 October 2024 and as last checked on 30 January 2026, still records section 54 as "to be proclaimed". The section note at https://cybercrimesact.co.za/section-54-obligations-of-electronic-communications-service-providers-and-financial-institutions/ says the same. Those secondary notes are not a gazette. They are a reason to check, not a reason to stop checking.

This kit was assembled in November 2026. A web search at that time still described section 54 as uncommenced. A web search is not a full audit of the Government Gazette. **Before you rely on the 72 hour duty, check whether a later proclamation has commenced section 54.** If it has not, the fine in section 54(3) is not an in-force penalty, and the 72 hour sentence is not an in-force deadline. You may still report the crime to SAPS and you should still preserve evidence. Say that clearly in the scribe log.

**Prescription of categories and form.** Even on the face of a commenced section 54, subsection (1) applies to a category or class of Part I Chapter 2 offences that has been determined under subsection (2), and the report has to be in the prescribed form and manner. Subsection (2) requires a Gazette notice. This kit does not assert that such a notice is, or is not, in force. **Check the Gazette. If no category and no form have been prescribed, say so, and do not invent a form.** Ask counsel. Until then, a report to SAPS is a criminal complaint on whatever channel SAPS is actually using, not a demonstrated discharge of section 54.

### What to tell SAPS without a prescribed form

For the exercise, and for a real firm that wants to report before the prescribed form exists, use the channel SAPS publishes on https://www.saps.gov.za/ on the day. Take a copy of what you submitted, the date and time, the name or reference you were given, and a note of what you were asked to preserve. Do not invent a unit e-mail address in the after action report. If the site is unclear, go to a police station and ask for the cybercrime function, then write down who you spoke to.

Preserve first, then tidy. The section 54 preservation idea is sound operational practice even while commencement is outstanding: keep the note on screen, the firewall summary, the Friday quarantine record, BaySwitch's mail to Lerato, and a list of who handled each item. The scribe log can be the chain of custody note for the exercise. It is not a forensic image.

## Joint Standard 2 of 2024

Sources:

- Joint Standard 2 of 2024, *Cybersecurity and Cyber Resilience Requirements for Financial Institutions*, made by the Financial Sector Conduct Authority and the Prudential Authority under section 107 read with sections 105, 106 and 108 of the Financial Sector Regulation Act 9 of 2017.
- Joint Communication 5 of 2024 states that the Authorities published the Joint Standard on 17 May 2024, and that Joint Notice 1 of 2024 determines the effective date as 1 June 2025. Confirm that date on www.fsca.co.za and www.resbank.co.za if you are using this after a later amendment.
- Joint Notice 2 of 2026, *Determination of the Notification Template for Material IT and Cyber Incidents*, signed 31 August 2026, takes effect on 1 September 2026. The copy read for this kit is the PDF on the South African Reserve Bank publications path: https://www.resbank.co.za/content/dam/sarb/publications/prudential-authority/pa-public-awareness/communication/2026/joint-communication-5-of-2026/Joint%20Notice%202%20of%202026%20-%20Determination%20of%20the%20Notification%20Template_310826.pdf

Download the Standard and the Notice from the Authorities. This kit does not attach their PDFs.

### Who

For this Joint Standard, "financial institution" has its own list. It includes, among others, banks and controlling companies, mutual banks, insurers, managers of collective investment schemes, market infrastructures, discretionary FSPs, certain Category I FSPs that provide investment fund administration services, administrative FSPs, pension funds, OTC derivative providers, section 13B administrators, and registered credit rating agencies. Read the definition in the Standard for the full wording and the statute each item points at. Paragraph (f) is the discretionary FSP. That is the limb Harbourline is written to meet.

The **responsible authority** is the authority responsible for the financial sector law, as the Standard defines it by pointing at the Financial Sector Regulation Act. For a discretionary FSP the discussion path in this exercise is the Financial Sector Conduct Authority. Banks and insurers have a different path in the Notice, through the Prudential Authority's Umoja portal. Do not send Harbourline's fictional report to Umoja.

### What "material" means

The Standard's definition: a disruption of a business activity, process or function which has, or is likely to have, a severe and widespread impact on the financial institution's operations, services to its customers, or the broader financial system and economy.

Joint Notice 2 of 2026 repeats that definition. The word "or" matters. A one-office FSP is unlikely to move the broader financial system. It can still look at severe and widespread impact on its own operations and on services to its customers. In the story, the portal is down, client files are unreadable, and a property transfer is stuck. The room must classify or must record why it will not. The facilitator does not announce the "right" classification.

### Paragraph 9, and the notice that fills it in

Paragraph 9.1: a financial institution must notify the responsible authority, in the form and manner determined by the Authorities, after classifying either of the following as a material incident:

- a cyber incident, or
- an information security compromise.

Paragraph 9.2 and 9.3: the Authorities may also require other reports under the Standard, and may determine the form, manner, content, and period by notice on their websites.

The Standard itself does not say "within 24 hours" or "within 14 days". Do not attribute those numbers to paragraph 9.

Joint Notice 2 of 2026 determines the template called *Reporting of Material IT and Cyber Incident Template* as the information to submit when an incident is classified as a material IT and cyber incident. It is made under paragraph 9.1 of Joint Standard 2 of 2024 and under the matching paragraph of Joint Standard 1 of 2023.

Manner, from paragraph 3.1 of the Notice:

- A bank, a branch, a controlling company, a mutual bank, and an insurer and controlling company submit on the Umoja portal. The Notice tells those firms to select submission type "notification" and submission name "Reporting of material IT and cyber incidents".
- The other institutions on the list, which includes a discretionary FSP, submit on the FSCA Joint Standards Submission Portal. The Notice's route is: www.fsca.co.za, Regulated Entities, E-Services, then Joint Standards Submission Portal.

Period: paragraph 3.2 of the Notice says the template must be submitted within the period set out on the cover page of the template. The Notice body, as fetched for this kit, does not restate that cover page. Commentary published around the Notice, including industry legal updates in September 2026, describes an initial notification within 24 hours after the incident is classified as material, a follow-up within 14 calendar days of notification, and a fuller report on a timeline agreed with the Authorities. Those updates also say the 24 hour period runs from classification, not from detection.

**Use the cover page of Annexure A, not the commentary, as the source of the period.** If the cover page and a newsletter disagree, the cover page and any later notice from the Authorities win. If you cannot open the template on the day, write "period not verified" in the scribe log. Do not invent a substitute number. Classification time should be recorded anyway, because the Notice's design, as described by the Authorities' template approach and by the commentary, makes the moment of classification the moment that matters.

### Other parts of the Standard the exercise touches

These are not notification clocks. They are why the fictional firm looks underprepared, and why inject 7 asks for a recovery point.

Paragraph 7.4 requires a financial institution to be able to respond and recover, to keep a backup strategy with regular backups and testing, to protect sensitive information on backup media and store that media offline or offsite, to have a communication strategy for affected financial customers including any recourse, and to set its recovery point objective and recovery time objective for its size and risk.

Paragraph 7.5 requires a cyber incident response and management plan that covers communication, coordination, and response, a way to find the control failures and the extent of impact, the use of lessons to improve controls and the plan, and testing of the plan against plausible threats, aligned to the recovery objectives.

Harbourline's two-page note, and the fact that this is the first time it has walked through an incident, is a paragraph 7.5 gap. The room may recommend what the plan should contain. The room may not pretend a test that never happened was a success.

### What the Authorities can do

The Authorities supervise financial institutions under the Financial Sector Regulation Act and can take regulatory action when a standard is contravened. This kit does not set out the penalty sections or a fine amount for a late Joint Standard notification. Those consequences depend on the financial sector law and on the enforcement path the Authority uses. Ask counsel, or read the Financial Sector Regulation Act, rather than quoting a number from memory.

## Who, what, when

Complete the "Our answer" column during inject 5. Leave it blank if you have not run the exercise. The "Verify" column is the work this kit will not do for you.

| # | Who acts | What they must do | When, on the instruments above | Harbourline path in the story | Verify before a real incident | Our answer |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | Operator | Tell the responsible party | Immediately, where section 21(2) grounds exist | BaySwitch tells Harbourline. The 08:40 mail to Lerato needs to reach the Information Officer | Contract and POPIA section 21(2) | |
| 2 | Responsible party (Information Officer or Deputy) | Notify the Information Regulator | As soon as reasonably possible after discovery. No hour in the Act. Explain any delay. Update if the first report was thin | eServices portal, once reasonable grounds are accepted | Current Regulator channel and fact sheet | |
| 3 | Responsible party | Notify data subjects in writing, with the section 22(5) content | As soon as reasonably possible. Delay only under a section 22(3) determination | E-mail, and a website notice if e-mail will not reach people. No section 22(3) determination exists in the injects | Section 22(3) to (5) | |
| 4 | Financial institution on the Joint Standard list | Notify the responsible authority after classifying a cyber incident or information security compromise as material | Period on the cover page of the template determined in Joint Notice 2 of 2026. Do not quote a number you have not read there | Discretionary FSP: FSCA Joint Standards Submission Portal. Record the time you classified | Template cover page and any later notice | |
| 5 | Same firm | Send the follow-up the template's cover page requires | Whatever that cover page says. Commentary has described 14 calendar days and a later agreed final report. Confirm | Only if you classified the incident as material | Same template | |
| 6 | ECSP or financial institution, and only if section 54 is in force and the offence is in a prescribed category | Report to SAPS in the prescribed form, and preserve information | Without undue delay and, where feasible, not later than 72 hours after becoming aware of the offence | Do not start this clock until the three checks in the section 54 warning are done. A voluntary SAPS report can still be made | Proclamation, Gazette notice under section 54(2), SAPS channel | |
| 7 | Anyone preserving evidence | Keep what investigators and the firm will need | From the first hour, not after the systems are rebuilt | Note, firewall summary, quarantine record, account-creation time, list of who handled each item | Counsel and SAPS instructions on the day | |

## What not to write in the after action report

- Do not write that Harbourline notified a regulator if the room did not decide to notify.
- Do not write a case number, a portal reference, or a fine. None were issued in the story.
- Do not convert "as soon as reasonably possible" into a number of hours.
- Do not state that section 54 was complied with unless you have also recorded that the section was in force and that a prescribed form existed on the day you say the report was made.

## Sources, short list

- POPIA section 22, section 21(2), section 19, section 73(b), section 74, section 103, section 107, section 109. Consolidation: https://www.saflii.org/za/legis/consol_act/popia4o2013399/
- Information Regulator fact sheet on security compromises, and the eServices compromises portal: https://eservices.inforegulator.org.za/compromises/default.aspx and https://inforegulator.org.za/popia-forms/
- Cybercrimes Act 19 of 2020 section 54 and section 1. Commencement of other provisions, excluding section 54: Proclamation R42, Government Gazette 45562, 30 November 2021, effective 1 December 2021. Gazette copy: https://www.gov.za/sites/default/files/gcis_document/202112/45562re11363proc42.pdf
- Joint Standard 2 of 2024, paragraphs 7.4, 7.5, and 9, and the definition of material incident and of financial institution
- Joint Notice 2 of 2026, effective 1 September 2026, SARB publications PDF linked above
- Financial Sector Regulation Act 9 of 2017, for the definition of financial institution used by the Cybercrimes Act and for the Authorities' supervisory role
