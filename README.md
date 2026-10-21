# Hospital Parking Revenue Reconciliation & Variance Dashboard

An Excel project that models the monthly workflow of a hospital parking revenue control analyst.

> **All data in this workbook is synthetic.** Accounts, locations, and amounts are invented for demonstration. No real hospital, patient, employee, or vendor data is used.

## What it does

| Sheet | Purpose |
|---|---|
| **Dashboard** | KPIs (collection rate, net variance, exceptions), monthly summary, exceptions by account, and charts |
| **Invoice_Recon** | Reconciles monthly invoices to collections for 8 public parking accounts (72 account-months), classifying each as Matched, Short Payment, Overpayment, or Missing Payment |
| **Budget_vs_Actual** | Compares revenue to budget for 4 parking locations and flags location-months outside a set threshold |
| **Employee_Access** | Reconciles active employee parking permits against payroll deductions and estimates unbilled revenue |
| **Assumptions** | Match tolerance, budget variance threshold, and permit rate, referenced by every formula |

## Key findings (synthetic data)

- **97.1% collection rate** on $679K billed, with a net variance of ($19,974)
- **9 invoice exceptions** totaling $21,330 in gross variance, including 2 missing payments
- **4 location-months** outside the ±5% budget threshold
- **13 active employee permits** not billed through payroll (~$1,235 estimated leakage)

## How it works

Blue cells are inputs, black cells are formulas, and green cells link across sheets. Change any input and every status, variance, KPI, and chart updates automatically. Built with SUMIFS, COUNTIFS, SUMPRODUCT, IFERROR, and conditional formatting.

*Built by Shailanshi Gupta, MS Business Analytics, Northeastern University.*
