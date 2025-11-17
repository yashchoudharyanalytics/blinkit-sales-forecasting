# 🛒 Blinkit Sales Forecasting – Python + Power BI

This project focuses on **time-series forecasting** for Blinkit sales using Python and ARIMA/SARIMA models, with final results visualised in a Power BI dashboard.

The goal is to demonstrate how forecasting + BI can be combined to support **demand planning, inventory, and business decisions**.

---

## 🔧 Tech Stack

- **Python:** Pandas, NumPy, Statsmodels, Matplotlib
- **Forecasting:** ARIMA / SARIMA
- **Visualisation:** Power BI
- **Other:** Time-series analysis, EDA, KPI design

---

## 📊 Project Workflow

1. **Data Understanding & Cleaning**
   - Handled missing values, outliers, and date formatting
   - Created time-series index and aggregated sales by time (daily/weekly/monthly)

2. **Exploratory Data Analysis (EDA)**
   - Trend, seasonality, and patterns in Blinkit sales
   - Visualised sales over time, peak periods, and anomalies

3. **Model Building – ARIMA / SARIMA**
   - Checked stationarity (ADF test, differencing)
   - Selected model parameters (p, d, q) / (P, D, Q, s)
   - Trained forecasting model and evaluated performance

4. **Forecasting & Evaluation**
   - Generated future sales forecasts
   - Compared forecast vs actual on test set
   - Used metrics like MAE / RMSE (if available)

5. **Power BI Dashboard**
   - Built a dashboard to show:
     - Historical sales trend
     - Forecasted sales
     - Category / region breakdown (if available)
     - Key KPIs and filters

---

## 📂 Repository Structure

```text
blinkit-sales-forecasting/
├── data/                     # Dataset (or sample)
├── notebooks/                # EDA + forecasting notebooks
├── powerbi/                  # Power BI report file
├── screenshots/              # Plots & dashboard images
└── README.md                 # Project documentation
