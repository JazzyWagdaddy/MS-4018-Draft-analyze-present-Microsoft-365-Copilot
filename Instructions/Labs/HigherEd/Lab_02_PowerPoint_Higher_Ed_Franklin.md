---
lab:
    title: 'Lab 2: Build a presentation from start to finish with Copilot in PowerPoint (Higher Education – Franklin University)'
    description: 'Microsoft 365 Copilot – Explore how Copilot in PowerPoint can help faculty, academic leaders, and staff build a governance-ready presentation from start to finish.'
    level: 'Lab 200'
    duration: '30'
    islab: true
    primarytopics:
        - Microsoft 365
        - Microsoft 365 Copilot
        - Higher Education
---

# Lab 2 – Build a presentation from start to finish with Copilot in PowerPoint

**Higher Education edition for Franklin University faculty and staff**

## Lab at a glance

| Item | Details |
|---|---|
| Audience | Franklin University faculty, program chairs, deans, academic and student-success staff, advisors, institutional research, and Center for Teaching and Learning / IT teams who present to councils, committees, and leadership |
| Duration | 30 minutes, plus optional self-paced challenges |
| Outcome | A polished, evidence-based presentation built from two campus documents, with speaker notes prepared for a skeptical leadership audience |
| Prerequisite | Lab 1, or basic familiarity with Microsoft 365 Copilot Chat |

## Scenario

Imagine you are an associate dean at the fictional **Contoso University**. Like many Franklin programs, Contoso serves a large share of students who work, commute, or study online, and the institution is trying to help more of them succeed in their first term.

The First-Year Success working group has proposed a one-year pilot that pairs early-alert outreach with peer mentoring. You have been asked to present the pilot to the **Provost's Council** next week. Your audience includes the Provost, academic deans, a Faculty Senate representative, and the **Vice President for Finance and Administration**, who expects evidence-based recommendations and a clear case for the investment.

You have two documents to draw from: the working group's pilot proposal and a separate student-voice report from Institutional Research. The two documents do not fully agree with each other, and neither one includes a final budget. Your goal is to produce a polished, data-informed presentation efficiently, without starting from scratch, and without letting Copilot fill the gaps with invented numbers.

By the end of this lab, you will plan a narrative with Idea Coach, create a presentation from two source files with specific output parameters, generate and refine speaker notes for a finance-minded leadership audience, use Copilot to explain a chart before you present it, and complete a final coaching pass that includes accuracy and accessibility.

## What you will learn

- Plan a presentation narrative before you build it.
- Write a creation prompt that sets slide count, sources, tone, and audience up front.
- Ground a deck in specific campus documents rather than general web content.
- Prepare speaker notes that anticipate hard questions from leadership and shared-governance bodies.
- Check charts and figures you did not write yourself before you present them.
- Review a deck for accuracy, unsupported claims, and accessibility.

## Before you begin

### Sample files

Throughout this lab, you craft prompts that reference these files. Download both files and save them to your OneDrive folder before you continue.

- **Contoso University – First-Year Success Pilot Proposal.docx**
- **Contoso University – First-Year Student Voice Findings.docx**

Both files describe a fictional university, all figures are illustrative, and they contain no real student data. They are the same files used in the Higher Education Copilot Notebooks lab, so you can reuse them if you completed that lab.

> [!NOTE]
> If either file hasn't synced to your OneDrive yet, wait a few minutes and refresh the file picker. You can start the planning step while you wait.

### Feature availability

Copilot in PowerPoint capabilities vary by license (faculty, staff, and student license types differ), institutional policy, platform, and rollout status. If a button or agent used in this lab is unavailable, read the exercise and continue. The core plan → create → refine → review workflow should remain the focus.

### Responsible-use reminder

- Use content you are permitted to access, and follow Franklin University's AI and data-classification guidance.
- **Do not add student education records or personally identifiable student information** (names, IDs, grades, advising notes, accommodation records) to a presentation prompt or deck. In real work, confirm with the registrar or data steward how FERPA applies before using student-level data.
- Do not use human-subjects research data unless your IRB protocol and data-use agreements allow it.
- Verify every figure, quotation, and claim on a slide against its source before you present it. You are accountable for what you present, not Copilot.
- Treat draft proposals, budgets, and personnel matters as pre-decisional. Share drafts only with the people who need them until shared-governance review is complete.

---

# Lab Time!

## Exercise 1 – Plan your narrative with Idea Coach

Before you open PowerPoint, use Idea Coach to define your narrative. A focused planning prompt now produces a stronger first draft and requires less revision later.

