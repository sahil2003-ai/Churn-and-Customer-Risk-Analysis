# Customer Churn and Risk Analysis

A Power BI portfolio project focused on exploring customer churn patterns and customer-risk indicators.

![BI](https://img.shields.io/badge/Tool-Power%20BI-F2C811)
![Focus](https://img.shields.io/badge/Focus-Customer%20Analytics-blue)

## Contents
- [Project Overview](#project-overview)
- [Business Questions](#business-questions)
- [Dashboard Scope](#dashboard-scope)
- [Metrics to Validate](#metrics-to-validate)
- [Technology Stack](#technology-stack)
- [Repository Structure](#repository-structure)
- [Open the Report](#open-the-report)
- [Limitations and Next Steps](#limitations-and-next-steps)

## Project Overview
The dashboard is intended to help explore customer churn and risk indicators, compare patterns across customer groups, and support further investigation. The report should be treated as descriptive analysis unless the repository includes a separately validated predictive model.

## Business Questions
- What share of customers are classified as churned?
- How does churn vary by customer segment or other available attributes?
- Which groups contribute most to churn counts?
- Are risk categories and their definitions consistent with the source data?

## Dashboard Scope
The repository contains the Power BI report but no separate source dataset, SQL queries, notebook, exported KPI table, or screenshots in the reviewed file inventory.

## Metrics to Validate

| Metric | Recommended definition |
|---|---|
| Customer count | Count of distinct customer IDs |
| Churn rate | Churned customers ÷ eligible customers |
| Retention rate | Retained customers ÷ eligible customers |
| Segment churn | Churned customers in a segment ÷ eligible customers in that segment |

These are suggested definitions, not claims about the exact DAX measures in the report. The source row count, churn rate, and subgroup results could not be independently recalculated from the available repository contents.

## Technology Stack
- **Power BI Desktop:** report and interactive visualizations.
- **DAX / Power Query:** review stored measures and data transformations.

## Repository Structure
```text
Churn-and-Customer-Risk-Analysis/
└── Churn and Customer Risk Analysis.pbix
```

## Open the Report
1. Open `Churn and Customer Risk Analysis.pbix` in Power BI Desktop.
2. Reconnect the source if prompted.
3. Refresh the report and verify the customer-grain and churn-label definitions.
4. Check whether filters exclude incomplete records or customers outside the analysis window.

## Limitations and Next Steps
- Document the source dataset, data dictionary, date range, and license.
- Add validated headline metrics and their definitions.
- Include genuine screenshots from the dashboard.
- Distinguish descriptive risk indicators from predictions of future churn.
- If prediction is added, use a time-aware holdout and report precision, recall, F1, and a baseline.

## Skills Demonstrated
Customer analytics, churn KPI definition, Power BI, segment analysis, dashboard interpretation, and metric validation.
