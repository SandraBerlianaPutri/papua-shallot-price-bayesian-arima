# Bayesian ARIMA for Shallot Price Forecasting in Papua

## About
This project applies Bayesian ARIMA modeling to forecast daily shallot prices in Papua, Indonesia. The workflow covers data preprocessing, stationarity assessment, model selection, Bayesian parameter estimation, residual diagnostics, and forecast evaluation.

## Project Analysis
- [View Full Analysis on RPubs](https://rpubs.com/sandraberlianaputri/bayesian-arima-shallot-prices)

## Dataset
- **Study period:** December 15, 2024 – May 8, 2025
- **Observations:** 145 daily records
- **Variables:**
  - `Tanggal`: Observation date
  - `Bawang.Merah`: Daily shallot price
- **Missing values:** 12 observations in the price variable, handled using linear interpolation
- **Data split:** 116 observations for training and 29 for testing

## Methods
- **Exploratory Data Analysis:** Summary statistics and daily price visualization.
- **Data Preprocessing:** Linear interpolation for missing price observations.
- **Stationarity Assessment:** Augmented Dickey–Fuller test, ACF, and Box–Cox transformation exploration.
- **Model Selection:** Automated ARIMA order search using `bayesforecast`.
- **Bayesian Estimation:** Parameter estimation using Markov Chain Monte Carlo (MCMC).
- **Residual Diagnostics:** Normality, autocorrelation, variance-related checks, and residual mean assessment.
- **Forecast Evaluation:** Comparison with held-out observations using RMSE, MAE, and MAPE.

## Author
**Sandra Berliana Putri** - Statistics and Data Science graduate from IPB University.
