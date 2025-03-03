This repository contains a Jupyter Notebook developed as part of the TMDL (Turing Machine & Deep Learning) course at Erasmus University during the 2022/2023 academic year. The project was completed in a group of 3 students, focusing on analyzing New York Stock Exchange (NYSE) trading data.

## Project Description

This research explores the relationship between monthly trade volume of the NYSE and financial macroeconomic factors, including:
- Inflation
- GDP growth
- Treasury yields
- S&P 500 closing price and moving average EPS
- Lagged monthly trade volume

## Data Sources

The data was sourced from:
- CBOE (Chicago Board Options Exchange)
- U.S. Bureau of Labor Statistics
- S&P Global Market Intelligence
- Compustat Capital IQ

The dataset covers the period from 2011 to April 2023, with all data aggregated monthly.

## Methodology

**Data Preprocessing and Feature Engineering**
**Exploratory Data Analysis:** Visualizing trends, checking stationarity, and analyzing correlations between financial indicators and market activity.
**Clustering for Market Patterns**: Identifying typical trading months to enhance model insights.
**Supervised Learning Models:**
   * **Linear Regression** as a baseline.
   * **Recurrent Neural Networks (RNNs)** for sequential market behavior.
   * **Long Short-Term Memory (LSTM) networks** for improved time-series forecasting.
  **Model Evaluation & Optimization**
