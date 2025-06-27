# 📊 Ethereum (ETH/USDT) Price Forecast Using ARIMA

This project applies **ARIMA (AutoRegressive Integrated Moving Average)** modeling to analyze and forecast the price of Ethereum (ETH) in USDT. The complete pipeline covers data collection, preprocessing, exploratory data analysis (EDA), stationarity testing, model selection, forecasting, and evaluation.

---

## 🔍 Project Objectives
- Collect and preprocess historical price data of Ethereum
- Perform EDA to uncover trends, volatility, and patterns
- Conduct stationarity testing and apply differencing
- Identify optimal ARIMA (p, d, q) parameters using ACF and PACF
- Forecast ETH prices for the next 30 days
- Evaluate model performance using RMSE and MAPE

---

## 🛠️ Tech Stack
- Python 3.x
- Pandas, NumPy
- Seaborn, Matplotlib
- Statsmodels (ARIMA modeling)
- Scikit-learn (evaluation metrics)
- yfinance (data sourcing)

---

## 📁 Repository Structure
```
├── data
│   └── ETH_USD_mock_data.csv         # Cleaned dataset
├── notebook
│   └── ETH_ARIMA_Forecast.ipynb     # Complete analysis and forecasting code
├── report
│   └── ETH_ARIMA_Final_Report.docx  # Final formatted report
├── visuals
│   └── charts/plots/screenshots     # All relevant visuals
└── README.md
```

---

## 📈 ARIMA Model Summary
- Selected Model: **ARIMA(0, 1, 1)**
- AIC: ~15832.42
- RMSE: ~79.61
- MAPE: **2.46%** (indicating high accuracy)

---

## 📉 Forecast Results
- Predicted Ethereum prices for 30 future days
- Visual forecast with confidence intervals
- Evaluation through residuals and actual vs. predicted plots

---

## 💡 How to Run
```bash
# Clone the repo
git clone https://github.com/yourusername/eth-arima-project.git
cd eth-arima-project

# Install required libraries
pip install -r requirements.txt

# Launch the notebook
jupyter notebook notebook/ETH_ARIMA_Forecast.ipynb
```

---

## 📚 References
- Krish Naik (YouTube): ARIMA Time Series Forecasting
- Statsmodels Documentation: ARIMA Models
- TowardsDataScience (Medium)
- yfinance Python Library

---

## 🎥 Video Demonstration
👉 [YouTube Walkthrough Link](https://youtu.be/v8U4TcjAc8M)

---

## 📎 Author Info
**Name:** Muhammad Abdullah  
**Phone:** 0300-0000000  
**InternID:** ABC123456

---
