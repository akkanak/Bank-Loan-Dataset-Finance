# Bank Loan Analysis Report | Power BI & MySQL Project

An interactive Power BI dashboard and SQL analytics solution designed to monitor bank loan portfolio performance, evaluate key financial metrics (KPIs), and assess credit risk profiles.

---

## Executive Summary (KPIs)

* **Total Loan Applications:** 38.6K (MTD: 4.3K | MoM: +6.9%)
* **Total Funded Amount:** $435.8M (MTD: $54M | MoM: +13.0%)
* **Total Amount Received:** $473.1M (MTD: $58.1M | MoM: +15.8%)
* **Average Interest Rate:** 12.05%
* **Average Debt-to-Income (DTI):** 13.33%

---

## Key Highlights & Risk Segmentation

### Good Loans vs. Bad Loans
* **Good Loan Issued:** 86.2% (33K Applications)
  * **Funded Amount:** $370.2M
  * **Amount Received:** $435.8M
* **Bad Loan Issued (Charged Off):** 13.8% (5.3K Applications)
  * **Funded Amount:** $65.5M
  * **Amount Received:** $37.3M

---

## Dashboard Pages Overview

1. **Summary Page:** Top-level executive view featuring high-level KPIs, MoM growth rates, and Good vs. Bad loan breakdown.
2. **Overview Page:** In-depth visual insights including monthly lending trends, state-wise distribution, loan purpose analysis, and home ownership breakdowns.
3. **Details Page:** Grid view allowing comprehensive filtering, record-level audit, and granular data inspection.

---

## Tools & Environment Used

* **Power BI Desktop:** Report & Dashboard Visualization
* **Database:** MySQL Server 8.0.46
* **Database Management:** MySQL Workbench 8.0
* **Data Prep & Analysis:** SQL Queries (`Query Document.docx`)
* **Documentation & Presentation:** MS Office 2016

---

## Repository Files

* `Bank Loan Dataset.pbix`: Power BI Dashboard file containing data model, DAX measures, and interactive report pages.
* `financial_loan.csv`: Source dataset containing loan applications and financial attributes.
* `Query Document.docx`: SQL queries executed for data extraction, verification, and KPI creation.
* `Terminologies in Data.docx`: Glossary of financial domain terms and dataset metrics.
* `DATA ANALYST PORTFOLIO PROJECT.pptx`: Presentation slide deck for stakeholder walkthroughs.

---

## How to Run locally

1. Clone this repository:
   ```bash
   git clone [https://github.com/akkanak/Bank-Loan-Dataset-Finance.git](https://github.com/akkanak/Bank-Loan-Dataset-Finance.git)
