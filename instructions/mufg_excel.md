# MUFG Excel Copilot Demo – Uncover New Data Insights

**Scenario:** You're **Priya Raman**, Portfolio Manager at MUFG EMEA. It's **Wednesday 21 October 2026**. Before next week's credit review, Haruka (Head of Corporate Banking) needs two answers:

1. How did the EMEA corporate loan book perform in Q3 2026?
2. How much of the €800m Fabrikam loan can the bank keep – **€200m, €250m or €300m** – and stay within its limits?

**Timing (60 minutes):** story so far 5 · Part 1 12 · Part 2 18 · Part 3 10 · five-minute challenge 7 · wrap-up 8

## Demo setup

**Use:**

- [Meridian_Portfolio_Q3_2026.xlsx](../files/Meridian_Portfolio_Q3_2026.xlsx) – 150 fictional loans, the quarterly trend, sector limits and the deal pipeline
- [Meridian_Fabrikam_Analysis.xlsx](../files/Meridian_Fabrikam_Analysis.xlsx) – the deal figures and the three hold options

> **NOTE:** Copilot in Excel works on files saved in OneDrive with AutoSave on. The data is already formatted as Excel tables.
> Keep a clean copy of the portfolio workbook: Part 1 fixes its data errors, so reset it before each session.
> The Analyst agent can take a few minutes. Run step 15 once before the session so you have the result ready.

**What's in the portfolio workbook:** `Portfolio_Exposures` (the loans) · `Quarterly_Trend` (last eight quarters) · `Risk_Appetite_Limits` (sector limits) · `Pipeline` (upcoming deals) · `Data_Dictionary` · `About`

## Copilot in Excel

### Part 1 – Understand and clean the data

**1. Get the big picture**

[Worksheet: any]

```text
Summarise what this workbook contains and what each sheet could be used for in a portfolio review.
```

**2. Explain the columns**

[Worksheet: Portfolio_Exposures]

```text
Explain the columns in the Portfolio_Exposures table in plain language for someone new to credit portfolios.
```

**3. Check the data before you trust it** (one prompt at a time)

[Worksheet: Portfolio_Exposures]

```text
Highlight any rows where the Facility_ID appears more than once.
```

```text
Highlight rows where Drawn_EURm is greater than Commitment_EURm.
```

```text
Show the distinct values in the Country column and how many rows use each one.
```

```text
Which rows have a blank Rating_Grade?
```

