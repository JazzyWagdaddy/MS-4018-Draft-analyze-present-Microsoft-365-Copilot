# Microsoft 365 Copilot in Teams: Hands-On Lab for Higher Education

Learners use either a live or fictional Teams workspace to practice catching up on conversations, extracting decisions and action items, preparing for a meeting, drafting a follow-up message, and checking Copilot's work.

> [!IMPORTANT]
> If you have access to a Teams meeting that was recorded, complete Lab 6 first, then complete labs 1-5.

## Lab at a glance

| Item | Details |
| --- | --- |
| Audience | University faculty and staff who are new to Microsoft 365 Copilot |
| Duration | 45 minutes |
| Format | Individual hands-on lab or facilitator-led workshop |
| Experience needed | Basic familiarity with Microsoft Teams |
| Product | Microsoft Teams with the Copilot experience available in your university environment |
| Exercises | Six connected exercises |
| Outcome | Use Copilot to understand, organize, and act on Teams conversations and meeting information |

## What you will learn

By the end of this lab, you will be able to:

1. **Catch up on a Teams conversation** without reading every message individually.
2. **Extract decisions, questions, and action items** from a discussion.
3. **Prepare for a meeting** using supplied conversation context.
4. **Draft a follow-up message** for a defined campus audience.
5. **Review and refine Copilot's response** against the original source.

You will also practice a reusable prompting pattern:

- **Goal:** What do you want Copilot to do?
- **Context:** Why do you need the result, and who will use it?
- **Source:** Which conversation, notes, or pasted text should Copilot use?
- **Expectations:** What structure, tone, length, and constraints should it follow?
- **Follow-up:** What should Copilot verify, correct, or transform next?

## Before you begin — 4 minutes

1. Open Microsoft Teams using your university account.
2. Open the Copilot experience available in your Teams environment.
3. Start a new Copilot conversation when the interface allows it.
4. Keep this lab open in another browser tab or window.
5. Use only the fictional content included in this lab.

Copilot features and entry points may differ by license, application version, and university configuration. If you cannot reference a Teams chat, channel, meeting, or recap directly, paste the fictional source material from this lab into the Copilot experience available to you.

> **Privacy reminder:** Do not enter student records, personnel information, research data, health information, financial information, or other protected or regulated content unless your university's policies and approved practices allow it.

## The scenario

You work at **Lakeside University**, a fictional institution. A cross-campus working group is planning a four-week **Student Connection Pilot** intended to help students find the right academic and support resources earlier in the semester.

The working group has been collaborating in Teams. You were added after the conversation began and need to understand the discussion, prepare for the next meeting, and communicate the next steps.

Use the same fictional source material throughout the lab so each exercise builds on the previous one.

## Fictional Teams conversation

> [!Note]
> Since Teams environments can vary, we are providing a sample conversation that all learners can use.
>
> If you would like to use a real conversation located in your Teams environment, please go ahead and do so!
> 

Copy the following conversation when an exercise asks you to provide the source:

