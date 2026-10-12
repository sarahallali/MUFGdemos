# MUFG Outlook Copilot Demo – From Inbox to Impact

**Scenario:** You're **Thomas Brennan**, Relationship Manager at MUFG EMEA. It's **Friday 9 October 2026** and you're back after two days at a client event. Your inbox is full of emails about **Project Meridian**: Fabrikam has asked MUFG to lead an €800m loan, five colleagues have sent updates, Tokyo Head Office wants a status report, and your boss, Haruka, wants a draft reply today.

**Goal:** catch up fast, reply well, and follow up without dropping anything.

**Timing (60 minutes):** story so far 5 · Part 1 12 · Part 2 15 · Part 3 13 · five-minute challenge 7 · wrap-up 8

## Demo setup

**Use:** [Meridian_Email_Pack.docx](../files/Meridian_Email_Pack.docx) – 18 fictional emails in 8 conversations.

Load the emails into your demo mailbox **at least one day before**, so Copilot can find them by search:

- **Quick way:** for each conversation, send yourself one email containing the whole conversation. Copy it from section 4 of the Email Pack ("Thread digests") and use the subject line shown above it.
- **Realistic way:** send each email from a second demo account to your mailbox, in order (E1 to E17), with the exact subject lines – including "RE:" and "FW:" – so Outlook groups them into conversations.

Then move the emails into a folder called **Project Meridian**.

> **NOTE:** All names and addresses are fictional (`.example`). Never send these emails to real external addresses. The new Outlook is recommended; Summarise, Draft with Copilot and Coaching also work in classic Outlook.

**The conversations you'll use**

