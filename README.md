# Crowding-Out Effect 

## Overview

This project analyzes the **crowding-out effect** using real-world U.S. data. It examines the relationship between **government spending**, **real interest rates**, and **private-sector investment** using a **Vector Autoregression (VAR) Model** in STATA. The analysis includes causality testing, forecasting, and impulse response functions to explore how government spending impacts private investment.

## Key Features

- **Data**: U.S. time-series data on government spending, real interest rates, and private-sector investment.
- **VAR Model**: Analyzes the interactions between the variables over different lags.
- **Granger Causality**: Identifies causal relationships between the variables.
- **Forecasting**: One-step and twelve-step forecasts for short and long-term trends.
- **Impulse Response**: Analyzes the effect of shocks (e.g., increase in government spending) on the variables.
- **Variance Decomposition**: Measures the contribution of each variable to forecast uncertainty.

## Methodology

1. **Data Transformation**: Ensures stationarity using STATA transformations.
2. **VAR Model**: Constructs a VAR model to analyze the relationships, with optimal lag determined by information criteria.
3. **Granger Causality**: Tests for bidirectional causality between variables.
4. **Forecasting**: Generates short and long-term forecasts using the VAR model.
5. **Impulse Response**: Analyzes responses to shocks, validating the crowding-out effect.
6. **Variance Decomposition**: Determines the contributions of each variable to forecast error variance.

## Results and Findings

- **Crowding-Out Effect**: The model shows that increased government spending raises interest rates, which negatively affects private-sector investment, confirming the crowding-out effect.
- **Forecasting Performance**: The model captures long-term trends but is less accurate in short-term forecasting.
- **Model Improvement**: Future enhancements could include a variable for **interest rate expectations** to improve investment predictions.
