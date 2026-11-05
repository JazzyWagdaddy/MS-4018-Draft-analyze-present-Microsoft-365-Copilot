# Excel in Higher Education

Imagine you are a student success analyst at **Lakeside University**, a fictional institution. Your responsibility is to help faculty and staff understand how students use academic support services and identify patterns that can improve planning, staffing, and student communication.

In this hands-on lab, you will use Copilot in Excel to explore an aggregated, fictional dataset about two student support services: **Academic Advising** and **Tutoring**. You will start by reviewing the data and identifying key measures. Next, you will analyze monthly demand, compare service use, and forecast future appointments. You will then use the Analyst agent to investigate the workbook and prepare a concise set of insights for university leaders.

## What you will practice

By the end of this lab, you will be able to:

- Summarize a higher-education dataset and identify important measures.
- Create charts that show student support trends over time.
- Compare the use of two campus services.
- Forecast future service demand with Copilot in Excel and Python.
- Explore workbook data with the Analyst agent.
- Turn analysis into practical insights for faculty, staff, and university leaders.
- Review AI-generated analysis before using it to make decisions.

> **Important:** Use only fictional, de-identified, or appropriately aggregated data in this lab. Do not enter student names, student identification numbers, grades, disability information, financial information, advising notes, personnel information, research data, or other protected university information unless your institution's policies explicitly allow it.

## Before you begin

To complete the full lab, you need:

- Microsoft Excel with Copilot.
- Access to OneDrive or SharePoint.
- Access to the Analyst agent, if it is available under your institution's Microsoft 365 license and configuration.
- The fictional sample workbook described below.

Copilot features and interface labels may vary by license, application version, and university configuration. If a feature is unavailable, review the prompt and discuss the expected result with your facilitator.

## Sample file