```text
STUDENT CONNECTION PILOT — FICTIONAL TEAMS CONVERSATION

Monday, 9:05 a.m. — Maya, Student Success:
We need a small pilot that helps students understand where to go for academic advising,
tutoring, financial wellness education, and general student-support questions.
The pilot should run for four weeks.

Monday, 9:18 a.m. — Daniel, Academic Advising:
Advising can provide a short “Start Here” guide. We need to avoid language that suggests every question belongs with an academic advisor.

Monday, 9:32 a.m. — Priya, Tutoring Services:
Tutoring can offer two 30-minute online orientation sessions during the first week. The dates and facilitators are not confirmed.

Monday, 10:04 a.m. — Elena, Communications:
I can draft a student announcement after the group confirms the audience, launch date, and call to action. We should use plain
language and keep the message short.

Monday, 11:20 a.m. — Marcus, Student Affairs:
Proposed audience: first-year undergraduate students in the College of Arts and Sciences. I suggest a four-week pilot beginning in October,
but the exact start date still needs approval.

Tuesday, 8:47 a.m. — Maya, Student Success:
For measurement, we can track visits to the Start Here guide, attendance at the tutoring orientations, and a short optional feedback form.
We should not claim that these measures prove an improvement in retention or academic performance.

Tuesday, 9:15 a.m. — Daniel, Academic Advising:
Agreed. Decision: keep the pilot limited to first-year students in the College of Arts and Sciences.
Open question: who owns the Start Here guide after the pilot?

Tuesday, 9:41 a.m. — Priya, Tutoring Services:
Action for me: propose two orientation times and identify facilitators by Friday.

Tuesday, 10:10 a.m. — Elena, Communications:
Action for me: prepare a draft announcement after I receive the approved start date and final resource link.
Who will approve the student-facing message?

Tuesday, 10:36 a.m. — Marcus, Student Affairs:
I will ask the associate dean to confirm the launch date and message approver. I will report back by Friday.

Tuesday, 11:02 a.m. — Maya, Student Success:
For our next meeting, we need to settle the Start Here guide owner, review the proposed orientation times,
confirm the launch date and message approval process, and agree on the feedback-form owner.
```

---

## Exercise 1: Catch up on a Teams conversation — 7 minutes

### Your task

Use Copilot to turn the fictional Teams conversation into a useful catch-up summary.

### Step 1: Start with a broad request

Paste the fictional Teams conversation into Copilot, then run:

```text
Summarize this Teams conversation.
```

### Step 2: Inspect the result

Ask yourself:

- Did Copilot identify the purpose of the Student Connection Pilot?
- Did it preserve the four-week duration and intended student audience?
- Did it distinguish confirmed decisions from suggestions?
- Did it include the unresolved questions?
- Did it clearly identify who agreed to do what?

### Step 3: Use a stronger catch-up prompt

Run:

```text
Using only the fictional Teams conversation provided above, create a catch-up summary for a university staff member who has
just joined the Student Connection Pilot working group.

Organize the response into:
1. Purpose and scope
2. Confirmed decisions
3. Proposed ideas that are not yet approved
4. Open questions
5. Action items with owner and stated deadline

Keep confirmed information separate from proposals. If a detail is missing, write "Not confirmed" instead of inventing it.
```

### Compare the responses

Identify at least two ways the second prompt improved the result. Look for clearer status labels, better organization, more precise ownership, and fewer unsupported assumptions.

### Checkpoint

You have completed this exercise when the summary lets a new working-group member understand the conversation without confusing decisions, proposals, and open questions.

**Skill unlocked:** Catch up on a Teams discussion with a purpose-built summary.

---

## Exercise 2: Extract decisions and action items — 8 minutes

### Your task

Use Copilot to create a structured record of what the working group decided and what still needs attention.

### Step 1: Build a decision log

Continue in the same Copilot conversation and run:

```text
Create a decision log from the Teams conversation.

Use a table with these columns:
- Topic
- Status: Confirmed decision, proposal, open question, or action item
- Details
- Owner
- Deadline
- Evidence from the conversation

Use only information stated in the conversation. Use "Not assigned" or "Not confirmed" when appropriate.
```

### Step 2: Check the classifications

Confirm that Copilot treats these items correctly:

- The pilot is limited to first-year undergraduate students in the College of Arts and Sciences.
- An October start is proposed, but the exact date is not approved.
- Priya agreed to propose two orientation times and identify facilitators by Friday.
- Marcus agreed to seek confirmation of the launch date and message approver by Friday.
- Ownership of the Start Here guide and feedback form remains unresolved.
- Elena's announcement depends on an approved start date and final resource link.

### Step 3: Request an action-only view

Run:

```text
Now create a separate action tracker containing only work that someone explicitly agreed to complete.

Use these columns:
- Action
- Owner
- Deadline
- Dependency
- Current status based on the conversation

Do not assign owners to unresolved questions. After the table, list any work that needs an owner.
```

### Mini-challenge

Ask Copilot to identify dependencies between the action items:

