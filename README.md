## Loan Default & Risk Analysis Dashboard
## Problem Statement

This dashboard provides an end-to-end analysis of loan performance and borrower risk profiles.
It helps financial institutions identify default trends, borrower behavior, and factors influencing loan risk, enabling them to minimize default rates and optimize lending strategies.

By analyzing multiple dimensions such as employment type, age group, income bracket, credit score, marital status, and education level, this dashboard offers a holistic view of loan distribution, repayment patterns, and potential high-risk segments.

## Key Insights

- Loan Purpose: Home and Business loans account for the highest loan disbursal amounts, while Education and Auto loans have relatively lower values.

- Income vs Employment Type: Full-time employees have the highest average income, while unemployed individuals show lower loan accessibility and higher default risk.

- Default Trends: Default rates are highest among unemployed and part-time borrowers, indicating a correlation between job instability and credit risk.

- Age Analysis: Middle-aged adults and adults account for the largest share of total loans, whereas teenagers and senior citizens borrow smaller amounts.

- Credit Score Impact: Borrowers with lower credit score bins tend to have higher loan amounts but also exhibit greater risk of default.

- Education Level: Loan disbursement is highest among Bachelor’s degree holders, gradually decreasing with higher educational levels.

- Yearly Trends: Default rates fluctuated between 2013–2018, with noticeable peaks around 2015 and 2017, followed by improvements later.

- Marital & Financial Behavior: Married applicants tend to have higher total loans compared to single or divorced applicants, especially among medium and high credit score categories.

## Steps Followed

Data Import & Model Setup

- step 1: understanding the data and Business Requirement

- step 2: Built an automated dataflow pipeline connecting Microsoft SQL Server to Power BI

- step 3: Data Cleaning & Preparation

- step 4: Verified data in Power Query Editor using Column Quality, Distribution, and Profile for missing or erroneous values.

## DAX Measures Created

Measures Table 1:

AVG income by employment type

AVG loan by Age group

default rate by employment type

loan amount by purpose

default rate by year

Measures Table 2:

AVG loan amount(by credit)

loans by education type

Median by Credit Score bins

Total loan(credit bins)

total loan(middle age adults)

Measures Table 3:

YOY default loan change

YOY loan amount change

YTD loan amount

Dashboard Design

## Created a three-page interactive dashboard:

Loan Default & Overview – Overview of loan purpose, income-employment type, and yearly default rate.

Applicant Demographics & Financial Profile – Visuals by credit score, education level, marital status, and mortgage/dependent analysis.

Financial Risk Metrics – Trend analysis for year-on-year loan and default changes, YTD loan performance, and Sankey visualization for income–employment relationships.


In short, the Loan Default & Risk Analysis Dashboard delivers actionable insights to reduce non-performing loans and improve portfolio quality across customer segments.

## Snapshot of dashboard,

"https://github.com/user-attachments/assets/f51478ee-6b56-4e1e-8028-0e1a90c5ca29"
