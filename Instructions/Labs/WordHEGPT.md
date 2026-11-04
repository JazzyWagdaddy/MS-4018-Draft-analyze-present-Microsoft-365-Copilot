# Microsoft 365 Copilot in Word: From Blank Page to Trusted Draft

> A 45-minute, hands-on lab for university faculty and staff

**Level:** Beginner  
**Format:** Individual hands-on practice or facilitated workshop  
**Time:** 45 minutes  
**Product:** Microsoft Word with Microsoft 365 Copilot

In this lab, you will use a fictional university initiative to practice five durable Copilot skills: **create, understand, improve, transform, and evaluate**. All source material is included below, so no separate downloads are required.

> [!IMPORTANT]
> Copilot can accelerate drafting and analysis, but it does not replace your judgment. You are responsible for checking facts, protecting university data, and approving the final document.

## Contents

- [Learning objectives](#learning-objectives)
- [Prerequisites](#prerequisites)
- [Lab schedule](#lab-schedule)
- [Responsible AI and privacy](#responsible-ai-and-privacy)
- [Exercise 1 — Create](#exercise-1--create-10-minutes)
- [Exercise 2 — Understand](#exercise-2--understand-8-minutes)
- [Exercise 3 — Improve](#exercise-3--improve-10-minutes)
- [Exercise 4 — Transform](#exercise-4--transform-7-minutes)
- [Exercise 5 — Evaluate](#exercise-5--evaluate-10-minutes)
- [Wrap-up and resources](#wrap-up-and-resources)

## Learning objectives

By the end of the lab, you will be able to:

1. Create a useful first draft from a clear brief.
2. Ask Copilot to summarize and interrogate a document without confusing proposals with decisions.
3. Improve selected text for clarity, tone, accessibility, and audience.
4. Transform unstructured notes into a useful structure without inventing details.
5. Evaluate AI-assisted writing against explicit criteria and verify it before sharing.

## Prerequisites

Before the timed lab, confirm that you have:

- Microsoft Word for the web or a current Word desktop app.
- An institutional Microsoft 365 account with access to Copilot in Word.
- The **Copilot** control or pane visible in Word. Features and labels may vary by license, platform, app version, and institutional rollout.
- Permission to create and edit Word documents.
- This README open beside Word.
- Your institution's policies for data classification, privacy, records retention, accessibility, and acceptable AI use.

Use only the fictional content in this lab. Do not substitute real student, employee, patient, donor, research, legal, or other restricted information during practice.

### Quick setup

1. Open Word and sign in with your institutional account.
2. Create a blank document named `Copilot-Word-Lab-YourName.docx`.
3. Open Copilot from the Word canvas, ribbon, or side pane.
4. If a direction below names a control you do not see, use the Copilot pane and describe the same outcome in the prompt. Do not spend lab time troubleshooting a missing preview feature.

## Lab schedule

| Exercise | Skill | Time | Deliverable |
|---|---|---:|---|
| 1 | Create | 10 min | Event announcement |
| 2 | Understand | 8 min | Grounded briefing note |
| 3 | Improve | 10 min | Clear, inclusive staff message |
| 4 | Transform | 7 min | Structured project update |
| 5 | Evaluate | 10 min | Requirements audit and verified revision |
|  | **Total** | **45 min** |  |

## A simple prompt pattern

For reliable results, include four ingredients:

| Ingredient | Question to answer | Example |
|---|---|---|
| Goal | What should Copilot do? | Draft an announcement. |
| Context | Who is it for and why? | Faculty and instructional staff who prepare course materials. |
| Source | What information may it use? | Use only the event brief below. |
| Expectations | What must the result look like? | 250 words, warm tone, heading and bullets; mark gaps instead of guessing. |

Treat your first prompt as a starting point. A strong workflow is **prompt → inspect → refine → verify**, not “generate once and send.”

## Responsible AI and privacy

Apply these practices throughout the lab:

- **Use the minimum necessary data.** Do not place personally identifiable student or employee information, grades, advising notes, disability information, protected research, or confidential personnel material in a prompt unless your institution has explicitly approved that use.
- **Follow institutional rules.** A tool's technical protections do not override university policy, consent requirements, records obligations, or data-classification rules.
- **Check access before referencing files.** Copilot respects existing Microsoft 365 permissions, but broad or incorrect permissions can still expose content to people who already have access. Check the source file, sharing settings, and sensitivity label.
- **Ground the request.** Tell Copilot which source to use and say “do not invent missing details.” Referencing a source improves relevance; it does not guarantee accuracy.
- **Verify every consequential claim.** Check names, dates, numbers, quotations, policies, citations, links, commitments, and decisions against an authoritative source.
- **Look for uneven impact.** Review tone, assumptions, stereotypes, accessibility, and whether the output excludes or disadvantages a group.
- **Keep a human accountable.** The document owner—not Copilot—decides what to accept and remains responsible for the final communication.
- **Disclose AI assistance when required.** Follow your institution's authorship, academic integrity, procurement, research, and communications guidance.

Microsoft states that commercial Microsoft 365 Copilot honors existing permissions and that prompts, responses, and Microsoft Graph data are not used to train foundation language models. Your institution may configure additional controls, so local policy remains the authority. See [Data, Privacy, and Security for Microsoft Copilot](https://learn.microsoft.com/en-us/microsoft-365-copilot/microsoft-365-copilot-privacy).

---

## Exercise 1 — Create (10 minutes)

### Goal

Create a first-draft announcement from a factual event brief, then refine it without allowing Copilot to fill gaps with guesses.

### Scenario

The fictional **Center for Teaching and Learning (CTL)** is launching a workshop for employees who prepare course materials. You need an announcement for the university intranet.

### Source: event brief

Copy this brief into your lab document under the heading `Exercise 1 — Source`.

```text
EVENT BRIEF — DIGITAL ACCESSIBILITY SPRINT

Audience: Faculty, teaching assistants, instructional designers, and staff who prepare course materials
Purpose: Help participants improve the accessibility of one existing course document
Date: Thursday, February 18, 2027
Time: 1:00–2:30 p.m. Eastern Time
Format: Hybrid — Lakeview Library, Room 204, and Microsoft Teams
Hosts: Center for Teaching and Learning and Office of Digital Accessibility
Participants will: run an accessibility check; repair headings, lists, links, and image descriptions; and create a short follow-up plan
Bring: One course handout, syllabus, or assignment sheet that contains no confidential student information
Capacity: 40 participants
Registration deadline: February 11, 2027
Registration link: Not yet provided
Accommodation contact: accessibility@example.edu
Cost: No cost to participants
```

### Do the task

**Minutes 0–2 — Prepare:** Read the brief and identify the missing registration link. Place your cursor below the source, open Copilot, and choose a drafting option if one is offered.

**Minutes 2–6 — Generate:** Copy and submit this prompt.

```text
Using only the event brief in this document, draft a 220–260 word intranet announcement for university faculty and staff.

Include:
- a descriptive headline;
- a two-sentence opening that explains the value of the event;
- a scannable event-details section;
- what participants should bring and learn; and
- a clear registration call to action.

Use a welcoming, professional, inclusive tone and plain language. Preserve the date, time, format, hosts, capacity, deadline, contact, and cost exactly. Do not invent a registration URL or any other missing fact. Mark missing information as [CONFIRM: description].
```

**Minutes 6–8 — Refine:** Inspect the draft. If the value to participants is vague, use this follow-up prompt.

```text
Revise the opening so the practical benefit is clear to a busy instructor. Keep every factual detail unchanged, avoid exaggerated claims, and keep the complete announcement under 260 words.
```

**Minutes 8–10 — Verify:** Compare the draft with the source brief.

### Expected outcome

A short announcement with a clear headline, accurate event details, a practical explanation of the workshop, a call to action, and a visible placeholder for the missing registration link.

### Verification checklist

- [ ] The audience and purpose match the brief.
- [ ] The date, time zone, location, online option, deadline, capacity, cost, hosts, and contact are exact.
- [ ] The draft says what participants will do and what they should bring.
- [ ] The missing link is marked `[CONFIRM]`; Copilot did not invent one.
- [ ] No guarantee such as “make every document fully compliant” was added.
- [ ] You—not Copilot—selected which version to keep.

> **Skill insight:** Specific constraints reduce guesswork, but verification is what catches unsupported details.

---

## Exercise 2 — Understand (8 minutes)

### Goal

Use Copilot to understand a planning document while preserving the difference between evidence, recommendations, and approved decisions.

### Source: working group update

Copy the following text into a new section headed `Exercise 2 — Source`.

```text
FLEXIBLE COURSE MATERIALS PILOT — WORKING GROUP UPDATE

Background
The provost asked a six-member working group to explore support for instructors who want to offer course readings in accessible digital formats. The group reviewed support requests from the previous academic year and surveyed 214 instructors. Of the 127 instructors who responded, 62% said they wanted short, task-based training; 48% requested individual consultations. The survey did not ask students about their experience.

Proposed pilot
The working group recommends a one-semester pilot serving up to 25 courses in Fall 2027. The proposed service would include two workshops, weekly virtual office hours, and up to three hours of consultation per participating course. Academic departments would nominate courses, with priority suggested for high-enrollment undergraduate courses. The selection method has not been approved.

Resources
The estimated pilot cost is $48,000: $30,000 for temporary staffing, $10,000 for document remediation support, and $8,000 for captioning. The library has offered existing training space at no charge. No funding source has been approved. The working group recommends a joint request to the provost and chief information officer.

Risks and open questions
Demand may exceed the 25-course limit. Temporary staffing may not be in place before the start of Fall 2027. The group has not determined how to measure student impact, how long remediated files will be retained, or which office will own the service after the pilot. Faculty representatives also asked whether participation could affect course review; the working group recommends that participation remain developmental and separate from evaluation.

Status and next step
The Faculty Learning Committee endorsed continued planning but did not approve the pilot, budget, selection method, or launch date. The provost's office requested a two-page decision memo by March 15, 2027. The memo must present costs, an assessment plan, data-governance responsibilities, and at least one option for operating within existing resources.
```

### Do the task

**Minutes 0–2 — Orient:** Read the headings, but do not study every sentence. Open Copilot in **chat-only** or question-and-answer mode so it does not edit the source.

**Minutes 2–5 — Ask:** Submit this prompt.

```text
Using only the working group update in this document, prepare a briefing for a department chair.

Return:
1. a three-sentence executive summary;
2. a table with the columns Category, Item, Status, and Source section;
3. separate rows for evidence, recommendations, approved decisions, and unresolved questions; and
4. the next required deliverable and deadline.

Do not treat a recommendation, endorsement, estimate, or proposed date as an approved decision. If the document does not answer something, say “Not stated.”
```

**Minutes 5–7 — Probe:** Ask one targeted follow-up.

```text
What are the three most important questions the decision memo must answer before leaders could responsibly approve this pilot? For each question, point to the source section that makes it necessary.
```

**Minutes 7–8 — Verify:** Check the output against the last two source sections.

### Expected outcome

A concise briefing that correctly reports the 127 survey responses, proposed 25-course limit, estimated $48,000 cost, lack of an approved funding source, major open questions, and March 15 decision-memo deadline—without claiming that the pilot was approved.

### Verification checklist

- [ ] Copilot distinguishes 214 people surveyed from 127 responses.
- [ ] The Fall 2027 pilot, 25-course limit, and selection method are labeled proposed or unapproved.
- [ ] The three cost components total $48,000.
- [ ] “Endorsed continued planning” is not restated as “approved the pilot.”
- [ ] The absence of student input and an assessment plan is visible.
- [ ] Each major point can be traced to a named source section.

> **Skill insight:** Asking for status labels and source locations makes a summary easier to audit.

---

## Exercise 3 — Improve (10 minutes)

### Goal

Improve an internal message for clarity, tone, accessibility, and actionability while preserving its facts.

### Source: rough message

Copy this text into a new section headed `Exercise 3 — Source`, then select only the message itself.

```text
Subject: Your course files need work

Everyone needs to fix their documents ASAP because our spot check found lots of accessibility problems, and this cannot continue. You are receiving this because your unit is part of the spring review. You need to locate 20 frequently used course documents and run the Microsoft Word accessibility checker before March 12, 2027, after which you should remediate whatever it flags and put the new versions in the shared Course Materials folder. Please utilize the remediation checklist on the CTL intranet. If you don't understand it, office hours are Tuesdays from 2:00 to 3:00 p.m. Eastern on Microsoft Teams. Questions can go to accessibility@example.edu. Managers will get a completion summary, so make sure you do it.
```

### Do the task

**Minutes 0–2 — Diagnose:** Before using Copilot, note two problems with the message. Consider tone, sentence length, jargon, scannability, or unclear responsibility.

**Minutes 2–6 — Rewrite:** With the message selected, choose **Rewrite**, **Edit with Copilot**, or use the Copilot pane. Submit:

```text
Rewrite the selected message for faculty and staff participating in the spring accessibility review.

Requirements:
- use a respectful, supportive, non-blaming tone;
- lead with the purpose and reader benefit;
- use plain language, active voice, and short paragraphs;
- present the required actions as a numbered list;
- include a descriptive subject line;
- preserve exactly the quantity (20 documents), deadline (March 12, 2027), folder name, office-hours schedule, platform, reporting note, and contact address; and
- do not add policy claims, consequences, links, dates, or support services that are not in the source.

Keep the message between 140 and 190 words.
```

**Minutes 6–8 — Critique:** Do not accept the rewrite immediately. Ask:

```text
Review your proposed rewrite as an editor. List any source fact that changed, any action whose owner is unclear, any jargon that remains, and any sentence that may sound punitive. Do not revise yet.
```

**Minutes 8–10 — Decide and verify:** Accept only useful changes or manually combine the best parts. Keep the rough source for comparison.

### Expected outcome

A respectful, scannable message with a clear purpose, a numbered three-step workflow, an exact deadline, support information, and a transparent note that managers receive a completion summary.

### Verification checklist

- [ ] The revision still requires 20 documents by March 12, 2027.
- [ ] `Course Materials` remains the exact folder name.
- [ ] Office hours remain Tuesdays, 2:00–3:00 p.m. Eastern, on Teams.
- [ ] The reporting note is transparent but not threatening.
- [ ] “Utilize” and “remediate” are replaced or explained in plainer language.
- [ ] The message has no invented consequences, resources, or links.
- [ ] You can explain why each retained change helps the audience.

> **Skill insight:** “Improve” is not the same as “make shorter.” Define the audience, facts that must not change, and the qualities that matter.

---

## Exercise 4 — Transform (7 minutes)

### Goal

Turn informal meeting notes into a structured status update without converting uncertainty into commitments.

### Source: meeting notes

Copy these notes into a new section headed `Exercise 4 — Source`.

```text
Digital Accessibility Sprint planning notes — November 3, 2026

Present: Maya Chen (CTL), Luis Romero (Digital Accessibility), Priya Shah (Library), Jordan Bell (IT)

- Room 204 is on hold. Priya will confirm the room by Nov. 10.
- Jordan tested the standard Teams link. Captions worked. He will send the final meeting link after the room is confirmed; no date was agreed.
- Luis has a draft remediation checklist. Maya and Luis will review it together on Nov. 12.
- Registration form still needs an owner. The group wants it live by Jan. 15, 2027, but the date is a target, not an approved deadline.
- Capacity discussed: 40 total participants, including online participants. Need to confirm whether the room and Teams setup can support that mix.
- Decision: participants will bring one non-confidential course document.
- Open question: Can teaching assistants register directly, or must a faculty member nominate them?
- Risk: If the Teams link is placed on a public page, unregistered people may join. Jordan suggested sending it only to registered participants; the group did not decide.
- Next meeting: Nov. 17 at 11:00 a.m. Eastern on Teams.
```

### Do the task

**Minutes 0–1 — Prepare:** Select the meeting notes and open Copilot.

**Minutes 1–4 — Transform:** Submit:

```text
Transform the selected meeting notes into a concise project status update.

Use these sections:
1. Confirmed decisions
2. Action items table with columns Action, Owner, Due date, and Status
3. Risks
4. Open questions
5. Next meeting

Use only the notes. Keep targets distinct from approved deadlines. If an owner or due date is missing, write “Unassigned” or “Not agreed”; do not infer one. Preserve names, dates, capacity, and the distinction between suggestions and decisions.
```

**Minutes 4–7 — Verify and format:** Compare every row with the notes. Use Word heading and table styles if Copilot did not apply them.

### Expected outcome

A readable status update with one confirmed participation decision, an action table, two unresolved logistical/security matters, an unassigned registration form, and the correct next meeting.

### Verification checklist

- [ ] Priya owns room confirmation due November 10, 2026.
- [ ] Maya and Luis jointly review the checklist on November 12, 2026.
- [ ] Jordan's Teams-link task has no invented due date.
- [ ] January 15, 2027 is labeled a target, not an approved deadline.
- [ ] The registration-form owner is `Unassigned`.
- [ ] The 40-person capacity and Teams-link approach are not shown as settled decisions.
- [ ] The next meeting is November 17 at 11:00 a.m. Eastern on Teams.

> **Skill insight:** Structured output can look authoritative even when the source is uncertain. Preserve uncertainty explicitly.

---

## Exercise 5 — Evaluate (10 minutes)

### Goal

Use Copilot as a critical reviewer, then perform the final human check before a document is shared.

### Source: communications checklist

Return to your announcement from Exercise 1. Copy the checklist below beneath it under the heading `Exercise 5 — Review criteria`.

```text
UNIVERSITY EVENT COMMUNICATIONS CHECKLIST

The announcement must:
1. name the intended audience and state why the event matters to them;
2. include the exact event title, date, time with time zone, delivery format, physical location, hosts, capacity, cost, registration deadline, and accommodation contact;
3. describe at least two concrete learning activities;
4. say what participants should bring and protect confidential information;
5. include a clear registration action without inventing a link;
6. use descriptive headings and a scannable list for event details;
7. use plain, inclusive language and avoid guarantees or unsupported claims;
8. keep the main announcement between 220 and 260 words; and
9. clearly mark any information that still requires confirmation.
```

### Do the task

**Minutes 0–4 — Audit:** Open Copilot in chat-only mode first. Submit:

```text
Evaluate the Exercise 1 announcement against all nine items in the University Event Communications Checklist.

Create a table with the columns Requirement, Rating, Evidence from draft, and Recommended fix. Use only these ratings: Met, Partially met, Missing, or Cannot verify. Quote or point to brief evidence; do not give credit without evidence. Do not revise the announcement yet.

After the table, list every factual claim in the announcement that should be checked against the event brief. Flag any claim that the brief does not support.
```

**Minutes 4–7 — Challenge:** Check whether the audit itself is accurate. Then submit:

```text
Now act as a skeptical university communications reviewer. Identify the three highest-risk problems that could cause confusion, exclude a reader, expose confidential information, or misstate a commitment. Explain each risk in one sentence. If there are fewer than three supported problems, say so rather than inventing one.
```

**Minutes 7–9 — Revise:** Ask for a revision only after reviewing the audit.

```text
Propose a revised announcement that addresses only the verified gaps in the audit. Preserve every fact from the event brief. Keep [CONFIRM: registration link] visible, do not invent information, and keep the announcement between 220 and 260 words. Show the revision as a draft for my approval rather than treating it as final.
```

**Minutes 9–10 — Human sign-off:** Perform the checks below. Do not share or publish the announcement during the lab.

### Expected outcome

An evidence-based audit, a prioritized risk review, and a revised announcement that meets the checklist while keeping missing information visible.

### Verification checklist

- [ ] Every rating cites evidence or accurately says the evidence is absent.
- [ ] The audit does not award credit merely because the wording sounds plausible.
- [ ] All dates, numbers, locations, names, and commitments match the original brief.
- [ ] The registration link remains a confirmation placeholder.
- [ ] The revision includes no student or employee personal information.
- [ ] Headings and lists are meaningful and accessible, not merely decorative.
- [ ] A human document owner would know what remains unresolved before publication.

### Final human approval gate

Before using any AI-assisted university document, ask:

1. **Accuracy:** Can I trace every consequential claim to an authoritative source?
2. **Authority:** Am I authorized to make every promise or decision stated here?
3. **Privacy:** Is the content appropriate for this system, audience, and sharing setting?
4. **Fairness and accessibility:** Could the wording or format exclude, stereotype, or disadvantage anyone?
5. **Accountability:** Who will approve, maintain, and correct this document?

If any answer is unclear, pause and resolve it before sharing.

> **Skill insight:** Copilot can help find omissions, but it can also miss them. Evaluation needs explicit criteria, source checking, and accountable human approval.

---

## Wrap-up and resources

### One-minute reflection

Write down:

- one Word task where Copilot could save you time;
- one type of information you should not place in a prompt without approval; and
- one verification step you will always keep human-led.

### What good practice looks like

| Skill | Strong habit |
|---|---|
| Create | Constrain the draft with audience, source, format, and “do not invent.” |
| Understand | Separate evidence, recommendations, decisions, and unknowns. |
| Improve | State what may change and which facts must remain exact. |
| Transform | Preserve owners, dates, statuses, and uncertainty. |
| Evaluate | Audit against criteria, verify against sources, and require human approval. |

### Official Microsoft resources

- [Welcome to Copilot in Word](https://support.microsoft.com/en-us/word/welcome-to-copilot-in-word.)
- [Draft and add content with Copilot in Word](https://support.microsoft.com/en-us/word/copilot/draft-and-add-content-with-copilot-in-word)
- [What information does Copilot use to answer my prompt?](https://support.microsoft.com/en-us/microsoft-365-copilot/what-information-does-copilot-use-to-answer-my-prompt)
- [Data, Privacy, and Security for Microsoft Copilot](https://learn.microsoft.com/en-us/microsoft-365-copilot/microsoft-365-copilot-privacy)

## Facilitator notes (optional)

- Test Copilot access, terminology, and feature availability in the institution's tenant before the session.
- Keep the five exercises to their stated times; setup should be completed before the clock starts.
- Encourage participants to compare outputs. Variation is expected and is useful for discussion.
- If Copilot is unavailable, pair participants or have them annotate what a strong output should contain using the verification checklist.
- Do not ask participants to demonstrate with real student or employee records.
- Close by reinforcing that fluent prompting is only one skill; source judgment, privacy, accessibility, and verification are equally important.

## License

This lab contains fictional training materials. Before publishing it in a repository, add the license your institution prefers (for example, [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) for openly licensed instructional material).
