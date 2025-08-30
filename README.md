# Analyze Stock Portfolio for Risks and Returns

![trader](trader.jpg)

## Project Description
This project explores Modern Portfolio Theory (MPT) by analyzing historical stock price data for the FAANG companies (Meta/Facebook, Apple, Amazon, Netflix, and Google) from 2020 to 2023. The goal is to understand how to balance risk and return in a stock portfolio and identify optimal asset allocations using mean-variance optimization.

## Data
The analysis uses the `faang_stocks.csv` dataset, which contains the closing prices for each of the FAANG stocks on each trading day during the specified period.

## Analysis and Findings
The notebook demonstrates the following:
* Calculation of daily and annualized stock returns.
* Evaluation of an equally-weighted portfolio's performance (return and Sharpe Ratio).
* Identification of the minimum volatility portfolio using mean-variance optimization.
* Identification of the portfolio that maximizes the Sharpe Ratio using mean-variance optimization.
* Visualization of stock prices over time.
The results highlight the difference in risk and return profiles between a simple equally-weighted portfolio and portfolios optimized for minimum volatility or maximum Sharpe Ratio.

## Key Concepts
* Arithmetic Returns
* Portfolio Returns
* Sharpe Ratio
* Standard Deviation (Volatility)
* Covariance Matrix
* Mean-Variance Optimization
* Efficient Frontier

## How to Run the Notebook
* Clone the repository.
* Ensure you have Python installed with the necessary libraries (pandas, numpy, matplotlib, pypfopt). You can install them using `pip`
