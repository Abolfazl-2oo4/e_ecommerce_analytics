# E-Commerce Analytics & Customer Intelligence Platform

## Overview

An end-to-end e-commerce analytics project built to analyze sales,
customers, products, categories, orders, payments, and inventory.

The project transforms raw transactional data into business-oriented
analytics and an interactive Power BI dashboard.

## Tech Stack

- PostgreSQL
- SQL
- Power BI
- DAX

## Project Pipeline

PostgreSQL → SQL Analytics → Power BI

## Database

The project uses a relational e-commerce database containing:

- Customers
- Orders
- Order Items
- Products
- Categories
- Payments

## SQL Analysis

Key analyses include:

- Sales and revenue analysis
- Customer behavior analysis
- Product performance analysis
- Category performance analysis
- Order status analysis
- Payment analysis
- Customer segmentation
- Window functions
- CTEs and subqueries
- Aggregations and joins
- Indexing
- Query optimization
- EXPLAIN ANALYZE
- Database constraints and relationships

## Power BI

The final BI layer includes:

- KPI Cards
- Revenue and Order Trends
- Customer Segmentation
- Product Analysis
- Category Analysis
- Payment Analysis
- Inventory Status
- Interactive Slicers
- Business-oriented dashboards

## Key Business Areas

### Sales Performance

Analysis of revenue, order volume, average order value,
and sales trends over time.

### Customer Analysis

Analysis of customer purchasing behavior, order frequency,
customer segmentation, and customer value.

### Product & Category Analysis

Identification of high-performing products and categories,
as well as products with low inventory levels.

### Orders & Payments

Analysis of order statuses and successful payments
across different payment methods.

### Inventory

Products are categorized based on their available stock
to help identify products with lower inventory levels
and potential purchasing needs.

## Key Business Insights

- The platform generated 3.60T in total revenue across 100K orders and 20K customers, with an average order value of 36.00M.

- Revenue and order volume fluctuate significantly over time, indicating considerable variation in sales performance across the analyzed period.

- Product_766 is the highest-revenue product among the displayed top-performing products, followed by Product_182 and Product_708.

## Business Objective

The goal of the project is to transform raw e-commerce
transactional data into actionable business insights
for sales, customer, product, order, payment, and
inventory decision-making.

## Project Structure

E-Commerce-Analytics/

├── README.md

├── sql/

│   └── database.sql

└── powerbi/

    └── E-Commerce_Analytics.pbix


