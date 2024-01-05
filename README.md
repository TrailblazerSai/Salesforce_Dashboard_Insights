# Salesforce Dashboard Insights

## Overview

The Salesforce Dashboard Insights project is a comprehensive analysis of sales performance and customer data using Salesforce CRM datasets. It provides actionable insights to optimize sales strategies, improve lead conversion rates, and track opportunities effectively. The project leverages powerful tools like Tableau, Power BI, SQL, and Excel to deliver interactive dashboards and detailed visualizations.

## Objective

To develop a robust analytical framework that empowers businesses to:
- Track sales performance metrics such as revenue, conversion rates, and pipeline health
- Identify high-performing regions, products, and sales representatives
- Improve decision-making with data-driven insights

## Tools and Technologies Used

- **Tableau**: For creating interactive dashboards to analyze sales and lead performance
- **Power BI**: For advanced data visualization and opportunity tracking
- **SQL**: For querying and transforming raw Salesforce CRM data
- **Excel**: For data preparation and cleaning

## Data Sources

The project utilizes Salesforce CRM datasets, including:
- Account Table: 3,052 records
- Lead Table: 10,000 records
- Opportunity Table: 4,647 records
- Opportunity Product Table: 10,000 records
- User Table: 100 records

## Key Features

### 1. Lead Analysis
- Analyzed lead performance by region, source, and conversion status
- Identified top-performing lead sources and regions

### 2. Opportunity Tracking
- Monitored active opportunities and their pipeline stages
- Calculated metrics like opportunity win rate and pipeline value

### 3. Sales Performance
- Tracked revenue growth trends over time
- Visualized sales performance by product and sales representative

### 4. Interactive Dashboards
- Created dynamic filters for region, product, and time period analysis
- Visualized KPIs such as "Revenue Growth," "Conversion Rates," and "Top Opportunities"

## Project Insights

- Lead Conversion: The most successful lead sources and regions were identified, highlighting areas for improvement
- Opportunity Stages: Active opportunities were analyzed to optimize pipeline management
- Sales Growth: Sales increased year-over-year, with actionable insights into key drivers of growth

## How to Use

### 1. Prerequisites
- Tableau or Tableau Public installed
- Power BI Desktop installed
- MySQL or any compatible SQL environment for running queries

### 2. Steps to Run

1. **SQL Queries:**
   ```sql
   -- Run the provided SQL scripts
   Lead_Analysis_Query.sql
   Opportunity_Tracking_Query.sql
   ```

2. **Tableau Dashboard:**
   - Open Sales_Performance_Insights.twbx in Tableau to view interactive dashboards

3. **Power BI Dashboard:**
   - Open Sales_Insights_Dashboard.pbix in Power BI for detailed opportunity analysis

## Challenges Faced

- Data Cleaning: Adjusting data types and resolving inconsistencies in the Salesforce CRM datasets
- Integration: Joining multiple datasets to create a unified data model for analysis
- Pipeline Metrics: Calculating accurate metrics like opportunity win rates and pipeline health

## Future Enhancements

- Automate the ETL process to handle real-time Salesforce CRM data updates
- Incorporate predictive analytics for revenue and conversion forecasting
- Expand dashboards to include advanced metrics like customer lifetime value (CLV)