1. Open the Microsoft Copilot app by navigating to `https://m365.cloud.microsoft` and signing in with your Franklin account.
2. Select **Idea Coach** from the left navigation pane. If it doesn't appear, select **More agents**, then in the search bar type **Idea Coach**, select the agent, and select **Add** to add it.
3. In the **Message Idea Coach** box, enter the following prompt:

    ```
    I need to present a proposed First-Year Success pilot to a university Provost's
    Council. The pilot pairs faculty early alerts with advisor outreach and peer
    mentoring for first-year students, many of whom work, commute, or study online.
    The audience includes the Provost, academic deans, a Faculty Senate
    representative, and a Vice President for Finance and Administration who focuses
    on return on investment and evidence of student impact. Identify three to four
    key messages and suggest a narrative arc for an eight-slide presentation that
    ends with the decisions I need the Council to make.
    ```

4. Review the key messages and narrative structure Idea Coach returns. Keep this output visible so you can reference it when writing your creation prompt.

> [!NOTE]
> Idea Coach doesn't create the deck for you. Its strength lies in helping you develop your own ideas into actions. Continue to interact with Idea Coach until you find a good starting point. For example, ask: *"What objections should I expect from a Faculty Senate representative about faculty workload in an early-alert process?"*

### What you learned

Leadership audiences on campus rarely want a tour of a proposal. They want to know what problem it solves, what evidence supports it, what it costs, what the risks are, and what they are being asked to decide. Planning the arc first keeps the deck pointed at a decision.

## Exercise 2 – Create a presentation from multiple sources

With your narrative plan ready, create the presentation by referencing both source files. Specifying your output parameters in the prompt means Copilot builds to your requirements from the start.

1. Open a blank PowerPoint presentation from your browser by navigating to `https://powerpoint.cloud.microsoft/new`.
2. Select the **Copilot** icon in the bottom-right corner of the canvas.
3. Enter the following creation prompt:

    ```
    Create an 8-slide presentation for a university Provost's Council on the proposed
    Contoso University First-Year Success pilot. Use the Pilot Proposal document for
    the pilot design, target students, timing, success measures, and requested
    decisions. Use the Student Voice Findings document for student needs, survey
    results, and Institutional Research recommendations. Where the two documents
    disagree, show both positions on the slide instead of choosing one. Do not invent
    budget figures, owners, dates, or outcome data that are not in the documents;
    label missing information as "To be confirmed."
    Tone: academic leadership – clear, evidence-based, and respectful of shared
    governance.
    Audience: the Provost, deans, a Faculty Senate representative, and a VP for
    Finance and Administration who value brevity and a clear case for investment.
    End with a slide listing the decisions requested of the Council.
    ```

4. Attach **Contoso University – First-Year Success Pilot Proposal.docx** and **Contoso University – First-Year Student Voice Findings.docx** using **Add work content** (type `/` or select **+** → **Add work content**).
5. Once both documents are attached, send the prompt so that Copilot uses them as the primary sources for the task.
6. If Copilot asks clarifying questions, answer using the key messages from your Idea Coach session.
7. Review the generated slides.

### Check your work

A strong draft should:

- Surface the three conflicts between the documents: **launch timing** (Spring 2027 vs. Fall 2027 orientation), **cohort size** (400 vs. about 250 students), and **primary success measure** (fall-to-spring persistence vs. first-term GPA and credit completion).
- Show the student privacy concern: the proposal shares alert reasons with peer mentors, while students and Institutional Research ask that alert details not go to mentors without consent.
- Label the budget and pilot lead as **To be confirmed** rather than inventing them.

If any of these are missing or a figure looks invented, select the slide and ask Copilot to correct it, for example: *"Add the cohort-size disagreement between the two documents to this slide."*

## Exercise 3 – Generate and refine speaker notes

Generate notes for every slide at once, then refine the slides most likely to draw hard questions.

1. Enter the following prompt in the Copilot pane:

    ```
    Generate speaker notes for all slides in this presentation. Keep the speaker
    notes professional and concise, and suitable for a 10-minute presentation.
    ```

2. Navigate to the slide that covers success measures, investment, or the budget.
3. Enter the following prompt:

    ```
    Rewrite the speaker notes on this slide to sound confident and evidence-based. I'm
    presenting to a VP for Finance and Administration who will ask what the pilot
    costs and how we will know it worked. The budget has not been finalized, so do not
    invent figures. Help me acknowledge that gap honestly, explain how the success
    measures and comparison group will show impact, and anticipate two likely
    questions with short answers.
    ```

4. Display the speaker notes by using one of the following options:
    - In the status bar at the bottom, select **Notes**.
    - On the ribbon, select **View** → **Notes**.
5. Review the revised speaker notes that Copilot generated.
6. Navigate to the slide that covers the pilot design or the early-alert process and enter:

    ```
    Add two sentences to the speaker notes on this slide that address a Faculty Senate
    representative's likely concern about faculty workload in submitting early alerts
    in week 3 and week 6.
    ```

