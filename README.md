# Project: Blinkit Sales Story: A Power BI Insightful Report 

# Table of content
- Introduction
- Objective
- Tools and Technologies
- Data Analyis
- Data Analysis (DAX)
- Build Dashboard or report
- Project Insights

# Introduction
The "Blinkit Sales Story" project is an interactive Power BI report designed to uncover valuable insights from Blinkit sales data. This analysis emphasizes the relationship between sales and various factors, such as fat content, item types, outlet characteristics, and geographic locations, offering a holistic view of business performance.

# Objective
The primary objective of this project is to analyze Blinkit sales data and derive actionable insights by visualizing key performance indicators (KPIs) such as: Total Sales, Average Sales,
Number of Items Sold and Average Rating.
Specific objectives include:
- Assessing the impact of fat content on sales performance.
- Identifying the best-performing item types.
- Evaluating sales trends across outlets based on establishment year, size, and location.
- Exploring a comprehensive breakdown of metrics by outlet type.

# Tools and Technologies
Power BI: For data visualization and dashboard creation.
Excel: Data preparation and formatting.
DAX (Data Analysis Expressions): For performing advanced calculations and creating custom measures.

# Data Analyis
1. Data Cleaning:
  - Handled missing and duplicate values.
  - Standardized column names for consistency.
  - Verified data types and corrected errors.
2.Exploratory Data Analysis (EDA):
  - Conducted preliminary analysis to understand trends, distributions, and correlations.
  - Identified potential KPIs and dimensions for deeper analysis.

# Data Analysis
Key Measures:
Total Sales:
```
Total Sales = SUM('BlinkIT Grocery Data'[Sales])
```
2.Average Sales:
```
Avg Sales = AVERAGE('BlinkIT Grocery Data'[Sales])
```
3.Number of Items:
```
No of items = COUNTROWS('BlinkIT Grocery Data')
```
4.Average Rating:
```
Avg Rating = AVERAGE('BlinkIT Grocery Data'[Rating])
```

# Build Dashboard or report
![Blinkit sales report]()

# Project Insights
- Impact of Fat Content:
    Low-fat products dominated total sales, suggesting a trend toward healthier options.
    High-fat products showed higher average ratings but lower total sales.
  
- Item Type Performance:
    Specific item types contributed disproportionately to total sales, indicating potential focus areas for promotion.
  
- Outlet Characteristics:
    Newer outlets showed rapid growth, while older outlets contributed consistently to sales.
    Medium-sized outlets had the highest sales volume compared to small and large ones.
