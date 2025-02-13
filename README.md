# Financial Time Series Smoothing and Forecasting Tutorial

This tutorial demonstrates various smoothing and forecasting techniques commonly used in financial time series analysis, using R and real market data.

## Overview

Learn how to:
- Retrieve and preprocess financial time-series data
- Apply different smoothing techniques
- Create forecasts using ARIMA models
- Visualize results using ggplot2

## Prerequisites

### Required R Packages
```r
install.packages(c(
    "tidyverse",
    "tidyquant",
    "TTR",
    "signal",
    "dlm",
    "forecast",
    "tsfe"
))
```

### Knowledge Requirements
- Basic R programming
- Understanding of time series concepts
- Familiarity with financial markets

## Techniques Covered

### Smoothing Methods
1. Simple Moving Average (SMA)
2. Exponential Moving Average (EMA)
3. Weighted Moving Average (WMA)
4. Savitzky-Golay Filter
5. Lowess Smoothing
6. Kalman Filter

### Forecasting
- ARIMA modeling and forecasting

## Data

The tutorial uses Apple Inc. (AAPL) stock data from Yahoo Finance, covering the period 2020-2022.

## Usage

1. Clone this repository in Posit Cloud
2. Open `index.qmd`
3. Install required packages
4. Run the code chunks sequentially

## Exercises

The tutorial includes hands-on exercises to:
- Compare different smoothing methods
- Analyze reaction speeds to price changes
- Experiment with ARIMA forecasting parameters

## Contributing

Feel free to submit issues and enhancement requests!

## License
MIT

## Author
Barry Quinn

## Acknowledgments
This tutorial is part of the Advanced Financial Data Analytics course materials.
