# ecommerce-eda-PythonAnalysis
__A data analysis project on e-commerce sales using Python and Jupyter Notebook. Includes exploratory data analysis (EDA), sales and profit insights, customer segmentation, and visualizations for data-driven decision-making.__
Steps Followed in the Analysis

# **Project Overview**

##### This project focuses on analyzing sales and profitability patterns in an E-commerce dataset to generate actionable business insights. Using Python and Jupyter Notebook, the analysis covers sales performance across months, categories, sub-categories, and customer segments.

##### The purpose of this project is to help businesses understand:

##### Which time periods contribute most to revenue.

##### Which product categories and sub-categories drive sales and profitability.

##### How customer segments differ in terms of sales contribution and profit margins.

##### Whether high sales always translate into higher profits, or if certain areas are loss-making despite strong revenue.

##### By combining data cleaning, visualization, and exploratory analysis, the project provides a clear view of both strengths and challenges in the store’s performance, enabling data-driven decision-making.

**Objectives**

->Data Cleaning & Preparation

Load and preprocess the dataset to make it ready for analysis.

Convert dates into usable formats (e.g., monthly sales tracking).

->Sales Analysis

# Business Questions / Objectives(KPIs)

The project is designed to answer the following business questions:

Calculate the monthly sales of the store and identify which month had the highest sales and which month had the lowest sales.

Analyze sales based on product categories and determine which category has the lowest sales and which category has the highest sales.

Perform sales analysis based on sub-categories to identify top and bottom performers.

Analyze the monthly profit from sales and determine which month had the highest profit.

Analyze the profit by category and sub-category to identify the most and least profitable areas.

Analyze the sales and profit by customer segment (Consumer, Corporate, Home Office).

Calculate and analyze the sales-to-profit ratio to check if higher sales always mean higher profits.


**Detailed Steps Followed**
1. Data Import & Setup

Imported essential Python libraries: pandas, numpy, matplotlib, seaborn, and plotly.

Loaded dataset (Sample - Superstore.csv) into Pandas DataFrame.

Checked for missing values, duplicates, and data types.

2. Data Cleaning & Transformation

Converted Order Date into datetime format.

Extracted Order Month for trend analysis.

Created summarized dataframes (e.g., sales by category, sales by month).

3. Exploratory Data Analysis (EDA)

a. Monthly Sales Analysis

Created line plots of monthly sales.

Observed seasonal demand patterns.

b. Sales by Category & Sub-Category

Used pie charts and bar plots to visualize contribution.

Found Technology & Office Supplies as strong performers, while Furniture lagged.

c. Profitability Analysis

Monthly profit trends visualized with bar charts.

Profit by Category → Technology most profitable, Furniture least profitable.

Profit by Sub-Category → Identified Copiers as highly profitable and Tables as loss-making.

d. Customer Segment Analysis

Compared sales vs profit by Consumer, Corporate, Home Office.

Found that Consumers drive sales, while Corporate/Home Office deliver better profitability.

e. Sales-to-Profit Ratio

Highlighted that high sales don’t guarantee high profit.

Identified categories/sub-categories with mismatched sales vs profit.

4. Visualization

Used Plotly Express for interactive charts: line plots, bar charts, pie charts.

Enhanced analysis with percentage and ratio visuals.


**Key Findings & Insights**

Monthly Trends

Seasonal demand is visible; some months consistently outperform others.

Category Insights

Office Supplies → Highest sales volume.

Technology → Strong profits.

Furniture → Lower profitability, with Tables showing negative margins.

Sub-Category Insights

Phones, Chairs, and Binders → Drive most sales.

Copiers → Extremely profitable.

Tables → Major loss contributor.

Customer Segment Insights

Consumers contribute most sales.

Corporate & Home Office segments are more efficient in profit contribution.

Sales vs Profit

High sales ≠ high profit. Some products sell in high volume but weaken margins.

✅ Conclusion: Businesses should focus on high-margin products (Technology, Copiers) while addressing loss-making categories (Furniture – especially Tables). Balancing sales volume with profitability can improve overall business health.

**📊 Tools & Libraries Used**

Python

Jupyter Notebook

Pandas & NumPy – Data cleaning and analysis

Matplotlib & Seaborn – Static visualization

Plotly – Interactive visualization
