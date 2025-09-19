# 📊 Sales Insights Dashboard

## 📌 Overview
This project is an **interactive Power BI dashboard** designed to analyze company sales performance.  
It provides insights into **revenue, sales trends, top customers, top products, and regional performance**.

---

## 🚀 Features
- **KPIs**
  - Total Revenue: `984.81M`
  - Total Sales Quantity: `2M`
- **Revenue by Market** – Breakdown of revenue across regions (Delhi NCR, Mumbai, Ahmedabad, etc.)
- **Sales Quantity by Market** – Sales volume distribution across cities
- **Revenue Trend** – Line chart showing sales performance from 2017–2020
- **Top 5 Customers** – Highest revenue-generating customers (e.g., Electricalsara Stores – 413M)
- **Top 5 Products** – Most sold products (e.g., Prod040 – 24M)

---

## 📂 Data Model
The project uses structured tables:

- `sales transactions` – Fact table with sales records  
- `sales customers` – Customer details  
- `sales products` – Product details (code, type, etc.)  
- `sales markets` – Market/region information  
- `sales employees` – Employee/sales rep data  
- `sales date` – Calendar/date table for time intelligence  

---

## 🛠️ Tools & Technologies
- **Power BI Desktop** – Data modeling, visualization, dashboard creation  
- **SQL / Power Query** – Data cleaning and transformation  
- **DAX (Data Analysis Expressions)** – Custom measures and KPIs  

---

## 📈 Key Insights
- **Delhi NCR** is the top market in both revenue and sales quantity  
- **Electricalsara Stores** is the top customer, contributing 413M revenue  
- **Product 040** is the best-selling product with 24M revenue  
- Sales show **volatility from 2017–2020**, peaking in early 2018 but declining after 2019  

---

## 📊 How to Use
1. Open the Power BI report file (`.pbix`).  
2. Use filters/slicers (Year, Date) to analyze data dynamically.  
3. Explore KPIs, charts, and insights across visuals.  

---

## 📌 Future Improvements
- Add **profitability analysis** (Revenue vs. Cost)  
- Implement **forecasting** for sales trends  
- Apply **row-level security (RLS)** for data access control  
- Add **map visuals** for geographical insights  

---
