# 📈 Stock Price Forecasting with ML & DL

A machine learning and deep learning project to forecast Apple Inc. (AAPL) stock prices using historical data from Yahoo Finance. This project compares multiple models including Linear Regression, LSTM, Random Forest, and XGBoost — with performance benchmarking, prediction intervals, and visualization dashboards.

---

## 📌 Features

- 📉 Predicts next-day closing price using:
  - Linear Regression
  - LSTM (Recurrent Neural Network)
  - Random Forest
  - XGBoost
- 📊 Visual comparison of actual vs predicted prices
- 🧪 Evaluation metrics: RMSE, MAE, R², MAPE
- 📦 Interactive plots with confidence intervals
- 🔥 Correlation heatmap, training/validation loss curves
- 📋 Model comparison table with metrics and intervals

---

## 🛠 Tech Stack

| Component          | Description                                 |
|--------------------|---------------------------------------------|
| **Languages**      | Python 3                                     |
| **ML Libraries**   | scikit-learn, TensorFlow (Keras), XGBoost    |
| **Data Source**    | Yahoo Finance (via `yfinance`)              |
| **Visualization**  | Matplotlib, Seaborn                         |
| **Data Handling**  | NumPy, Pandas                               |

---

## 📥 Dataset

Pulled directly using:
```python
import yfinance as yf
data = yf.download("AAPL", start="2015-01-01", end="2025-04-24")