Download the [Lakeside University Student Support Trends workbook](https://raw.githubusercontent.com/JazzyWagdaddy/MS-4018-Draft-analyze-present-Microsoft-365-Copilot/master/Instructions/Labs/Media/Lakeside%20University%20Student%20Support%20Trends.xlsx), and save it to your OneDrive folder before beginning.

The workbook should contain aggregated monthly data with these columns:

| Column | Description |
| --- | --- |
| Month | Month represented by the row |
| Academic Advising Appointments | Number of completed academic advising appointments |
| Tutoring Appointments | Number of completed tutoring appointments |
| Total Support Appointments | Combined number of advising and tutoring appointments |
| Advising No-Show Rate | Percentage of scheduled advising appointments recorded as no-shows |
| Tutoring No-Show Rate | Percentage of scheduled tutoring appointments recorded as no-shows |
| Average Advising Wait Time (days) | Average number of days between scheduling and an advising appointment |
| Average Tutoring Wait Time (days) | Average number of days between scheduling and a tutoring appointment |

All data used in the workbook should be fictional and aggregated. The workbook should not contain personally identifiable student information.

---

## Exercise 1 — Explore the data

To make useful recommendations, you must first understand what the workbook contains and which measures may matter to student success planning.

1. Open **Lakeside University Student Support Trends.xlsx** from OneDrive.
2. Select the **Copilot** icon in Excel.
3. Confirm that **Allow editing** is selected, if that option is displayed.
4. Enter and submit the following prompt:

   ```text
   Summarize this dataset and provide an overview of the key student support metrics.
   Identify important patterns in appointment volume, no-show rates, and wait times.
   Use only the information in this workbook, and clearly label any interpretation
   that is not directly supported by the data.
   ```

5. Review Copilot's response. It may create a new worksheet containing an executive-style summary of important findings, patterns, interpretations, and possible next steps.
6. Submit this follow-up prompt:

   ```text
   Create a new sheet with a table showing the key patterns in the data. Include the metric, the observed pattern,
   the months affected, and why the pattern may matter to university planning. Do not claim that the data proves a cause.
   ```

7. Review the table that Copilot creates.

### Check your work

Confirm that the response:

- Uses only measures that appear in the workbook.
- Distinguishes observed patterns from possible explanations.
- Does not identify or make claims about individual students.
- Includes appointment volume, no-show rates, and wait times.
- Uses language appropriate for faculty, staff, and university leaders.

---

## Exercise 2 — Identify service-demand trends

Student support leaders need to understand how demand changes during the academic year so they can plan staffing, appointment availability, and student communication.

1. Keep the Copilot pane open.
2. Enter and submit the following prompt:

   ```text
   Create a new sheet with a line chart of Total Support Appointments over the months.
   Add a clear chart title and label the axes.
   Below the chart, summarize the three most important changes in demand shown by the data.
   ```

3. Review the chart and Copilot's summary.
4. Consider the following questions:

   - Which months have the highest and lowest appointment volume?
   - Are changes gradual, seasonal, or concentrated in a few months?
   - Does the chart support the written summary?
   - Would an academic calendar or additional data be needed before explaining why the changes occurred?

> **Reminder:** A pattern in the workbook does not automatically establish its cause. Avoid assuming that registration, exams, financial aid deadlines, staffing, or another campus event caused a change unless the workbook includes evidence supporting that conclusion.

---

## Exercise 3 — Compare student support services

University leaders may need to compare Academic Advising and Tutoring to understand how students use each service and where operational planning may differ.

1. In the Copilot pane, enter and submit the following prompt:

   ```text
   Create a new sheet with a clustered bar chart comparing Academic Advising Appointments
   and Tutoring Appointments for each month. Use a descriptive title,
   clearly identify both services, and keep the chart readable for a university leadership audience.
   ```

2. Review the chart that Copilot creates.  Pretty awesome!
3. Ask Copilot to compare service use during a defined academic period:

   ```text
   Summarize the total Academic Advising Appointments and Tutoring Appointments during the fall term
   months included in this workbook. Before calculating, state which months you are treating as the fall term.
   If the workbook does not define the fall term, ask me to confirm the months instead of assuming.
   ```

4. If Copilot asks you to define the fall term, choose any of the months specified and click **Submit**.
5. Review the comparison.
6. Submit this follow-up prompt:

   ```text
   Compare the two services using appointment volume, no-show rate, and average wait time.
   Present the result in a table. For each conclusion, identify the workbook measure that supports it.
   Do not rank service quality or staff performance.
   ```

### Check your work

Confirm that Copilot:

- Used a clearly defined set of months.
- Calculated totals from the correct columns.
- Compared the services without treating different measures as interchangeable.
- Avoided unsupported judgments about students, faculty, or staff.
- Did not interpret demand alone as proof that one service is more effective.

---

## Exercise 4 — Forecast demand with Python

Copilot in Excel with Python can help you run a statistical forecast without writing the code yourself. In this exercise, you will forecast future service demand based on the historical monthly patterns in the workbook.

1. In the Copilot pane, submit the following prompt:

   ```text
   Predict next quarter's Academic Advising Appointments and Tutoring Appointments using the
   most appropriate forecasting method supported by the historical data. Include the forecast,
   a chart, the method used, and model diagnostics.
   Explain important limitations, including the number of historical observations
   and any seasonal pattern the model cannot reliably establish.
   ```

2. Review the generated Python code, forecast worksheet, chart, and model diagnostics.  Note this may take a few moments for Copilot to process your prompt and generate a response.
3. Check whether Copilot explains:

   - Which forecasting method it selected.
   - Why the method is appropriate for the available data.
   - How many historical periods were used.
   - The predicted values for each service.
   - The uncertainty or limitations of the forecast.

4. Select **Done** to confirm the changes, and then save the workbook because you will use the updated file in the next exercise.
5. Close Excel.

### Responsible-use checkpoint

A forecast is an estimate, not a commitment or guaranteed outcome. University leaders should consider academic-calendar events, program changes, staffing, service eligibility, communication campaigns, and other contextual information before using the forecast for operational decisions.

---

## Exercise 5 — Explore the data with the Analyst agent

The Analyst agent provides a chat-based way to investigate patterns across files before developing or revising a workbook.

1. Open Copilot Chat, and then select the **Analyst** agent from the left navigation.
3. Select the **+** icon and attach **Lakeside University Student Support Trends.xlsx** from OneDrive.
4. Enter and submit the following prompt:

   ```text
   Compare Academic Advising and Tutoring across the year using appointment volume,
   no-show rate, and average wait time. Identify the strongest supported patterns,
   explain which measures support each finding, and distinguish observations from
   possible interpretations. Do not evaluate individual employee performance or
   infer outcomes for individual students.
   ```

5. Review the response and compare it with the analysis created in Excel.
6. Ask the following follow-up question:

   ```text
   Which conclusions are supported directly by the workbook, which conclusions require
   additional university context, and what additional aggregated data would be useful
   before making a staffing or service-planning decision?
   ```

### Compare the experiences

Consider:

- Which tool made it easier to create or modify workbook content?
- Which tool made it easier to ask follow-up analytical questions?
- Did both tools identify the same major patterns?
- Did either tool make an assumption that was not supported by the workbook?
- Which findings would need validation by a student success, institutional research, or service-area leader?

---

## Exercise 6 — Generate and communicate insights

Your final task is to turn the analysis into a concise briefing for a university audience.

1. In the Analyst agent, submit the following prompt:

   ```text
   Provide the top five insights from the Lakeside University Student Support Trends data for a student success leadership team.

   For each insight, include:
   - The finding
   - The supporting metric or pattern
   - Why it may matter for planning
   - A recommended question or next step

   Use only aggregated information from the workbook. Do not claim that a relationship is causal unless the data establishes causation.
   Label unsupported details as "Additional information needed."
   ```

2. Review the five insights.
3. Ask Copilot to adapt the results for one additional campus audience. Choose one option:

   **Option A — Faculty and staff update**

   ```text
   Turn the five insights into a faculty and staff update of no more than 200 words.
   Use plain language, explain why the analysis matters, and avoid technical forecasting terms unless they are defined.
   ```

   **Option B — University leadership briefing**

   ```text
   Turn the five insights into an executive briefing for university leadership.
   Use a table with the columns Finding, Evidence, Planning implication, and Decision
   or follow-up needed. Keep the briefing concise and distinguish confirmed findings from recommendations.
   ```

   **Option C — Student success planning discussion**

   ```text
   Turn the five insights into a 20-minute discussion agenda for student success leaders.
   Include a time allocation, the evidence to review, and the decision or question for each agenda item. Mark time allocations as suggested.
   ```

4. Review the adapted result for accuracy, tone, and audience fit.

### Final review checklist

Before using or sharing the analysis, confirm:

- **Accuracy:** Figures, totals, periods, and chart labels match the workbook.
- **Completeness:** The response addresses appointment volume, no-show rates, and wait times where requested.
- **Grounding:** Findings are supported by workbook data, and assumptions are clearly labeled.
- **Privacy:** The content contains only fictional or appropriately aggregated information.
- **Fairness:** The analysis does not make unsupported judgments about individual students or employees.
- **Audience:** Language and detail are appropriate for the intended campus audience.
- **Forecast limitations:** Predictions are presented as estimates and include meaningful limitations.
- **Human review:** A qualified university employee reviews the findings before they influence decisions.

---

## Wrap-up

You have practiced using Copilot in Excel to:

- Summarize a higher-education dataset.
- Identify important measures and patterns.
- Create line and bar charts.
- Compare student support services.
- Forecast future appointment demand with Python.
- Analyze the same workbook using the Analyst agent.
- Produce a concise set of insights for different university audiences.
- Apply privacy, grounding, fairness, and human-review checks to AI-assisted analysis.

The strongest analysis combines accurate workbook calculations with university context and responsible human judgment. Copilot can help identify patterns, create visualizations, and organize findings, but faculty and staff remain responsible for validating the data, interpreting the institutional context, and deciding what actions are appropriate.

## Optional extension activities

If time allows, try one or more of these prompts:

### Examine no-show patterns

```text
Create a chart comparing the Advising No-Show Rate and Tutoring No-Show Rate by month.
Identify the largest changes, but do not speculate about student motivation or causes that are not present in the workbook.
```

### Explore wait times

```text
Create a table comparing average wait times for Academic Advising and Tutoring.
Highlight months in which either service exceeded its annual median wait time, and explain how you calculated the median.
```

### Build a planning dashboard

```text
Create a new sheet with a simple student support planning dashboard that includes total appointments,
average no-show rates, average wait times, monthly demand trends, and the next-quarter forecast.
Use clear labels and include a note that the data is fictional and aggregated.
```

### Review the workbook for decision readiness

```text
Review the workbook for missing definitions, inconsistent units, incomplete periods, or other data-quality issues that could affect interpretation. Create a table with Issue, Evidence, Potential impact, and Recommended correction. Do not change the data yet.
```


