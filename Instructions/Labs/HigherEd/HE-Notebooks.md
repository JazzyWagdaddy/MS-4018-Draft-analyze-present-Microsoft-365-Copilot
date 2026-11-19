# Microsoft Copilot Notebooks/Workspaces for Higher Education

A hands-on lab for faculty, academic leaders, and university staff. You will learn the complete core workflow: create a notebook, add trusted references, ask grounded questions, shape responses with instructions, create useful outputs, and understand sharing, limits, and the extra care that student and institutional data requires.

## Lab at a glance

> Microsoft states the Copilot app still calls them **Notebooks** (OneNote is unchanged), and "workspace" is the new project-hub redesign rolling out mid-2026. This lab uses both terms.

| Item | Details |
|---|---|
| Audience | Faculty, deans and department chairs, advisors, student-success staff, institutional research, and campus IT/teaching-and-learning teams who are new to Copilot Notebooks |
| Duration | 30 minutes, plus optional self-paced higher-ed challenges |
| Outcome | A working notebook that answers questions and creates content from a curated set of campus references |

## What you will learn

By the end of the lab, you will be able to:

- Explain what a Copilot Notebook is and when it helps in academic and administrative work.
- Create and name a notebook.
- Add, inspect, and remove references.
- Ask questions that are grounded in notebook content.
- Improve results with follow-up prompts and notebook instructions.
- Recognize sharing and permission implications, including FERPA, research data, and shared-governance considerations.

## The mental model

A Copilot Notebook is a scoped AI workspace. You choose the references, and Copilot uses that curated context to answer questions, summarize, analyze, and draft content.

Think of the workflow as:

```
Create a notebook
        ↓
Add trusted references
        ↓
Ask grounded questions
        ↓
Refine with follow-up prompts and instructions
        ↓
Create and collaborate on useful outputs
        ↓
Return to the workspace each term and pick up right where you left off
```

On campus, a notebook works best when it maps to one initiative, course, committee charge, or review cycle: a course redesign, an accreditation standard, a program review, a grant proposal, or a student-success pilot.

## Before you begin

### Required

- A Microsoft account (your institutional account) that can access Copilot Notebooks.
- A SharePoint or OneDrive service plan to create notebooks.
- Access to the Microsoft Copilot app from your desktop.
- Two sample files:
  - Instructions/Labs/Media/Contoso University - First-Year Student Voice Findings.docx
  - **Contoso University – First-Year Student Voice Findings**

Download both files and save them to your OneDrive folder before you continue. Both files describe a fictional university and contain no real student data.

### Feature availability

Copilot Notebook capabilities vary by account, license (including faculty, staff, and student license types), institutional policy, platform, and rollout status. If a button used in an optional exercise is unavailable, read the exercise and continue. The core create → reference → prompt workflow should remain the focus.

### Responsible-use reminder

- Use content you are permitted to access, and follow your institution's AI and data-classification policies.
- **Do not add student education records or personally identifiable student information** (names, IDs, grades, advising notes, accommodation records) to a lab notebook. In real work, confirm with your registrar or data steward how FERPA applies before using student-level data.
- Do not add human-subjects research data unless your IRB protocol and data-use agreements allow it.
- Check generated answers against their cited or linked references. Do not treat an AI-generated answer as automatically correct.
- Obtain consent before recording or transcribing people, including students in class sessions, office hours, or focus groups.
- Review file permissions before sharing a notebook.

---

# Lab Time!

## Task 1: Create your first Notebook

### Scenario

You have just joined the fictional **Contoso University** First-Year Success working group as an associate dean. The Provost's Office is preparing to launch a pilot that pairs early-alert outreach with peer mentoring for first-year students. You need to understand the initiative quickly and prepare a concise readiness brief for the Provost's Council.

### Steps

1. Ensure that you have downloaded the required files, then sign in to the Microsoft Copilot app on your desktop with your institutional account.
2. In the left navigation, open **Notebooks**. If you do not see it, check the app launcher.
3. Select **All notebooks**, and then select **New notebook**.
4. Name the Notebook by copying and pasting this text: `Contoso First-Year Success Lab`
5. Notice the options to add content or previous chats to this Notebook. You'll work with these later.
6. When ready, click **Create**.
7. Keep the notebook open for the rest of the lab.

### Check your work

You should see a new notebook with an area for references and a Copilot message box.

### What you learned

A notebook is most useful when it is organized around a defined initiative, course, committee charge, decision, or learning goal, not as an unbounded collection of unrelated files. A notebook per course section, per accreditation standard, or per pilot is a good starting rule.