### What you learned

Speaker notes are where you prepare for the room. Telling Copilot who will push back, and on what, produces notes that help you respond rather than recite. Telling Copilot what it must not invent keeps you from walking into a council meeting with a number you cannot defend.

## Exercise 4 – Review a chart with an Explain prompt

Your deck synthesizes data from two source files, which means some charts or tables may include figures you didn't write yourself. Use Copilot to understand the data before you present it.

1. Navigate to a slide that contains a chart or table of the student survey results (commuting, working 15 or more hours per week, preferring evening or remote meetings, not visiting daytime drop-in centers).

    > [!NOTE]
    > If Copilot did not create a chart, ask: *"Add a slide with a chart of the four survey results from the Student Voice Findings document."* If a chart still isn't generated, use the table Copilot created; the Explain prompt works on tables too.

2. Enter the following prompt in the Copilot pane:

    ```
    Explain the content in this chart so I can more easily understand and discuss it
    as I present it to the Provost's Council. Tell me what the data shows, what it does
    not show, and any limitations of the survey I should mention.
    ```

3. Review Copilot's plain-language breakdown of what the chart shows, what the data means in context, and how it fits the narrative of the surrounding slide.
4. Compare the values on the slide with the **Survey item** table in the Student Voice Findings document. Confirm every percentage matches the source.

### Check your work

A strong explanation should note that the figures describe student **perceptions and circumstances**, not proof that the pilot will improve outcomes, and that the survey had a moderate (38%) response rate that may under-represent disengaged students. Those are exactly the caveats a careful council member will raise.

## Exercise 5 – Run a final coaching pass

Before you wrap up, ask Copilot to surface any remaining issues across the full deck.

1. In the Copilot pane, enter the following prompt:

    ```
    Give me improvement tips for this presentation, both overall and slide by slide.
    Focus on narrative coherence, clarity of the decisions I'm asking the Council to
    make, any claim or figure that is not supported by the two source documents, and
    any wording that could identify or stigmatize students. Also flag accessibility
    issues such as missing alt text, low-contrast text, or dense slides.
    ```

2. Review Copilot's response and apply any changes using the Copilot features you practiced in this lab.
3. Run the built-in accessibility check: on the ribbon, select **Review** → **Check Accessibility**, and resolve any errors. Accessible materials are an institutional expectation for anything shared with students, faculty, or the public.

### Check your work

Your finished deck should:

- Lead to a clear set of decisions for the Council.
- Show the conflicts between the two source documents rather than hiding them.
- Contain no invented budget, owner, date, or outcome figure.
- Contain no information that could identify an individual student.
- Have speaker notes ready for the finance and shared-governance questions.
- Pass the accessibility check, or have its remaining issues noted.

**End of Lab**

---

# Optional self-paced challenges for Franklin University

Each challenge uses the same plan → create → refine → review workflow. Use only non-sensitive, permitted content, and apply the same rule: tell Copilot what it must not invent.

| Challenge | Suggested source files | Starter creation prompt |
|---|---|---|
| Program review presentation | Your program review self-study and an aggregate (non-identifiable) enrollment and completion summary | Create a 10-slide presentation for the curriculum committee summarizing this program review. Include strengths, gaps, and three recommendations. Use only the attached files and label anything unsupported as "To be confirmed." |
| Accreditation or assessment update | Your assessment report and the accreditor's published standard | Create a 6-slide update for academic leadership showing how our evidence maps to this standard. Include one slide on gaps and next steps. Do not invent evidence. |
| Course or module redesign pitch | Your current syllabus, course outcomes, and an anonymized end-of-term evaluation summary | Create a 7-slide proposal to redesign this online course for working adult learners. Show the outcomes, the proposed changes, and how we will measure the impact. |
| New faculty or adjunct orientation | Faculty handbook sections, LMS guidance, and teaching-and-learning resources | Create a 12-slide orientation deck for new adjunct faculty teaching online. Use a welcoming, practical tone and end with a checklist for the first week of the term. |
| Board or advisory council update | An approved strategic plan summary and a published annual report | Create a 6-slide update for an industry advisory board. Use plain language for an external audience and include only information approved for external sharing. |
| Student-facing workshop | A study-skills or career-services handout you own | Create an 8-slide workshop presentation for adult learners balancing work, family, and school. Keep each slide to three short bullets and add speaker notes with one discussion question per slide. |

## Quick reference: the creation prompt formula

> Create a **[number]**-slide **[type]** presentation for **[audience]** on **[topic]**. Use **[file A]** for **[content]** and **[file B]** for **[content]**. Tone: **[tone]**. Audience: **[what they care about]**. **[Quality rule – for example, do not invent figures; label gaps as "To be confirmed."]** End with **[a call to action or decision]**.
