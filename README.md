# Retail-Data-Analysis-Walmart
This repository contains an end-to-end exploratory and business-driven data analysis project on Walmart’s transactional dataset.
The analysis was performed using Python for data cleaning and transformation, and MySQL for deriving key business insights.

## Project Objective
To analyze Walmart's sales data to identify business trends and provide actionable insights on:
- Customer purchasing behavior
- Payment method preferences
- Branch performance
- Profitability by product category
- Sales seasonality and time-based performance

## Dataset

- **Source:** Walmart Sales Data (Kaggle)
- **Rows:** ~10,000 transactions
- **Fields:** Invoice ID, Branch, City, Category, Unit Price, Quantity, Date, Time, Payment Method, Rating, Profit Margin

## Tools & Technologies Used

- **Language:** Python 3.13.2
- **Libraries:** pandas, sqlalchemy, pymysql
- **Database:** MySQL
- **IDE:** Jupyter Notebook
- **Other:** SQL for solving business queries

## Key Steps

### 1. Data Cleaning & Preparation
- Removed duplicates and missing values
- Converted columns to appropriate data types
- Added new features like total, day_of_week, month

### 2. Data Export & SQL Integration
- Uploaded cleaned data into MySQL using SQLAlchemy
- Solved business problems with efficient SQL queries

## Business Questions Solved

1. What is the most preferred payment method?
2. Which product category is the most profitable?
3. Which branch has the highest total revenue?
4. What time of the day has the highest sales?
5. What is the average rating per city?
6. How many transactions are made per branch?
7. What is the sales performance month-wise and day-wise?
   
## Walmart Analysis pipeline
()
