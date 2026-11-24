# AarogyaCare Hospital – Operations & Financial Performance Dashboard

## Project Overview

AarogyaCare Hospital is an Excel-based data analysis and dashboard project designed to monitor hospital operations and financial performance. The workbook uses fictional hospital data for the calendar year 2025 and brings patient, doctor, admission, and billing information together in an interactive-style management dashboard.

The dashboard is built with Excel formulas, summary tables, and standard charts. It does **not** use PivotTables or PivotCharts.

## Workbook Structure

The workbook contains six worksheets:

| Worksheet | Description |
|---|---|
| **Dashboard** | Main dashboard with key performance indicators (KPIs), summary tables, and charts |
| **Patients** | Patient master data, including patient ID, name, gender, date of birth, city, and registration date |
| **Doctors** | Doctor master data, including department, designation, and employment type |
| **Admissions** | Admission register with patient, doctor, department, admission/discharge dates, length of stay, status, and admission type |
| **Billing** | Billing register with gross bill, discount, net bill, amount paid, outstanding amount, and payment status |
| **Data Dictionary** | Definitions of the fields used throughout the workbook |

## Dataset Summary

The workbook contains fictional practice data:

- **500** patient records
- **40** doctor records
- **1,500** admission records
- **1,500** billing records
- Reporting period: **1 January 2025 – 31 December 2025**
- Currency: **Indian Rupees (INR)**

## Dashboard KPIs

The Dashboard sheet tracks the following headline metrics:

### Hospital Operations
- Total Patients
- Total Admissions
- Discharged Patients
- Currently Admitted
- Average Length of Stay

### Financial Performance
- Net Billing Revenue
- Amount Collected
- Outstanding Amount

### Additional Analysis
- Admissions by Department
- Monthly Admissions Trend
- Net Revenue by Department
- Payment Status Breakdown
- Admission Type Breakdown
- Discharge Rate
- Average Net Bill
- Collection Rate
- Total Doctors
- Departments Represented

## Excel Skills and Formulas Used

The workbook demonstrates formula-driven analysis using functions such as:

- `COUNTA` – counts records and populated identifiers
- `COUNTIF` – counts records matching one condition
- `COUNTIFS` – counts records matching multiple conditions, including monthly date ranges
- `SUM` – calculates totals
- `SUMIFS` – calculates totals based on criteria
- `AVERAGE` – calculates average length of stay and average net bill
- `IF` – assigns payment status based on outstanding balances
- `IFERROR` – handles calculation errors and division-by-zero cases
- `EDATE` – helps define monthly reporting periods
- `UNIQUE` – identifies distinct departments (requires a compatible Excel version)

The Billing sheet also contains row-level calculations for:

- **Net Bill** = Gross Bill − Discount
- **Outstanding Amount** = Net Bill − Amount Paid
- **Payment Status** = Paid, Partially Paid, or Unpaid


## How to Use

1. Open the workbook in Microsoft Excel.
2. Start with the **Dashboard** sheet to review the KPIs, charts, and summary analysis.
3. Explore the **Patients**, **Doctors**, **Admissions**, and **Billing** sheets to understand the source data.
4. Inspect the formulas in the Billing and Dashboard sheets to understand how the calculations work.
5. If you add or replace source records, make sure the formulas and chart source ranges cover the updated data.
6. Use the **Data Dictionary** sheet whenever you need clarification about a column.


## Project Objectives

- Practise cleaning, organizing, and analysing structured data in Excel.
- Calculate hospital operational and financial KPIs.
- Analyse admissions across departments and months.
- Monitor billing, collections, and outstanding balances.
- Build charts from formula-driven summary tables.
- Present data in a clear dashboard format for reporting and decision-making practice.

## Important Note

All names and records in this workbook are fictional and generated for educational and portfolio purposes. This project is not based on real patient records and must not be used for clinical, operational, or financial decisions.
