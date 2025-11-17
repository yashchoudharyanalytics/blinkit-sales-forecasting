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


5. **Power BI Dashboard**
   - Built a dashboard to show:
     - Historical sales trend
     - Forecasted sales
     - Category / region breakdown 
     - Key KPIs and filters

Key Learnings & Insights

Identified seasonality and trend patterns in Blinkit sales.

Built ARIMA/SARIMA models to predict future demand.

Demonstrated how Python forecasting can integrate with Power BI for business reporting.

Showcased an end-to-end analytics workflow from raw data → model → dashboard.

---

## 📂 Repository Structure

```text
blinkit-sales-forecasting/
├── data/                     # Dataset (or sample)
├── notebooks/                # EDA + forecasting notebooks
├── powerbi/                  # Power BI report file
├── screenshots/              # Plots & dashboard images
└── README.md                 # Project documentation

