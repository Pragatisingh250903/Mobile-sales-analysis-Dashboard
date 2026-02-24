#📊 Mobile Sales Dashboard – Power BI Project

##📌 Project Overview

The Mobile Sales Dashboard is an interactive Business Intelligence solution developed using Microsoft Power BI to analyze and monitor mobile phone sales performance.

This dashboard provides a comprehensive view of sales metrics, product performance, profitability, and regional trends, enabling stakeholders to make data-driven business decisions.

The project focuses on transforming raw sales data into meaningful insights through data modeling, DAX calculations, and interactive visualizations.

##🎯 Objectives

Analyze overall mobile sales performance.

Track revenue, profit, and quantity sold.

Identify top-performing brands and models.

Monitor monthly and regional sales trends.

Compare performance against targets.

Enable dynamic filtering for deeper analysis.

##🛠️ Tools & Technologies Used

Microsoft Power BI

Power Query (Data Cleaning & Transformation)

DAX (Data Analysis Expressions)

Data Modeling (Relationships & Schema Design)

Interactive Visualizations & KPI Cards

##📂 Dataset Description

The dataset contains transactional-level mobile sales data, including:

Order Date

Region / Location

Brand

Model

Sales Amount

Quantity Sold

Profit

Target (if applicable)

Data was cleaned and transformed using Power Query, ensuring:

Removal of duplicates

Handling missing values

Correct data types

Standardized formatting

##📊 Key Features of the Dashboard

1️⃣ KPI Overview Section

Total Sales Revenue

Total Profit

Total Quantity Sold

Target Achievement %

Profit Margin %

These KPIs provide a quick summary of business performance.

2️⃣ Sales Trend Analysis

Monthly sales trends (line/area charts)

Year-over-Year or Month-over-Month growth tracking

Seasonal performance insights

3️⃣ Brand & Product Analysis

Brand-wise sales comparison

Top-selling mobile models

Profitability by brand

Contribution % by each product category

4️⃣ Regional Performance Analysis

Region-wise revenue distribution

Profit comparison across locations

Identification of high-performing and underperforming regions

5️⃣ Interactive Filtering

Slicers for:

Brand

Region

Date

Model

Allows users to dynamically explore data and drill down into specific segments.

##🧮 DAX Measures Implemented

Some important DAX measures used:

Total Sales = SUM(Sales[Sales Amount])

Total Profit = SUM(Sales[Profit])

Total Quantity = SUM(Sales[Quantity])

Profit Margin % = DIVIDE([Total Profit], [Total Sales])

Target Achievement % = DIVIDE([Total Sales], [Target])

These measures ensure dynamic and accurate calculations based on selected filters.

##🏗️ Data Modeling Approach

Established relationships between fact and dimension tables.

Implemented a structured data model for optimized performance.

Ensured proper cardinality and cross-filter direction.

Followed best practices to maintain scalability and performance efficiency.

##📈 Business Insights Generated

Identified top-performing brands contributing maximum revenue.

Highlighted high-demand mobile models.

Detected seasonal sales fluctuations.

Analyzed regional sales gaps.

Evaluated profitability trends across products.

##🚀 Business Impact

This dashboard helps management to:

Monitor sales performance in real time

Improve strategic decision-making

Optimize inventory planning

Enhance regional sales strategies

Focus on high-profit product segments

##🔮 Future Improvements

Integration with live database (SQL Server / MySQL)

Forecasting using time-series analysis

Customer segmentation analysis

Drill-through detail pages

Advanced KPI benchmarking

