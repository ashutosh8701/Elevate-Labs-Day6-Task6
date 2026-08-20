# Task 6 — Sales Trend Analysis Using SQL Aggregations

## 🔍 Key Findings

- Dataset contained **500 orders**, **20 products**, **10 cities**, and **100 customers**.
- Generated **₹2,61,178** in total revenue across 2023–2024.
- 2024 revenue reached **₹1,36,329** against **₹1,24,849** in 2023 — representing **9.2% YoY growth**.
- Order volume grew **3.3% YoY** (246 to 254 orders), indicating that growth was driven by **higher order value rather than higher order count**.
- Revenue was near-uniform across quarters (**24.7%–25.6%**), indicating no meaningful seasonality in this dataset.
- **Pune (₹34,404)**, **Kolkata (₹32,341)**, and **Mumbai (₹30,251)** were the top-performing cities.
- **HDD (₹18,900)**, **Mouse (₹18,734)**, and **Smartphone (₹18,464)** generated the highest revenue.
- All **100 customers were repeat buyers**, averaging **5 orders each**.

## 🎯 Objective

The objective of this project was to analyse monthly sales performance by examining revenue trends and order volumes using SQL aggregation functions, grouping operations, and time-based analysis techniques.

## 📊 Dataset Used

- Online Sales Dataset — **500 orders**, 7 fields, 2023–2024

## 🛠️ Tools Used

- MySQL Workbench
- SQL
- CSV Dataset Import

## 🔬 Work Performed

- Imported and structured the online sales dataset in MySQL.
- Wrote **20 SQL queries** covering date conversion, monthly aggregation, year-on-year comparison, and view creation.
- Converted text-based order dates into SQL date format using `STR_TO_DATE()`.
- Extracted month and year information into indexed columns via `ALTER TABLE` and `UPDATE`.
- Used aggregate functions such as `SUM()` and `COUNT(DISTINCT)`.
- Performed monthly revenue and order volume analysis.
- Compared sales performance across **2023 and 2024**.
- Identified top-performing and low-performing months.
- Analysed revenue by city, product, and customer.
- Created SQL views for summarised reporting and analysis.

## 📁 Files Included

- SQL Script File (`.sql`)
- Online Sales Dataset (`.csv`)
- PDF Report with Findings
- Query Output Screenshots

## 📈 Outcome

Applied SQL aggregation, grouping, filtering, and time-series techniques to quantify a 9.2% year-on-year revenue increase, isolate the value-versus-volume driver behind that growth, and rank markets and products by contribution.