Copilot finds four problems – see the [appendix](#appendix-data-errors-built-in-on-purpose). Fix them live:

- Delete the second copy of MER-0123 (row 125).
- Change MER-0122's drawn amount from 63 to **36** ("the data owner confirmed it").
- Change "NL" and "The Netherlands" to **Netherlands**.
- **Leave the two blank ratings blank** and flag them to Credit Risk.

> **Say this out loud:** Copilot finds the problems; people decide the fix. Never let AI guess a credit rating.
> Watch the `Risk_Appetite_Limits` sheet: the Industrials share moves from 13.54% to **13.61%** once the duplicate is gone.

### Part 2 – Explore performance

**4. Add a calculated column**

[Worksheet: Portfolio_Exposures]

```text
Add a column called Utilisation_pct that divides Drawn_EURm by Commitment_EURm.
```

What to look for: overall, about **69.9%** of the money promised has been drawn (€19,281m of €27,600m).

**5. Add the return**

```text
Add a column called RoRWA_pct that divides Annualised_Revenue_EURm by RWA_EURm.
```

What to look for: overall **1.89%** – below the 2.5% hurdle for new loans. By sector, Infrastructure is highest (2.16%) and Automotive lowest (1.66%).

**6. Summarise by sector**

```text
Create a PivotTable showing total Commitment_EURm and RWA_EURm by Sector, sorted from largest to smallest,
with each sector's share of total commitments.
```

What to look for: Energy & Utilities 14.0%, Industrials 13.6%, Infrastructure 11.7% …

**7. Compare with the limits**

```text
Compare each sector's share of commitments with the limits on the Risk_Appetite_Limits sheet.
Which sectors are above their early-warning level?
```

What to look for: only **Industrials** – 13.61% against an early warning of 13.5% and a limit of 15%.

**8. Spot the loans that need attention**

```text
Highlight facilities that are on the watch list or in IFRS 9 Stage 2 or Stage 3.
```

What to look for: 14 loans – 13 in Stage 2 and one in Stage 3 (Drevanta Automotive Components, €45m).

**9. Find the downgrades**

```text
Which sectors had the most rating downgrades this quarter? Compare Rating_Grade with Prior_Quarter_Rating.
```

What to look for: 17 loans downgraded – Automotive 7, Chemicals & Materials 6. The two blank ratings are missing, not downgraded.

**10. Chart the trend**

[Worksheet: Quarterly_Trend]

```text
Create a line chart of Industrials_Share_pct over the last eight quarters and describe the trend.
```

What to look for: from 12.0% (Q4 2024) to 13.61% (Q3 2026) – up about 0.23 points every quarter.

**11. What stands out?**

```text
What are the main trends in revenue, impairment charges and Stage 2 exposure over the last eight quarters?
What stands out in Q3 2026?
```

What to look for: revenue up only 0.5% while lending grew 1.3% (margins are being squeezed); impairment charges jumped to €15.4m from €7.0m (one loan moved to Stage 3); Stage 2 loans reached €2,220m, 8.0% of the book.

### Part 3 – Decide

**12. Forecast**

[Worksheet: Quarterly_Trend]

```text
Forecast Industrials_Share_pct for the next four quarters based on the last eight quarters
and add the forecast to the chart. Explain the method you used.
```

What to look for: a straight-line trend gives 13.86%, 14.10%, 14.33% and 14.56% (other methods may differ slightly). The share keeps rising even without the Fabrikam deal.

**13. Compare the three options**

[Workbook: Meridian_Fabrikam_Analysis · Worksheet: Hold_Scenarios]

```text
For each hold option, explain the impact on Industrials concentration including the pipeline,
single-name limit usage and return on RWA. Which options stay within risk appetite?
```

What to look for: see the [expected results](#appendix-expected-results-for-the-three-options) – €300m breaks the 15% limit.

**14. Add a status column**

```text
Add a column that labels each option 'Within appetite', 'Early warning' or 'Breach' using the 15% limit
and the 13.5% early-warning level for Industrials concentration including the pipeline.
```

What to look for: €200m and €250m – Early warning; €300m – Breach.

> **Say this out loud:** ask Copilot to explain any formula before you rely on it.

**15. Hand the whole analysis to the Analyst agent**

Open the **Microsoft 365 Copilot app → Agents → Analyst** and attach both workbooks:

```text
You are supporting the Head of Corporate Banking. Using the attached workbooks, prepare an executive analysis:
1) Q3 2026 portfolio performance highlights;
2) sector concentration risks and trends, including a forecast of the Industrials share;
3) the impact of a €200m, €250m and €300m Fabrikam hold on concentration, single-name limits and returns;
4) a recommendation with conditions.
Separate facts from assumptions, show the calculations you used, and list any data limitations.
```

Follow-up:

```text
Which assumption would most change your recommendation, and how?
```

What to look for: whether the expected pipeline deals close; whether MUFG wins the hedging business; a 20% fall in Fabrikam's earnings would break its 3.25x leverage covenant.

## Five-minute challenge

Haruka: "I have five minutes. What do I need to know?"

```text
Give me three numbers and one recommendation for Haruka about the Fabrikam hold, with the evidence for each.
```

What to look for: 15.05% (€300m breaks the limit) · 14.90% (€250m stays within it) · 3.20% return on RWA at €250m, above the 2.5% hurdle → recommend **€250m**, provided MUFG wins the hedging business.

## Try it on your own work

```text
Act as my Microsoft 365 Copilot coach. I work as a [role] in [department] at a bank in EMEA.
Suggest five ways I can use Copilot in Excel with the data I work with. For each: the business question,
a ready-to-use prompt, how my data should be structured, a suitable chart, and what I must validate before sharing.
Start simple, then add two advanced ideas, including one for the Analyst agent. Ask me questions about my data first.
```

## Key takeaway

Copilot in Excel takes you from a raw extract to a decision: clean the data, explore it in plain language, forecast, compare options and hand the full analysis to the Analyst agent – while you check every number.

## Appendix: data errors built in on purpose

Sheet `Portfolio_Exposures` (header in row 1):

| Issue | Row(s) | What you'll see | Fix |
|---|---|---|---|
| Duplicate loan | 98 and 125 | MER-0123 (Talara Media S.A., €130m) listed twice | Delete one copy |
| Drawn more than the limit | 124 | MER-0122 (Pelstra Foods B.V.): drawn 63, commitment 60 | Correct to 36 |
| Country written three ways | 6, 17, 28 | "NL", "NL", "The Netherlands" | Change to "Netherlands" |
| Missing ratings | 15 and 141 | MER-0014 and MER-0139 have no Rating_Grade | Leave blank; flag to Credit Risk |

Totals before the fixes: commitments €27,730m, Industrials 13.54%. After: **€27,600m**, Industrials **13.61%**.

## Appendix: expected results for the three options

| Final hold | Industrials share (incl. pipeline) | Status | Single-name limit used | Return on RWA (incl. other business) |
|---|---|---|---|---|
| €200m | 14.76% | Early warning | 78% | 3.03% |
| **€250m** | **14.90%** | **Early warning** | **88%** | **3.20%** |
| €300m | 15.05% | Breach | 98% | 3.00% |

- The loan on its own earns 2.01% for every option – below the 2.5% hurdle. The hedging and cash-management business makes the difference.
- The largest hold that stays within the 15% limit, including the pipeline, is about **€282m**.
