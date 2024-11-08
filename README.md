# NASDAQ Linear Regression Trading Model

This contains a Linear Regression trading model for predicting NASDAQ  movements and executing a strategy aimed at outperforming the market. Key performance metrics include annual return, Sharpe ratio, maximum drawdown, and volatility.

## Libraries Used

This project uses the following libraries:

<p align="center">
  <img src="https://pandas.pydata.org/static/img/pandas_white.svg" alt="Pandas" height="50">
  <img src="https://numpy.org/doc/stable/_static/numpylogo.svg" alt="NumPy" height="50">
  <img src="https://matplotlib.org/_static/logo2_compressed.svg" alt="Matplotlib" height="50">
  <img src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" alt="Scikit-learn" height="50">
  <img src="https://seaborn.pydata.org/_images/logo-wide-lightbg.svg" alt="Seaborn" height="50">
</p>



## Features

- **Data Preparation**: Processes NASDAQ historical data, including handling missing values and normalisation.
- **Linear Regression Model**: Utilises LR to forecast price movements with a feature set optimised for trend detection.
- **Backtesting**: Evaluates the model’s performance against the market using cumulative returns.
- **Performance Metrics**: Includes total return, annual return, volatility, Sharpe ratio, and max drawdown.

## Results

The model achieves an annual return of 18.86% with a Sharpe ratio of 0.92. __However, it shows a significant drawdown of 186.77%__, highlighting sensitivity to volatile periods.


## Performance Metrics

- **Total Return**: Overall return from the strategy.
- **Annual Return**: Average return per year.
- **Volatility**: Annualised standard deviation of returns.
- **Sharpe Ratio**: Risk-adjusted return measure.
- **Max Drawdown**: Largest observed loss from peak to trough.

## Limitations & Future Work

- High max drawdown indicates potential over-sensitivity to market volatility.
- Consider exploring non-linear models such as **Decision Trees**, **Random Forests**, or **Support Vector Machines** (SVM), which often handle complex market patterns more effectively. Neural network models, like **LSTM** (Long Short-Term Memory), may also offer improved stability and accuracy over time by capturing non-linear dependencies in financial data.