## Task 2: Add references/content

> In some UI versions, resources that you add are called **REFERENCES** and in other versions they are called **CONTENT**. Both are the same.

### Steps

1. In your notebook, on the right-hand side of the screen, select the plus symbol next to **In Contoso First-Year Success Lab** and then choose **Add content**. Your UI may say **Add references**.
2. Choose **Upload** and upload these files:
   - Contoso University – First-Year Success Pilot Proposal
   - Contoso University – First-Year Student Voice Findings
3. Confirm that both files appear in the content/references section of your Notebook.

Throughout this lab, you craft prompts that reference these files.

### Explore other reference/content methods

Open **Add references** or **Add content** again and review the additional options available to you:

- **Work Content** – launches the Object Picker, where you can reference work files, meetings, emails, SharePoint sites, and Teams chats (for example, a committee's SharePoint site or a department Teams channel).
- **Upload** – upload files from your local or network drives.
- **Links** – add links to websites as content (for example, a public accreditor standard or your institution's published AI guidance).
- **OneDrive** – provide a link to a OneDrive folder or individual files from your Most Recently Used (MRU) list.

Do not add confidential, student-identifiable, or unrelated material just to complete the exercise.

### Key concept: the reference boundary

The references define the notebook's working context. Copilot does not automatically treat every file, email, chat, LMS course, or website you can access as part of this notebook. Adding a specific file directly is the safest way to ensure it is included in the notebook's grounding set.

### Check your work

Your notebook should show two references.

## Task 3: Ask grounded questions

Paste and run the following prompt in the Chat window, then review the response in detail.

```
Using only the references in this notebook, summarize the pilot in five bullets.
Include the target students, goal, proposed timing, success measures, and the most
important student concern. After each bullet, identify which reference supports it.
```

Because Copilot uses only the documents in the Notebook as its source, ask the following next, then review the response in detail:

```
Which requested details are missing, unclear, or conflicting across the references?
Do not guess. Create a table with the columns Detail, What the references say,
Gap or conflict, and Recommended follow-up question.
```

Finally, ask:

```
What evidence in the notebook supports the recommendation to prioritize evening and
mobile access to peer mentors? Quote only short phrases and explain how each phrase
supports the recommendation.
```

### Observe

Look for these behaviors:

- The answer should focus on the two added references.
- Copilot should distinguish stated facts from gaps.
- The two documents intentionally disagree on pilot timing, cohort size, and the primary success measure. A strong response surfaces those conflicts instead of picking one silently.
- A strong response should avoid inventing owners, dates, budgets, enrollment figures, or retention rates.
- Reference indicators should let you inspect the supporting content.

### Prompt pattern to remember

Use this reusable formula:

> Using **[scope]**, perform **[task]**. Include **[required fields]**. Use **[format]**. Apply **[quality rule]**.

Higher-ed example:

> Using only this notebook, compare the proposed pilot design with what students said in the focus groups. Use a table with Alignment, Tension, and Open question columns. Do not fill missing details with assumptions.

## Task 4: Set notebook instructions

Notebook instructions let you define response preferences that apply throughout the Notebook and do not apply to anything outside it.

### Steps

1. Open the notebook's **More options** menu. Its location varies by UI version: where you see the name of the project, click the down arrow, or click the three dots near the green shield icon.
2. Select **Instructions**.
3. Enter:

```
Write for an associate dean who is new to this initiative and will brief the
Provost's Council. Use plain language, short sections, and concise tables. Separate
confirmed facts from assumptions and open questions. Never invent a date, owner,
budget, enrollment figure, or student outcome metric that is not present in the
references. Never include information that could identify an individual student.
```

4. Save the instructions.
5. Re-run this shorter prompt:

```
Give me a pilot-readiness assessment.
```

### Compare

Did the result now:

- Use a clearer, governance-ready structure?
- Separate facts from open questions?
- Avoid unsupported specifics?
- Reflect the intended audience and tone?

### What you learned

Use notebook instructions for durable behavior within the Notebook, such as audience (students, faculty senate, cabinet, accreditor), tone, formatting, terminology, and rules. Use the individual prompt for the task-specific request. These instructions are specific to this notebook and do not apply to any other notebook or to chats outside it.

## Task 5: Create a useful deliverable

Start a new chat (the plus button near the top), then paste and run the following prompt, and respond to any follow-up questions that Copilot may have:

```
Create a readiness brief titled "Contoso First-Year Success Pilot — Readiness Brief
for the Provost's Council." Include:
1. A two-sentence executive summary.
2. A table of confirmed scope, target students, timing, and success measures.
3. The top three student needs, with supporting evidence.
4. A Risks and Open Questions table with columns Item, Why it matters, Evidence
   available, and Next action. Include student privacy and data-sharing questions.
5. Three decisions the Council should make next.
Use only this notebook's references. Label any unsupported information as
"Not found in references."
```

Review the response Copilot provides. This prompt may take a few minutes to run.

### Check your work

Your brief should contain all five requested sections and clearly expose information gaps (such as the missing budget and unconfirmed pilot owner) instead of hiding them.

## Task 6: Share your Notebook

### Sharing inspection

1. Close any windows from previous tasks and then open a new chat (this keeps the screen less cluttered).
2. Select **Share** or **Add Members**, depending on your UI version.
3. Review the invite experience and only send an invitation to an approved lab partner or colleague. Do not share this broadly across the institution, to student groups, or to distribution lists. It's only a lab!

Before sharing, think about the following:

- Do I have permission to share every referenced file?
- Should the people I invite have access to this content? Do they have a legitimate educational interest in any student-related information it contains?
- Do they already have access to this content today?
- Could sharing the notebook grant or request access to linked content, such as a committee SharePoint site or a department Teams channel?
- Is edit access appropriate, or should most collaborators only view?
- Are any collaborators external (guest faculty, consultants, partner institutions, accreditation reviewers), and does institutional policy allow it?
- Does the notebook contain pre-decisional material (draft budgets, personnel matters, unreleased program changes) that should stay with a smaller group until shared-governance review is complete?

## Task 7: Add previous chats to Notebooks

You may have started brainstorming in Copilot Chat before this lab, for example drafting talking points for a department meeting. Now it's time to bring that work into your Notebook so it becomes part of your content.

A good reason to add a Copilot Chat conversation to a Copilot Notebook is to turn useful discussions into persistent project context that you can keep building on across the term. This lets you preserve and build on your ideas rather than starting from scratch.

> **Simple takeaway:** Chat = conversation. Notebook = ongoing workspace and context.

1. On the upper left-hand side of your screen, click the button to expand your **Sidebar**.
2. Look toward the bottom left of the Sidebar and notice your **Chat history**.
3. Hover over (don't click on) any previous chat, and then click the three-dot ellipsis.
4. Choose **Move to Notebook**, then select the **Contoso First-Year Success Lab** notebook you've been working on.
5. Open the **Contoso First-Year Success Lab** notebook and scroll down to your chat history. The chat you just added now appears and is part of this Notebook.

---

# Optional self-paced challenges for higher education

Each challenge uses the same create → reference → prompt workflow. Use only non-sensitive, permitted content.

| Challenge | Suggested references | Starter prompt |
|---|---|---|
| Course redesign | Your syllabus, course learning outcomes, a rubric, and an anonymized end-of-term course evaluation summary | Using only this notebook, map each assignment to the course learning outcomes in a table. Flag outcomes that no assignment assesses. |
| Accreditation self-study | The accreditor's published standard, last self-study section, and current assessment report | Using only this notebook, draft an evidence inventory for this standard with columns Criterion, Evidence we have, Gap, and Owner to confirm. Do not invent evidence. |
| Program review | Program review template, enrollment and completion summary (aggregate only), and external reviewer report | Summarize the reviewer's recommendations and draft a response plan with columns Recommendation, Proposed action, Resources needed, and Timeline (Not found in references if absent). |
| Grant proposal | Funder's call for proposals, your draft narrative, and the institution's boilerplate | Compare the draft narrative with the review criteria. List each criterion, where the draft addresses it, and what is missing. |
| Research literature review | Open-access papers you are permitted to use | Using only these papers, build a table of research question, method, sample, key finding, and limitation for each paper. |
| Committee or senate work | Committee charge, prior minutes, and the policy draft under review | Summarize the open issues in the policy draft and list the questions the committee still needs to resolve, citing the minutes for each. |

## Facilitator notes

- The two sample documents are fictional and deliberately inconsistent on timing (Spring 2027 vs. Fall 2027), cohort size (400 vs. 250 students), and the primary success measure (persistence vs. GPA). The budget and the accountable pilot owner are intentionally missing. These gaps drive the Task 3 and Task 5 discussions.
- For campuses with student-licensed users, consider a parallel version where students build a notebook for a course project and practice citing sources and checking AI output against them.
- Close with a short discussion: Which of your current projects would benefit from a notebook, and what would you never add to one?
