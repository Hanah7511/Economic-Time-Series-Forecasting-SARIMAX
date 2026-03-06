# 📊 Economic Time-Series Forecasting using SARIMAX (Iran GDP Prediction)

## 🚀 Project Overview
This project develops a **multivariate economic time-series forecasting system** to predict Iran’s GDP using advanced statistical and machine learning approaches, including Linear Regression, ARIMA, and SARIMAX models.

The study focuses on long-term macroeconomic forecasting by incorporating exogenous economic indicators such as inflation, population, and trade dynamics to improve forecasting realism.

---

## 🎯 Objectives
- Forecast Iran’s GDP for the next 10 years (2024–2033)
- Compare classical ML and time-series models
- Build a statistically validated forecasting pipeline
- Incorporate macroeconomic exogenous variables for realistic predictions

---

## 🧠 Methodology Pipeline
The project follows a structured and research-oriented workflow:

1️⃣ Data Preprocessing  
2️⃣ Exploratory Data Analysis (EDA)  
3️⃣ Linear Regression Baseline (Machine Learning Approach)  
4️⃣ Feature Engineering (Log Transformation & Lag Features)  
5️⃣ Stationarity Testing (ADF Test)  
6️⃣ ARIMA Baseline Model (Univariate Time-Series)  
7️⃣ Model Upgrade to SARIMAX (Multivariate Forecasting) ⭐  
8️⃣ 10-Year GDP Forecast (2024–2033)  
9️⃣ Residual Diagnostics & Model Validation  
🔟 Final Visualization & Economic Interpretation  

---

## 📈 Models Implemented
### 🔹 Linear Regression (Baseline ML Model)
- Used macroeconomic indicators as predictors
- Provided initial benchmark performance
- Highlighted limitations for time-dependent data

### 🔹 ARIMA (Time-Series Baseline)
- Order selected based on ADF, ACF, and PACF analysis
- Captured GDP temporal dynamics
- Served as statistical benchmark model

### 🔹 SARIMAX (Final Advanced Model) ⭐
Final model used:
> **SARIMAX(1,1,0)** with exogenous macroeconomic variables

#### Exogenous Variables Included:
- Inflation Rate (%)
- Population Total
- Trade (% of GDP)

Why SARIMAX?
> GDP is influenced by multiple macroeconomic factors, not just past values.  
> SARIMAX provides superior economic realism compared to standalone ARIMA.

---

## 🧪 Statistical Validation
- Augmented Dickey-Fuller (ADF) Test for stationarity
- Differencing applied to remove trend (d = 1)
- Residual diagnostics performed
- Ljung-Box test confirms white-noise residuals (well-fitted model)

---

## 📊 Key Features
✔ Log transformation for variance stabilization  
✔ Lag feature engineering (GDP memory effect)  
✔ Multivariate time-series modeling  
✔ Residual diagnostics and white-noise validation  
✔ Long-horizon economic forecasting (10 years)  

---

## 📉 Results & Insights
- SARIMAX outperformed ARIMA in economic realism
- Residuals behaved close to white noise (validated model assumptions)
- Forecast shows steady GDP recovery trend post-2023
- Demonstrates strong macroeconomic dependency in GDP forecasting

---

## 📅 Forecast Output
- Forecast Horizon: **10 Years (2024–2033)**
- Output: Real GDP Forecast (USD)
- Visualization: Historical vs Forecast GDP trend

---

## 🛠 Tech Stack
- Python
- Pandas & NumPy (Data Processing)
- Matplotlib & Seaborn (Visualization)
- Statsmodels (ARIMA, SARIMAX, ADF Test)
- Scikit-learn (Linear Regression)
- Jupyter Notebook

---

## 📂 Repository Structure

```
Economic-Time-Series-Forecasting-SARIMAX/
│
├── Multivariate_GDP_Forecasting_SARIMAX.ipynb # Main notebook
├── data.csv # Dataset
├── requirements.txt # Dependencies
└── README.md # Project documentation
```

---

## ▶️ How to Run the Project
1. Clone the repository:
```bash
git clone https://github.com/Hanah7511/Economic-Time-Series-Forecasting-SARIMAX.git
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. open the notebook:
```bash
jupyter notebook
```
4. Run all cells to reproduce the forecast results.

---

## 💼 Portfolio Relevance

This project demonstrates:

- Applied Time-Series Forecasting
- Econometric Modeling Skills
- Statistical Diagnostics & Validation
- End-to-End ML + Time-Series Pipeline
- Research-level forecasting methodology

Suitable for:

Data Science | AI/ML | Economic Analytics | Forecasting Roles

---

👩‍💻 Author

Hana Al Haris
AI/ML Student | Aspiring Data Scientist
Focus: Time-Series Forecasting • Machine Learning • Economic Analytics
