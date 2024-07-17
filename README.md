# Horse-Racing-Trading
![Horse Racing](Horse%20Racing/Horse%20Racing.jpg)

The plot shows the portfolio value over time when applying the Bond Rotation strategy.

This repository provides Python code for analyzing financial time-series data and developing a trading strategy based on statistical analysis and indicators.

Key Features:
Data Analysis and Visualization:

Utilizes pandas for data manipulation and matplotlib for visualization.
Resamples data into different time intervals (5 min, 10 min, 15 min, 30 min) to analyze price movements over time.
Statistical Analysis:

Calculates mean, standard deviation, median, quantiles, and interquartile range (IQR) for different time intervals to understand price variations and volatility.
Strategy Development:

Implements a delta-based trading strategy using price differentials and thresholds.
Evaluates strategy performance using train-test splits and performance metrics (e.g., accuracy) to assess predictive power.
Technical Indicators:

Utilizes Relative Strength Index (RSI) to gauge overbought and oversold conditions in different time frames.
Tasks Covered:
Task 4: Quantile plot, first and third quantile calculation, and IQR analysis for 10-minute data.
Task 5: Comparison of standard deviation across different time intervals (5 min, 10 min, 15 min, 30 min) and analysis of price changes using deltas.
Task 6: Calculation of expected price drop after reaching previous high for multiple range periods (5, 10, 15, 20).
Task 7: Use of RSI to analyze price behavior across various time frames.
Task 8: Development of a delta-based trading strategy, train-test split, and evaluation of strategy performance metrics.
Task 9: Implementation of performance metrics to assess strategy effectiveness (e.g., accuracy, precision, recall).
Usage:
Clone the repository and run the provided Python scripts to analyze your financial data.
Modify parameters and thresholds in the strategy function (delta_strategy) to optimize trading decisions based on your dataset and trading preferences.
Conclusion:
This repository serves as a comprehensive toolkit for financial data analysis and strategy development, empowering users to make informed trading decisions through statistical insights and technical indicators.
