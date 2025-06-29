# -Return-Prediction-and-Portfolio-Risk-Analysis
# Return Prediction and Portfolio Risk Analysis

This project analyzes the monthly returns of **Hang Seng Bank (HSB)** and **AIA** using historical adjusted closing prices. It includes return computation, correlation analysis, plotting, and portfolio risk evaluation.

##  Features

The project consists of the following key parts:

### Part 1: Expected Return & Standard Deviation
- Computes monthly return for HSB and AIA.
- Calculates expected return and standard deviation for each stock.
- Displays results in a formatted DataFrame.

### Part 2: Correlation & Visualization
- Plots monthly returns of HSB and AIA from 2016 to 2021.
- Calculates and interprets Pearson correlation between the two stocks.
- Uses `matplotlib` for clear, time-series visualization.

### Part 3: Portfolio Variance
- Simulates a portfolio composed of 65% HSB and 35% AIA.
- Computes portfolio variance and standard deviation.
- Considers correlation between assets.

##  Files

- `Return_Prediction.py`: The main Python script that executes all three analysis stages.
- `data.csv`: Input data file containing historical stock prices.
