
---

# Gold Price Forecasting using ARIMA Model in R

## 📌 Project Overview

This project analyzes and forecasts gold prices using **Time Series Analysis** and the **ARIMA (AutoRegressive Integrated Moving Average) model** implemented in **R Programming**.
The study focuses on gold price data from **2014 to 2024**, sourced from Kaggle, and aims to provide insights into historical patterns and predict future trends.

---

## 🎯 Objectives

* Forecast future gold prices using the ARIMA model.
* Analyze trends and patterns of gold stock through **time series analysis**.
* Implement statistical modeling in **R** to evaluate accuracy and provide investment insights.

---

## 📂 Dataset

* **Source:** [Kaggle – Gold Stock Prices](https://www.kaggle.com/datasets/sahilwagh/gold-stock-prices)
* **Period:** January 19, 2014 – January 22, 2024
* **Records:** 2,532 entries
* **Features:** Date, Open, Close, High, Low, Volume

---

## 🛠️ Methodology

1. **Data Collection** – Gold price data extracted from Kaggle.
2. **Data Preparation** – Cleaning, transformation (BoxCox), and stationarity checks (ADF test).
3. **Exploratory Data Analysis (EDA)** – Trend analysis, decomposition, and visualization.
4. **Model Building** – Implementing ARIMA models.
5. **Model Evaluation** – Comparing accuracy of ARIMA(0,1,0) vs ARIMA(1,1,0).
6. **Forecasting** – Predicting gold prices and validating results.

---

## 📊 Results

* **Trend:** Gold price shows a continuous upward trend over the decade.
* **Best Model:** ARIMA(0,1,0) performed better than ARIMA(1,1,0).
* **Accuracy:** ARIMA(0,1,0) achieved lower RMSE, MAE, and MAPE values, making it the preferred model.
* **Investment Insights:** Forecasts help investors, businesses, and policymakers make informed financial decisions.

---

## 📷 Visualizations

The project includes:

* Time series trend plots
* Seasonal decomposition graphs
* ACF/PACF plots for parameter selection
* Forecast vs. actual price comparison

---

## 📌 Tools & Libraries

* **R Programming**
* `forecast` package
* `ggplot2` for visualization
* `tseries` for stationarity tests

---

## 📖 References

1. Banhi Guha and Gautam Bandyopadhyay (2016), *Gold Price Forecasting Using ARIMA Model*
2. Sharma, R.K. (2016), *Forecasting Gold price with Box Jenkins ARIMA Method*
3. Srilekha Nallamothu et al. (2023), *Forecasting gold prices in India using ARIMA model*
4. Kaggle Dataset – [Gold Stock Prices](https://www.kaggle.com/datasets/sahilwagh/gold-stock-prices)

---

## 👩‍💻 Authors

* Chepur Nandika
* Kuna Rasagnya
* Narsapuram Harshitha
* Puli Shakshitha
* Rudrakshala Kavya Sri

Guided by **Ms. M. Anusha, Assistant Professor, Department of Statistics**
Government Degree College for Women (Autonomous), Begumpet, Hyderabad

---

✨ *This project demonstrates the application of time series modeling to real-world financial data, showcasing the power of statistical forecasting in investment decision-making.*

---
