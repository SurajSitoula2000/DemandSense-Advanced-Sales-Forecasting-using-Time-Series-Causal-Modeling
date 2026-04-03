## 📌 Project Overview:
This project focuses on forecasting retail product sales using historical data and advanced time series techniques. Multiple statistical models such as Naive Forecasting, Holt-Winters, ARIMA, and Regression were implemented and compared to identify the most accurate forecasting approach.

## 🎯 Objective
- Analyze historical sales data to identify trends, seasonality, and patterns
- Build and compare multiple forecasting models
- Evaluate model performance using error metrics like MAPE
- Provide actionable insights for demand planning and business decision-making

## 📊 Dataset Description:
- Contains sales data from 10 stores and 50 products
- Time period: 2013 – 2017
- Features include:
    - Date
    - Store ID
    - Item ID
    - Sales

## 🛠️ Tools & Technologies:
- Python (Pandas, NumPy)
- Matplotlib & Seaborn (Visualization)
- Statsmodels (Time Series Models)
- Jupyter Notebook

## ⚙️ Project Workflow:
1. Data Cleaning & Preprocessing
- Removed unnecessary columns
- Converted date column to datetime format
- Handled missing values using interpolation

2. Exploratory Data Analysis (EDA)
- Analyzed sales trends across:
    - Days of the week
    - Months
    - Years
- Identified:
    - Increasing yearly sales trend
    - Strong seasonality patterns
    - Weekly demand fluctuations
      
3. Feature Engineering
- Extracted time-based features (day, month, year)
- Focused analysis on specific store-item combinations

5. Time Series Modeling
Implemented and compared:
  - Naive Forecasting (Baseline)
  - Holt-Winters (Exponential Smoothing)
  - ARIMA / SARIMA
  - Regression (Causal Model)
    
5. Model Evaluation
- Used MAPE (Mean Absolute Percentage Error) for performance comparison
- Compared models against baseline

## 📈 Results & Insights (IMPORTANT – Use in Resume also)
- Baseline model achieved MAPE: 26.03%
- Holt-Winters model captured trend & seasonality effectively (MAPE: ~27.6%)
- ARIMA model showed moderate performance (MAPE: ~30.8%)
- Strong seasonal and upward trend patterns observed in sales data

## 📊 Key Insights
- Sales peak during mid-year months (June–July)
- Highest demand observed on Saturdays
- Clear seasonal and trend components influence sales forecasting

## 🚀 Future Improvements
- Incorporate external factors (holidays, promotions, pricing)
- Use machine learning models (XGBoost, LSTM)
- Deploy forecasting model using Streamlit or Flask

## 👨‍💻 Author
Suraj Sitoula \
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/suraj-sitoula/) \
Aspiring Data Analyst | Skilled in SQL, Python, Power BI, Tableau, Machine Learning!
