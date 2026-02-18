Superstore Sales Analysis Dashboard – Power BI Project
📌 Project Overview

This project presents an interactive Superstore Sales Analysis Dashboard built using Microsoft Power BI.
The objective of this project is to analyze business performance, identify trends, and generate actionable insights from sales data.

The dashboard provides a clear understanding of sales, profit, orders, and regional performance using dynamic visualizations and filters.

🎯 Project Objectives

Analyze Total Sales, Profit, and Orders

Identify high-performing categories and products

Compare regional performance

Track sales trends over time

Calculate and analyze Profit Margin

Create an interactive dashboard for business insights

📂 Dataset Information

Dataset: Superstore Sales Dataset

Data includes:

Order Date

Ship Mode

Customer Segment

Region

Category & Sub-Category

Sales

Profit

Quantity

The dataset was cleaned before loading into Power BI to remove duplicates and handle missing values.

🛠 Tools & Technologies Used

Microsoft Power BI

Power Query (Data Cleaning & Transformation)

DAX (Data Analysis Expressions)

Data Modeling

Interactive Visualizations

📊 Key Metrics (KPIs)

💰 Total Sales: 2.30M+

📈 Total Profit: 286K+

🛒 Total Orders: 10K+

📊 Profit Margin %

📈 Dashboard Features
1️⃣ Sales Overview

Total Sales, Profit, Orders (KPI Cards)

Sales by Category

Sales by Region

2️⃣ Profit Analysis

Profit by Category & Sub-Category

Regional Profit Distribution

Profit Margin Calculation

3️⃣ Time-Series Analysis

Monthly / Yearly Sales Trend

Growth Pattern Visualization

4️⃣ Interactive Filters (Slicers)

Region

Category

Segment

Order Date

🔗 Data Modeling

Created relationships between:

Orders Table

Customer Data

Product Categories

Applied star schema principles

Optimized model performance

🧮 DAX Measures Used

Some key DAX measures:

Total Sales = SUM(Superstore[Sales])

Total Profit = SUM(Superstore[Profit])

Total Orders = COUNT(Superstore[Order ID])

Profit Margin = DIVIDE([Total Profit], [Total Sales], 0)

💡 Key Insights

Certain regions contribute higher sales but lower profit.

Technology category generates higher profit margins.

Seasonal trends impact overall revenue.

Some sub-categories have high sales but low profitability.

🚀 Business Value

This dashboard helps decision-makers to:

Improve profit margins

Focus on high-performing regions

Identify underperforming products

Make data-driven strategic decisions

 Project Outcome

This project demonstrates:

Strong understanding of Power BI fundamentals

Data cleaning and transformation skills

DAX calculation proficiency

Data modeling knowledge

Dashboard design and storytelling ability

 How to Use

Open the .pbix file in Power BI Desktop.

Interact with slicers to filter data.

Analyze KPIs and trends.

Explore category and regional insights.
