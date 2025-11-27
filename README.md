# Time Series Analysis of Palantir Stock Prices

## Project Overview

This project presents a complete analysis and forecasting study of a univariate time series based on daily stock prices of Palantir Technologies Inc. (PLTR). The analysis was conducted in RStudio. The goal was to explore the structure of the time series, evaluate statistical properties, and build predictive models suitable for short-term forecasting.

## Objective

The main objective of the study is to examine the behavior of Palantir stock prices over time, understand the underlying patterns such as trends and seasonality, and apply appropriate time series models to generate forecasts and evaluate their quality.

## Data Source and Description

The dataset consists of daily closing prices of Palantir Technologies Inc. The data was obtained from a publicly accessible financial source (Yahoo Finance).
The time series reflects the evolution of market value for PLTR, characterized by typical stock market properties such as non-stationarity, volatility clustering, and irregular fluctuations influenced by market events.

## Visualization

A graphical representation of the stock price series is included in the report, illustrating long-term movements, trend components, and variability. Additional plots such as ACF, PACF, seasonal diagnostics, decomposition charts, and residual diagnostics are used throughout the analysis.

## Methodology

To address the forecasting goal, several methods commonly used in time series analysis were applied, including:

* Stationarity assessment with the Augmented Dickey–Fuller test
* Autocorrelation and partial autocorrelation analysis
* ARIMA model selection and fitting
* Holt–Winters exponential smoothing
* Diagnostic evaluation and comparison of model performance

The methods were selected to reflect both statistical properties of the dataset and practical forecasting needs.

## Interpretation of Results

The analysis includes detailed interpretation of the fitted models, their parameters, statistical significance, and diagnostic checks such as residual analysis and Ljung–Box tests. Forecasts are presented together with confidence intervals, allowing assessment of the model’s usefulness in predicting future stock movements.

## Model Evaluation

The quality of forecasts is evaluated using standard statistical criteria and error measures. A comparison between ARIMA and Holt–Winters results highlights differences in predictive performance and suitability for this specific time series.


## Summary and Conclusions

The study concludes with a summary of the key findings, evaluation of model effectiveness, and insights into the forecasting behavior of Palantir stock prices. The analysis demonstrates the applicability of classical time series methods in financial forecasting and highlights both strengths and limitations of the explored models.

## Project Contents

This repository contains:

* The complete analysis in **R Markdown** (`.Rmd`)
* Exported versions of the report in **PDF** and **HTML**

## Author

Filip Misiak, Adam Kowalczyk

## License

This project is licensed under the MIT License.
