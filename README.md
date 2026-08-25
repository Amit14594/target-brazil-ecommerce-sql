# Target Brazil E-Commerce — SQL Case Study

**Domain:** Retail / E-commerce Analytics  
**Tools:** SQL (BigQuery), Data Analysis  
**Dataset:** ~100,000 orders from Target’s Brazil operation (2016–2018)

---

## 📌 Problem Statement

Target is expanding its e-commerce presence. This project analyzes order-level data covering customers, orders, order items, payments, products, sellers and geolocation to extract business insights that can support growth strategy in Brazil.

---

## 🎯 Objectives

1. Explore the structure and quality of the dataset
2. Understand evolution of e-commerce orders over time
3. Analyze impact on economy (orders, revenue trends)
4. Deep-dive into Sales, Freight & Delivery Time performance
5. Analyze payment methods and installment behavior
6. Generate actionable business recommendations

---

## 🛠️ Tech Stack

- **SQL** (Google BigQuery syntax + local validation)
- Window functions, CTEs, Joins, Aggregations, Date functions

---

## 📊 Key Analyses Performed

| Section | Focus Area |
|---------|------------|
| I. Initial Exploration | Data types, time range, cities & states coverage |
| II. In-Depth Exploration | Customer & order behavior patterns |
| III. Evolution of Orders | Monthly/yearly growth trends in Brazil |
| IV. Impact on Economy | Revenue and order volume contribution |
| V. Sales, Freight & Delivery | Freight cost vs delivery time, late deliveries |
| VI. Payments Analysis | Payment type preference, installment trends |
| VII. Insights & Recommendations | Strategic takeaways for expansion |

---

## 💡 Sample Business Insights

- Orders spanned **Sep 2016 – Oct 2018** across **4,119 cities** and all **27 Brazilian states**.
- Demand is heavily concentrated in a few high-population states (SP, RJ, MG, etc.).
- Delivery performance and freight cost show clear regional variation — opportunity for logistics optimization.
- Payment method and installment behavior reveal customer purchasing power segments.

*(Full query results and detailed insights are in the PDF report.)*

---

## 📁 Repository Structure

```
├── README.md
├── queries/
│   ├── 01_initial_exploration.sql
│   ├── 02_in_depth_exploration.sql
│   ├── 03_evolution_of_orders.sql
│   ├── 04_economy_impact.sql
│   ├── 05_sales_freight_delivery.sql
│   └── 06_payments_analysis.sql
├── insights/
│   └── business_recommendations.md
└── Target_SQL_Case_Study.pdf          # Full report with results
```

---

## 🚀 How to Run

1. Load the Target Brazil public dataset (or equivalent) into BigQuery / any SQL engine.
2. Execute queries section-wise from the `/queries` folder.
3. Compare results with the insights documented in the PDF.

---

## 📈 Skills Demonstrated

- Advanced SQL (multi-table joins, window functions, date arithmetic)
- Business-oriented analysis & storytelling
- Translating raw data into strategic recommendations

---

**Author:** Amit Narendra Adikane  
**LinkedIn:** [amit-adikane](https://www.linkedin.com/in/amit-adikane-4060a91b1/)

---
