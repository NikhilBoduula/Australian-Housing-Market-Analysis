📊 Australian Housing Market Analysis Dashboard
📌 Project Overview

This project presents an end-to-end analysis of the Australian housing market using monthly macroeconomic data.
The objective is to understand how interest rate movements influence house prices and to communicate these insights through clear visual analytics.

The project integrates data analysis, machine learning, time-series forecasting, and interactive visualization to deliver both technical and business-level insights.

🎯 What Was Accomplished

Analyzed long-term trends in Australian house prices

Studied the impact of interest rates on housing prices

Built predictive models to forecast future price movement

Designed an interactive Power BI dashboard for easy interpretation

🛠️ Tools & Technologies Used
🔹 Python

Used for data processing and analytical modeling:

Data cleaning and preprocessing

Exploratory Data Analysis (EDA)

Correlation analysis

Linear Regression

ARIMA time-series forecasting

Libraries used:

pandas

numpy

matplotlib

scikit-learn

statsmodels

🔹 Jupyter Notebook / VS Code

Used as the analysis workspace to:

Execute step-by-step analysis

Visualize trends and relationships

Experiment with models and parameters

Document insights clearly

🔹 Power BI

Used to convert analytical results into business-friendly visuals:

KPI cards summarizing key metrics

Time-series trend analysis

Relationship analysis using scatter plots

Interactive dashboard for decision-making

📂 Dataset Description

Source: Australian macroeconomic monthly dataset

Time Granularity: Monthly

Features:

Month – Time period

Cash_Rate_Target – Official interest rate

House_Price_Index – Residential property price index

🔍 Analysis Performed (Python)
1️⃣ Data Preparation

Loaded and cleaned monthly housing data

Converted time columns for time-series analysis

Verified data consistency and completeness

2️⃣ Exploratory Data Analysis (EDA)

Visualized trends in house prices and interest rates

Identified growth, decline, and stabilization phases

Compared long-term patterns across years

3️⃣ Correlation & Regression Analysis

Calculated correlation between interest rates and house prices

Built a Linear Regression model to quantify the impact

Key Finding:

A moderate negative relationship exists between interest rates and house prices.
Higher interest rates generally lead to a decline in housing prices.

4️⃣ Time-Series Forecasting

Applied the ARIMA model on house price index

Forecasted future price trends

Observed short-term price stability in recent years

📈 Power BI Dashboard

The Power BI dashboard provides an interactive summary of insights:

Dashboard Components:

KPI Cards

Average House Price Index

Average Cash Rate

Latest House Price Index

Line Charts

House price trend over time

Interest rate trend over time

Scatter Plot

Relationship between interest rates and house prices

📌 The dashboard enables non-technical users to quickly understand complex housing market trends.

📊 Key Insights

Australian house prices grew rapidly until around 2017

Prices have shown relative stability in recent years

Interest rates have a clear inverse effect on housing prices

Forecasting indicates short-term stability in house prices

📁 Project Structure
Australian-Housing-Market-Analysis/
│
├── data/
│   └── Australia_Macro_Data_Monthly.csv
│
├── notebooks/
│   └── Australian_Housing_Analysis.ipynb
│
├── powerbi/
│   └── Australian_Housing_Market_Dashboard.pbix
│
├── README.md

🚀 How to Run the Project

Clone the GitHub repository

Install required Python libraries

Open the Jupyter notebook and run cells sequentially

Open the Power BI .pbix file to explore the dashboard

🎯 Conclusion

This project demonstrates a complete data analytics lifecycle, from raw data to actionable insights.
By combining Python-based analysis with Power BI visualization, the project successfully delivers meaningful insights into the Australian housing market.

👤 Author

Nikhil Boddula
B.Tech CSE (Data Science)
Aspiring Data Analyst / Data Scientist
