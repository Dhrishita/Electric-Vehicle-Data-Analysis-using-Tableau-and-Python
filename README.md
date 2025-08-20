# 🚗 Electric-Vehicle-Data-Analysis-using-Tableau-and-Python

This project focuses on analyzing Electric Vehicle (EV) data to uncover insights into adoption trends, vehicle distribution, range statistics, and eligibility under Clean Alternative Fuel Vehicle (CAFV) programs. Using Python for data cleaning and analysis and Tableau for interactive dashboard creation, the project provides a comprehensive overview of EV adoption across states, manufacturers, and models.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Problem Statement](#problem-statement)
- [Key Metrics](#key-metrics)
- [Visual Insights](#visual-insights)
- [Tools and Technologies](#Tools-and-Technologies)
- [Data Cleaning and Analysis](#Data-Cleaning-and-Analysis)
- [Dashboard](#dashboard)
- [Visual Highlights](#Visual-Highlights)
- [Next Steps / Recommendations](#Next-Steps-/-Recommendations)
- [Installation](#installation)
- [Conclusion](#conclusion)
- [Contact](#contact)

## 📖 Project Overview

The project provides an end-to-end EV Data Analysis pipeline:
- Cleaning and preprocessing raw EV data using Python.
- Performing exploratory data analysis (EDA) to identify patterns.
- Creating interactive Tableau dashboards for better visualization of insights.

This analysis helps policymakers, manufacturers, and researchers understand EV adoption patterns and plan sustainable transportation strategies.

## 📂 Dataset

- Source: [Kaggle – Electric Vehicle Population Dataset](https://www.kaggle.com/datasets/utkarshx27/electric-vehicle-population-data)
- Attributes:
  - Vehicle make and model
  - EV type (BEV / PHEV)
  - Electric range
  - State and county distribution
  - CAFV eligibility
    
## 🚩 Problem Statement

The coffee shop struggled to understand its overall sales performance and lacked visibility into:

- 📊 Total sales and transaction analysis
- 📦 Total quantity sold
- 📅 Sales patterns across weekdays vs. weekends
- 🏬 Sales performance by store location
- 📈 Daily & hourly sales trends
- 🍵 Product category contributions
- ⭐ Best-selling products (Top 10)

The objective was to uncover key drivers of sales and identify areas for improvement.

## 📊 Key Metrics

- Total Sales: $698,812.33
- Total Footfall: 149,116
- Avg. Bill per Person: $4.69
- Avg. Orders per Person: 1.44

## 🔍 Visual Insights

- 🕒 Peak Sales Hours: Morning hours, particularly between 9 AM and 11 AM, record the highest transaction volume.
- 📊 Category Sales Breakdown: Coffee (39%), Tea (28%), Bakery (12%), etc.
- 📏 Size Distribution: Regular (31%), Large (30%), Small (9%)
- 📍 Top Locations by Footfall: Hell’s Kitchen, Astoria, Lower Manhattan
- 🥇 Top-Selling Products: Barista Espresso, Brewed Teas, Hot Chocolate
- 📅 Sales Distribution: Sales are stronger on weekdays, with distinct patterns observed across different months.
- 💳 Preferred Payment Method: Card payments dominate over cash transactions.
- ☕ Top-Selling Beverages: Latte and Americano with Milk lead as the most popular items.
- 🎯 Customer Retention: A small subset of loyal customers is responsible for a significant proportion of repeat purchases.

## 🛠️ Tools and Technologies

- Programming: Python 🐍
- MySQL: For storing and querying sales data.
- Excel: For initial data cleaning and preparation.
- Power BI: For data visualization and exploratory data analysis (EDA).
- Libraries: Pandas, Matplotlib, Seaborn
- Environment: Google Colab Notebook

## 🧹 Data Cleaning and Analysis

Data cleaning was performed in Excel and transformed into power bi power query to ensure data integrity and consistency.

Excel

- Changing Data Types: Ensured that numeric columns (e.g., sales amount, quantity sold, order ID) were set to appropriate numeric data types.
- Replacing Null Values: Applied methods such as filling with mean/median for numeric fields.
- Formatting Cells: Ensured proper formatting for columns, such as setting number formats with appropriate decimal places.
- Handling Missing Values: Used Excel functions to fill or remove missing data.
- Categorizing Products and Locations: Ensured consistent labeling for products and locations.
- Standardizing Date Formats: Used Excel functions to convert date columns to a consistent format.

Power BI

- Data Modeling: Created a date table and connected it with the transaction table using the date column as the common key. This allows for time-based analysis and filtering in the dashboard.
- Conditional Formatting: Used conditional formatting to highlight important data points and trends in the visualizations.
- Data Validation: Implemented data validation rules to ensure data quality and accuracy.
- Data Transformation: Utilized Power Query Editor to perform data cleaning operations such as removing duplicates, filtering rows, and transforming data types.

MySql & DAX

- Utilized MySql and DAX to make measures and calculations for Total sales, Total orders, Total quantity sold, Sales analysis by weekdays and weekends, Sales analysis by store location, Daily sales with average line, Sales analysis by product category, Sales analysis by days and hours.

## 📈 Dashboard

<img width="1827" height="766" alt="Dashboard" src="https://github.com/user-attachments/assets/8932bfe5-c196-43b3-be3e-63c940265114" />

## 📊 Visual Highlights

Selected visualizations from the analysis:

1. 📈 Daily Sales Trend

<img width="1200" height="600" alt="Daily_sales_trend" src="https://github.com/user-attachments/assets/9c96f4cd-5efb-4747-9e4c-b643d8896200" />

2. ☕ Best-Selling Products

<img width="1000" height="500" alt="Best_selling_product" src="https://github.com/user-attachments/assets/61b481bb-5f85-45da-b3c1-067179e30acc" />

3. ⏰ Peak Sales Hours

<img width="1000" height="500" alt="Peak_sales_analysis" src="https://github.com/user-attachments/assets/6b482a6b-55f6-4ecd-bf11-dcdc7f361a9f" />

## 🎯 Next Steps / Recommendations

Based on the analysis, the following insights and recommendations were derived:

- Optimize Product Mix: Focus on high-performing products and consider phasing out or improving low-performing products.
- Enhance Location Performance: Identify locations with lower sales and analyze factors contributing to underperformance. Implement targeted strategies to boost sales in these locations.
- Weekday vs. Weekend Promotions: Leverage sales patterns to design promotions and marketing campaigns tailored for weekdays and weekends.
- Time-Based Marketing: Utilize insights from daily and hourly sales analysis to optimize opening hours and schedule targeted promotions.
- Customer Preferences: Use product sales data to understand customer preferences and tailor offerings accordingly.

## ⚙️ Installation

To get started with the project, follow these steps:

1. Clone the repository:
   
   ```bash
   git clone https://github.com/Dhrishita/Coffee-Shop-Sales-Analysis-with-Dashboard.git
   cd CoffeeSales
   pip install -r requirements.txt

## Conclusion

The Coffee Shop Sales Analysis dashboard provides valuable insights into the sales performance of the coffee shop. By understanding key metrics and trends, the company can make data-driven decisions to enhance sales strategies, improve product offerings, and optimize overall performance.

## Contact
If you have any questions or suggestions, feel free to open an issue or contact:
Dhrishita Parve: dhrishitap18@gmail.com






