# Retail Sales Analysis using Excel, MySQL & Power BI

## Project Overview

This project demonstrates an end-to-end Retail Sales Analysis solution by transforming raw business data into meaningful insights. The dataset consists of multiple Excel files representing different business entities such as customers, products, orders, stores, brands, categories, stocks, staff, and order items.
Instead of combining all files into a single dataset, each file was cleaned individually because every file represents a different table in the database. After cleaning, the data was imported into MySQL, where a relational database schema was designed using Primary Keys and Foreign Keys. Finally, the SQL database was connected to Power BI to create an interactive dashboard that helps analyze sales performance, customer behavior, inventory, and overall business performance.

# Project Objectives

* Clean and prepare raw retail data for analysis.
* Design a normalized relational database.
* Build relationships between different business entities.
* Perform SQL analysis to generate business insights.
* Create an interactive Power BI dashboard for decision-making.
* 
# Tools & Technologies

* **Microsoft Excel** – Data Cleaning & Preparation
* **MySQL** – Database Creation, SQL Schema & Analysis
* **Power BI** – Data Visualization & Dashboard

# Dataset Description

The project contains multiple Excel files, including:

* Customers
* Orders
* Order Items
* Products
* Categories
* Brands
* Stores
* Staffs
* Stocks

Since every file contains different information and different numbers of rows and columns, they were treated as separate database tables rather than merged into one dataset.

# 📊 Data Cleaning (Microsoft Excel)

Each dataset was cleaned individually before importing into MySQL.

The cleaning process included:

* Removing duplicate records
* Handling missing values
* Correcting inconsistent data
* Removing unnecessary spaces
* Standardizing column names
* Verifying data formats
* Checking data consistency
* Validating unique IDs
* Preparing datasets for SQL import

The cleaned datasets were then saved and imported into MySQL.


# Database Design (MySQL)

After cleaning the data, a relational database named **Retail_Analysis** was created in MySQL.

Each cleaned Excel file was imported as an individual table to maintain database normalization and reduce data redundancy.

Tables created include:

* Customers
* Orders
* Order_Items
* Products
* Categories
* Brands
* Stores
* Staffs
* Stocks


# SQL Schema Design

A relational schema was designed by defining Primary Keys and Foreign Keys to establish relationships between different tables.

### Relationships Created

* Categories → Products
* Brands → Products
* Customers → Orders
* Stores → Orders
* Staffs → Orders
* Orders → Order Items
* Products → Order Items
* Stores → Stocks
* Products → Stocks

This schema ensures data integrity and enables efficient SQL joins for business analysis.

# 📈 SQL Analysis

Several SQL queries were performed to analyze retail business performance.

The analysis includes:

* Total Sales
* Total Revenue
* Top Selling Products
* Best Performing Stores
* Customer Purchase Analysis
* Order Analysis
* Product Performance
* Brand-wise Sales
* Category-wise Sales
* Inventory Analysis
* Monthly Sales Trends

These queries helped generate meaningful insights for business decision-making.

# 📊 Power BI Dashboard

The SQL database was connected to Power BI to build an interactive dashboard.

The dashboard includes:

### KPI Cards

* Total Sales
* Total Orders
* Total Customers
* Total Revenue

### Visualizations

* Bar Charts
* Line Charts
* Pie/Donut Charts
* Column Charts
* Tables
* Slicers
* Interactive Filters

### Dashboard Features

* Sales Performance Analysis
* Product Performance
* Customer Insights
* Store-wise Analysis
* Category Analysis
* Brand Analysis
* Inventory Monitoring
* Dynamic Filtering




#  Skills Demonstrated

* Data Cleaning
* Data Validation
* Data Preparation
* Database Design
* SQL Schema Design
* Primary & Foreign Key Relationships
* SQL Queries
* Data Analysis
* Business Intelligence
* Data Visualization
* Dashboard Development
* Retail Business Analysis

# 📌 Key Outcomes

* Improved data quality through systematic cleaning.
* Designed a normalized relational database using MySQL.
* Built relationships between multiple business entities.
* Performed SQL-based business analysis.
* Developed an interactive Power BI dashboard for retail performance monitoring.
* Converted raw retail data into actionable business insights.
