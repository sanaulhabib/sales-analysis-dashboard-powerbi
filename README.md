# sales-analysis-dashboard-powerbi
Power BI sales dashboard with KPI cards, trend &amp; regional analysis

## 📌 Project Overview

This project looks at a company's sales data and turns it into an easy-to-read dashboard. The data covers 5 regions, more than 20 product types, and different order channels, over about 20 months (Feb 2025 – Oct 2026).

I cleaned the raw data, organized it properly, and built an interactive Power BI dashboard. The dashboard shows total sales, profit, cost, profit margin, total order, avg. order value, monthly sales trend, sales vs profit by region and how each region, product, channel and segment is performing.


## 🖼️ Dashboard Preview
<img width="1024" height="587" alt="sales-analysis-dashboard" src="https://github.com/user-attachments/assets/3ed22ed4-37ac-412a-bc5f-ed64d9853053" />

## 🎯 Business Problem

The company sells in 5 regions and has more than 20 types of products. But the sales data was spread across different spreadsheets, so it was hard to see the full picture. Management needed to answer some simple business questions :
- Is the company reaching its monthly sales target?
- Which products and regions have the highest sales?
- Which customer segment and sales channels bring in the most money?
- What are the top 10 products?
- Who are the top 10 customers?

## 💡 Solution
I combined 23 Excel tables into one connected data model, then built an interactive Power BI dashboard showing total sales, profit, profit margin,  and region wise performance that can be filter by Region, Category, Channel and Date.

## 🔄 Project Workflow

- **Extracted the data** — Imported the messy raw Excel data into Power BI
- **Cleaned the data** — Used Power Query to fix nulls, remove duplicates, trim extra spaces, fix capitalization, handle errors, and fill missing values
- **Identified Fact and Dimension tables** — Sorted the tables into facts (transactions) and dimensions (products, customers, dates, etc.)
- **Connected the tables** — Built relationships between the fact and dimension tables
- **Built the data model** — Organized everything into a clean star schema
- **Created measures with DAX** — Wrote DAX calculations for Total Sales, Total Cost, Total Profit, Profit Margin, and other KPIs
- **Built the dashboard** — Created KPI cards, charts, and filters to show sales, profit, and performance

## 🔍 Key Insights
- Total sales is 526.64k with 36.9% profit margin
- Europe leads in sales (167K) and Latin America is the lowest (41K)
- Electronics is the highest selling category
- Team M047 is the highest selling product
- Summit Commerce is the top customer

## ✅ Recommendations
- **Set realistic sales target:** Targets are missed almost every month, set targets using real past sales
- **Invest in Latin America:** Sales is 4x lower than Europe (41K vs. 167K), review marketing and account coverage there
- **Expand Electronics:** This is the top sales category (152.7K), increase stock priority
- **Protect top customers:** The top 10 customers bring in most of the money, keep them happy with good service or rewards, and try to get more new customers too

## ▶️ How to Explore

1. Download [`sales_data_analysis.pbix`](sales_data_analysis.pbix)](https://github.com/sanaulhabib/sales-analysis-dashboard-powerbi/blob/main/03-dashboard-file/sales_data_anaylsis.pbix)
2. Open it in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
3. Use the slicers (Region, Category, Year/Month, Channel) to explore the data interactively
