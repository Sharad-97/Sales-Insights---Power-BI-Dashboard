# 📊 Sales Insights: Revenue, Market & Profitability Analysis Dashboard

An interactive dashboard built to analyze enterprise sales data focusing on revenue trends, market performance, customer contribution, and profitability to support strategic business decisions.

---

## 🎯 Purpose

The Sales Insights Dashboard is a visually engaging and analytical Power BI report designed to help organizations monitor sales performance, revenue growth, and profit margins across multiple markets and customers. This project transforms raw transactional data using SQL and Power BI, enabling management and MIS teams to quickly identify high-performing regions, profitable customers, and areas impacting overall margins.

---

## 🛠 Tech Stack

- 🛢 SQL (MySQL) – Data exploration, joins, filtering, aggregation, and validation of business metrics  
- 📂 Power Query – Data cleaning, transformation, and currency normalization  
- 🧠 DAX (Data Analysis Expressions) – Calculated measures for revenue, profit margin %, contribution %, KPIs, and trends  
- 🧩 Data Modeling – Fact and dimension tables (transactions, customers, markets, products, date) connected for accurate cross-filtering  
- 📊 Power BI Desktop – Dashboard development and interactive visualization  

---

## 📁 Data Source

**Source:** Simulated enterprise sales dataset.  
The dataset represents real-world business sales transactions and includes customer master data, a transactions table containing sales amount, product codes, market codes, and currency, along with regional sales markets data such as Delhi NCR, Mumbai, Chennai, Ahmedabad, etc. It also includes a date table. The data spans multiple years (2017–2020) and supports market-level, customer-level, product-level, and time-based analysis.

---

## ⭐ Features & Highlights

### Business Problem
Sales organizations often face challenges such as:
- Limited visibility into market-wise revenue and profitability  
- Difficulty identifying high-revenue but low-margin customers  
- Manual and time-consuming Excel-based MIS reporting  
- Inconsistent analysis due to currency differences / duplicate values (INR vs USD)  

### Goal of the Dashboard
- Build an end-to-end sales insights solution using SQL and Power BI  
- Enable management to:
  - Track revenue, sales quantity, and profit margins  
  - Compare performance across markets and customers  
  - Monitor trends over time  
- Replace static reports with an interactive, dynamic dashboard  

---

## 📊 Walkthrough of Key Visuals

1. **Key KPIs (Top Section):**  
   Total Revenue: ₹985M, Total Sales Quantity: 2M, Total Profit Margin: ₹24.7M, Profit Target Indicator (2%)

2. **Market Performance Analysis:**  
   Revenue by Market, Sales Quantity by Market (Helps identify dominant markets such as Delhi NCR and Mumbai)

3. **Customer & Product Analysis:**  
   Top Customers by Revenue, Top Products by Revenue (Highlights revenue concentration and key business drivers)

4. **Time-Based Trend Analysis:**  
   Yearly and monthly revenue trends (2017–2020), helps detect seasonality, growth patterns, and recent performance shifts

5. **Profitability Insights:**  
   Profit % by Market, Profit Contribution % by Market, Customer-level profitability table showing (Revenue contribution %, Profit margin, Profit contribution %) – enables identification of loss-making customers and low-margin markets

---

## 📈 Business Impact & Insights

- Better Decision-Making: Leadership can track whether revenue growth is translating into sustainable profit  
- Market Optimization: Highlights markets with strong sales but weak margins  
- Customer Profitability Management: Helps prioritize profitable customers and reassess low-margin accounts  
- MIS Automation: Reduces manual reporting efforts and improves reporting consistency  
- Strategic Focus: Encourages margin-driven growth rather than revenue-only targets  

---
