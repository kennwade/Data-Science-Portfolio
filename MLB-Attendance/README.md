# Project Title: Using Data to Improve MLB Attendance

## Overview
This project analyzes attendance data for the Los Angeles Dodgers Major League Baseball (MLB) team. The goal is to identify key factors influencing attendance and make recommendations to improve game attendance.

## Dataset Description
The dataset contains information on Los Angeles Dodgers games, including factors such as weather, promotions, opponents, and attendance numbers.

- **Source**: Dodgers attendance data

## Methodology
1. **Data Cleaning**: Missing values were handled, and new features (e.g., weekend indicator) were created.
2. **Exploratory Data Analysis (EDA)**: Analyzed relationships between attendance and various factors using line plots, box plots, and correlation matrices.
3. **Modeling**: A regression model was built to predict attendance based on weather, promotions, and other features.
4. **Evaluation**: The model's performance was evaluated using Mean Squared Error and R-squared scores.

## Key Findings
- Promotions like fireworks and bobbleheads significantly impact attendance.
- Weekends generally see higher attendance.
- Weather conditions have a minor effect on attendance.

## Files
- [`mlb_attendance_analysis.ipynb`](./mlb_attendance_analysis.ipynb): Jupyter Notebook containing the full analysis and modeling code.

## Tools & Technologies Used
- Python (Jupyter Notebooks)
- Libraries: pandas, matplotlib, seaborn, scikit-learn

## Future Work
- Analyze the impact of ticket prices and seating arrangements on attendance.
- Incorporate additional data, such as real-time weather details, for enhanced predictions.
- Explore promotional strategies beyond fireworks and bobbleheads.

## Instructions for Use
1. Clone the repository.
2. Navigate to the `MLB Attendance` folder.
3. Open and run the Jupyter Notebook `mlb_attendance_analysis.ipynb`.
