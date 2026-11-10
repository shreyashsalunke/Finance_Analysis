# Financial Loan Analysis | SQL & Power BI Dashboard

## Project Overview

This project focuses on analyzing a financial loan portfolio to evaluate loan performance, customer borrowing behavior, repayment trends, and overall lending activity.

Using SQL for data analysis and Microsoft Power BI for data visualization, this project aims to transform raw loan data into meaningful business insights that can support data-driven decision-making.

## Business Objectives

The primary objectives of this project are:

- Analyze overall loan application and funding performance.
- Monitor loan repayment and outstanding loan status.
- Identify patterns in fully paid and charged-off loans.
- Understand borrowing trends based on loan purpose.
- Analyze loan distribution across different geographical locations.
- Evaluate borrower profiles using annual income, employment length, and debt-to-income ratio (DTI).
- Examine loan grades, sub-grades, and interest rates to understand lending patterns.

## Dataset Overview

The project uses a financial loan dataset containing **38,576 loan records and 24 columns**.

**Dataset:** `financial_loan.csv`

Key attributes include:

| Category | Columns |
|---|---|
| Loan Information | Loan Amount, Term, Installment, Loan Status |
| Borrower Information | Annual Income, Employment Length, Home Ownership |
| Credit Information | Grade, Sub-Grade, Interest Rate, DTI, Total Accounts |
| Payment Information | Total Payment, Last Payment Date, Next Payment Date |
| Geographical Information | Address State |
| Application Information | Application Type, Loan Purpose, Verification Status |

## Tools & Technologies

- **Microsoft Power BI:** Interactive dashboard development, data visualization, and KPI reporting.
- **SQL:** Data extraction, aggregation, filtering, and analytical queries.
- **Microsoft Excel / CSV:** Dataset handling and initial data inspection.

## Key Performance Indicators (KPIs)

The analysis focuses on the following key metrics:

- Total Loan Applications
- Total Funded Amount
- Total Amount Received
- Average Interest Rate
- Average Debt-to-Income Ratio (DTI)


## Key Findings from Dataset Exploration

- The dataset contains 38,576 loan records.
- Approximately 83.33% of loans are marked as Fully Paid.
- Approximately 13.82% of loans are marked as Charged Off.
- Approximately 2.85% of loans are currently active.
- Debt consolidation is the most common loan purpose.
- California has the highest number of loan records among the represented states.
- Employment title contains some missing values, which should be considered during data preparation.

## SQL Analysis

SQL is used to explore the loan dataset and extract meaningful information through analytical queries.

The SQL analysis focuses on:
- Loan status and repayment analysis.
- Loan distribution by purpose and geographical location.
- Borrower income and employment analysis.
- Interest rate and loan grade analysis.
- Loan amount and payment aggregations.
- Identification of trends and patterns in lending activity.

Refer to the SQL Queries PDF included in this repository for the detailed queries.

## Power BI Dashboard

The Power BI dashboard provides an interactive view of the financial loan portfolio, helping users monitor lending performance and explore borrower and repayment patterns.

**Dashboard File:** `Financial_Loan_Dashboard.pbix`

**Dashboard Preview:** See the dashboard screenshot included in this repository.

## Project Files

| File | Description |
|---|---|
| `financial_loan.csv` | Financial loan dataset |
| `Financial_Loan_Dashboard.pbix` | Interactive Power BI dashboard |
| `SQL_Queries.pdf` | SQL analysis and queries |
| `Dashboard_Screenshot.png` | Dashboard preview |
| `README.md` | Project documentation |

## Conclusion

This project demonstrates the practical application of SQL and Power BI in financial data analysis. It highlights how raw loan data can be explored, analyzed, and transformed into meaningful insights to understand loan performance, borrower characteristics, and repayment behavior.

The project showcases practical skills in SQL querying, data analysis, KPI development, and interactive dashboard creation.

---

**Author:** Shreyash Salunke

**Project Domain:** Financial Analytics

**Tools:** MSSQL | Microsoft Power BI | Excel

**Project Type:** Data Analytics
