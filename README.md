# 📊 End-to-End Sales Forecasting & Business Intelligence Dashboard

## 🚀 Project Summary

This project demonstrates how Machine Learning & Business Intelligence can be combined to build an executive sales forecasting dashboard.

The solution simulates a real-world analytics workflow:

**Raw Data → ETL → Forecast Model → Data Warehouse → Power BI Dashboard**

### 🎯 Objectives

* Transform raw retail sales data into analytics-ready datasets
* Build a time-series forecasting model
* Evaluate model performance using ML metrics
* Integrate predictions into a BI dashboard
* Create executive-level KPIs & interactive analytics

### 🏗️ Architecture Overview:

Raw Sales Data->
Python ETL Pipeline->
Time-Series Forecast Model->
Prediction Export (CSV)->
Power BI Star Schema->
Executive Dashboard

### 🤖 Machine Learning & Forecasting

Sales forecasting was performed using Facebook Prophet.

**-📏 Model Evaluation**

- MAE: 14,501

- RMSE: 19,156

- MAPE: 17.8%

The model captures trend & seasonality, making it suitable for business planning.

### ⚙️ Data Engineering & ETL

Python pipeline performs:

- Date parsing & feature engineering

- Monthly aggregation of sales

- Category-level forecasting

- Export of BI-ready datasets

 Libraries Used :

- Pandas

- NumPy

- Prophet

### 🧩 Data Modeling & Star Schema

A star schema was designed in Power BI.

**⭐ Fact Table**

fact_sales → historical transactions

**📅 Dimension Table**

calendar → continuous date table

**🔮 Prediction Table**

category_forecasts → ML predictions

This enables scalable & performant analytics.

### 📈 Business KPIs (DAX)

Executive metrics created in Power BI:

- Total Revenue

- Forecast Revenue

- Forecast Gap

- Month-over-Month Growth

- Year-over-Year Growth

These KPIs support strategic planning & performance monitoring.

### 📊 Dashboard Highlights
- Executive Overview
- Revenue KPI cards
- Forecast vs Actual trend
- Growth indicators
- Performance Insights
- Revenue by Region
- Revenue by Product Category
- Interactive Date Filtering

### 🛠️ Tech Stack
- Area	Tools
- Data Processing	Python & Pandas
- Machine Learning	Prophet
- BI & Visualization	Power BI
- Analytics	DAX

### 💼 Business Value

This solution demonstrates how predictive analytics can enable:

- Revenue planning & budgeting

- Demand forecasting

- Performance monitoring

- Data-driven decision making

### 📌 Conclusion

This project showcases an end-to-end analytics pipeline combining:

* Data Engineering + Machine Learning + Business Intelligence to deliver actionable insights for business users.

  <img width="1913" height="982" alt="image" src="https://github.com/user-attachments/assets/eb51843a-8322-4f44-a960-fbfce7cdc940" />



https://github.com/user-attachments/assets/d3902a4b-12a6-4c7b-8b52-293f70d7d76e