```text
Show the action-item dependencies as an ordered sequence. Explain which tasks can begin now and which tasks are
waiting for another decision or deliverable.
```

### Checkpoint

You have completed this exercise when you have a decision log and an action tracker that preserve owners, deadlines, dependencies, and unresolved ownership.

**Skill unlocked:** Convert a Teams discussion into decisions and accountable next steps.

---

## Exercise 3: Prepare for the next meeting — 8 minutes

### Your task

Use the conversation to prepare a focused working-group meeting.

### Step 1: Draft an agenda

Run:

```text
Create a 25-minute agenda for the next Student Connection Pilot working-group meeting.

Use only the Teams conversation as the source. The meeting must address:
- Start Here guide ownership
- Proposed tutoring orientation times and facilitators
- Launch-date confirmation
- Student-message approval process
- Feedback-form ownership

For each agenda item, include:
- Suggested time allocation
- Discussion objective
- Decision or output needed
- Person who should be prepared to provide information, when supported by the conversation

Label every time allocation as a suggested allocation. Do not invent meeting attendees, policies, dates, or owners.
```

### Step 2: Check the agenda

Review whether the agenda:

- Fits within 25 minutes.
- Covers all five topics identified for the next meeting.
- Uses decisions and outputs rather than vague discussion labels.
- Avoids assigning unresolved work to a person.
- Makes the proposed nature of the time allocations clear.

### Step 3: Create a personal preparation list

Assume you are helping Maya facilitate the meeting. Run:

```text
Based on the conversation and proposed agenda, create a preparation checklist for the meeting facilitator.

Organize it into:
- Before the meeting
- During the meeting
- Immediately after the meeting

Separate source-supported tasks from suggested facilitation practices. Do not state that Maya accepted work that
she did not explicitly accept in the conversation.
```

### Mini-challenge

Ask Copilot to generate five questions the facilitator can use to move unresolved topics toward a decision. Require each question to name the open issue it addresses.

### Checkpoint

You have completed this exercise when the meeting agenda is time-bounded, decision-focused, and traceable to the conversation.

**Skill unlocked:** Turn Teams context into a focused meeting plan.

---

## Exercise 4: Draft a follow-up Teams message — 8 minutes

### Your task

Use Copilot to draft a concise message that the facilitator could post to the working group after the meeting.

For this exercise, assume the following **fictional meeting outcomes**:

```text
FICTIONAL MEETING OUTCOMES

- Daniel will own the Start Here guide during the four-week pilot.
- Priya proposed Tuesday at 3:00 p.m. and Thursday at noon for the two online tutoring orientations.
Facilitators are still to be confirmed.
- The associate dean approved October 6 as the pilot start date.
- The associate dean will approve the student-facing message.
- Maya will create the optional feedback form.
- The final resource link is still pending.
- Elena will draft the student announcement after the final resource link is available.
```

### Step 1: Draft the message

Paste the fictional meeting outcomes into the same Copilot conversation, then run:

```text
Draft a Teams message for the Student Connection Pilot working group using the fictional meeting outcomes.

The message should:
- Thank the group without sounding overly formal
- Summarize the confirmed decisions
- List action items with owners
- Clearly identify the remaining unresolved items
- State the approved pilot start date
- Keep the message under 220 words
- Use plain, professional language appropriate for university faculty and staff

Use only the meeting outcomes and earlier conversation. Do not invent deadlines or claim that the final resource
link or facilitators are confirmed.
```

### Step 2: Evaluate the draft

Check whether the message:

- Clearly distinguishes decisions from remaining gaps.
- Preserves the approved October 6 start date.
- Identifies Daniel, Maya, and Elena's responsibilities accurately.
- Does not imply that tutoring facilitators are confirmed.
- Does not imply that Elena can finish the announcement before receiving the resource link.
- Is short enough to post in Teams.

### Step 3: Adapt it for another audience

Run:

```text
Rewrite the message as a brief update for the associate dean.

Keep it under 140 words. Emphasize readiness, remaining dependencies, and any item that could delay
the student announcement. Use a concise, decision-focused tone.
```

