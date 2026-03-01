# 📊 Excel Business Intelligence-AtliQ Hardwares – Sales Performance Analytics

📊 From Raw Sales Data to Executive Insights
Sales Analytics Dashboard – AtliQ Hardwares

## Sales Analytics Report
### Customer Performance Report - https://github.com/prajwal-555/Excel-Business-Intelligence-Sales-Finance-Reporting/blob/main/Customer%20Performance%20Report.pdf
### Market Performance vs Target - https://github.com/prajwal-555/Excel-Business-Intelligence-Sales-Finance-Reporting/blob/main/Market%20Performance%20vs%20Target.pdf

## 🧩 The Story Behind the Data

Between 2019 and 2021, AtliQ Hardwares experienced explosive revenue growth:

   - 2019: $87.5M

   - 2020: $196.7M

   - 2021: $598.9M

   - 📈 304.5% growth in just three years


At first glance, this looks like a massive success story.

But one critical question remained:

If revenue is growing this fast… why are markets still missing their targets?

This project was built to answer that question.

## 🎯 The Business Challenge

Leadership needed clarity on:

 - Which customers are driving growth?

 - Which markets are underperforming?

 - Why are targets being missed despite strong revenue?

 - Where should strategic focus shift next?

The existing reports were static spreadsheets — no relationships, no modeling, no real insights.

I transformed this into a dynamic, executive-ready analytics solution.

## 🛠️ How I Solved It
### Step 1️⃣ – Extract

Imported raw customer and market sales reports into Excel.

### Step 2️⃣ – Transform (Power Query)

Cleaned and structured the data using ETL methodology:

 - Standardized revenue formats (USD)

 - Removed inconsistencies

 - Normalized tables

 - Structured into fact and dimension tables

 - Created a scalable model foundation

### Step 3️⃣ – Load (Power Pivot Data Model)

Built a relational data model:

 - Fact Table → Sales

 - Dimension Tables → Customer, Market, Date

 - Created relationships for dynamic filtering

This allowed true analytical capability instead of flat reporting.

## 📊 Key DAX Measures

Examples of calculated measures created using DAX:
 - Net Sales - =SUM(fact_sales_monthly[net_sales_amount])
 - Net Sales 19 - =CALCULATE([Net Sales],dim_date[FY]="2019")
 - Net Sales 20 - =CALCULATE([Net Sales],dim_date[FY]="2020")
 - Net Sales 21 - =CALCULATE([Net Sales],dim_date[FY]="2021")
 - 21 vs 20 - =DIVIDE([Net Sales 21],[Net Sales 20],0)
 - target 21 - =SUM(ns_targets_2021[ns_target])
 - 2021-Target - =[Net Sales 21]-[target 21]


## 📖 What the Data Revealed
🚀 1. Growth Was Real — But Uneven

Top 2021 Customers:

 - Amazon – $82.1M

 - AtliQ Exclusive – $61.1M

 - AtliQ e Store – $53.0M

 - Several customers grew over 400% YoY.

📌 Insight: Growth was heavily concentrated among key accounts.

## 🌍 2. High Revenue ≠ Target Achievement

Despite record-breaking sales:

 - Overall 2021 target shortfall: -$54.9M (-8.4%)

 - USA missed target by -$10.2M

 - India missed target by -$9.6M

📌 Insight: Targets may have been overly aggressive or misaligned with market realities.

## 📊 3. Revenue Dependency Risk

Top 5 markets contributed a significant share of total revenue:

 - India – $161.3M

 - USA – $87.8M

 - South Korea – $49.0M

 - Canada – $35.1M

 - United Kingdom – $34.2M

📌 Insight: Heavy reliance on key markets increases strategic risk.

## 💡 Business Recommendations

Based on the analysis:

 - Re-evaluate target-setting methodology

 - Diversify revenue concentration across markets

 - Strengthen growth strategy for mid-tier customers

 - Investigate persistent underperformance gaps

## 🎨 Dashboard Capabilities

 - The final solution includes:

 - Interactive Filters (Market, region, division)

 - YoY trend visualizations

 - Target vs Actual comparisons

 - Contribution analysis

 - Executive-ready summary view

Built entirely with:

 - Microsoft Excel

 - Power Query

 - Power Pivot

 - DAX

## 📌 What Makes This Project Strong

This is not just a dashboard.

It demonstrates:

 - End-to-end ETL workflow

 - Relational data modeling inside Excel

 - Business-first thinking

 - Analytical storytelling

 - Executive-level insight generation


## 🎯 Technical & Soft Skills:
- [x]	Proficiency in ETL methodology (Extract, Transform, Load).
- [x]	Skills to generate a date table using Power Query.
- [x]	Ability to derive fiscal months and quarters.
- [x]	Establishing data model relationships with Power Pivot.
- [x]	Proficiency in incorporating supplementary data into an existing data model.
- [x]	Utilizing DAX to create calculated columns.

## 🎯 Soft Skills:
- [x]	Refined understanding of Sales & Finance Reports
- [x]	Designing user-centric reports with empathy in mind.
- [x]	Optimization of report generation through meticulous fine-tuning.
- [x]	Developing a systematic approach to devising a report building plan.
