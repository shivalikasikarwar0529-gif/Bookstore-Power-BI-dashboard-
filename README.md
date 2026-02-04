# Bookstore Strategic Analysis Dashboard

## Project Overview
This project provides a comprehensive analysis of a bookstore's performance, inventory, and customer base. As a Data Analyst, I developed this end-to-end solution to help stakeholders track sales trends, manage stock levels, and identify top-performing genres and authors.

The dashboard transforms raw transactional data into actionable insights, focusing on revenue growth and inventory efficiency.

## Dashboard Previews

### 1. Strategic Overview
Summary of total books, authors, and orders to understand the scale of operations.
![Overview](Bookstore_analysis_Overview.jpg)

### 2. Market Performance
A look at the $73K total revenue with a trend analysis from 2022 to 2024.
![Market Performance](Bookstore_analysis_Market_Performance.png)

### 3. Quick Snapshots & Inventory
Real-time inventory tracking, including value ($685K) and low-stock alerts.
![Quick Snapshots](Bookstore_analysis_Quick_Snapshot.png)

## Key Features
* **Quick Snapshots:** High-level view of total stock (25K), inventory value, and critical "Out of Stock" alerts.
* **Market Performance:** Analysis of revenue trends, average order values, and geographical sales.
* **Inventory Management:** A "Low Stock Alert" system categorized by genre.
* **Customer Insights:** Visualization of the top 10 customers and authors.

## Tech Stack
* **Data Source:** SQL Server (Relational Database)
* **Tool:** Power BI Desktop
* **Concepts:** Data Modeling, ETL, DAX, and Interactive Visualization.

## Data Workflow
1. **Extraction:** Connected Power BI to **SQL Server** to pull transactional records.
2. **Transformation:** Cleaned data using Power Query for accuracy.
3. **Modeling:** Established relationships (Star Schema) for seamless filtering.
4. **Visualization:** Developed interactive reports for business health and trends.

## Key Insights
* **Revenue Growth:** The business saw a sharp increase in revenue in 2023.
* **Inventory Priority:** 5 key items are currently out of stock, representing a priority for procurement.
* **Customer Base:** A small group of top customers contributes significantly to the total revenue.
