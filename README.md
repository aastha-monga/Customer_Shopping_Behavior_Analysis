# Customer Shopping Behavior Analysis

## 1. Project Overview

This project analyzes customer shopping behavior to identify purchasing patterns, customer segments, product performance, discount usage, subscription behavior, and revenue trends.

The project follows an end-to-end data analytics workflow using **Python, Jupyter, PostgreSQL, SQL, and Power BI**.

## 2. Business Objective

The goal is to turn customer transaction data into actionable business insights that can help answer questions such as:

1. How does revenue differ between male and female customers?
2. Do customers who use discounts still make high-value purchases?
3. Which products receive the highest average ratings?
4. How does shipping type affect average purchase amount?
5. Do subscribed customers spend more than non-subscribers?
6. Which products have the highest discount usage?
7. How can customers be segmented based on previous purchases?
8. What are the most purchased products within each category?
9. Are repeat buyers more likely to subscribe?
10. Which age groups contribute the most revenue?

## 3. Technologies Used

- Python
- Pandas
- Jupyter Notebook
- PostgreSQL
- SQL
- Power BI

## 4. Project Workflow

```text
Raw Customer Data
        ↓
Python / Pandas
        ↓
Data Cleaning & Feature Engineering
        ↓
Cleaned Dataset
        ↓
PostgreSQL Database
        ↓
SQL Analysis
        ↓
Power BI Dashboard
        ↓
Business Insights
```

## 5. Data Preparation

The dataset was processed using Python and Pandas.

Key preprocessing steps include:

- Loading the customer shopping dataset
- Inspecting data types and dataset structure
- Checking and handling missing values
- Standardizing column names
- Creating customer age groups
- Converting purchase frequency into approximate days
- Identifying and removing redundant information
- Validating the final dataset
- Preparing the cleaned dataset for database analysis

## 6. PostgreSQL and SQL Analysis

The cleaned customer data is analyzed using PostgreSQL and SQL.

The analysis covers:

1. Revenue by gender
2. High-value purchases made using discounts
3. Top-rated products
4. Average purchase amount by shipping type
5. Subscriber vs. non-subscriber spending
6. Product-level discount rates
7. Customer segmentation
8. Top products within each category
9. Repeat buyers and subscription behavior
10. Revenue contribution by age group

The SQL queries are available in:

`customer_shopping_behavior_sql_querries`

## 7. Power BI Dashboard

The analyzed customer data is used to build an interactive Power BI dashboard.

The dashboard focuses on:

- Customer demographics
- Revenue performance
- Purchase behavior
- Product performance
- Subscription behavior
- Discount usage
- Customer segments

## 8. How to Run the Project

### Step 1: Run the Jupyter Notebook

Open the customer shopping behavior analysis notebook and run the Python/Pandas cells to clean and prepare the dataset.

### Step 2: Prepare the Database

Create a PostgreSQL database and import the cleaned customer dataset into the database.

### Step 3: Run the SQL Analysis

Open:

`customer_shopping_behavior_sql_querries`

Run the queries against the customer dataset in PostgreSQL.

### Step 4: Open the Power BI Dashboard

Open the Power BI dashboard and refresh the data if required.

## 9. Business Insights

The analysis helps identify:

- High-value customer groups
- Products with strong customer ratings
- Products with high discount usage
- Differences between subscribers and non-subscribers
- Customer segments based on purchase history
- High-performing product categories
- Revenue contribution across age groups
- Potential opportunities for customer retention and subscription growth
