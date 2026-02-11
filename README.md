# Time Series Sales Forecast with TBATS

Time series analysis and sales forecasting using TBATS models with multiple seasonalities in R.  
The project includes data exploration, stationarity testing, model evaluation, forecasting, and interactive visualizations.

---

## Project Overview

This repository contains a complete workflow for **sales time series analysis**, applied to daily sales data over five years.  
The main objective is to **model and forecast future sales** using the **TBATS** model, which is well-suited for series with multiple seasonal patterns.

---

## Objectives

- Explore and visualize historical sales data  
- Analyze temporal structure and seasonality  
- Test stationarity using the Dickey-Fuller test  
- Train TBATS forecasting models  
- Generate future sales predictions with confidence intervals  
- Evaluate model performance using error metrics  
- Compare different seasonal configurations  
- Build an interactive Shiny application  

---

## Dataset

- **Source**: `train.csv`  
- **Period**: 2013-01-01 to 2017-12-31  
- **Frequency**: Daily  
- **Context**: Simulated sales data for Patagonia “Nano Puff Jacket” products  
- **Main variables**:
  - `date`
  - `sales`
  - `store`
  - `item`

The analysis focuses on a randomly selected product and the store with the highest sales volume.

---

## Methodology

1. Exploratory data analysis and visualization  
2. Stationarity testing (ADF test)  
3. Train / test split  
4. Time series construction  
5. TBATS model fitting with multiple seasonalities  
6. Forecasting and confidence intervals  
7. Model evaluation (MAE, MSE, MAPE, RMSE)  
8. Seasonal configuration comparison  

---

##  Tools

- `forecast`
- `TSA`
- `tseries`
- `ggplot2`
- `dplyr`
- `readr`
- `plotly`
- `shiny`

All required packages are installed automatically if not available.

---

##  How to Run

1. Clone the repository  
2. Ensure `train.csv` is in the root directory  
3. Open and run `series_temporales.Rmd`  
4. Render to HTML or run as a Shiny application  

---

##  Technologies

- R  
- RMarkdown  
- Shiny  
- Time Series Analysis  
- Data Science  