| Email | Subject | From |
|---|---|---|
| E1 | Heads-up: Fabrikam – possible acquisition financing | Thomas |
| E2–E4 | Strictly confidential – Project Contoso: request for financing proposal | Yuki Hayashi (Fabrikam CFO), Thomas, Markus Brandt (Fabrikam Treasurer) |
| E5 | Launching Project Meridian – Fabrikam acquisition financing | Haruka |
| E6–E12 | Project Meridian – workstream updates | Elena, Karim, Grace, Sander, Priya, Thomas |
| E13–E14 | Fabrikam – request for status update (E14 is Haruka's "FW:") | Tokyo Head Office, forwarded by Haruka |
| E15–E16 | Project Meridian – diary and logistics | Olivia, Thomas |
| E17 | Notes – Fabrikam meeting this morning (rough) | Olivia |
| E18 (optional) | Project Meridian – Executive Committee decision | Haruka |

## Copilot in Outlook

### Part 1 – Catch up

**1. Summarise a long conversation**

[Email: Project Meridian – workstream updates] Open the conversation and select **Summarise** at the top.

What to look for: Credit Risk prefers keeping €200m because Industrials is close to its limit; Compliance lists open client checks; Operations gives account-opening lead times; the analyst sees leverage of about 2.7x; Thomas argues for €300m.

**2. Summarise across all your emails**

[Copilot Chat in Outlook]

```text
Summarise the emails about Project Meridian and Fabrikam from the last week.
Group the summary by workstream – credit risk, compliance, operations, financial analysis and Tokyo Head Office –
and for each one list the decisions made, the open questions and who owns the next step.
```

**3. Find what needs a reply**

```text
Which Project Meridian emails need a reply from me, and by when? Put the most urgent first.
```

What to look for: Haruka's request for a draft reply to Tokyo comes first. Tokyo needs it by 09:00 Tokyo time on Tuesday 13 October – that's 01:00 in London, so it must go on Monday. Next come Markus Brandt's meeting proposal and Karim's request for client documents (due Friday 9 October).

> **Say this out loud:** Copilot may also list something that has already been answered further down a thread. Open the thread before you act.

**4. Check the facts**

```text
Compare the financing amounts mentioned in the Fabrikam emails and in the internal Project Meridian emails.
Are there any differences? Show which email each figure comes from.
```

What to look for: "c. €750m" in Thomas's heads-up after a phone call (E1, Friday 2 October) against **€800m** in the client's formal written request (E2, Monday 5 October).

> **Say this out loud:** the written request wins – and you confirm the amount with the client. Copilot finds the difference; you decide which figure is right.

### Part 2 – Reply

**5. Reply to the client**

[Email: E4 from Markus Brandt] Select **Reply all** (so Hayashi-san stays in copy), then **Draft with Copilot**:

```text
Thank Mr Brandt and Hayashi-san for their request and confirm we are delighted to support.
Confirm the meeting on Tuesday 13 October at 10:00 London time and propose an agenda:
Fabrikam's strategic rationale, financing structure and timeline, hedging and cash management,
sustainability-linked features, and next steps.
Ask for Contoso's 2025 audited accounts and the group structure chart.
Use a formal, warm tone. Do not commit to any amount, hold size or terms.
```

Then change the tone to **Formal** and the length to **Short**, and select **Coaching by Copilot** to get feedback on the draft.

> **Check before you share:** it's an external email – check the recipients, and make sure there are no internal details and no commitments.

**6. Draft the update for Tokyo**

[Email: E14 – FW: Fabrikam – request for status update] Select **Reply**, then **Draft with Copilot**:

```text
Draft a concise status update for Yamamoto-san, General Manager at Tokyo Head Office, for Haruka to review.
Use these headings: Opportunity, Proposed MUFG role, Amount and structure, Key risks under review, Timeline, Next update.
Formal and respectful tone, no more than 150 words.
State that MUFG's final hold is under review and will be confirmed after the Executive Committee on 12 November.
```

Refine it:

```text
Make it more concise and use bullet points under each heading.
```

> **Say this out loud:** Haruka asked for no hold size yet – the draft respects that.

**7. Reply to the project group**

[Email: E12 – the latest message in "Project Meridian – workstream updates"] Select **Reply all**, then **Draft with Copilot**:

```text
Thank everyone for their updates. Confirm that inputs for the Executive Briefing are due on Friday 23 October,
list each requested input with its owner in a short table, and invite questions before the client meeting on 13 October.
Collaborative, concise tone.
```

What to look for: credit view – Elena; client checks and documents – Karim; onboarding lead times – Grace; financial model (16 October) – Sander; portfolio impact and hold options (22 October) – Priya.

### Part 3 – Prepare and follow up

**8. Prepare for the client meeting**

[Copilot Chat in Outlook]

```text
I'm meeting Fabrikam on Tuesday 13 October. Based on my emails, prepare a one-page brief:
Fabrikam's objectives, what we know about the transaction, questions to ask the client,
internal positions I should be aware of, and topics I should not discuss externally.
```

What to look for under "not to discuss": internal ratings, sector limits, the €200m versus €300m debate, and any hold size.

**9. Follow up after the meeting** (it's now Tuesday 13 October)

[Email: E17 – Notes – Fabrikam meeting this morning (rough)] Select **Forward**, address it to Mr Brandt and Hayashi-san (it's a demo – no need to send it), then **Draft with Copilot**:

```text
Using Olivia's notes below, draft a follow-up email to Mr Brandt and Hayashi-san that thanks them for today's meeting,
summarises what we discussed, lists the agreed next steps with owners and dates, and lists the open questions.
Where the notes do not show an owner or a date, mark it [to confirm].
Formal tone. Do not include any internal comments.
```

What to look for: "[to confirm]" next to the hedging call and the early-December signing question.

> **Check before you share:** delete Olivia's original notes below your draft before sending. They include internal remarks such as "still think we can push for €300m".

**10. Draft an agenda** (you're now Olivia, Haruka's assistant)

[Copilot Chat in Outlook]

```text
Draft a 90-minute agenda for the Project Meridian credit and compliance review on Tuesday 27 October,
based on the workstream emails. Include the time for each item and its owner.
```

**11. Optional – plan your week**

```text
Which emails in my inbox need action from me this week? Group them by urgency and suggest a one-line response for each.
```

## Five-minute challenge

Haruka stops by: "What's still open on Project Meridian?"

```text
List every open action and unanswered question across the Project Meridian and Fabrikam emails.
Show a table with the item, owner, due date and source email. Flag anything with no owner or no due date.
```

## Try it on your own work

Participants replace the [brackets] and paste this into Copilot Chat:

```text
Act as my Microsoft 365 Copilot coach. I work as a [role] in [department] at a bank in EMEA.
Suggest five practical ways I can use Copilot in Outlook to manage my inbox, write clearer emails and prepare for meetings.
For each one, give me a ready-to-use prompt, what I should check before sending, and one follow-up prompt to improve the result.
Start with beginner-friendly ideas, then add two more advanced ones. Ask me questions if you need more context.
```

## Key takeaway

Copilot in Outlook turns a full inbox into a clear picture – what happened, what's open, who owns it – and gives you good first drafts for every audience. You still check the facts and the recipients before anything is sent.

## Appendix: details built in on purpose

Please don't correct these – they create the teaching moments.

| What | Where | Why it's there |
|---|---|---|
| "c. €750m" versus €800m | E1 versus E2 | Check figures against the written source |
| Credit Risk wants €200m, Thomas wants €300m | E6, E11, E12 | Copilot summarises both views; people decide |
| "Don't commit to a hold size" | E14 | Drafts must follow the manager's instruction |
| Actions with no owner or date | E16 (Global Markets "TBC"), E17 (hedging call, early-December signing) | Spot gaps before they become problems |
| Internal remarks in the meeting notes | E17 | Internal comments must never reach the client |
