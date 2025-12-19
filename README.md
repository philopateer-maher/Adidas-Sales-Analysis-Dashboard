# Adidas Sales Analysis Dashboard 📊

## 📖 Project Overview
This project is a comprehensive **Power BI Dashboard** designed to analyze sales data for Adidas. The report transforms raw sales data into actionable insights, focusing on revenue trends, product performance, retailer partnerships, and operational efficiency.

The dashboard features a modern UI with consistent navigation, rounded aesthetic elements, and interactive AI-driven visuals.

## 🔍 Dashboard Structure
The report is divided into 4 strategic pages, each answering specific business questions:

### 1. Executive Overview (High-Level Trends)
* **Goal:** Assess overall business health over time and geography.
* **Key Visuals:**
    * Monthly Revenue & Profit Trends (Area Chart).
    * Geographic Sales Heatmap (Map).
    * Regional Market Share (Donut Chart).
    * Top 10 Cities by Revenue.

### 2. Product Performance
* **Goal:** Identify which products drive volume versus those that drive profit.
* **Key Visuals:**
    * **"Magic Quadrant" Analysis:** Scatter plot comparing Volume vs. Profit Margin.
    * Product Sales Ranking (Bar Chart).
    * Profit Contribution (Tree Map).
    * Monthly Unit Volume trends (Stacked Column Chart).

### 3. Retailer & Channel Analysis
* **Goal:** Evaluate partner performance and sales channel efficiency (Online vs. In-Store).
* **Key Visuals:**
    * Detailed Retailer Financial Matrix (Custom styled with calculated margins).
    * Revenue Share by Sales Method.
    * Channel Growth Trends.

### 4. Efficiency & Profitability Deep Dive
* **Goal:** Analyze where money is being made or lost using advanced AI analytics.
* **Key Visuals:**
    * **Decomposition Tree:** AI-driven root cause analysis for Profit Margin %.
    * Revenue vs. Margin Correlation trends.
    * Sales Volume Funnel by Region.

## 🛠️ Technical Implementation
* **Data Modeling:** Star schema optimization (separating fact tables from dimension lookups).
* **DAX Measures:** Complex calculations for:
    * `Profit Margin %` (DIVIDE logic to handle errors).
    * `Total Transactions` (COUNTROWS).
    * Time Intelligence (YTD, Growth calculations).
* **UI/UX Design:**
    * Custom rounded card designs with accent bars.
    * Consistent "5-Card KPI" header across all pages.
    * Conditional formatting for financial tables (Millions "M" formatting).

## 🚀 How to Use
1.  Download the `.pbix` file from this repository.
2.  Open the file in **Microsoft Power BI Desktop**.
3.  Use the **Date** and **Region** slicers (synced across all pages) to filter the data.
4.  Interact with the **Decomposition Tree** on Page 4 to explore margin drivers dynamically.

## 📂 Dataset
* **Source:** Adidas US Sales Dataset.
* **Metrics:** Total Sales, Operating Profit, Units Sold, Price per Unit.
* **Dimensions:** Time (Invoice Date), Location (Region, State, City), Product, Retailer.
