# 📈 Sales Forecasting System

## Overview

This project develops an end-to-end Sales Forecasting System using Time Series Analysis, Statistical Forecasting, Deep Learning, and Business Intelligence.

The objective is to forecast future retail sales and compare multiple forecasting approaches:

- ARIMA
- Prophet
- LSTM Neural Network

The final model is selected using MAE and RMSE evaluation metrics.

---

## Dataset

**Dataset:** Walmart Weekly Sales Dataset

The dataset contains historical weekly retail sales data used for forecasting future demand.

---

## Technologies Used

### Data Analysis

- Python
- Pandas
- NumPy

### Visualization

- Matplotlib
- Seaborn
- Plotly

### Forecasting

- Statsmodels (ARIMA)
- Prophet
- TensorFlow / Keras (LSTM)

### Business Intelligence

- Power BI

---

# Project Workflow

1. Data Cleaning
2. Exploratory Data Analysis
3. Weekly Sales Aggregation
4. Stationarity Testing
5. ACF & PACF Analysis
6. ARIMA Forecasting
7. Prophet Forecasting
8. LSTM Forecasting
9. Model Evaluation
10. Dashboard Development

---

# Model Performance

| Model | MAE | RMSE |
|---------|---------:|---------:|
| ARIMA | 6,910,390 | 7,567,086 |
| Prophet | 6,901,726 | 8,335,014 |
| LSTM | 6,510,116 | 6,849,696 |

---

# Best Model

🏆 **LSTM Neural Network**

The LSTM model achieved the lowest MAE and RMSE values and was selected as the final forecasting model.

---

# Power BI Dashboard

## Final Dashboard

![Power BI Dashboard](dashboard/screenshots/powerbi_dashboard.png)

The dashboard contains:

- Total Sales KPI
- Weekly Sales Trend
- RMSE Comparison
- Best Model Summary
- Forecast Visualization

---

# Exploratory Data Analysis

## Weekly Sales Trend

![Weekly Sales Trend](dashboard/screenshots/weekly_sales_trend.png)

---

## STL Decomposition

![STL Decomposition](dashboard/screenshots/stl_decomposition.png)

---

# Stationarity Analysis

## ADF Test

![ADF Test](dashboard/screenshots/adf_test.png)

---

## ACF Plot

![ACF Plot](dashboard/screenshots/acf_plot.png)

---

## PACF Plot

![PACF Plot](dashboard/screenshots/pacf_plot.png)

---

# ARIMA Forecasting

## ARIMA Forecast

![ARIMA Forecast](dashboard/screenshots/arima_forecast.png)

---

## ARIMA Actual vs Predicted

![ARIMA Actual vs Predicted](dashboard/screenshots/arima_actual_vs_predicted.png)

---

# Prophet Forecasting

## Prophet Forecast

![Prophet Forecast](dashboard/screenshots/prophet_forecast.png)

---

## Prophet Components

![Prophet Components](dashboard/screenshots/prophet_components.png)

---

# LSTM Forecasting

## LSTM Training Loss Curve

![LSTM Loss Curve](dashboard/screenshots/lstm_loss_curve.png)

---

## LSTM Actual vs Predicted

![LSTM Forecast](dashboard/screenshots/lstm_actual_vs_predicted.png)

---

# Project Structure

```text
sales-forecasting-system/

├── data/
│
├── notebooks/
│   ├── 01_EDA.ipynb
│   └── 02_models.ipynb
│
├── models/
│   ├── arima_model.pkl
│   ├── prophet_model.pkl
│   └── lstm_model.keras
│
├── reports/
│   └── model_comparison.csv
│
├── dashboard/
│   ├── powerbi/
│   │   └── sales_forecasting_dashboard.pbix
│   │
│   └── screenshots/
│       ├── powerbi_dashboard.png
│       ├── acf_plot.png
│       ├── pacf_plot.png
│       ├── stl_decomposition.png
│       ├── adf_test.png
│       ├── weekly_sales_trend.png
│       ├── arima_forecast.png
│       ├── arima_actual_vs_predicted.png
│       ├── prophet_forecast.png
│       ├── prophet_components.png
│       ├── lstm_loss_curve.png
│       └── lstm_actual_vs_predicted.png
│
├── README.md
└── requirements.txt
```

---

# Repository Contents

### Notebooks

- 01_EDA.ipynb
- 02_models.ipynb

### Models

- ARIMA Model
- Prophet Model
- LSTM Model

### Reports

- Model Comparison CSV

### Dashboard

- Power BI Dashboard (.pbix)
- Dashboard Screenshots

---

# Author

**Harish J**

Sales Forecasting System using ARIMA, Prophet, LSTM, and Power BI.
