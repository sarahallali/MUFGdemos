# MUFG Word Copilot Demo – Draft Impactful Documents

**Scenario:** You're **Thomas Brennan**, Relationship Manager. It's **Monday 2 November 2026**. The Executive Committee paper on Project Meridian is due on Friday. Your draft is half-finished, and the inputs from Credit Risk, Compliance, Operations and Portfolio Management sit in separate documents. Last week's review agreed to recommend keeping **€250m** of the loan – but your draft still says €300m.

**Goal:** turn a messy draft and six source documents into a clear, accurate paper – and tailor it for Tokyo and for the client.

**Timing (60 minutes):** story so far 5 · Part 1 10 · Part 2 20 · Part 3 10 · five-minute challenge 7 · wrap-up 8

## Demo setup

**Use:**

- The paper you'll improve: [Meridian_Executive_Briefing_Draft.docx](../files/Meridian_Executive_Briefing_Draft.docx)
- Sources:
  - [Meridian_Review_Minutes.docx](../files/Meridian_Review_Minutes.docx) – what the 27 October review agreed
  - [Meridian_Credit_Risk_Assessment_Draft.docx](../files/Meridian_Credit_Risk_Assessment_Draft.docx) – Credit Risk's view
  - [Meridian_Portfolio_Summary_Q3.docx](../files/Meridian_Portfolio_Summary_Q3.docx) – the loan book and the three hold options
  - [Meridian_Compliance_Review_Note.docx](../files/Meridian_Compliance_Review_Note.docx) – open client checks
  - [Meridian_Operational_Readiness_Note.docx](../files/Meridian_Operational_Readiness_Note.docx) – account opening and payments
  - [Meridian_Client_Meeting_Notes.docx](../files/Meridian_Client_Meeting_Notes.docx) – notes from the 13 October client meeting
- To compare at the end: [Meridian_Executive_Briefing_Final.docx](../files/Meridian_Executive_Briefing_Final.docx) and [Meridian_Client_Briefing_Example.docx](../files/Meridian_Client_Briefing_Example.docx)

