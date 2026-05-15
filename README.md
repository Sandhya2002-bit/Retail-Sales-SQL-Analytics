# Retail Sales SQL Analytics Project

## Project Overview

This project focuses on analyzing retail sales data using SQL to uncover valuable business insights related to customer behavior, product performance, profitability, regional trends, and sales growth.

The goal of this project is to demonstrate practical SQL skills combined with business analysis techniques commonly used in real-world Data Analyst and Business Intelligence roles.

---

## Dataset Used

The project uses the Superstore Sales Dataset, which contains retail transaction data including:

- Orders
- Customers
- Products
- Regions
- Sales
- Profit
- Discounts
- Shipping details

Dataset Source:
Kaggle Superstore Dataset

---

## Tools & Technologies

- MySQL Workbench
- SQL
- GitHub
- Kaggle Dataset

---

## SQL Concepts Demonstrated

This project includes practical usage of:

- SELECT statements
- WHERE clause
- GROUP BY
- ORDER BY
- Aggregate Functions
- CASE Statements
- Window Functions
- Common Table Expressions (CTEs)
- Subqueries
- Ranking Functions

---

## Business Questions Answered

The analysis focuses on solving important business problems such as:

- Which product categories generate the highest profit?
- Which regions contribute the most sales revenue?
- Who are the top spending customers?
- What are the monthly sales trends?
- Which products are underperforming?
- How do discounts impact profitability?

---

## Project Structure

Retail-Sales-SQL-Analytics/
│

├── dataset/
│   └── sales_data.csv
│
├── sql_queries/
│   └── analysis_queries.sql
│

├── images/
│   └── query_results.png
│

├── insights_report.md
│

└── README.md

---

## Sample SQL Queries

### Total Sales Analysis

sql
SELECT 
    SUM(Sales) AS Total_Sales
FROM sales;

### Top 10 customers

SELECT 
    Customer_Name,
    SUM(Sales) AS Total_Spent
FROM sales
GROUP BY Customer_Name
ORDER BY Total_Spent DESC
LIMIT 10;

### Profit by Category

SELECT 
    Category,
    SUM(Profit) AS Total_Profit
FROM sales
GROUP BY Category
ORDER BY Total_Profit DESC;

---

### Key Business Insights

* Office Supplies generated the highest overall profit.
* Furniture category showed negative profitability, indicating potential operational or discount-related challenges.
* A small group of customers contributed significantly to total sales revenue.
* Regional sales performance varied considerably across locations.
* Discounts had a noticeable impact on profit margins in certain categories.

Detailed findings are available in:
insights_report.md

---

Learning Outcomes

Through this project, I strengthened my understanding of:

* SQL for business analytics
* Data exploration and reporting
* Writing analytical queries
* Translating raw data into business insights
* Structuring professional analytics projects for GitHub portfolios

---

### Future Improvements

Future enhancements planned for this project include:

* Power BI dashboard integration
* Advanced KPI reporting
* Sales forecasting analysis
* Customer segmentation analysis
* Interactive business dashboards

---

### Author

Sandhya Hanabar

Aspiring Data Analyst | SQL | Python | Machine Learning | Data Visualization



