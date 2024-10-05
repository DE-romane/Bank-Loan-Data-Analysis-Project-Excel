# Bank Loan Data Analysis Project (Excel)

## Overview
The **Bank Loan Data Analysis Project** was developed to monitor, assess, and provide insights into a bank's lending activities and overall performance. The project was created using **Excel**, leveraging pivot tables, charts, and formulas to enhance data-driven decision-making. By visualizing key metrics, the project aims to assist the bank's strategic planning and improve lending operations.

## Data Source
The project uses data from the file `bank_loan_dataset.csv`, which was loaded into Excel for analysis. The dataset contains the following fields:

### Data Fields
- **Loan ID**: Unique identifier for loans.
- **Address State**: Location of the borrower for regional analysis.
- **Employment Length**: Indicator of employment stability.
- **Employee Title**: Job title for income source verification.
- **Grade/Sub Grade**: Creditworthiness and risk classification.
- **Home Ownership**: Housing status, used to assess financial stability.
- **Issue Date**: Loan origination date.
- **Loan Status**: Current state of the loan (e.g., paid, delinquent) for tracking performance.
- **Purpose**: The reason for the loan, allowing for segmentation and customization.
- **Term**: Loan duration (e.g., 36 months, 60 months).
- **Verification Status**: Status of financial verification.
- **Annual Income**: Yearly earnings of the borrower, reflecting creditworthiness.
- **DTI**: Debt-to-income ratio, an indicator of financial burden.
- **Instalment**: Monthly repayment amount.
- **Interest Rate**: Cost of borrowing.
- **Loan Amount**: Principal amount borrowed.

These fields play a critical role in managing loans, assessing borrower risk, structuring loan terms, and making informed lending decisions.

## Problem Statement
The main goal of the project is to create a comprehensive **Bank Loan Report** that provides insights into key loan metrics and performance over time. The report is divided into **three dashboards** to support data-driven decision-making in the bank's lending strategy.

## Dashboard 1: Summary
![Summary]()

The Summary Dashboard provides an overview of the bank's lending activities and performance through the following **Key Performance Indicators (KPIs)**:
1. **Total Loan Applications**: Calculate the total number of loan applications and track Month-to-Date (MTD) and Month-over-Month (MoM) changes.
2. **Total Funded Amount**: Analyze the total amount of funds disbursed as loans and observe MTD and MoM variations.
3. **Total Amount Received**: Monitor the total repayment amount from borrowers, with MTD and MoM comparisons.
4. **Average Interest Rate**: Calculate the average interest rate across loans, highlighting MTD and MoM trends.
5. **Average Debt-to-Income Ratio (DTI)**: Evaluate the average DTI of borrowers and track MTD and MoM fluctuations.

### Good Loan vs. Bad Loan KPIs
To assess loan performance, the project distinguishes between **Good Loans** (e.g., "Fully Paid" or "Current" status) and **Bad Loans** (e.g., "Charged Off" status). KPIs for each category include:
- **Good Loan KPIs**: 
  - Good Loan Application Percentage, Total Good Loan Applications, Funded Amount, and Total Received Amount.
- **Bad Loan KPIs**: 
  - Bad Loan Application Percentage, Total Bad Loan Applications, Funded Amount, and Total Received Amount.

## Dashboard 2: Visual Overview
[Summary](Summary.png)

This dashboard features a variety of **charts** for visualizing loan data:
1. **Monthly Trends (Line Chart)**: Displays trends in loan applications, funded amounts, and received amounts over time.
2. **Regional Analysis (Filled Map)**: Highlights lending activity by state, showing regional disparities.
3. **Loan Term Analysis (Donut Chart)**: Visualizes loan applications and amounts based on different loan terms.
4. **Employee Length Analysis (Bar Chart)**: Shows how loan metrics vary across employment lengths.
5. **Loan Purpose Breakdown (Bar Chart)**: Categorizes loans by purpose, illustrating the main reasons for borrowing.
6. **Home Ownership Analysis (Tree Map)**: Displays lending metrics based on home ownership status.

## Dashboard 3: Details
![Summary]()

The **Details Dashboard** consolidates all loan data into a comprehensive view, offering a detailed snapshot of key metrics such as loan applications, amounts, interest rates, and borrower profiles. This dashboard serves as a centralized interface for accessing and analyzing critical information.

## Data Validation
To ensure the accuracy and integrity of the data, a thorough **data validation** process was implemented:
- Data from `bank_loan_dataset.csv` was loaded into both **Excel** and **SQL Server**.
- SQL queries were run to verify data accuracy and integrity, ensuring consistency between Excel and the database.
- KPI calculations in Excel were cross-verified using SQL scripts to confirm reliability.

Validation steps can be reviewed in the file "Data-Validation-SQL.pdf."

## Conclusion
This **Bank Loan Dashboard** project provides a reliable, validated, and visually rich report on the bank's lending activities. With the combination of intuitive visualizations and robust data validation techniques, the project supports informed decision-making, helping the bank optimize its loan portfolio and lending strategy.
