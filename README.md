# Euro to USD Trend Analysis & Forecasting

This project performs a comprehensive analysis and forecasting of the Euro to US Dollar exchange rate using Python. It includes data cleaning, exploratory data analysis, time series forecasting, and volatility analysis.

## Project Structure

- `euro-us-analysis.py` — The main Python script that executes all phases of the analysis.
- `EuroCR.csv` — Dataset containing historical Euro exchange rates against various currencies.

## Features

1. **Data Cleaning & Preparation**
   - Parses the date column and sets it as the DataFrame index.
   - Cleans column names.
   - Selects relevant currencies (USD, GBP, INR).
   - Handles missing values by forward-filling.

2. **Exploratory Data Analysis (EDA)**
   - Line plot of EUR to USD trends over time.
   - Highlights significant events like the 2008 Financial Crisis and COVID-19 pandemic.
   - Heatmap showing correlation between selected currencies.

3. **Time Series Forecasting**
   - Splits data into training and testing sets.
   - Fits a SARIMAX model to training data.
   - Forecasts the EUR to USD rate for the next 90 days.
   - Plots forecasted vs actual data.
   - Evaluates model performance using RMSE and MAE metrics.

4. **Volatility Analysis**
   - Calculates daily percentage returns of the exchange rate.
   - Computes and plots 30-day rolling standard deviation to analyze volatility.

## Prerequisites

- Python 3.x
- Required Python libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - statsmodels

Install dependencies with:

pip install pandas numpy matplotlib seaborn statsmodels

text

## How to Run

1. Ensure `EuroCR.csv` is in the same directory as `euro-us-analysis.py`.
2. Open a terminal or command prompt.
3. Navigate to the project directory.
4. Run the script:

python euro-us-analysis.py

text

The script will output progress messages and display relevant plots during its execution.

## Notes

- The analysis highlights macroeconomic impacts on the EUR/USD exchange rate.
- Forecasting helps predict near-term movements based on historical trends.
- Volatility insights reveal periods of market stability and uncertainty.
