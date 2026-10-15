# Evaluating an AI Agent's Learning-Roadmap Responses

A QA review of four AI-agent responses to beginner Business Intelligence & Data Analytics prompts, scored on accuracy, clarity, reasoning and creativity.

**Overall score: 7.5 / 10**

## Prompts evaluated
1. Six-month roadmap (Excel, SQL, Power BI, Python, projects)
2. Skill-gap analysis and practical learning plan
3. Beginner Excel / Power BI business analytics project
4. Data analytics internship preparation checklist

## Scorecard (out of 10)
| Prompt | Accuracy | Clarity | Reasoning | Creativity | Overall |
|---|---|---|---|---|---|
| 1. Roadmap | 7 | 8 | 6.5 | 6 | 7 |
| 2. Skill gaps | 7 | 8 | 6 | 6 | 6.8 |
| 3. Project | 7.5 | 8.5 | 8 | 7.5 | 8 |
| 4. Internship checklist | 8 | 8.5 | 7.5 | 7 | 7.8 |
| **Average** | **7.4** | **8.3** | **7.0** | **6.6** | **7.5** |

> Scores are subjective evaluator judgements. Response time was not scored.

## Strengths
- Consistent, scannable structure with a concrete next step
- Complete project blueprint with a weighted evaluation rubric
- Practical resume, interview and portfolio guidance

## Issues found
- **Invented context:** assumed 12 hrs/week and a Computer Science major
- **Rigid template:** the same 8 sections forced onto every prompt
- **Thin skill-gap analysis** in Response 2
- **Technical error:** Profit Margin % as a calculated column; use a DAX measure such as `DIVIDE(SUM(Profit), SUM(Sales))`
- **Superstore is already clean,** so "remove nulls/duplicates" steps are largely moot
- **Timeline mismatch** in Response 4; Python never scheduled
- Minor: mislabelled "Database Migration" project, generic links, arbitrary metrics

## Gaps across all responses
- No statistics fundamentals (distributions, hypothesis testing, A/B testing)
- No realistic expectations for first-year internships
- Shallow interview preparation

## Recommendations
1. Ask clarifying questions or state assumptions before planning
2. Adapt structure to the request instead of reusing one template
3. Prioritise skill gaps and tie projects to them
4. Validate technical details before recommending them

## Repository structure
```
.
├── README.md
└── AI_Agent_Evaluation_Report.pdf
```

## Part of
AI Model Face-Off: comparing Claude, ChatGPT, Gemini and Perplexity.

## Author
**Likith G**: BBA (Business Intelligence & Data Analytics), Bengaluru, India
