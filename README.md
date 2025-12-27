AI-Powered Sales Forecasting Dashboard
Project Overview
This project focuses on building an AI-powered sales forecasting system that helps retail businesses predict future sales trends using historical transaction data. The solution combines machine learning–based time series forecasting with an interactive Power BI dashboard to support data-driven business decisions.
The project simulates a real-world analytics workflow, including data preprocessing, exploratory analysis, model training, forecasting, and visualization.

Objectives
Analyze historical retail sales data to identify trends and seasonality
Forecast future sales using time-series models
Visualize actual and predicted sales in an interactive dashboard
Provide actionable business insights for planning and decision-making

Dataset
The project uses the Kaggle Retail / Rossmann Store Sales dataset, which includes:
train.csv – Historical sales and promotional data
test.csv – Future dates for prediction
store.csv – Store-level metadata
These datasets were merged and processed to enrich the forecasting model with business context.

Tools & Technologies
Python – Data processing and model development
Pandas, NumPy – Data cleaning and feature engineering
Matplotlib, Seaborn – Exploratory data analysis
Facebook Prophet – Time series forecasting
Jupyter Notebook / Google Colab – Development environment
Power BI Desktop – Interactive dashboard creation

Project Workflow
Data collection and merging of transactional and store-level datasets
Data cleaning, preprocessing, and handling missing values
Exploratory data analysis to identify trends and seasonality
Time-series forecasting using the Prophet model
Generation of future sales predictions
Visualization of actual vs forecasted sales using Power BI
Business insight generation and interpretation

Dashboard Features
Actual vs Forecasted sales trend line
Monthly and yearly sales comparisons
KPI cards for total and average sales
Interactive filters for time-based analysis
Business insight annotations

Project Structure
├── data/
│   ├── train.csv
│   ├── test.csv
│   ├── store.csv
│   ├── monthly_sales.csv
│   └── sales_forecast.csv
├── notebooks/
│   └── sales_forecasting.ipynb
├── powerbi/
│   └── sales_forecasting_dashboard.pbix
├── README.md

Key Insights
Sales exhibit strong seasonal patterns influenced by promotions and holidays
Certain months consistently generate higher revenue
Forecasted trends indicate stable demand in upcoming periods
The model supports proactive inventory and promotion planning

 Future Enhancements
Add holiday and promotion-based regressors to the forecasting model
Compare multiple models (ARIMA, XGBoost) for accuracy
Automate data refresh and dashboard updates
Deploy forecasting model as a web API

Learning Outcomes
Practical understanding of time-series forecasting
Experience in combining machine learning with business analytics
Hands-on Power BI dashboard development
End-to-end data science project execution

Contact
Author: Nikshith Kumar
LinkedIn: https://www.linkedin.com/in/nikshith-selari/
