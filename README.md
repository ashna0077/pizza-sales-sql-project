# 🍕 Pizza Sales Analysis using SQL (MySQL)

## Overview
This project explores pizza sales data using **MySQL** to understand how the business is performing and how customers place orders.  
The analysis focuses on answering practical business questions related to revenue, product performance, and ordering patterns using SQL.

The project was built end-to-end — from database design to analysis — to demonstrate strong SQL fundamentals and business thinking.

---

## Tools Used
- MySQL  
- MySQL Workbench  
- SQL (JOINs, aggregations, CTEs, window functions)  
- GitHub for documentation  

---

## Dataset Summary
The dataset represents a pizza restaurant’s sales and is structured into **four normalized tables**:

| Table | Description |
|------|-------------|
| `orders` | Order date and time information |
| `order_details` | Line-level details of pizzas ordered |
| `pizza` | Pizza size and pricing information |
| `pizza_types` | Pizza names, categories, and ingredients |

This structure avoids duplication and makes analysis more efficient.

---

## Database Design (ER Model)
The database follows a clean relational design:

- One order can contain multiple pizzas  
- Each pizza can appear in multiple orders  
- Each pizza belongs to a single pizza type  

This design supports scalable analysis and accurate revenue calculations.

A detailed ER explanation is available here:  
👉 **01_ER_Diagram.md**

---

## Business Questions
The analysis focuses on real business questions such as:

- How much total revenue does the store generate?
- Which pizza categories contribute the most to revenue?
- What are the top-selling pizzas?
- When do customers place the most orders?
- Which pizza sizes perform best?

The full list of questions is documented in:  
👉 **02_Business_Questions.md**

---

## SQL Analysis
All analysis is done using well-structured SQL queries with clear comments and aliases.  
The project covers:

- Multi-table JOINs  
- Aggregations using `SUM`, `COUNT`, and `AVG`  
- `GROUP BY` and `HAVING` clauses  
- Common Table Expressions (CTEs)  
- Window functions for ranking and running totals  

All SQL queries are available in:  
👉 **03_SQL_Queries.sql**

---

## Key Insights
Some of the main takeaways from the analysis include:

- Certain pizza categories consistently generate higher revenue
- Larger pizza sizes contribute more to total sales
- Order volumes are higher during evening hours

Detailed insights and recommendations are documented in:  
👉 **04_Insights.md**

---

How to Run the Project

1. Create a MySQL database
2. Run the table creation and analysis queries from `03_SQL_Queries.sql`

---

## Skills Demonstrated
- SQL querying and optimization  
- Relational database design  
- Translating business questions into SQL queries  
- Data analysis and interpretation  
- Technical documentation using GitHub  

---

## Future Enhancements
- Add a larger time range of data for trend analysis  
- Build dashboards using Tableau or Power BI  
- Automate reporting using stored procedures  

---

## Author
**Ashna Stalin**  
Master’s Student in Business Analytics  
Interested in Data Analytics, SQL, and Business Intelligence
