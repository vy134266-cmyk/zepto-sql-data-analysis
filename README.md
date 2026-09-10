# 🛒 Zepto Product Data Analysis using SQL

## 📌 Project Overview

This project analyzes Zepto product-level data using **PostgreSQL** to uncover insights into product pricing, discounts, inventory, stock availability, and product weight.

The project demonstrates practical SQL skills including data exploration, data cleaning, aggregation, conditional logic, and business-focused analysis.

---

## 🎯 Business Objective

The objective of this project is to analyze Zepto product and inventory data and answer important business questions such as:

* Which products offer the highest discounts?
* Which high-MRP products are out of stock?
* Which categories have the highest potential inventory value?
* Which categories offer the highest average discounts?
* Which products provide the best price per gram?
* Which categories have the highest inventory weight?

---

## 🛠️ Tools & Technologies

* **PostgreSQL**
* **SQL**
* **GitHub**
* **CSV**

---

## 📂 Dataset

The dataset contains product-level information including:

* SKU ID
* Product category
* Product name
* MRP
* Discount percentage
* Available quantity
* Discounted selling price
* Product weight
* Stock availability
* Quantity

---

## 🔍 Project Workflow

### 1. Data Exploration

The dataset was explored to understand its structure and quality.

Analysis included:

* Total number of records
* Sample records
* NULL value checks
* Unique product categories
* In-stock vs out-of-stock products
* Products appearing across multiple SKUs

### 2. Data Cleaning

The dataset was cleaned before analysis.

Cleaning steps included:

* Identifying products with zero prices
* Removing invalid zero-MRP records
* Converting price values from paise to Indian Rupees
* Verifying transformed price values

### 3. Business Analysis

SQL queries were used to analyze:

* Product discounts
* Product pricing
* Stock availability
* Inventory value
* Category performance
* Product weight
* Price efficiency

---

## 📊 Business Questions

The project answers the following questions:

1. What are the top 10 products based on discount percentage?
2. Which high-MRP products are currently out of stock?
3. What is the potential inventory revenue by category?
4. Which products have an MRP greater than ₹500 and a discount below 10%?
5. Which 5 categories have the highest average discount?
6. What is the price per gram for products weighing at least 100g?
7. How can products be categorized based on weight?
8. What is the total inventory weight by category?
9. Which products have the highest potential inventory value?
10. Which products have the highest absolute discount?
11. What is the stock availability by category?
12. How do average MRP and selling price compare across categories?

---

## 🧠 SQL Skills Demonstrated

This project demonstrates practical use of:

* SELECT
* WHERE
* ORDER BY
* GROUP BY
* HAVING
* DISTINCT
* COUNT()
* SUM()
* AVG()
* ROUND()
* CASE statements
* NULLIF()
* Boolean filtering
* Calculated columns
* Data cleaning
* Data transformation
* Aggregate analysis

---

## 💡 Key Insights

The analysis can help identify:

* Products with the highest promotional discounts
* High-value products that are out of stock
* Categories with significant potential inventory value
* Categories offering higher average discounts
* Products with better price-per-gram efficiency
* Categories holding large amounts of inventory
* Products contributing significantly to potential inventory value

> **Note:** Potential inventory revenue is calculated as discounted selling price × available quantity. It represents the theoretical value of currently available inventory if all units were sold, rather than historical actual sales revenue.

---

## 📁 Repository Structure

```text
zepto-sql-data-analysis/
│
├── README.md
├── zepto_analysis.sql
└── zepto_v1.csv
```

---

## 🚀 How to Run

1. Install PostgreSQL.
2. Create a PostgreSQL database.
3. Import `zepto_v1.csv`.
4. Open `zepto_analysis.sql` in pgAdmin or another SQL client.
5. Run the queries to reproduce the analysis.

---

## 📌 Future Improvements

Possible improvements include:

* Building a Power BI dashboard
* Adding sales data for actual revenue analysis
* Creating inventory turnover metrics
* Identifying slow-moving products
* Performing category-level profitability analysis
* Adding advanced SQL using CTEs and window functions

---

## 👨‍💻 Author

**Your Name**

Aspiring Data Analyst | SQL | PostgreSQL | Data Analytics
