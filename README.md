# Insurance-Analytics-PowerBI
Insurance Analytics Power BI Dashboard  A complete end–to–end data analysis project built using MS SQL Server, Power BI Desktop, Power Query &amp; DAX. This dashboard visualizes key insurance metrics like premium, claims, coverage, age insights, and policy activity status, helping stakeholders quickly understand business performance.

📊 Insurance Analytics Dashboard — Power BI + SQL Server

This project is a complete Insurance Data Analysis Dashboard built using
Microsoft SQL Server (SSMS) for data loading & processing and Power BI for visualization.

It covers everything from data import → cleaning → modeling → DAX → visuals → publishing → RLS.

🔥 Project Overview

This project analyzes Insurance policy, premium, customer, and claim details.
It provides insights such as:

Total Premium Collected

Total Coverage Amount

Total Claim Amount

Claim Status Analysis

Customer Activity (Active vs Inactive)

Age-based claim trends

Policy Type performance

Gender-wise customer distribution

Sentiment & Text analytics on feedback

🏗 Tools & Technologies Used

SQL Server Management Studio (SSMS)

Power BI Desktop

DAX Calculations

Power Query Editor

Import Data / Modeling / RLS / Publishing

📥 Data Import & Preprocessing

Created database: InsuranceDB

Imported dataset using:
Right Click → Tasks → Import Flat File → Browse → Load

Verified Column Quality, Column Distribution, Column Profile

Cleaned data:

Removed empty rows

Fixed data types

Standardized dates

Created new calculated columns

🧮 Calculated Columns Created
1. Age Group

Logic:

Age ≤ 24 → Young

Age ≤ 60 → Adult

Else → Senior

2. Active / Inactive Policy

Logic:

Policy End Date ≤ 10-12-2024 → Inactive

Else → Active

3. Text Sentiment Classification

Based on sentiment score:

Score ≥ 0.8 → Excellent

Score ≥ 0.6 → Good

Else → Improvement Needed

📈 Key Visuals Included
✔ Cards

Total Premium

Total Coverage Amount

Total Claim Amount

✔ Slicers

Policy Number

Claim Number

Customer ID

Dates

✔ Multi-row Cards

Count of Male

Count of Female

✔ Ribbon Chart

Claims by Claim Status

✔ Bar Charts

Premium Amount by Policy Type

Claim Amount by Policy Type

✔ Line / Area Chart

Claim Amount by Age Group

✔ Donut Charts

Active vs Inactive Policies

✔ Matrix View

Policy Type vs Claim Status vs Coverage Amount

🔐 Row Level Security (RLS)

Implemented RLS based on Policy Type:

Example:

Travel → Only sees Travel data

Home → Only sees Home data

Vehicle → Only sees Vehicle data

Tested in Power BI Desktop and Power BI Service.

🌐 Power BI Service Publishing

Created Workspace

Published Report

Scheduled Refresh

Enabled RLS

Shared dashboard with users

Dashboard_screenshot:

1...
<img width="1743" height="778" alt="image" src="https://github.com/user-attachments/assets/f394cc39-7eac-42a2-8183-3aac99c2dbb3" />
2..
<img width="1699" height="845" alt="image" src="https://github.com/user-attachments/assets/a593f728-fd34-4e9b-9720-cd1550ca48ed" />


