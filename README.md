# AtliQ Sales Analysis SQL Project

## Project Overview
This SQL project for AtliQ focuses on generating critical sales reports and analytics to enhance business strategies. It involves tasks such as aggregating sales data, creating stored procedures for market classification, and analyzing regional sales performances.

## Task Breakdown

### Task 1: Monthly Product Sales Report for Croma India (FY 2021)
- **Objective**: Generate a monthly aggregated sales report at the product code level for Croma India customer for the fiscal year 2021.
- **Purpose**: This report aims to track individual product sales and facilitate further product analytics in Excel.

### Task 2: Market Badge Determination Stored Procedure
- **Objective**: Create a stored procedure to classify markets into 'Gold' or 'Silver' based on total sold quantity.
- **Logic**:
  - If total sold qty > 5 million, market is 'Gold'.
  - Otherwise, market is 'Silver'.
- **Inputs**: Market and fiscal year.
- **Output**: Market badge classification.

### Task 3: Generation of Net Sales Views
- **Objective**: Create views for pre-invoice and post-invoice tables to generate a net sales view.
- **Advantages**: This approach makes queries faster, easier, and more storage-efficient. The views can be reused for future queries.
- **Purpose**: To provide a consolidated view of net sales across different markets.

### Task 4: Regional Sales Analysis
- **Objective**: Analyze region-wise (e.g., APAC, EU) percentage net sales breakdown by customers.
- **Purpose**: To perform a regional analysis on the financial performance of the company and understand regional market dynamics.

## Technologies Used
- SQL for database querying and view creation.
- Excel for further data analysis and visualization.

## Insights and Conclusions
This project provides AtliQ with critical insights into product sales, market segmentation, and regional financial performance, aiding in strategic decision-making and market positioning.

## Call to Action
Explore the detailed SQL queries, stored procedures, and views in this repository. Your contributions and feedback are welcome to enhance the project's effectiveness and accuracy.

---

This repository serves as a resource for SQL practitioners and business analysts interested in sales data analysis and market segmentation strategies.
