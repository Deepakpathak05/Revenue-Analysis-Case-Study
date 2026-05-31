# 📊 Revenue Analysis Case Study

## Overview

This project investigates a business revenue decline through data preparation, trend analysis, root cause investigation, and dashboard development.

The objective was to identify when the revenue decline began, understand the factors contributing to the decline, and provide actionable business recommendations supported by data.

---

## Business Problem

The business experienced a significant decline in revenue performance.

The analysis focuses on:

- Revenue trends over time
- Revenue by region
- Revenue by channel
- Revenue by product category
- Order volume changes
- Cancellation rates
- Return rates
- Discount trends
- Customer purchasing behavior

---

## Project Objectives

### Data Preparation
- Load and inspect all provided datasets
- Identify and resolve data quality issues
- Validate dataset relationships
- Prepare data for reporting and dashboard development

### Revenue Trend Analysis
- Analyze revenue by month
- Analyze revenue by channel
- Analyze revenue by region
- Analyze revenue by product category
- Identify when the revenue decline began

### Root Cause Investigation
- Examine order volume trends
- Analyze cancellation rates
- Analyze return rates
- Evaluate discount trends
- Investigate customer purchase behavior
- Identify major return drivers

### Dashboard Development
- Build an interactive Power BI dashboard
- Enable filtering by key business dimensions
- Present findings in an executive-friendly format

### Recommendations
- Provide data-driven recommendations to improve revenue performance

---

## Datasets Used

### Orders Dataset
Contains order-level transactional data including:

- Order ID
- Order Date
- Channel
- Revenue
- Order Status

### Order Items Dataset
Contains product-level sales information including:

- Product ID
- Category
- Quantity
- Unit Price
- Line Total

### Customers Dataset
Contains customer information including:

- Customer ID
- Region
- Signup Date

### Returns Dataset
Contains return-related information including:

- Return ID
- Return Date
- Return Reason
- Refund Amount

---

## Tools & Technologies

### Data Analysis
- Python
- Pandas
- NumPy

### Data Visualization
- Matplotlib
- Seaborn

### Business Intelligence
- Power BI

### Development Environment
- Jupyter Notebook

---

## Data Cleaning & Preparation

The following data quality checks were performed:

- Missing value assessment
- Data type validation
- Date format standardization
- Duplicate record checks
- Revenue validation
- Dataset relationship validation

Cleaned datasets were prepared for Power BI reporting and business analysis.

---

## Revenue Trend Analysis

Revenue performance was analyzed across:

- Monthly trends
- Sales channels
- Geographic regions
- Product categories

### Key Finding

Revenue remained relatively stable throughout 2023 and the first half of 2024.

A significant decline began during **July 2024**, with revenue continuing to decrease in the following months.

---

## Root Cause Analysis

The investigation focused on:

### Order Volume
A significant decline in order volume coincided with the revenue decline period.

### Discount Trends
Average discount levels increased during the decline period, indicating efforts to stimulate demand.

### Cancellation Rates
Cancellation rates increased substantially, reaching approximately **33%** during the decline period.

### Return Rates
Return rates increased significantly, reaching approximately **34%**.

### Return Drivers
The most common return reasons were:

1. Late Delivery
2. Damaged Products
3. Product Not As Described

---

## Dashboard Overview

The Power BI dashboard consists of three pages:

### 1. Executive Revenue Overview
- Revenue KPIs
- Revenue Trend Analysis
- Revenue by Region
- Revenue by Channel
- Revenue by Product Category

### 2. Root Cause Investigation
- Order Volume Trend
- Discount Analysis
- Cancellation Rate Trend
- Return Rate Trend
- Customer Purchase Mix
- Return Reason Analysis

### 3. Executive Summary & Recommendations
- Key Findings
- Root Cause Summary
- Business Recommendations
- Executive KPIs

---

## Key Insights

- Revenue remained stable through most of the analysis period.
- Revenue decline began in July 2024.
- Order volume dropped significantly during the decline period.
- Average discounts increased while revenue continued to fall.
- Cancellation rates increased to approximately 33%.
- Return rates increased to approximately 34%.
- Late delivery emerged as the leading return driver.
- Operational and customer experience issues appear to be major contributors to declining revenue.

---

## Recommendations

### Improve Fulfillment & Delivery Performance
- Reduce delivery delays
- Improve logistics monitoring
- Strengthen service-level agreement tracking

### Reduce Product Quality Issues
- Enhance quality control processes
- Improve packaging and handling procedures

### Optimize Discount Strategy
- Evaluate promotional effectiveness
- Focus on customer experience improvements rather than relying solely on discounts

---

## Repository Structure

```text
Revenue-Analysis-Case-Study
│
├── notebooks
│   └── Deepak_Pathak_Revenue_Analysis_Case_Study.ipynb
│
├── dashboard
│   ├── Deepak_Pathak_BI_Analytics_Assessment.pbix
│   ├── Executive_Revenue_Overview.png
│   ├── Root_Cause_Analysis.png
│   └── Executive_Summary.png
│
├── documentation
│   └── Deepak_Pathak_Data_Preparation_Summary.docx
│
├── data
│   ├── cleaned_orders.csv
│   ├── cleaned_order_items.csv
│   ├── cleaned_customers.csv
│   └── cleaned_returns.csv
│
└── README.md
```

---

## Author

**Deepak Pathak**

Data Analyst | Business Intelligence Enthusiast

Skills:
- Python
- SQL
- Power BI
- Data Analysis
- Data Visualization
- Business Intelligence

---
