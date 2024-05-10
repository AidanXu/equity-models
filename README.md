# Volatility Forecasting in the S&P 500 (SPY)

## Overview

This project demonstrates the use of statistical models to forecast volatility in the S&P 500 (SPY) by analyzing historical data from 2010 to 2019. We employ several techniques including GARCH, exponential moving averages, and Poisson jump diffusions to model and predict market volatility. Our models are built and evaluated using historical closing prices, log returns, and volume data.

## Methodology

### 1. Data Collection and Preprocessing
* Historical SPY data was obtained covering the period between January 1, 2010, and December 31, 2019.
* The dataset includes daily open, high, low, close, adjusted close, and trading volume.
* Log returns were calculated and then scaled for modeling.

### 2. Modeling Techniques
* GARCH (Generalized Autoregressive Conditional Heteroskedasticity): The GARCH model is used to forecast volatility by capturing volatility clustering patterns in historical data.
* Exponential Moving Average (EMA): EMA is used to smooth historical price data, which helps identify trends and fluctuations over different time horizons.
* Poisson Jump Diffusions: This model integrates sudden jumps in prices with continuous price movements, accounting for sporadic high-impact market events.

### 3. Model Implementation and Evaluation
* Training Period: Models were trained on data from 2010 to 2019.
* Testing Period: Forecasts were evaluated against real market data for 2020 and onward.
* Metrics: Forecasted volatility is compared with realized volatility using various error metrics.


