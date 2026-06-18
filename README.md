# ConnectTel Call Centre Cost Analysis

A business analyst case study examining operational inefficiencies in a telecom call centre, with data-backed findings and recommendations to reduce costs without compromising customer experience.

---

## Project Overview

ConnectTel, a South African telecom provider, was experiencing high operational costs in its customer service call centre. The goal of this analysis was to identify the root causes of those inefficiencies and propose practical improvements.

This project was completed as part of a graduate business analyst application. The analysis covers team-level, shift-level, and agent-level performance trends using real call centre data.

---

## Tools Used

- Microsoft Excel (AVERAGEIF formulas, bar charts, data filtering)
- PowerPoint (client-ready presentation)

---

## Key Findings

**Finding 1 — Team B has a significantly higher cost per call**
- Team B averages R27.57 per call vs R25.41 (Team A) and R25.24 (Team C)
- Root cause: Team B's average call duration is 7.52 minutes — approximately 25% longer than the other teams
- Longer calls directly correlate with higher cost per call (r = 0.74)

**Finding 2 — New agents escalate calls at double the rate**
- Agents with 0–3 months experience escalate 17.8% of calls
- Agents with 6+ months experience escalate only 8.4%
- Escalations pull supervisors into calls, extending resolution time and increasing cost

**Finding 3 — Evening shift has a lower First Call Resolution rate**
- Evening shift FCR: 72.2% vs 82.2% (Morning) and 82.7% (Afternoon)
- A 10 percentage point gap means more unresolved calls and likely more callbacks
- Higher callback volume increases total call volume and operating cost

---

## Recommendations

| # | Recommendation | Target |
|---|---------------|--------|
| 1 | Targeted call coaching for Team B — review longest calls, identify root causes | Reduce call duration to match Team A |
| 2 | Structured onboarding and mentorship for new agents | Halve escalation rate within 3 months |
| 3 | Evening shift FCR improvement programme — investigate staffing mix and call complexity | Close the 10pp FCR gap vs day shifts |

---

## Repository Structure

```
connecttel-callcentre-analysis/
│
├── README.md
├── data/
│   └── ConnectTel_CallCenterData.xlsx        # Raw dataset
├── analysis/
│   └── ConnectTel_Workings_Phemelo.xlsx      # Excel analysis (formulas, charts, observations)
└── presentation/
    └── ConnectTel_Diagnostic.pdf             # Client-ready presentation
```

---

## How to Navigate the Excel File

The workings file has 5 sheets:

- **Raw Data** — the original dataset (450 records, 12 columns)
- **Team Analysis** — AVERAGEIF breakdown by team with charts
- **Experience Analysis** — escalation and cost trends by agent experience level
- **Shift Analysis** — FCR and cost trends by shift
- **Agent Analysis** — individual agent performance comparison
- **Summary_Insights** — key findings and observations in plain language

---

## Author

**Phemelo Bohlale Sebopelo**  
BSc Information Technology — Richfield Graduate Institute of Technology (2025)  
GitHub: [github.com/Phemelocodemode](https://github.com/Phemelocodemode)
