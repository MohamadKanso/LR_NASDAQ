# NASDAQ Linear Regression Trading Model

This repository contains a Linear Regression (LR) trading model for predicting NASDAQ stock movements and executing a strategy aimed at outperforming the market. Key performance metrics include annual return, Sharpe ratio, maximum drawdown, and volatility.

## Features

- **Data Preparation**: Processes NASDAQ historical data, including handling missing values and normalisation.
- **Linear Regression Model**: Utilises LR to forecast price movements with a feature set optimised for trend detection.
- **Backtesting**: Evaluates the model’s performance against the market using cumulative returns.
- **Performance Metrics**: Includes total return, annual return, volatility, Sharpe ratio, and max drawdown.

## Results

The model achieves an annual return of 18.86% with a Sharpe ratio of 0.92. However, it shows a significant drawdown of 186.77%, highlighting sensitivity to volatile periods.


## Performance Metrics

- **Total Return**: Overall return from the strategy.
- **Annual Return**: Average return per year.
- **Volatility**: Annualised standard deviation of returns.
- **Sharpe Ratio**: Risk-adjusted return measure.
- **Max Drawdown**: Largest observed loss from peak to trough.

## Limitations & Future Work

- High max drawdown indicates potential over-sensitivity to market volatility.
- Consider exploring non-linear models such as **Decision Trees**, **Random Forests**, or **Support Vector Machines** (SVM), which often handle complex market patterns more effectively. Neural network models, like **LSTM** (Long Short-Term Memory), may also offer improved stability and accuracy over time by capturing non-linear dependencies in financial data.

