# 📊 E‑Commerce Sales Performance Analysis

## 📌 Project Overview
This project delivers an end‑to‑end analysis of e‑commerce sales transactions (11,000+ rows) using **Python, Excel, and Power BI**. The goal is to clean and explore raw sales data, define business KPIs, and build interactive dashboards that provide actionable insights into revenue growth, product trends, regional performance, and customer behavior.

---

## 🎯 Business Objectives
- Track overall sales growth (monthly, yearly).
- Identify top‑performing products and categories.
- Analyze regional sales performance for resource allocation.
- Evaluate sales representative performance.
- Assess discount impact on sales and profitability.
- Provide actionable insights for management to improve revenue and margins.

---

## 🗂 Dataset
- **Rows:** 11,000 synthetic transactions
- **Columns:**
  - `OrderID` – unique transaction ID  
  - `OrderDate` – purchase date  
  - `CustomerID`, `CustomerName` – customer details  
  - `Region` – North, South, East, West  
  - `ProductCategory`, `ProductName` – product details  
  - `Quantity`, `UnitPrice`, `Discount` – sales metrics  
  - `PaymentMethod` – Credit Card, Debit Card, PayPal, Cash  
  - `ShippingCost` – delivery charges  
  - `TotalSales` – calculated as `(Quantity × UnitPrice × (1 – Discount)) + ShippingCost`

---

## 🛠️ Tools & Technologies
- **Python (pandas, numpy, matplotlib, seaborn):** Data cleaning, EDA, KPI calculations.
- **Excel:** Raw dataset storage, pivot tables, quick checks.
- **Power BI:** Interactive dashboards, DAX measures, executive reporting.

---

## 🔧 Workflow
1. **Data Preparation (Python & Excel)**
   - Clean missing values, duplicates, and outliers.
   - Validate `TotalSales` calculations.
   - Derive fields: Month, Year, Discount flag, Customer segmentation.

2. **KPI Definition**
   - Total Revenue, Monthly Revenue, MoM & YoY Growth.
   - Average Order Value (AOV).
   - Top Products & Category Contribution.
   - Regional Revenue & Growth.
   - New vs. Repeat Customers, RFM Segmentation.
   - Gross Margin % (based on category cost assumptions).

3. **Dashboard Development (Power BI)**
   - **Executive Summary:** Revenue trend, growth, KPIs.
   - **Product Analysis:** Top categories/products, discount vs. units.
   - **Regional Analysis:** Map/bar chart by region.
   - **Customer Insights:** New vs. repeat share, RFM segments.
   - **Sales Rep Leaderboard:** Performance comparison.

4. **Insights & Recommendations**
   - Electronics drive majority of revenue, but Furniture yields higher margins.
   - Discounts increase unit sales but reduce profitability beyond 20%.
   - North region shows declining trend → targeted promotions recommended.
   - Repeat customers generate 3× higher lifetime value → loyalty programs suggested.

---

## 📑 Deliverables
- `ecommerce_sales_11000.xlsx` – raw dataset.
- `ecommerce_sales_clean.xlsx` – cleaned dataset.
- `notebooks/EDA.ipynb` – Python exploratory analysis.
- `powerbi/dashboard.pbix` – interactive dashboard.
- `reports/summary.pdf` – business insights report.
- Screenshots of Power BI visuals for quick portfolio review.

---

## 📌 Resume Highlights
- Built an **end‑to‑end analytics pipeline** using Python, Excel, and Power BI for 11,000+ transactions.
- Delivered an **interactive dashboard** tracking revenue growth, product performance, and regional trends.
- Identified actionable insights such as **high‑margin categories** and **underperforming regions**, enabling targeted strategies.

---

## 🚀 How to Run
1. Clone the repository.
2. Install Python dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn openpyxl
