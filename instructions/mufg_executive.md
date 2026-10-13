# MUFG Executive Session – Explore Microsoft 365 Copilot (90 minutes)

**For:** executives and senior leaders at MUFG EMEA.

**Format:** virtual and trainer-led – slides plus live demos. Attendees can follow along in Copilot Chat, but don't have to.

**The story (30 seconds):** Haruka Sato is Head of Corporate Banking for EMEA (fictional). It's Monday morning and she's back from two days in Tokyo. On Thursday she asks the Executive Committee to approve Project Meridian: leading a €800m loan for Fabrikam, a long-standing client, and keeping €250m of it. Her inbox also holds a request from Tokyo, a town hall to prepare, a hiring approval and a cost overrun. Copilot gets her through the day.

## Demo setup

**Slides:** `MUFG Executive Session – Explore Microsoft 365 Copilot.pptx` – the MS-4021 course deck adapted for MUFG. It isn't stored in this repository – keep it with your session materials. Slide 6 stays hidden.

**Scenario:** [Meridian_Executive_Demo_Scenario.docx](../files/Meridian_Executive_Demo_Scenario.docx) – the story, the 15 prompts below, a set-up checklist, and Haruka's calendar and 14 inbox emails to load into your demo account **one or two days before** the session.

**Files** (from the [files](../files) folder – upload them to the demo account's OneDrive):

| Demo | Files |
|---|---|
| 07:30 Catch me up | Haruka's inbox (from the scenario document) |
| 09:00 Prepare me | Haruka's inbox and calendar, plus the files below |
| 11:00 Help me decide | [Meridian_Executive_Briefing_Final.docx](../files/Meridian_Executive_Briefing_Final.docx), [Meridian_Review_Minutes.docx](../files/Meridian_Review_Minutes.docx) |
| 14:00 Show me the numbers | [Meridian_Fabrikam_Analysis.xlsx](../files/Meridian_Fabrikam_Analysis.xlsx), [Meridian_Portfolio_Q3_2026.xlsx](../files/Meridian_Portfolio_Q3_2026.xlsx) |
| 16:00 Help me say it | [Meridian_Executive_Briefing_Final.docx](../files/Meridian_Executive_Briefing_Final.docx), [Meridian_Portfolio_Summary_Q3.docx](../files/Meridian_Portfolio_Summary_Q3.docx). Back-ups: [Meridian_ExCo_Presentation_Example.pptx](../files/Meridian_ExCo_Presentation_Example.pptx), [Meridian_ExCo_Questions.docx](../files/Meridian_ExCo_Questions.docx) |
| 17:30 Keep me ahead | All of the above |

> **NOTE:** This session only uses Copilot Chat, Copilot in Outlook, Word, Excel and PowerPoint, and the Analyst and Researcher agents.
> Run the Analyst and Researcher prompts once before the session (they take a few minutes) and keep the results open.
> Keep a screenshot of every demo. If a live demo stalls, switch to the screenshot within 15 seconds and keep talking.
> If you also run the Outlook demo, use a different demo account (or remove its emails first), so its inbox doesn't mix with Haruka's.

## Run of show

| Time | Slide | What happens |
|---|---|---|
| 0:00 | 1 | Welcome. The promise: three prompts you can use tomorrow morning |
| 0:03 | 2 | Agenda, and the two moments to join in |
| 0:05 | 3–5 | What Copilot is, where it works, and why it knows your work (Work IQ) |
| 0:13 | 7 | Trust – the slide leaders care about most (6 minutes) |
| 0:19 | 8 | Chat question: "If AI could take one task off your week, what would it be?" |
| 0:24 | 9–11 | How to ask: Goal, Context, Source, Expectations – the board-paper example |
| 0:32 | 12 | Follow along: the Monday briefing prompt |
| 0:40 | 13 | Save and share your best prompts |
| 0:43 | 14 | **Live demos: an executive's day (35 minutes)** |
| 1:18 | 15 | Next steps: AI Skills Navigator, and "Which prompt will you try first?" |
| 1:24 | – | Questions |

Slide 6 is hidden – skip it. The speaker notes in the deck carry the same timings and talking points.

## What to say (slides 1–13)

- **Slide 1:** 90 minutes, questions in the chat at any time. Everything in the demos is fictional – no real client or MUFG data.
- **Slides 3–5:** Copilot doesn't replace your judgement; it's a first-draft engine and a research assistant that already knows your work. A public chatbot writes *a* status report – Copilot writes *your* status report from *your* week. It only uses content you can already open.
- **Slide 7:** data protected at rest and in transit; your permissions are respected; your data isn't used to train the foundation models. Leadership message: **AI drafts, people decide** – and people stay accountable. Route detailed legal or compliance questions to the account team.
- **Slide 8:** read five or six chat answers aloud and group them (email, meeting preparation, long papers, numbers, presentations). Spend more demo time where the chat points.
- **Slides 10–11:** brief Copilot the way you'd brief your chief of staff: what you want, why, from which sources, and in what format. Read "Summarise this" aloud, then the full board-paper prompt – let the room hear the difference.
- **Slide 12:** paste the prompt into the meeting chat, run it on screen and give attendees three minutes to try it:

```text
Act as my chief of staff. Using my emails and calendar from the past week, prepare my briefing for the week ahead.
List the decisions I made, the decisions still waiting for me, and the three things I should focus on.
Keep it under 150 words, use bullet points, and suggest one item I could delegate.
```

  Debrief in the chat: Was it useful? How would you improve it? Would you use it every Monday morning? Point out that no file was attached – Copilot used their own email and calendar, within their permissions.
- **Slide 13:** show where to find and save prompts (aka.ms/CopilotGallery) and save the Monday briefing prompt. Leaders who share their best prompts set the tone for everyone else.

## Live demos – an executive's day (slide 14)

Open with: *"Meet Haruka Sato, Head of Corporate Banking for EMEA. She's fictional – her day isn't. Let's follow it."*

For each moment: say the need first, read the prompt aloud as you type it, then look at the result together – including what you'd check. The same 15 prompts are in the scenario document.

### 07:30 – Catch me up (Outlook · 7 min)

*Haruka is back from two days in Tokyo. Fourteen emails are waiting.*

**1.** Outlook → Copilot Chat

```text
I'm back from two days in Tokyo. Go through my inbox and tell me what needs my attention: decisions waiting for me, deadlines, and anything I can delegate. Most urgent first, in a short table.
```

Look for: Olivia’s three decisions (today) · Grace’s OK (Tuesday) · the Tokyo input, due Wednesday at 18:00 Tokyo time – 09:00 in London, so really Tuesday · the town hall messages (Wednesday) · the hires and the risk plan (Friday). The newsletter and the training reminder can wait.

**2.** Outlook → email “Your week at a glance – w/c 9 November” → Reply → Draft with Copilot

```text
Reply to Olivia: please accept the dinner with Erik Lindqvist on 18 November, decline the Amsterdam speaking invitation with thanks and offer Thomas Brennan as a speaker instead, and tell her I will approve the two hires by email. Short and friendly.
```

Look for: Three clear answers, ready to send after a quick read.

**3.** Outlook → email “Q4 business review – EMEA Corporate Banking input by Wednesday 11 November” → Reply → Draft with Copilot, then Coaching by Copilot

```text
Thank Yamamoto-san for his request and for his hospitality in Tokyo. Confirm that the one-page input will reach him before 18:00 Tokyo time on Wednesday 11 November, and that the Project Meridian decision will follow after the Executive Committee on 12 November. Formal and respectful, under 100 words.
```

Look for: A formal reply that commits to the deadline – not to the decision. Coaching by Copilot comments on tone and clarity.

> **Say this out loud:** "Thirty minutes of reading becomes three – and nothing goes out until I've read it."

### 09:00 – Prepare me (Copilot Chat · 6 min)

*Her 1:1 with Elena Rossi, Credit Risk, starts in 15 minutes.*

**4.** Microsoft 365 Copilot Chat

```text
Prepare me for my 09:00 meeting with Elena Rossi about the Fabrikam loan. From my emails, calendar and files, brief me in half a page: what has changed since the review on 27 October, her position, the open risks, and two questions I should ask her.
```

Look for: The final credit memo shows leverage of 2.7x, not 2.9x · Credit Risk supports keeping €250m, with conditions · Thomas still prefers €300m · one compliance check is done, two are still open.

**5.** Same chat

```text
What should I avoid committing to before the Executive Committee decides?
```

Look for: A hold above €250m, the early-December signing date the client asked about, and any terms.

> **Say this out loud:** "This is the briefing a chief of staff would write – from content I already have access to."

### 11:00 – Help me decide (Word + Copilot Chat · 8 min)

*The Executive Committee paper is in front of her. She has ten minutes.*

**6.** Word → Meridian_Executive_Briefing_Final.docx → Copilot pane (type / to pick a file)

```text
Summarise this decision paper for me. I chair the Executive Committee on Thursday and have ten minutes to prepare. Use this document and /Meridian_Review_Minutes. Give me the decision being asked, the three main risks and three questions I should ask, in under 200 words.
```

Look for: The decision: lead the €800m loan and keep €250m, subject to three conditions – open compliance checks, an ESG review of the Dunkirk plant, and the hedging strategy.

**7.** Same Copilot pane

```text
Act as a sceptical Executive Committee member. What are the three weakest points in this paper, and what evidence would address each one?
```

Look for: The loan alone earns 2.01%, below the 2.5% hurdle, so the hedging business matters · the ESG report arrives after the Committee · a 20% fall in earnings would break the leverage covenant.

**8.** Microsoft 365 Copilot Chat

```text
Compare /Meridian_Executive_Briefing_Final with my latest emails from Karim Benali, Elena Rossi and Thomas Brennan. What has changed since the paper was written, and what should I update before Thursday?
```

Look for: The sanctions screening finished on Friday afternoon with no matches – one open item is now closed. The ownership confirmation (11 November) and the Dunkirk ESG report (13 November) are still open, and the client has asked about signing in early December.

> **Say this out loud:** "Copilot reads the paper in seconds and spots what has moved on. The decision stays with me."

### 14:00 – Show me the numbers (Excel + Analyst agent · 7 min)

*She wants the answer and the evidence – not the spreadsheet.*

**9.** Excel → Meridian_Fabrikam_Analysis.xlsx → sheet Hold_Scenarios → Copilot

```text
Explain these three options in plain English for an executive: which one keeps us within our limits, which earns the best return, and what is the trade-off?
```

Look for: €300m breaks the 15% sector limit (15.05%); €250m stays within it (14.90%) and earns the best return (3.20%).

**10.** Microsoft 365 Copilot app → Agents → Analyst, with both workbooks attached (run it before the session)

```text
Priya Raman forecasts that Industrials will reach about 14.6% of our loan book by Q3 2027, even without new deals. Using the attached workbooks, check her forecast, then give me three numbers and one recommendation about the Fabrikam hold, with the evidence for each. Show your calculations and flag any data you are unsure about.
```

Look for: 14.56% for Q3 2027, so Priya’s forecast holds · 15.05% · 14.90% · 3.20% → keep €250m. It may also flag the duplicate loan and the missing ratings built into the workbook.

> **Say this out loud:** "Good analysts – human or AI – check the data first."

### 16:00 – Help me say it (PowerPoint + Copilot Chat · 7 min)

*Two audiences this week: the Executive Committee on Thursday, all staff on Friday.*

**11.** PowerPoint → blank presentation → Copilot → Create a presentation from a file → Meridian_Executive_Briefing_Final

```text
Create a 6-slide presentation for the EMEA Executive Committee: decision required, the opportunity, the numbers, risks and conditions, recommendation, next steps.
```

Look for: Check the numbers on the slides: €800m loan, €250m hold, leverage 2.7x, 14.90%, 3.20%, three conditions.

**12.** Same presentation

```text
Add speaker notes for a five-minute delivery. Mention the one number to remember on each slide.
```

Look for: One key number per slide, in Haruka’s voice.

**13.** Microsoft 365 Copilot Chat

```text
Draft five key messages for Friday's Corporate Banking town hall, based on Daniel Okafor's email and /Meridian_Portfolio_Summary_Q3: Q3 performance, client successes, people and recognition, priorities for 2027, and one thing everyone can do. Warm and confident, about 30 seconds each. Do not mention any confidential client or deal.
```

Look for: Astwyn Renewables and Galmere Ports as the client successes – and nothing about Fabrikam or Project Meridian, even though the portfolio summary mentions it.

> **Say this out loud:** "Check before you share: the numbers on the slides, and nothing confidential in the town hall."

### 17:30 – Keep me ahead (Researcher agent + Copilot Chat · optional)

*Before she leaves: Thursday covered, tomorrow planned.*

**14.** Microsoft 365 Copilot app → Agents → Researcher (run it before the session)

```text
Prepare my briefing pack for Thursday's Executive Committee, using my emails and documents. Page 1: Project Meridian – the decision, the key numbers, the conditions, and what has changed since the pre-read. Page 2: Industrials concentration – Priya's proposed options and what each would achieve. Finish with the three questions I am most likely to be asked, with short answers.
```

Look for: A two-page pack with sources – the screening update and Priya’s three options included.

**15.** Microsoft 365 Copilot Chat

```text
Based on my emails and calendar, what are the three things I should do first tomorrow, and what can I delegate – and to whom?
```

Look for: Finish the Tokyo input · the 08:00 call with Tokyo · Grace’s OK · decide on calling Hayashi-san. Delegate the cost actions to Marc Lefèvre and the speaking reply to Olivia.

> **Say this out loud:** "Thursday is covered and tomorrow is planned – in two prompts."

## Five prompts to take away

Paste these into the meeting chat at the end, so attendees leave with them.

**1. Monday briefing**

```text
Act as my chief of staff. Using my emails and calendar from the past week, prepare my briefing for the week ahead:
the decisions I made, the decisions still waiting for me, and the three things I should focus on. Under 150 words.
```

**2. Catch me up**

```text
I've been away for [two days]. Go through my inbox and tell me what needs my attention this week:
decisions waiting for me, deadlines, and what I can delegate. Most urgent first, in a short table.
```

**3. Prepare me**

```text
I'm meeting [name, role] about [topic] in [15 minutes]. From my emails and files, brief me in half a page:
their position, the open issues, and two questions I should ask.
```

**4. Help me decide** (in Word)

```text
Summarise this paper for me: the decision being asked, the three main risks and three questions I should ask,
in under 200 words.
```

**5. Help me say it** (in PowerPoint)

```text
Create a [6]-slide presentation from /[document] for [audience], with speaker notes for a [5]-minute delivery.
```

## Questions executives often ask

| Question | Short answer |
|---|---|
| Is our data used to train the AI? | No – your data isn't used to train the foundation models (slide 7). |
| Can Copilot see things I'm not allowed to see? | No. It only uses content you can already open. |
| How accurate is it? | It gives strong first drafts and shows the sources it used. Open them and check the numbers before you rely on them. |
| Will it replace my analysts? | It removes first drafts and searching. Judgement, challenge and accountability stay with people. |
| Where do I start tomorrow? | With the five prompts above – and save the ones that work for you (slide 13). |

Questions about licences, rollout or configuration: note them and pass them to the account team.

## Key takeaway

For leaders, Copilot works like a chief of staff that already knows your work: it catches you up, prepares you, challenges the paper in front of you, explains the numbers and drafts the message. You still make the call.

## Appendix: details built in on purpose

Please don't correct these in the scenario – they create the teaching moments.

| What | Where | Why it's there |
|---|---|---|
| The Tokyo deadline is 18:00 Tokyo time – 09:00 in London | Email from Takeshi Yamamoto | A Wednesday deadline that really means Tuesday |
| Screening finished after the paper was written | Email from Karim Benali (Friday afternoon) | Information moves on – check what has changed |
| "Don't mention the client or the deal" | Email from Daniel Okafor (town hall) | Confidentiality in staff communications |
| Thomas still prefers €300m but backs €250m | Email from Thomas Brennan | Copilot reports both views; Haruka decides |
| Items to delegate | Speaking invitation, cost forecast, dinner logistics | Executives decide and delegate |
| Low-priority emails | Research newsletter, training reminder | Good triage puts them at the bottom |

