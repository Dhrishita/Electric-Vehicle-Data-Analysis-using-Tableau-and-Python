# 🚗 Electric-Vehicle-Data-Analysis-using-Tableau-and-Python

This project focuses on analyzing Electric Vehicle (EV) adoption trends using Python for data cleaning, preprocessing, and exploratory analysis, and Tableau for data visualization and dashboard creation.

The aim is to uncover key insights about EV growth, distribution, and adoption patterns, helping policymakers, businesses, and researchers make data-driven decisions.

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

Electric Vehicles are becoming a crucial part of the sustainable transport ecosystem.

The main challenges addressed in this project:

- Understanding the adoption rate of EVs over time
- Identifying top EV manufacturers and models
- Analyzing geographical distribution of EVs
- Studying EV range trends and preferences
- Providing visual insights for stakeholders

## 🔑 Key Metrics

- Total Vehicles: 150,413
- Total BEV Vehicles: 116,745 (77.6%)
- Total PHEV Vehicles: 33,668 (22.4%)
- Average Electric Range: 67.83 miles
- CAFV Eligible Vehicles: 62,887 (41.8%)

## 🔍 Visual Insights

- Top EV Manufacturers: Tesla, Nissan, Chevrolet dominate the market.
- Top EV Models: Tesla Model Y, Model 3, and Nissan Leaf are the most popular.
- Geographic Distribution: High EV adoption in Washington, California, and nearby regions.
- CAFV Analysis: Nearly half of the EVs have unknown CAFV eligibility status.

## 🛠️ Tools and Technologies

- Programming: Python 🐍
- Excel: For initial data cleaning and preparation.
- Tableau: For data visualization and exploratory data analysis (EDA).
- Libraries: Pandas, NumPy, Matplotlib, Seaborn
- Environment: Google Colab Notebook

## 🧹 Data Cleaning and Analysis

- Removed duplicates and null values.
- Standardized EV types into BEV (Battery Electric Vehicle) and PHEV (Plug-in Hybrid Electric Vehicle).
- Extracted numeric values from range fields.
- Grouped and aggregated data by state, make, and model.

## 📈 Dashboard

<img width="2798" height="1242" alt="Electric Vehicle Data Analysis" src="https://github.com/user-attachments/assets/d38f658e-e54c-4336-8dd4-b67790235744" />


## 📊 Visual Highlights

- Tesla accounts for 52% of EV adoption, showcasing its market dominance.
- Washington state shows the highest EV concentration.
- Average EV range is improving but still varies widely by model.
- CAFV data highlights policy-driven incentives’ impact on EV ownership.

## 🎯 Next Steps / Recommendations

Based on the analysis, the following insights and recommendations were derived:

- Promote High-Performing EV Models: Focus on top-selling EV brands and models that show consistent adoption. Encourage their market presence through incentives, promotions, or collaborations with manufacturers.
- Address Low Adoption Regions: Identify states/cities with lower EV registrations. Investigate barriers such as lack of charging infrastructure or awareness, and implement location-specific awareness campaigns and infrastructure investments.
- Encourage Long-Range EV Adoption: Insights show that newer EV models offer better ranges. Promote these models through policy support, subsidies, and campaigns to attract consumers looking for reliability in long-distance travel.
- Charging Infrastructure Expansion: Geographical analysis highlights areas with rising adoption. Prioritize setting up charging stations in these hotspots to sustain growth and enhance convenience.
- Customer Preference Analysis: Utilize brand and vehicle type distribution to understand whether consumers prefer BEVs or PHEVs, and align marketing and policy strategies accordingly.

## ⚙️ Installation

To get started with the project, follow these steps:

1. Clone the repository:
   
   ```bash
   git clone https://github.com/Dhrishita/Electric-Vehicle-Data-Analysis-using-Tableau-and-Python.git
   cd Electric-Vehicle-Data-Analysis-using-Tableau-and-Python
   
2. Install dependencies:
   
   ```bash
   pip install -r requirements.txt

3. Run the Colab Notebook for analysis:

   ```bash
   pytho3 EV_Data_Analysis.py

## Conclusion

This project demonstrates how Python + Tableau can be leveraged for data-driven insights into EV adoption. The findings can guide manufacturers, policymakers, and researchers in shaping the future of sustainable transportation.

## Contact
If you have any questions or suggestions, feel free to open an issue or contact:
Dhrishita Parve: dhrishitap18@gmail.com






