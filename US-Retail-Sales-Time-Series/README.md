# Project Title: Time Series Modeling of US Retail Sales

## Overview
This project involves analyzing and modeling the monthly retail sales data in the US using time series analysis techniques. The objective is to build a predictive model to forecast future sales and evaluate its accuracy using real-world retail data.

## Dataset Description
The dataset includes monthly retail sales data for the US from January 1992 to June 2021.

- **Source**: US Retail Sales Dataset (`us_retail_sales.csv`)

## Methodology
1. **Data Visualization**: Plotted the time series data to observe trends and seasonal patterns.
2. **Data Splitting**: Split the data into training (1992-2020) and testing (2020-2021) sets.
3. **Model Building**: Built an ARIMA model to predict future retail sales.
4. **Model Evaluation**: Calculated the RMSE to measure prediction accuracy.

## Key Findings
The model captured general trends but had high RMSE due to significant deviations in some periods, particularly during the pandemic.

## Tools & Technologies Used
- Python (Jupyter Notebooks)
- Libraries: pandas, statsmodels, matplotlib

## Instructions for Use
1. Clone the repository.
2. Run the Jupyter Notebooks under the `US Retail Sales Time Series` folder.
