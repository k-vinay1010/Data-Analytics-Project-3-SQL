# 📊 Data Analytics Project 3 – SQL Data Analysis

## 📌 Project Overview

This project is part of the **DecodeLabs Data Analytics Industrial Training Program (Batch 2026)**.

Project 3 focuses on **SQL Data Analysis**: using structured queries to filter, group, aggregate, sort, and extract business insights from the e-commerce dataset prepared in Project 1.

The DecodeLabs brief defines the goal as using SQL queries to extract insights from a dataset. Its core requirements are `SELECT`, `WHERE`, `ORDER BY`, `GROUP BY`, and basic aggregations such as `COUNT`, `SUM`, and `AVG`.

---

## 🎯 Project Objectives

- Query the Project 1 e-commerce dataset using SQL
- Filter records using `WHERE`
- Sort results using `ORDER BY`
- Group records using `GROUP BY`
- Calculate business metrics using `COUNT`, `SUM`, and `AVG`
- Use `HAVING` to filter grouped results
- Analyze products, order status, referral sources, payments, coupons, and customers
- Convert transactional records into structured business insights

---

## 📂 Dataset

This project uses the same e-commerce dataset from **Project 1 – Data Cleaning and Preparation**.

- **Records:** 1,200 orders
- **Date range:** January 2023 – June 2025
- **Products:** Chair, Printer, Laptop, Tablet, Monitor, Desk, Phone
- **Measures:** Quantity, Unit Price, Items in Cart, Total Price
- **Dimensions:** Product, Order Status, Payment Method, Coupon Code, Referral Source

---

## 🛠️ Tools & Technologies

- **MySQL 8.0**
- SQL
- Microsoft Excel for reference/output validation
- GitHub

---

## 🔍 SQL Concepts Practiced

- `SELECT`
- `WHERE`
- `ORDER BY`
- `GROUP BY`
- `HAVING`
- `COUNT()`
- `COUNT(DISTINCT ...)`
- `SUM()`
- `AVG()`
- `MIN()`
- `MAX()`
- `LIMIT`
- Multi-column grouping
- Filtering and aggregation

---

## 🔄 Project Workflow

```text
Project 1 Dataset
       ↓
SQL Table Creation
       ↓
Data Loading
       ↓
SELECT & Filtering
       ↓
GROUP BY & Aggregations
       ↓
HAVING & Sorting
       ↓
Business Analysis
       ↓
SQL Insights
```

---

## 📊 Analysis Performed

### 1. Overall Business Summary

Calculated:

- Total orders
- Unique customers
- Total revenue
- Average order value

### 2. Product Performance

Compared:

- Order count
- Units sold
- Total sales
- Average order value

across all products.

### 3. Order Status Analysis

Grouped orders by:

- Delivered
- Shipped
- Pending
- Returned
- Cancelled

and calculated order volume and sales.

### 4. Referral Source Analysis

Compared order count, total sales, and average order value across referral sources.

### 5. Payment Method Analysis

Analyzed sales and order volume by payment method.

### 6. Coupon Code Analysis

Compared coupon usage, total sales, and average order value.

### 7. Filtering & Sorting

Used `WHERE` and `ORDER BY` to identify high-quantity and high-value transactions.

### 8. HAVING

Used `HAVING` to identify products with at least 150 orders.

### 9. Yearly Sales Analysis

Grouped transactions by year to compare order volume, total sales, and average order value.

### 10. Customer Analysis

Grouped orders by customer and identified the top customers by total sales.

---

## 💡 Key Findings

- The dataset contains **1,200 orders** covering January 2023 to June 2025.
- Total order value in the dataset is approximately **₹12.65 lakh**.
- **Chair** has the highest total sales among the products.
- **Instagram** has the highest total sales among the referral sources.
- **Cancelled** has the highest order count among the five order-status categories.
- **2023** has the highest total sales among the calendar years represented.
- The analysis demonstrates how SQL can turn transactional records into structured business summaries.

---

## 📁 Project Files

| File | Description |
|---|---|
| `Project_3_SQL_Data_Analysis.sql` | Complete MySQL 8.0 script with table creation, 1,200-row dataset loading, and 15 analysis queries |
| `project1_orders.csv` | SQL-friendly CSV version of the Project 1 dataset |
| `Project_3_SQL_Query_Results.xlsx` | Reference workbook containing query outputs, query catalog, and key insights |
| `README.md` | Project documentation |

---

## 🧠 Query Portfolio

The SQL script contains **15 practical analysis queries**:

1. Overall dataset summary
2. High-quantity order filtering
3. Top 10 highest-value orders
4. Product-level sales performance
5. Order-status analysis
6. Referral-source analysis
7. Payment-method analysis
8. Coupon-code performance
9. `GROUP BY` + `HAVING`
10. Yearly sales trend
11. Product and order-status breakdown
12. High-value order filtering
13. Product pricing analysis
14. Referral source + product analysis
15. Top customers by revenue

---

## ▶️ How to Run

The SQL script is written for **MySQL 8.0**.

1. Create or open a MySQL database.
2. Open `Project_3_SQL_Data_Analysis.sql`.
3. Run the script.
4. The `orders` table will be created and populated with the Project 1 dataset.
5. Run the analysis queries individually to explore the results.
6. Use `Project_3_SQL_Query_Results.xlsx` as a reference for the expected output.

---

## 🎓 Learning Outcome

This project helped me move from spreadsheet-based analysis toward **database-driven analysis using SQL**.

The key learning was to think about an analytical question before writing the query:

**Question → Filter → Group → Aggregate → Sort → Interpret**

The project also strengthened my understanding of how SQL can convert raw transactional data into specific, structured answers.

---

## 📌 Project Series

### Project 1
**Data Cleaning and Preparation**

### Project 2
**Exploratory Data Analysis (EDA)**

### Project 3
**SQL Data Analysis**

Together, these projects represent the progression from:

**Data Preparation → Data Exploration → SQL-Based Analysis**

---

## 👨‍💻 Author

**K. Vinay**

BBA Business Analytics  
Osmania University, Hyderabad

### 🔗 LinkedIn

https://www.linkedin.com/in/k-vinay-b1b789424/

---

⭐ **This project is part of my hands-on journey toward becoming a Data Analyst.**
