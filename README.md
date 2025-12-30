# Online_BookStore_SQL_project
📚 Online Bookstore SQL Project
📌 Project Overview

This project demonstrates the use of SQL to design, manage, and analyze an Online Bookstore Database.
It covers database creation, table design, data import, and querying using basic and advanced SQL concepts.

🛠️ Technologies Used

SQL

CSV files (for data import)

🗂️ Database Structure
1️⃣ Books Table

Stores information about books such as title, author, genre, price, and stock.

Book_ID (Primary Key)

Title

Author

Genre

Published_Year

Price

Stock

2️⃣ Customers Table

Stores customer details.

Customer_ID (Primary Key)

Name

Email

Phone

City

Country

3️⃣ Orders Table

Stores order information.

Order_ID (Primary Key)

Customer_ID (Foreign Key)

Book_ID (Foreign Key)

Order_Date

Quantity

Total_Amount

📥 Data Import

Data is imported into the tables using CSV files with the COPY command for:

Books

Customers

Orders

🔍 Queries Covered
🔹 Basic Queries

Retrieve books by genre

Find books published after a specific year

List customers by country

Show orders within a date range

Calculate total stock and total revenue

Find most expensive and least stocked books

🔹 Advanced Queries

Total books sold by genre

Average book price by genre

Customers with multiple orders

Most frequently ordered book

Top 3 expensive books in a genre

Total books sold by each author

Cities of customers who spent over a certain amount

Customer with the highest total spending


🎯 Key Concepts Used

JOIN (INNER & LEFT JOIN)

GROUP BY

HAVING

Aggregate functions (SUM, AVG, COUNT)

ORDER BY and LIMIT

DISTINCT

Foreign key relationships

✅ Outcome

This project helps in understanding:

Real-world database design

Data analysis using SQL

Business insights from sales data.