### Checkpoint

You have completed this exercise when you have two versions grounded in the same information but adapted for different audiences and purposes.

**Skill unlocked:** Draft and adapt follow-up communication from Teams context.

---

## Exercise 5: Review and refine Copilot's work — 7 minutes

### Your task

Ask Copilot to evaluate its own outputs against the source before you rely on or share them.

### Step 1: Request a source check

Run:

```text
Review the catch-up summary, decision log, action tracker, meeting agenda,
and follow-up messages created in this conversation.

Compare them with the original fictional Teams conversation and the fictional meeting outcomes.

Create a review table with:
- Claim or task
- Source-supported, partially supported, unsupported, or missing
- Supporting text or source location
- Correction needed

Check especially for:
- Incorrect owners
- Invented deadlines
- Proposals presented as decisions
- Open questions presented as resolved
- Missing dependencies
- Changes to the approved start date
- Claims that facilitators or the resource link are confirmed

Do not revise the outputs yet.
```

### Step 2: Inspect the review

Check whether Copilot evaluated each important fact separately. If it grouped several facts into one row, ask it to split them into individual claims.

### Step 3: Correct only the weak areas

Run:

```text
Correct every item marked partially supported, unsupported, or missing.

Preserve accurate content and the requested format of each output.
Do not add facts, owners, or deadlines that are not in the source material.

After the corrected outputs, add a short "What changed" section
that identifies each correction and the source requirement it addresses.
```

### Final quality check

Before using a Copilot-generated response, verify:

- **Accuracy:** Names, dates, owners, and decisions match the source.
- **Status:** Decisions, proposals, open questions, and completed work remain distinct.
- **Completeness:** The response addresses every requested topic.
- **Grounding:** Unsupported details are not presented as facts.
- **Audience:** The wording fits the intended university audience.
- **Format:** Tables, lists, lengths, and headings follow the prompt.
- **Privacy:** The content is appropriate to enter, use, and share under university policy.

### Checkpoint

You have completed this exercise when Copilot has identified weaknesses before editing, corrected only the weak areas, and explained what changed.

**Skill unlocked:** Verify Teams-based Copilot output before acting on it.

---

## Exercise 6 - Gain insights from an existing Teams meeting

### Step 1 - Recap a Meeting.
1. Find an existing Teams meeting that was recorded.  If you do not have this available, please conclude this lab and start with Lab #1.
2. Open up Copilot within the Teams meeting that was recorded.
3. Click on the  **Recap the meeting** sample prompt and examine the results.
4. Experiment with the follow-up prompts that Copilot suggests.

### Step 2 - Send a follow-up.
1. Click on or enter this prompt, then hit send.
```
Draft a follow-up message for participants
```
2. Review the options, and have Copilot create the message in Outlook or Teams, but do not send it.  For example:
```
use option 1 and open in outlook
```
3. Experiment with the follow-up prompts that Copilot suggests.
   
### Step 3 - List action items from a meeting.
1. Click on or enter this prompt, then hit send.
```
   List action items from the meeting
   ```
2. Customize this prompt:
```
   Write a 3-bullet update about this meeting I can send to my manager
```
3. Experiment with the follow-up prompts that Copilot suggests.
 
### Step 4 - Find action items from any meeting assign to you.
1. Open a new Copilot Chat window within Teams.
2. Enter this prompt:
```
Do I have any action items or follow-ups from any meetings this week?
List them by due date and then draft a follow-up response in Chat.
```
3. Experiment with the follow-up prompts that Copilot suggests.

### Step 5 - Prepare for an upcoming meeting.
1. Open a new Copilot Chat window within Teams Calendar and enter this prompt:
```
when is my next meeting with /
```
2. Select a coworker that you often meet with.
3. Select an upcoming meeting and then click on ##`Ask Copilot##.  Enter this prompt:
```
What do I need to do in order to be prepared for this meeting?
```
4. Review the results and then experiment with the follow-up prompts that Copilot suggests.

---
## End of Lab
