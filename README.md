# APS1052Project---Bitcoin-Price-Prediction-with-Machine-Learning

This project extends Case Study 1 (Stock Price Prediction) from Chapter 5 of *Machine Learning and Data Science Blueprints for Finance* by Tatsat, applying supervised learning techniques to predict Bitcoin returns.

## Problem Setup
- **Target**: Bitcoin (BTC-USD) 5-day log returns
- **Features**: 
  - Technical indicators from OHLCV
  - Macroeconomic indices (S&P500, Dow Jones, VIX)
  - ETFs (SPY, GLD)
  - Company stocks (IBM, GOOGL, MSFT)
- **Period**: 2010–2024

## Pipeline
- Data preprocessing: cleaning, normalization, feature creation
- Feature selection: mutual information & recursive elimination
- Model comparison: Linear Regression, Random Forest, XGBoost
- Evaluation:
  - Statistical metrics: RMSE, R²
  - Financial metrics: Sharpe Ratio, CAGR
- Bias control:
  - Bootstrapping for variance estimation
  - Monte Carlo permutation & White Reality Check

## Results
- XGBoost outperformed linear models in predictive accuracy
- Trading simulations showed positive equity growth
- Sharpe ratio improved with additional macro features
- White Reality Check confirmed robustness against overfitting

## Skills Demonstrated
- Machine learning pipeline automation (Scikit-learn, XGBoost)
- Financial feature engineering
- Risk-adjusted backtesting (Sharpe, CAGR)
- Bootstrapping & Monte Carlo methods to validate results
