MALTRA FOOD GROCER ACCOUNTANT PORTFOLIO
========================================
Files:
- Maltra_Food_Grocer_Accountant_Portfolio.xlsx: working papers, formula-driven calculations, dashboard and Power BI data.
- Maltra_Food_Grocer_Case_Study_and_Interview_Guide.docx: case study, role mapping, accounting approach and interview walkthrough.
- Maltra_PowerBI_FactData.csv: long-format dataset for Power BI import.

IMPORTANT:
All entities, balances, transactions, financial results and events are illustrative and fictional. This portfolio is an independent skills demonstration and is not affiliated with Maltra Foods, Robert Half, or the unnamed employer.

Workbook notes:
- Open in Excel and allow formulas to recalculate.
- Review formulas and accounting assumptions before adapting.
- Fixed-asset depreciation uses a simplified full-month convention and must be aligned to policy in a real engagement.
- Group P&L is a management view before consolidation eliminations.
- ABS tracker is a workflow example only. Confirm current official survey instructions, reporting unit and definitions before any real submission.
- Journal examples are drafts and must not be posted without evidence, assessment and approval.
- Power BI CSV is fictional, not connected to a live ERP.

Recommended Power BI measures:
Actual = CALCULATE(SUM(Fact[Amount]), Fact[Scenario] = "Actual")
Budget = CALCULATE(SUM(Fact[Amount]), Fact[Scenario] = "Budget")
Variance = [Actual] - [Budget]
Variance % = DIVIDE([Variance], [Budget])
