# 📊 Maven Market Retail Analytics Dashboard

[![PowerBI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com)
[![DAX](https://img.shields.io/badge/DAX-15%2B%20Measures-5A189A?style=for-the-badge)](https://learn.microsoft.com/en-us/dax/)
[![SQL](https://img.shields.io/badge/SQL-Data%20Prep-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com)

---

## 📌 Project Overview

An enterprise-grade **5-page Power BI retail analytics dashboard** built on the Maven Market dataset, covering 24 retail stores. Designed to give leadership full visibility into sales performance, customer behavior, product trends, store efficiency, and returns impact — all through a single interactive report.

---

## 🎯 Key Metrics

| Metric | Value |
|--------|-------|
| 📄 Dashboard Pages | **5** |
| 🧮 DAX Measures Created | **15+** |
| 🏪 Stores Analyzed | **24** |
| 📦 Analysis Areas | Sales, Customers, Products, Returns, Store Performance |
| 🔗 Data Model | Star Schema with multiple related tables |

---

## 🗂️ Dashboard Pages

| Page | Focus |
|------|-------|
| 1. Executive Summary | Top-level KPIs — revenue, profit, transactions |
| 2. Sales Analysis | Monthly/yearly trends, region & category breakdown |
| 3. Customer Insights | Segmentation by membership, occupation, retention rate |
| 4. Product Performance | Top products, slow-movers, high-margin items |
| 5. Store Performance | Store-wise sales comparison, growth trends across 24 locations |

---

## 🛠️ Tech Stack

| Category | Tools |
|----------|-------|
| BI & Visualization | Power BI Desktop |
| Calculations | DAX (15+ custom measures) |
| Data Preparation | SQL, Excel |
| Data Modeling | Star Schema, Relationships, Calculated Columns |

---

## 🧮 Sample DAX Measures

```dax
-- Total Revenue
Total Revenue = SUMX(Sales, Sales[Quantity] * RELATED(Products[RetailPrice]))

-- Profit Margin %
Profit Margin % = DIVIDE([Total Profit], [Total Revenue], 0)

-- Return Rate
Return Rate = DIVIDE([Total Returns], [Total Transactions], 0)

-- YoY Revenue Growth
YoY Growth = DIVIDE([Total Revenue] - [LY Revenue], [LY Revenue], 0)
```

---

## 📁 Project Structure

```
maven-market-analysis/
├── 📂 Maven_Market_Analysis/   # .pbix dashboard file + source data
└── 📄 README.md
```

---

## 📈 Key Business Insights

- Identified **top revenue-generating products** by category and region
- Detected **high-value customer segments** based on membership tier and purchase frequency
- Flagged **slow-moving inventory** impacting profitability across stores
- Analyzed **return rate trends** and their impact on net revenue
- Compared **store performance** across all 24 locations to surface underperformers

---

## 🚀 How to Use

1. Clone or download this repository
2. Open the `.pbix` file in **Power BI Desktop** (free download from Microsoft)
3. Explore all 5 dashboard pages using slicers and drill-through filters

---

## 📬 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sonali_More-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sonalim03)
[![GitHub](https://img.shields.io/badge/GitHub-sonalim03-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sonalim03)
[![Email](https://img.shields.io/badge/Email-sonalimore5117@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sonalimore5117@gmail.com)

---

> 💡 *Part of my Data Analyst portfolio. Actively seeking Power BI / Data Analyst roles in Mumbai/Navi Mumbai.*
