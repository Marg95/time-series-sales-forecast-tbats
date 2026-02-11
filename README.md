# Time Series Sales Forecast with TBATS

Time series analysis and sales forecasting using TBATS models with multiple seasonalities in R.  
This project develops a complete forecasting workflow including data exploration, statistical testing, model validation, and interactive visualization.


---

## Project Overview

This repository presents a full end-to-end workflow for **daily sales forecasting** over a five-year period.

The objective is to model complex seasonal sales behavior using the **TBATS model**, particularly suitable for time series with multiple seasonal patterns (e.g., weekly and annual seasonality).

The project integrates statistical validation, model comparison, and performance evaluation to generate reliable future sales predictions.

---

## Business Value

The developed methodology supports:

- Demand forecasting for inventory planning  
- Identification of seasonal sales patterns  
- Short- and medium-term sales projections  
- Model performance comparison for decision support  
- Reduction of uncertainty in commercial planning  

---

## Objectives

- Explore and visualize historical sales data  
- Identify temporal patterns and seasonality  
- Test stationarity using the Augmented Dickey-Fuller test  
- Train TBATS forecasting models with multiple seasonalities  
- Generate future sales predictions with confidence intervals  
- Evaluate model performance using error metrics  
- Compare different seasonal configurations  
- Develop an interactive Shiny application for visualization  

---

## Dataset

- **Source**: `train.csv`  
- **Period**: 2013-01-01 to 2017-12-31  
- **Frequency**: Daily  
- **Context**: Simulated retail sales data (Patagonia “Nano Puff Jacket”)  
- **Main variables**:
  - `date`
  - `sales`
  - `store`
  - `item`

The analysis focuses on a selected product and the store with the highest sales volume to ensure consistent demand behavior modeling.

---

## Methodology

1. Exploratory Data Analysis (EDA) and visualization  
2. Time series decomposition  
3. Stationarity testing (ADF test)  
4. Train / test split  
5. Time series object construction  
6. TBATS model fitting with multiple seasonalities  
7. Forecast generation with confidence intervals  
8. Model evaluation (MAE, MSE, RMSE, MAPE)  
9. Seasonal configuration comparison  

---

## Technologies and Tools

- R  
- RMarkdown  
- Shiny  
- `forecast`  
- `tseries`  
- `TSA`  
- `ggplot2`  
- `dplyr`  
- `readr`  
- `plotly`  

All required packages are installed automatically if not available.

---

## Results

The workflow produces:

- Forecast visualizations with confidence intervals  
- Error metrics for model validation  
- Comparative analysis of seasonal configurations  
- Interactive dashboard for dynamic exploration  

---

## How to Run

1. Clone the repository  
2. Ensure `train.csv` is located in the root directory  
3. Open and run `series_temporales.Rmd`  
4. Render to HTML or launch as a Shiny application  

---

## Skills Demonstrated

- Time series analysis  
- Forecasting with multiple seasonalities  
- Statistical testing and validation  
- Model evaluation and performance metrics  
- Interactive dashboard development  
- Business-oriented data interpretation  

---

## Author

Maria Marcela Gomez
