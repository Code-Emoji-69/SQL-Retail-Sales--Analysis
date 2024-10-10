# SQL-Retail-Sales--Analysis

This project focuses on analyzing retail sales data using SQL. It involves data cleaning, exploration, and answering key business questions using SQL queries. The data contains transactions related to retail sales, covering details such as transaction ID, date, time, customer demographics, product categories, and total sales.

# Project Overview
The project is structured to showcase various SQL capabilities including:
Database Creation: Creating a retail sales database and table schema to hold the data.
Data Cleaning: Identifying and removing null or incomplete data entries.
Data Exploration: Basic queries to understand the dataset.
Data Analysis: Answering business-related questions by writing SQL queries.

# Table Structure
Transaction ID: Unique identifier for each sale transaction.
Sale Date & Time: Date and time of the transaction.
Customer ID, Gender, Age: Information about the customer.
Category: Product category for the transaction.
Quantity, Price Per Unit, COGS (Cost of Goods Sold), Total Sale: Sales and financial data for the products sold.


# Key SQL Queries & Analysis
1.	Data Cleaning: Removing records with null values in key columns such as transaction_id, sale_date, sale_time, etc.
2.	Total Sales: Calculating total sales in the dataset.
3.	Customer Count: Counting the number of unique customers.
4.	Category Sales: Summing up the total sales by category.
5.	Average Age: Finding the average age of customers who purchased items from a specific category (e.g., Beauty).
6.	Top Customers: Identifying the top 5 customers with the highest total sales.
7.	Sales Shifts: Categorizing transactions into different shifts (Morning, Afternoon, Evening) based on the time of sale.

# Sample Business Questions Addressed
o	What were the total sales made on a specific date (e.g., 2022-11-05)?
o	Which customers made purchases from the 'Clothing' category with a quantity greater than 4 in November 2022?
o	Which category had the highest total sales?
o	Who are the top 5 customers by total sales?
o	Which is the best-selling month in each year?


# Key SQL Functions Used
Aggregations: COUNT(), SUM(), AVG()
Date Functions: EXTRACT(YEAR FROM ...), TO_CHAR()
Window Functions: RANK() OVER(...)
Common Table Expressions (CTEs): For more complex queries and shift categorization.
Conditional Logic: CASE for categorizing shifts.

# How to Use
Step 1: Clone the repository to your local machine.
Step 2: Load the SQL scripts into your preferred SQL environment (e.g.,  I used PostgreSQL).
Step 3: Run the SQL queries in the order provided or customize them to suit your dataset.

# Conclusion
This project demonstrates the use of SQL for performing data analysis on retail sales. The queries included here can be modified and extended to accommodate other business problems and datasets.
