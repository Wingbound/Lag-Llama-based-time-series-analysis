# Lag-Llama-based-time-series-analysis

# 🛒 Time Series Sales Forecasting

This project focuses on time series forecasting of daily sales data using state-of-the-art machine learning and statistical models, including [Lag-Llama](https://github.com/microsoft/forecasting/tree/main/lag-llama) and Auto-ARIMA.

## 📌 Project Objectives

- Prepare and clean raw sales data with missing dates.
- Interpolate missing values to obtain a continuous daily time series.
- Apply forecasting models to predict future sales.
- Evaluate model performance and visualize forecast results.

## 📂 Notebook

- `sales_new.ipynb`: Main Jupyter notebook containing the complete pipeline from data preprocessing to model evaluation and forecasting.

## ⚙️ Models Used

- **Lag-Llama**: A transformer-based model designed for accurate time series forecasting, leveraging lag-based representation.
- **Auto-ARIMA**: A statistical method that automates ARIMA model selection based on AIC/BIC scores.

## 🧰 Dependencies

This project uses the following key libraries:

- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn`
- `gluonts`
- `statsmodels`
- `tqdm`
