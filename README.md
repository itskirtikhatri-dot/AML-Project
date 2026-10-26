# Anti-Money Laundering (AML) Transaction Analysis — Excel

## Project Overview

This project uses Microsoft Excel to explore a small transaction dataset and demonstrate how transaction patterns can be summarized for an anti-money laundering (AML) review. The workbook includes a transaction table, dashboard charts, customer risk profiling, a draft suspicious activity report section, and a summary of observations.

The aim is to demonstrate data preparation, aggregation, risk-indicator exploration, and communicating findings clearly.

> **Important:** Before publishing, state the dataset's origin accurately. If the records are fictional or constructed for practice, label them as synthetic sample data. Do not describe this workbook as an official Estonian AML case unless you have a reliable source and permission to make that connection.

## Tools Used

- **Microsoft Excel** — transaction review, summaries, charts, and risk profiling
- **Pivot tables / summary tables** — customer-level transaction totals and counts
- **Excel charts** — visual summaries of the sample data
- **GitHub** — project documentation and portfolio sharing

Only list features you personally used and can explain in an interview.

## Workbook Contents

| Worksheet | Purpose |
|---|---|
| `AML Case` | Transaction-level records and customer-level summary |
| `Dashboard` | Visual overview of transaction patterns |
| `Risk_Profiling` | Illustrative customer risk levels and reasons |
| `SAR_Report` | Draft report section for the customer flagged for review |
| `Insights` | Short summary of observations recorded in the workbook |

## Analysis Questions

This project explores questions such as:

1. How many transactions are recorded for each customer?
2. What is the total transaction amount associated with each customer?
3. Which transactions involve transfers between different countries?
4. Which records have indicators that may warrant additional review?
5. How can summary tables and charts communicate these patterns?

## Summary of the Current Sample

The workbook currently contains **8 transaction records across 3 customer IDs**.

| Customer ID | Transaction count | Total transaction amount* | Workbook risk label |
|---|---:|---:|---|
| C201 | 4 | 210,000 | High |
| C202 | 2 | 90,000 | Medium |
| C203 | 2 | 500 | Low |
| **Total** | **8** | **300,500** | — |

\*The workbook does not clearly specify the currency. Confirm and label the currency in the data before publishing; do not add a currency symbol without verification.

The workbook labels C201 as high risk based on shell-company classification, high transaction values, and multiple recipient countries. C202 is labelled medium risk because of cross-border transactions, while C203 is labelled low risk because its recorded transactions are local and lower in value. These are the classifications entered in this sample workbook, not independently validated AML conclusions.

## Method

1. Reviewed the transaction fields, including customer ID, amount, date, sending country, receiving country, and company type.
2. Summarized transaction amounts and transaction counts by customer.
3. Used charts to visualize selected patterns.
4. Recorded illustrative risk labels and the reasons entered in the workbook.
5. Summarized the observations and documented limitations.

## Key Observations

- C201 has the largest total transaction amount in this sample: 210,000 across four transactions.
- C201's recorded transactions involve multiple recipient countries.
- C202 has a total transaction amount of 90,000 across two transactions.
- C203 has a total transaction amount of 500 across two locally recorded transactions.

These observations describe the sample only. They do not establish that money laundering occurred.

## Important Limitations

- The sample is small, with only eight transaction records and three customers.
- The currency and provenance of the records must be clearly documented.
- Risk labels are indicative classifications in the workbook and should not be treated as proof of wrongdoing.
- Cross-border transfers, large amounts, or shell-company indicators alone do not establish money laundering.
- A real AML investigation would require more context, validated data, documented thresholds, applicable legal requirements, and review by qualified professionals.
- The `SAR_Report` sheet is a draft exercise, not a real or submitted Suspicious Activity Report.

## Possible Improvements

- Add a clear data-source statement and currency field.
- Document the criteria used to assign each risk level.
- Add a dashboard subtitle showing the period and number of records analysed.
- Format amounts consistently and check dates and labels.
- Add screenshots of the completed Excel dashboard.
- Expand the analysis only when additional reliable data is available.

## Files

- `Project of AML - Kirti.xlsx` — Excel workbook containing the analysis and dashboard
- `README.md` — project documentation

## Author

Created as a data-analysis portfolio learning project using Microsoft Excel.
