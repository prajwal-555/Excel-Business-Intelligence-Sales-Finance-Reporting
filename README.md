# 📊 Excel Business Intelligence-AtliQ Hardwares – Sales Performance Analytics

An end-to-end **Sales Analytics portfolio project** built using **Advanced Excel**, **Power Query**, **Power Pivot**, and **DAX**, focused on evaluating **customer sales performance** and **market performance vs targets**.

This project demonstrates a real-world **sales reporting and analytics workflow**, following a structured **ETL (Extract, Transform, Load)** methodology and delivering actionable, decision-ready insights

📊 From Raw Sales Data to Executive Insights
Sales Analytics Dashboard – AtliQ Hardwares

## 🚀 Sales Analytics Report
### 📂 Customer Performance Report - https://github.com/prajwal-555/Excel-Business-Intelligence-Sales-Finance-Reporting/blob/main/Customer%20Performance%20Report.pdf
### 📂 Market Performance vs Target - https://github.com/prajwal-555/Excel-Business-Intelligence-Sales-Finance-Reporting/blob/main/Market%20Performance%20vs%20Target.pdf

---

## 📌 Table of Contents
- 📖 Project Overview
- 🎯 Business Objective
- 🛠 Tools & Technologies
- 🔄 ETL Methodology
- 🧱 Data Model
- 📐 Key Metrics
- 📊 Analysis & Insights
- 🎛 Excel Dashboard Overview
- 📂 Repository Structure
- 💡 Skills Demonstrated
- 🚀 Future Improvements

---

## 📖 Project Overview
This project analyzes **sales performance data** to understand:
- How customers and markets have grown over time
- Which customers drive the most revenue
- How actual sales compare against predefined targets
- Where performance gaps exist across regions and markets

All analysis is performed entirely in **Microsoft Excel**, leveraging its modern analytics capabilities.

---

## 🎯 Business Objective
The project is designed to answer key business questions such as:
- 👥 Which **customers are driving the highest sales growth**?
- 🌍 How are different **markets performing against targets**?
- 📉 Where are the **largest shortfalls vs targets**, and how significant are they?
- 📈 Which customer segments show **strong YoY momentum**?

The insights support **sales leadership, business reviews, and strategic planning**.

---

## 🛠 Tools & Technologies
- 🧮 **Microsoft Excel (Advanced)**
- 🔄 **Power Query** – Data extraction, transformation, and cleaning
- 🧱 **Power Pivot** – Data modeling and relationships
- 📐 **DAX (Data Analysis Expressions)** – Measures & KPIs
- 📊 Pivot Tables & Pivot Charts
- 🎛 Interactive Excel Dashboards

---

## 🔄 ETL Methodology (Extract, Transform, Load)

### 📥 1. Extract
- Imported **customer-level sales reports** and **market performance vs target reports**
- Source data provided in semi-structured, report-style formats

### 🔧 2. Transform
Data cleaning and transformation performed using **Power Query**:
- 🧹 Removed blank rows and unnecessary formatting
- 🏷 Standardized customer and market names
- 🔄 Reshaped wide tables into analysis-ready structures
- 📅 Created fiscal year and YoY comparison fields
- ✅ Ensured consistent units and currency (USD)

### 📤 3. Load
- Loaded cleaned data into the **Excel Data Model**
- 🧩 Built fact and dimension tables
- 🔗 Established relationships using **Power Pivot**

---

## 🧱 Data Model
The data model follows a **star-schema-inspired approach**:
- ⭐ **Fact Tables**:
  - Customer Sales Performance
  - Market Performance vs Target
- 📂 **Dimension Tables**:
  - Customer
  - Market
  - Fiscal Year

This enables fast slicing, filtering, and scalable analysis using Pivot Tables and DAX.

---

## 📐 Key Metrics (DAX)
Key measures created include:
- 💰 Net Sales - =SUM(fact_sales_monthly[net_sales_amount])
- 💰 Net Sales 19 - =CALCULATE([Net Sales],dim_date[FY]="2019")
- 💰 Net Sales 20 - =CALCULATE([Net Sales],dim_date[FY]="2020")
- 💰 Net Sales 21 - =CALCULATE([Net Sales],dim_date[FY]="2021")
- 📊 21 vs 20 - =DIVIDE([Net Sales 21],[Net Sales 20],0)
- 🎯 target 21 - =SUM(ns_targets_2021[ns_target])
- 📉 2021-Target - =[Net Sales 21]-[target 21]

All KPIs dynamically update based on filters.

---

## 📊 Analysis & Insights (Examples)

### 👥 Customer Performance Analysis
- Multiple customers show **exceptional YoY growth** from 2020 to 2021
- Large enterprise and e-commerce customers contribute a significant share of total revenue
- Long-tail customers collectively add meaningful incremental growth

### 🌍 Market Performance vs Target
- **Overall sales fell short of targets**, indicating execution or demand challenges
- Some markets narrowly missed targets, while others show **double-digit % shortfalls**
- High-revenue markets still present **opportunities for optimization and recovery**

### 📈 Growth vs Scale
- High-growth customers are not always the largest contributors
- The analysis helps identify:
  - Customers to **protect and expand**
  - Markets requiring **corrective actions**

---

## 🎛 Excel Dashboard Overview
The Excel dashboard includes:
- 📌 **Sales Overview KPIs**
- 👥 **Customer-wise Sales & YoY Growth**
- 🌍 **Market Performance vs Target**
- 📉 **Variance Analysis (Actual vs Target)**
- 🎚 Interactive slicers for Year, Market, and Customer

> The dashboard is fully interactive and built using Pivot Charts connected to the Data Model.

---

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
