# 🍽️ Food Delivery Analytics Dashboard

## 📌 Project Overview
This project analyzes food delivery order data to understand revenue performance, customer behavior, and restaurant performance. An interactive Power BI dashboard helps users explore business KPIs and identify useful trends.

## 🎯 Project Objectives
- Analyze total revenue, order volume, and average order value.
- Understand customer demographics and spending behavior.
- Identify top-performing restaurants, cities, and cuisines.
- Track monthly revenue trends.
- Clean and validate data before reporting.

## 🛠️ Tools & Technologies
- **Python:** Data cleaning and preprocessing
- **MySQL:** Data validation, querying, and analysis
- **Power BI:** Interactive dashboards, KPIs, and visualizations
- **Excel/CSV:** Data storage and exchange

## 📊 Dashboard Pages

### 1. Overview
- Total Revenue
- Total Orders
- Eligible Orders
- Average Order Value
- Monthly Revenue Trend
- Top 10 Restaurants by Revenue
- Revenue by City

### 2. Customer Analysis
- Customers by Gender
- Customers by Occupation
- Customers by Age Group
- Revenue by Occupation
- Repeat Customer Rate
- Customer Spending Segments

### 3. Restaurant Analysis
- Total Restaurants
- Average Restaurant Rating
- Total Cities
- Top 10 Restaurants by Revenue
- Restaurant Ratings Distribution
- Revenue by City
- Revenue by Cuisine

## 🔍 Key Insights & Findings

### 1. Revenue Performance
- Total recorded sales amount to approximately **₹986.57 million**.
- **148,670 orders** are eligible for revenue analysis out of 150,281 total orders.
- Average Order Value (AOV) is approximately **₹6,635.94**.
- Monthly revenue trends help identify stronger and weaker sales periods.

### 2. Customer Analysis
- Customer demographics can be compared by gender, age group, and occupation.
- Revenue by occupation helps identify customer groups contributing to sales.
- Repeat Customer Rate measures customer retention and repeat purchasing behavior.
- Spending segments classify customers into low, medium, and high spenders for further analysis.

### 3. Restaurant Performance
- Ranking restaurants by revenue identifies the highest-revenue contributors.
- Revenue by city helps compare geographic performance.
- Revenue by cuisine highlights differences in sales contribution across cuisine categories.
- Restaurant rating distribution helps understand the availability of ratings and the spread of restaurant scores.

### 4. Data Quality Findings
- The dataset contains **150,281 orders** and **100,000 customer records**.
- **1,617 orders** have missing restaurant IDs.
- **87 distinct non-null restaurant IDs** in orders were found to have no matching restaurant record.
- **1,609 orders** have zero sales amounts, and **2 orders** have negative sales amounts.
- No exact duplicate order rows were found during validation.

### 5. Business Recommendations
- Investigate missing and unmatched restaurant IDs to improve restaurant-level reporting.
- Study monthly revenue declines to identify possible opportunities for sales improvement.
- Develop retention campaigns for customers who purchase infrequently.
- Use customer spending segments to plan targeted offers and loyalty programs.
- Combine revenue, cuisine, city, and rating information to support restaurant performance reviews.

*Note: Revenue and order metrics use the project's positive-sales eligibility rule. Restaurant-level totals may differ from overall revenue because some orders have missing or unmatched restaurant IDs. Confirm monthly trends, top restaurants, and customer segment percentages against the final Power BI report before publishing.*

## 🧹 Data Cleaning & Quality Checks
- Checked missing values and duplicate records.
- Standardized dates and data types.
- Investigated zero and negative sales amounts.
- Identified missing and unmatched restaurant IDs.
- Created a flag to identify orders included in revenue calculations.
- Preserved valid records while documenting data-quality issues.

## 📈 Business Value
The dashboard helps stakeholders monitor revenue trends, compare restaurant performance, understand customer segments, and make data-informed decisions.

## 🚀 Key Learning Outcomes
- Data cleaning and validation using Python.
- SQL queries for business analysis.
- Data modeling and DAX measures in Power BI.
- Interactive report design and KPI development.
- Translating raw data into business insights.

## 👨‍💻 Author
**Satish Ayare**  
Aspiring Data Analyst | Python | SQL | Power BI
