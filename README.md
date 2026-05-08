
# House Prices: Data Preprocessing (Assignment 1)

## Project Overview
This project demonstrates a complete data preprocessing pipeline for the "House Prices: Advanced Regression Techniques" dataset. The goal is to prepare the raw data for machine learning models.

## Key Steps Performed:
* **Memory Optimization**: Reduced memory usage by defining efficient data types for columns.
* **Data Cleaning**: Handled missing values (NaN) and removed significant outliers in `GrLivArea`.
* **Exploratory Data Analysis (EDA)**: Visualized feature correlations using Heatmaps and analyzed geographic price trends.
* **Feature Engineering**: 
    - Created a new feature `TotalSF` (Sum of TotalBsmtSF, 1stFlrSF, and 2ndFlrSF).
    - Applied **Label Encoding** for ordinal features (e.g., ExterQual).
    - Applied **One-Hot Encoding** for nominal features (e.g., Neighborhood).

## Libraries Used:
* Pandas, NumPy, Matplotlib, Seaborn.

---
**Course:** Machine Learning  
**Instructor:** Dr. Ibrahim O. Kaware  
**Student:** Malak Darwish Ammar
