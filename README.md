# ecommerce-eda-PythonAnalysis
__A data analysis project on e-commerce sales using Python and Jupyter Notebook. Includes exploratory data analysis (EDA), sales and profit insights, customer segmentation, and visualizations for data-driven decision-making.__
Steps Followed in the Analysis

**Project Overview**

This project performs a comprehensive exploratory data analysis (EDA) on an E-commerce sales dataset using Python and Jupyter Notebook. The goal is to uncover business insights around sales performance, profitability, customer segments, and product trends.

The analysis helps in answering key questions such as:

Which categories and sub-categories drive the most sales and profit?

1.Do high sales always mean high profits?

2.Which customer segments are most valuable?

3.Are there seasonal trends in sales and profit?

**Objectives**

->Data Cleaning & Preparation

Load and preprocess the dataset to make it ready for analysis.

Convert dates into usable formats (e.g., monthly sales tracking).

->Sales Analysis

Analyze monthly sales performance.

Evaluate sales distribution by category and sub-category.

Identify top-performing products and weak performers.

->Profitability Analysis

Compare sales vs profit across time, categories, and sub-categories.

Find loss-making items that negatively affect overall margins.

-Customer Segment Insights

Explore sales and profit by Consumer, Corporate, and Home Office segments.

Evaluate contribution and profitability of each segment.

-Visualization & Storytelling

Use interactive charts for clear storytelling.

Provide actionable insights for business strategy.


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
