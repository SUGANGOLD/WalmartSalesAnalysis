# 🛒 Walmart Sales Data Cleaning and Exploratory Data Analysis (EDA) with SQL

## 📌 Project Overview

This project involves performing **data cleaning** and **exploratory data analysis (EDA)** on a retail sales dataset from a fictional Walmart store using **pure SQL**. The goal is to uncover key business insights related to sales, customers, revenue, products, and time-based trends.

---

## 🗃️ Dataset

- **Source**: `WalmartSalesData.csv`
- **Size**: ~1,000 rows
- **Features**:
  - Invoice ID, Branch, City
  - Customer Type, Gender
  - Product Line, Unit Price, Quantity
  - Tax, Total, Payment Method
  - Date & Time, Rating

---

## 🛠️ Technologies Used

- **MySQL** – Data cleaning, transformation, and querying
- **SQL** – Exploratory data analysis (EDA)
- **DB Tool** – MySQL Workbench / DBeaver (Recommended)

---

## 🔧 Data Cleaning & Feature Engineering

✔️ Created new features:
- `time_of_day` — Morning, Afternoon, Evening (based on sale time)  
- `day_name` — Name of the day from sale date  
- `month_name` — Month of sale  

✔️ Removed redundancies and ensured consistency of:
- City/Branch mappings  
- Product categories  
- Payment methods  

---

## 📊 Key SQL Queries and EDA Insights

### 🏙️ General
- Number of unique cities and branch locations
- Mapping branches to cities

### 📦 Products
- Most sold product lines
- Highest revenue product categories
- Product lines with highest VAT and ratings

### 👥 Customers
- Customer type distribution and buying patterns
- Gender analysis and per-branch distribution
- Time/day-based rating behaviors

### 📅 Time-based Trends
- Sales by day of week and time of day
- Revenue trends by month
- Branch-specific performance and COGS

---

## 📈 Business KPIs Answered

- 📌 Which product line sells the most?
- 💰 Which city or branch generates the most revenue?
- ⏰ What time of day and day of the week sees the highest sales?
- 🧾 Which customer type pays the most VAT?
- 📉 Are there any low-performing product lines or branches?

---

## 📁 Files Included

| File Name                         | Description                                |
|----------------------------------|--------------------------------------------|
| `Walmart_Sales_EDA_SQL_Project.sql` | Main SQL script (cleaning + EDA)         |
| `WalmartSalesData.csv`           | Sample raw dataset                         |
| `Walmart_Sales_EDA_SQL_Project.pdf` | Annotated SQL script in PDF format      |
| `README.md`                      | Project overview and documentation         |

---

## ✅ How to Use

1. Import `WalmartSalesData.csv` into your MySQL database.
2. Run the SQL queries from `Walmart_Sales_EDA_SQL_Project.sql` step-by-step.
3. View results in your SQL client or export them to dashboards.

---

## 💼 Author

**Sugan [Data Analyst | Fresher | Portfolio Builder]**  
📧 *Available for internships & freelance data roles*  
🌐 LinkedIn | GitHub | Portfolio (Add your links here)

---

## 🏁 Conclusion

This project demonstrates how SQL alone can be used to:
- Clean data
- Create new insights
- Answer business questions
- Build real-world portfolio-ready reports

---