> **NOTE:** Put all the files in the same OneDrive folder and allow up to 10 minutes for them to sync.
> When a prompt shows **/File_Name**, type **/** in the Copilot box and pick that file from the list.
> Keep a clean copy of the draft – the demo changes it.

## Copilot in Word

### Part 1 – Understand the draft

Open `Meridian_Executive_Briefing_Draft.docx` and open the **Copilot** pane.

**1. Summarise it**

```text
Summarise this draft in five bullet points for Haruka Sato, Head of Corporate Banking.
```

**2. Find the gaps**

```text
Which sections of this briefing are incomplete, unsupported or inconsistent?
List each one and the information needed to complete it.
```

What to look for: no executive summary yet; placeholders in sections 7 and 9; a thin risks section; a €300m recommendation with no evidence behind it.

**3. Think like the reader**

```text
What questions is the Executive Committee likely to ask after reading this draft?
```

### Part 2 – Build it from several documents

**4. Check the recommendation**

```text
Compare this draft with /Meridian_Review_Minutes. Does the recommendation in the draft match
what was agreed at the review? List any differences.
```

What to look for: the draft says **€300m**; the review agreed to recommend **€250m** with conditions.

**5. Check the numbers**

```text
Compare the pro-forma leverage and EBITDA figures in /Meridian_Credit_Risk_Assessment_Draft with this draft.
Which figures differ, and which source is more recent?
```

What to look for: the credit memo shows **2.9x**, because it uses last year's earnings (€860m). The draft shows **2.7x**, based on the latest audited earnings (€930m). The minutes confirm the memo is being updated.

> **Say this out loud:** Copilot spots the difference. You check the source and decide which number is right.

**6. Write the missing portfolio section**

Delete the placeholder **[Priya to provide – hold scenarios]** in section 7. On the empty line, select the Copilot icon in the margin (or press **Alt + I**) and enter:

```text
Write the Portfolio impact section using /Meridian_Portfolio_Summary_Q3 and /Meridian_Review_Minutes.
Include a short table comparing the €200m, €250m and €300m hold options:
Industrials concentration including the high-probability pipeline, single-name limit usage,
and return on RWA including ancillary business.
End with one sentence explaining why €250m is recommended.
```

What to look for: 14.76% / 14.90% / **15.05% (breach)**; 78% / 88% / 98%; 3.03% / 3.20% / 3.00%.

**7. Write the compliance and operations section**

Delete the placeholder **[Karim / Grace to update]** in section 9 and enter:

```text
Write the Compliance, ESG and operational readiness section using /Meridian_Compliance_Review_Note
and /Meridian_Operational_Readiness_Note. Show the open items in a table with owner, expected date and status.
```

What to look for: confirmation of who ultimately owns one of the sellers (11 November); sanctions screening (6 November); the ESG report on the Dunkirk plant (13 November); UAE account set-up, 6–8 weeks.

**8. Write the executive summary**

Delete **[To be written]** in section 2 and enter:

```text
Write an executive summary of no more than 150 words: the opportunity, the recommendation,
the main risks and conditions, and the decision required from the Executive Committee on 12 November.
```

Then correct section 10 (Recommendation) to **€250m** – type it yourself, or ask Copilot to rewrite it using /Meridian_Review_Minutes.

### Part 3 – Polish and tailor

**9. Make it concise**

Select section 5, **Strategic rationale for MUFG**, and enter:

```text
Rewrite this section in a concise, factual executive tone. Remove promotional language. Maximum 120 words.
```

**10. Turn a list into a table**

Select the list in section 12, **Open questions**, and enter:

```text
Turn this list into a table with columns: Question, Owner, Due date, Status.
```

**11. Get honest feedback**

```text
Review this briefing as a demanding Executive Committee member. What is unclear, unsupported by evidence or missing?
Suggest specific improvements in order of importance.
```

**12. A version for Tokyo** (new blank document → Copilot)

```text
Using /Meridian_Executive_Briefing_Draft, write a one-page summary for Tokyo Head Office.
Formal tone, numbered headings: Purpose, Transaction, Recommendation, Conditions, Timeline.
Do not include internal debate or individual opinions.
```

**13. A version for the client** (new blank document → Copilot)

```text
Using /Meridian_Executive_Briefing_Draft and /Meridian_Client_Meeting_Notes, draft a client briefing for Fabrikam's CFO
describing MUFG's indicative financing approach: proposed structure, MUFG's role, the sustainability-linked option,
hedging and cash-management support, onboarding and timeline.
State clearly that it is indicative and non-binding, subject to credit approval, due diligence and documentation.
Do not include internal information such as hold-size discussions, internal ratings, limits or returns.
```

Compare the result with `Meridian_Client_Briefing_Example.docx`.

> **Check before you share:** anything that goes to a client is reviewed by the right people first – and contains nothing internal.

## Five-minute challenge

Haruka has five minutes between meetings.

```text
Summarise this briefing on one page: what we recommend, why, what could go wrong,
and what we need from the Executive Committee.
```

Optional, for colleagues across EMEA:

```text
Write a 100-word summary of this briefing in French for the Paris compliance colleagues.
```

Ask a fluent speaker to check any translation before using it.

## Try it on your own work

```text
Act as my Microsoft 365 Copilot coach. I work as a [role] in [department] at a bank in EMEA.
Suggest five ways I can use Copilot in Word for documents I write regularly. For each: a ready-to-use prompt,
the source files I should reference, a follow-up prompt to improve the draft, and what I must check before sharing.
Start simple, then add two advanced ideas. Ask me questions if you need more context.
```

## Key takeaway

Copilot in Word pulls content from several documents into one draft, spots inconsistencies, and rewrites the same message for different readers. The final check – and the signature – stay with you.

## Appendix: details built in on purpose

Please don't correct these in the source files – they create the teaching moments.

| What | Where | Why it's there |
|---|---|---|
| €300m recommendation versus the agreed €250m | Draft, section 10 / Review minutes | Copilot spots a conflict between documents |
| Leverage of 2.9x versus 2.7x | Credit risk memo, section 4 / Draft, section 6 | Old figures in one source |
| Placeholders | Draft, sections 2, 7 and 9 | Drafting from several sources |
| Wordy, promotional text | Draft, section 5 | Rewriting for an executive reader |
| Internal remarks | Client meeting notes, "Internal remarks – NOT for the client" | Nothing internal goes to the client |
