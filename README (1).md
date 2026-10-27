# BDA400 Assignment 6 — Technical Analysis Using R, Visualization Stage

**Student:** Kartik Bishnoi  
**Course:** BDA400 / Data Science Tools and Techniques

## Project description
An interactive R Shiny dashboard that retrieves historical stock data from Yahoo Finance, visualizes price movement, calculates moving averages, RSI and MACD, and annotates moving-average crossover signals.

## Files
- `app.R` — complete Shiny application source code.
- `Kartik_Bishnoi_CA_BDA400_A06.pdf` — project report and submission cover page.

## Requirements
R and RStudio, internet access, and the R packages `shiny`, `ggplot2`, `quantmod`, `TTR`, and `dplyr`.

Install missing packages in the R console:
```r
install.packages(c("shiny", "ggplot2", "quantmod", "TTR", "dplyr"))
```

## Run
1. Open `app.R` in RStudio.
2. Install any missing packages.
3. Click **Run App** or run `shiny::runApp()` from the folder containing `app.R`.
4. Enter a Yahoo Finance symbol such as `AAPL`, choose dates, time frame, chart type, and indicators.

## Trading rule
A Buy signal is shown when the 20-period simple moving average crosses above the 50-period average. A Sell signal is shown when it crosses below. Other observations are labelled Hold internally; the table lists only crossover events.

## Notes
Stock data depends on Yahoo Finance availability and internet connectivity. Signals are educational examples and are not investment advice. The app should be run and checked in the student's own R environment before submission.

## Repository
Paste your public GitHub repository URL here before submitting: **[Add repository URL]**
