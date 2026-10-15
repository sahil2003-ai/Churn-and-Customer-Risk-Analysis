# Customer Churn and Risk Analysis

A Power BI portfolio project focused on exploring customer churn and risk indicators.

## Project files

| File | Purpose |
|---|---|
| `Churn and Customer Risk Analysis.pbix` | Power BI report |
| `README.md` | Project documentation |

## Analysis scope

The report is intended to help review customer-group measures and explore how risk or churn varies across the fields available in the underlying model. Churn must be defined using the dataset's actual target/measure; risk labels should not be treated as a known future outcome unless the data supports that interpretation.

## Tools

- Microsoft Power BI Desktop
- Power Query / DAX only where implemented in the PBIX

## How to verify the report

1. Open the PBIX in Power BI Desktop.
2. Inspect the source connection, model tables, date coverage, and refresh status.
3. Identify the exact churn definition and calculate its numerator and denominator.
4. Check every KPI's formula, filter context, and reporting period.
5. Validate displayed totals against underlying data where accessible.
6. Capture report screenshots and document results only after confirmation.

## Verified results status

The repository file inventory contains the PBIX report but no separate source dataset, SQL queries, notebook, exported KPI table, or screenshots. Its row count, churn rate, and subgroup results could not be independently recalculated in this review. Accordingly, this README does not make numerical claims about churn, retention, customer risk, or business impact.

## Limitations and responsible use

- The exact source, data coverage, and definitions must be documented from the PBIX.
- Descriptive differences between customer groups do not prove what caused churn.
- Avoid using group-level patterns alone to make consequential decisions about individual customers.
- Document the data source and license before redistribution.

## Improvements to complete

- [ ] Document the source dataset and data dictionary.
- [ ] Add KPI definitions and validated numerical results.
- [ ] Include screenshots from the actual report.
- [ ] Reconcile totals and filters with the source data.

## Skills demonstrated

Customer analytics, KPI definition, Power BI dashboards, data validation, and responsible interpretation of risk indicators.

## Author

Sahil Gaikwad · [GitHub](https://github.com/sahil2003-ai) · [LinkedIn](https://www.linkedin.com/in/sahil-gaikwad-a76b7224a/)
