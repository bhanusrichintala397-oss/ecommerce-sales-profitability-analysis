# E-commerce Sales & Profitability Analysis

## Project Overview

This project analyzes e-commerce transaction data to understand sales performance, profitability, product performance, customer behavior, regional trends, and the relationship between discounts and profit.

The project uses Python, Pandas, SQL, SQLite, and Matplotlib to transform raw transactional data into meaningful business insights.

## Business Objectives

- Analyze overall sales and profitability
- Compare performance across product categories and sub-categories
- Identify profitable and loss-making sub-categories
- Understand the relationship between discounts and profit
- Analyze customer and order patterns
- Examine sales and profit trends over time
- Use SQL for business-focused data analysis
- Develop data-driven business recommendations

## Dataset

The project uses the Sample Superstore dataset containing **9,994 transactions** and **21 columns**.

Key fields include:

- Order Date
- Ship Date
- Customer
- Segment
- Region
- Category
- Sub-Category
- Product
- Sales
- Quantity
- Discount
- Profit

## Tools & Technologies

- Python
- Pandas
- SQL
- SQLite
- Matplotlib
- Jupyter Notebook

## Analysis Performed

### Data Preparation
- Loaded and inspected the dataset
- Checked data types
- Converted date columns into datetime format
- Checked for missing values
- Generated descriptive statistics

### Sales & Profitability Analysis
- Analyzed total sales and profit
- Compared category-level performance
- Calculated profit margins
- Analyzed sub-category profitability
- Identified loss-making sub-categories

### Discount Analysis
- Examined the relationship between discount and profit
- Performed a focused analysis of the Tables sub-category
- Used correlation analysis to identify the strength and direction of the relationship

### Product & Customer Analysis
- Identified top products by sales and profit
- Analyzed customer sales performance
- Examined order and customer metrics

### Regional & Time Analysis
- Compared sales and profit across regions
- Analyzed monthly sales and profit trends

### SQL Analysis
SQL queries were used to:
- Aggregate sales and profit by category
- Analyze sub-category profitability
- Identify loss-making sub-categories

## Key Findings

- Total sales were approximately **$2.30 million**.
- Total profit was approximately **$286,397**.
- The overall profit margin was **12.47%**.
- Technology generated the highest sales and profit among the three main categories.
- Technology had a profit margin of approximately **17.40%**.
- Office Supplies had a profit margin of approximately **17.04%**.
- Furniture generated substantial sales but had a much lower profit margin of approximately **2.49%**.
- Tables generated an overall loss of approximately **$17,725**.
- The correlation between discount and profit was negative overall and was stronger for the Tables sub-category.

## Business Recommendations

- Review pricing and discount strategies for loss-making sub-categories.
- Investigate Furniture products to identify opportunities for improving margins.
- Evaluate products using both revenue and profitability rather than sales alone.
- Monitor high-discount transactions and their effect on profitability.
- Use product-level profitability analysis to support pricing and sales decisions.

## Project Structure

```text
Ecommerce-Sales-Analysis/
│
├── README.md
├── Ecommerce_Sales_Analysis.ipynb
├── Sample - Superstore.csv
