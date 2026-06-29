# Database-Programming-Assignment-I_31453_2025


Student Information

- Student Name: Mazin Hassan
- Student ID: 31453/2025
- Course: Database Programming
- Assignment: CTEs & SQL Window Functions

---

Business Problem

This project is a Sales Management System designed to manage customers, products, and customer orders. The system stores customer information, product details, and purchase records to help businesses analyze sales performance and support decision-making.

---

Database Schema

The database consists of three related tables:

Customers

- CustomerID (Primary Key)
- CustomerName
- Phone
- City

Products

- ProductID (Primary Key)
- ProductName
- Category
- Price

Orders

- OrderID (Primary Key)
- CustomerID (Foreign Key)
- ProductID (Foreign Key)
- Quantity
- OrderDate

---

ER Diagram

The database contains three related tables:

- Customers (1) → (M) Orders
- Products (1) → (M) Orders

Orders acts as the transaction table connecting customers and products.

---

CTE Implementations

The project demonstrates the following Common Table Expressions:

- Simple CTE
- Multiple CTEs
- Recursive CTE
- CTE with Aggregation
- CTE with JOIN

Each query includes SQL code, execution results, and business explanation.

---

Window Function Implementations

The following SQL Window Functions were implemented:

- ROW_NUMBER()
- RANK()
- DENSE_RANK()
- PERCENT_RANK()
- SUM() OVER()
- AVG() OVER()
- MIN() OVER()
- MAX() OVER()
- LAG()
- LEAD()
- NTILE()
- CUME_DIST()

Each function was executed successfully and its output was analyzed.

---

Analysis and Findings

Descriptive Analysis

The reports show customer orders, product sales, and purchasing activity.

Diagnostic Analysis

The analysis explains which products are ordered most frequently and identifies the most active customers.

Prescriptive Analysis

The business should increase stock for high-demand products, offer promotions to loyal customers, and monitor low-selling products to improve sales performance.

---

References

- Oracle SQL*Plus Documentation
- Oracle Database 21c Documentation
- Database Programming Course Notes

---

Academic Integrity Statement

I declare that this assignment is my own original work. All SQL scripts, database design, documentation, and analysis were completed independently in accordance with the university's academic integrity policy.
