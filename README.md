# 🧠 Buyer Sense – Customer Behaviour Analysis (End-to-End Project)

![Project Overview](images/BuyerSense_Dashboard.png)

> An end-to-end **Customer Behaviour Analysis** project by **Vivek Sharma**, built using **Python, SQL, and Power BI**, designed to explore, analyze, and visualize buyer patterns to support data-driven decision-making.

---

## 🚀 Project Overview

**Buyer Sense** aims to analyze customer purchase patterns, segment users based on their behavior, and visualize insights to help businesses understand their customers better.  
This project follows the **complete data analytics lifecycle** — from data collection and cleaning to visualization and reporting.

---

## 🧩 Key Features

- 🧹 Data cleaning & preprocessing using **Python (Pandas, NumPy)**
- 🗃️ Data storage and querying with **MySQL**
- 📊 Interactive dashboards in **Power BI**
- 🔍 Customer segmentation & trend analysis
- 📈 Insightful visual reports for better business strategies

---

## 🧰 Tech Stack

| Category | Tools & Technologies |
|-----------|----------------------|
| Programming | Python |
| Database | MySQL |
| Visualization | Power BI |
| Libraries | Pandas, NumPy, Matplotlib, Seaborn |
| Version Control | Git & GitHub |

---

## 📂 Project Workflow

1. **Data Collection** → Raw dataset imported into Python  
2. **Data Cleaning & Transformation** → Handled missing values, outliers, and formatted data  
3. **Data Storage** → Cleaned data pushed into MySQL database  
4. **Data Analysis** → SQL queries and Python analytics for customer behavior  
5. **Visualization** → Power BI dashboards showing patterns, frequency, and insights  

---

## 📸 Project Dashboard Preview

*(Replace the image below with your Power BI dashboard screenshot)*  
![Dashboard Screenshot](images/powerbi_dashboard.png)

---

## 🧮 SQL Integration

SQL was used for:
- Filtering customer segments  
- Aggregating purchase data  
- Generating behavior-based KPIs  

Example:
```sql
SELECT 
    customer_id,
    COUNT(order_id) AS total_orders,
    SUM(order_amount) AS total_spent
FROM customer_orders
GROUP BY customer_id
ORDER BY total_spent DESC;
