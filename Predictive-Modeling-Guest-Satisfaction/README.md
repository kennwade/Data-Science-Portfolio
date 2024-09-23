# Project Title: Predictive Modeling of Guest Satisfaction in the Hospitality Industry

## Overview
This project aims to develop a predictive model for tourism data, focusing on metrics like total domestic trips, overnight visitors, and same-day visitors. The goal is to provide insights to improve resource allocation and visitor experience in the tourism industry.

## Dataset Description
The dataset is sourced from Kaggle and contains tourism metrics, including domestic trips, overnight visitors, and nights spent in accommodation across multiple countries from 2008 to 2021.

- **Source**: Kaggle (Tourism - OECD dataset)

## Methodology
1. **Data Cleaning**: The dataset was cleaned by handling missing values, imputing with medians, and removing outliers.
2. **Exploratory Data Analysis (EDA)**: A correlation heatmap was generated to examine the relationships between tourism metrics over time.
3. **Modeling**: Linear regression was initially used, but a Random Forest Regressor was selected for its better performance. 
4. **Evaluation**: The model was evaluated using Mean Squared Error (MSE) and visualized using a scatter plot comparing predicted vs actual values.

## Key Findings
The Random Forest model performed better after handling outliers, accurately predicting tourism trends. This model can help in strategic decision-making for tourism-dependent regions.

## Tools & Technologies Used
- Python (Jupyter Notebooks)
- Libraries: pandas, scikit-learn, matplotlib

## Instructions for Use
1. Clone the repository.
2. Run the Jupyter Notebooks under the `Predictive Modeling` folder.
