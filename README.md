
# 🛒 BlinkIT Grocery Data Dashboard – Power BI Project

##  Project Overview

This project presents a comprehensive Power BI dashboard built using BlinkIT's grocery sales data. The goal was to create an insightful, interactive visual analytics solution to help understand product trends, category performance, sales distribution, and customer buying behavior.

The project includes data exploration, transformation, and visualization to support data-driven decision-making for stakeholders in a retail/grocery business environment.

---

##  Files Included

- `BlinkIT Grocery Data.xlsx`: Raw dataset containing transactional-level data on product sales.
- `amanblinkit.pbix`: Power BI file that includes data model, transformations, and dashboard visualizations.

---

##  Key Features

- **Interactive Dashboard**: Visual storytelling with slicers and dynamic visuals.
- **Sales Analysis**: Total revenue, average sales per category, and performance over time.
- **Product Performance**: Best and worst-selling products.
- **Category Breakdown**: Sub-category-level insights with category filters.
- **Time Series Analysis**: Trend visualization to understand growth and fluctuations.
- **Customer Insights**: Identify key patterns and behaviors that drive sales.

---

##  Tools & Technologies Used

- **Power BI Desktop**
- **Excel (Data Source)**
- **DAX (Data Analysis Expressions)**
- **Power Query (Data Transformation)**

---

##  How to Use

1. Download both files: `BlinkIT Grocery Data.xlsx` and `amanblinkit.pbix`.
2. Open `amanblinkit.pbix` in Power BI Desktop.
3. Refresh the data source to ensure the dashboard reflects the latest data.
4. Use the slicers and filters to interact with the report.

---

##  Dashboard Walkthrough

###  1. Data Preparation & Cleaning (Power Query)

- Removed null & duplicate values.
- Standardized column names for readability.
- Converted date fields for proper time-based analysis.
- Parsed and merged relevant columns.
- Added derived columns (month/year) for trend analysis.

###  2. Data Modeling & DAX Calculations

- Built a star schema with related tables.
- Used DAX for key metrics like:
  - `Total Revenue`
  - `Average Revenue per Order`
  - `Top Product`
  - Time-based measures (YoY growth, monthly trends)

###  3. Executive Summary Page

- KPIs: Total Revenue, Orders, Avg Revenue/Order
- Trend line for revenue over time
- Category-wise revenue contribution

###  4. Product Performance Page

- Bar charts for top & bottom products
- Matrix with product metrics (quantity sold, revenue)
- Filter options for detailed views

###  5. Category & Subcategory Breakdown

- Stacked column charts and treemaps
- Slicers for interactive filtering
- DAX functions for dynamic updates

###  6. Time Series Trends

- Monthly/Yearly trend lines
- YoY comparison using DAX (`SAMEPERIODLASTYEAR`, `DATEADD`)

###  7. Customer Insights

- Order frequency analysis
- Preferred product categories
- Purchase behavior over time

---

##  Final Result

An interactive, business-oriented dashboard offering a 360-degree view of sales and product analytics. Ideal for retail/grocery sector insights.


