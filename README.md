# MUFG Copilot Demos – Project Meridian

Four ready-to-run Microsoft 365 Copilot demos – **Outlook, Word, Excel and PowerPoint** – built around one simple banking story.

| Folder | What's inside |
|---|---|
| [`instructions/`](instructions) | One demo script per app, with copy-ready prompts |
| [`files/`](files) | The practice files the demos use |

> **Everything here is fictional.** The people, companies, deals and figures were invented for training and are labelled "FICTIONAL – FOR TRAINING USE ONLY". No real client or bank data is used.
> Please keep this repository **private**: it was prepared for MUFG training sessions.

## The story in one minute

Fabrikam Industries, a long-standing client based in Tokyo, wants to buy Contoso Energy Materials, a European battery-recycling company. It asks MUFG EMEA to lead an **€800m loan**.

The Corporate Banking team has **six weeks** to check the deal and decide how much of the loan the bank should keep on its own books: **€200m, €250m or €300m**. The EMEA Executive Committee decides on **Thursday 12 November 2026**. (The outcome: €250m, with three conditions.)

## The four demos

Each demo stands alone, fits a 60-minute session and picks up one week of the story.

| Demo | Week of the story | You play | Script |
|---|---|---|---|
| Outlook | Week 1 – The request arrives | Thomas, Relationship Manager | [mufg_outlook.md](instructions/mufg_outlook.md) |
| Excel | Week 3 – The numbers | Priya, Portfolio Manager | [mufg_excel.md](instructions/mufg_excel.md) |
| Word | Week 5 – The briefing paper | Thomas, writing for the Executive Committee | [mufg_word.md](instructions/mufg_word.md) |
| PowerPoint | Week 6 – The decision | A colleague of Haruka's, building her presentation | [mufg_ppt.md](instructions/mufg_ppt.md) |

Open every session with [Meridian_Intro_Slides.pptx](files/Meridian_Intro_Slides.pptx): three minutes to set the scene.

## Who's who

| Person | Role in the story |
|---|---|
| Haruka Sato | Head of Corporate Banking – the sponsor, presents to the Executive Committee |
| Thomas Brennan | Relationship Manager for Fabrikam – wants to keep €300m |
| Priya Raman | Portfolio Manager – checks the impact on the loan book |
| Sander de Vries | Financial Analyst – builds the numbers |
| Elena Rossi | Credit Risk Manager – prefers €200m |
| Karim Benali | Compliance Officer – client checks (KYC) and ESG |
| Grace Mensah | Operations Manager – account opening and payments |
| Olivia Grant | Executive Assistant to Haruka – diary, notes and follow-ups |

The client: Yuki Hayashi (Chief Financial Officer, Fabrikam, Tokyo) and Markus Brandt (Group Treasurer Europe, Fabrikam).

## Get ready (the day before)

1. Download everything: **Code → Download ZIP**.
2. Upload the `files` folder to your OneDrive, for example into a folder called *Project Meridian*. Allow up to 10 minutes for the files to sync.
3. **Outlook demo only:** load the demo emails into your mailbox. See [Demo setup](instructions/mufg_outlook.md#demo-setup).
4. Keep a clean copy of `Meridian_Portfolio_Q3_2026.xlsx` and `Meridian_Executive_Briefing_Draft.docx`. The demos change them, so reset them between sessions.
5. Run each prompt once. Copilot's wording changes every time; the numbers should not.
6. Presenting it yourself? Put your name on slide 1 of the intro slides.

## Files at a glance

| File | Used in | What it is |
|---|---|---|
| [Meridian_Intro_Slides.pptx](files/Meridian_Intro_Slides.pptx) | All | The story, the cast and today's chapter |
| [Meridian_Prompt_Cards.docx](files/Meridian_Prompt_Cards.docx) | All | Hand-out: ready-to-use prompts for each app |
| [Meridian_Email_Pack.docx](files/Meridian_Email_Pack.docx) | Outlook | 18 emails to load into your demo mailbox |
| [Meridian_Portfolio_Q3_2026.xlsx](files/Meridian_Portfolio_Q3_2026.xlsx) | Excel | 150 fictional loans, with a few data errors on purpose |
| [Meridian_Fabrikam_Analysis.xlsx](files/Meridian_Fabrikam_Analysis.xlsx) | Excel | The deal figures and the €200m / €250m / €300m options |
| [Meridian_Executive_Briefing_Draft.docx](files/Meridian_Executive_Briefing_Draft.docx) | Word | The half-finished paper you improve |
| [Meridian_Client_Meeting_Notes.docx](files/Meridian_Client_Meeting_Notes.docx) | Word | Notes from the client meeting on 13 October |
| [Meridian_Credit_Risk_Assessment_Draft.docx](files/Meridian_Credit_Risk_Assessment_Draft.docx) | Word | Credit Risk's view – uses out-of-date figures on purpose |
| [Meridian_Compliance_Review_Note.docx](files/Meridian_Compliance_Review_Note.docx) | Word | Open compliance and ESG checks |
| [Meridian_Operational_Readiness_Note.docx](files/Meridian_Operational_Readiness_Note.docx) | Word | Account-opening and payment readiness |
| [Meridian_Review_Minutes.docx](files/Meridian_Review_Minutes.docx) | Word | Minutes of the 27 October review – agreed to recommend €250m |
| [Meridian_Portfolio_Summary_Q3.docx](files/Meridian_Portfolio_Summary_Q3.docx) | Word | Two-page summary of the loan book |
| [Meridian_Executive_Briefing_Final.docx](files/Meridian_Executive_Briefing_Final.docx) | Word, PowerPoint | The finished paper, and the source for the presentation |
| [Meridian_Client_Briefing_Example.docx](files/Meridian_Client_Briefing_Example.docx) | Word | Example of a client-ready version |
| [Meridian_ExCo_Presentation_Example.pptx](files/Meridian_ExCo_Presentation_Example.pptx) | PowerPoint | Example finished deck, with speaker notes |
| [Meridian_ExCo_Questions.docx](files/Meridian_ExCo_Questions.docx) | PowerPoint | Likely Executive Committee questions, with answers |

## Good habits to show in every demo

- **Copilot drafts, you decide.** You stay accountable for what you send.
- **Check every number** against its source before you share it.
- **Keep internal remarks out** of anything that goes to a client.
- **Copilot only uses content you can already open.** It works within your existing permissions.

## Banking words in plain English

- **Commitment / drawn:** the most a client can borrow / what they have actually borrowed.
- **Final hold:** the part of a shared loan the bank keeps on its own books.
- **Concentration limit:** the most the bank lends to one sector. Industrials: 15% of the loan book, with an early warning at 13.5%.
- **Leverage:** debt divided by yearly earnings (EBITDA). 2.7x means the debt equals 2.7 years of earnings.
- **Return on RWA:** yearly income divided by risk-weighted assets. The bank's hurdle for new loans is 2.5%.
- **KYC / ESG:** know-your-customer checks / environmental, social and governance review.
