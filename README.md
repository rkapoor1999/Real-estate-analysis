# Real Estate Price Prediction Model

## Overview
This project implements an end-to-end machine learning solution for predicting real estate property values across the United States using a dataset of over 2 million property records.

## Key Features
- **Data Exploration**: Comprehensive analysis of missing data patterns across property types and geographical regions
- **Advanced Imputation**: Sophisticated grouped imputation strategies based on property status and location
- **Feature Engineering**: Custom features capturing property efficiency metrics (price-per-sqft, bed-bath ratios, land utilization)
- **Model Development**: XGBoost regression model with hyperparameter tuning achieving 99% R-squared accuracy

## Project Structure
```
real_estate_analysis/
├── data/
│   ├── raw/                                                              # Raw data files
├── encoders/
├── models/                                                               # Saved models
├── notebooks/                                                            
|   └── 01_Real_Estate_Data_Exploration_and_Imputation.ipynb              
│   └── 02_Imputation_Outlier_Skewness_handling.ipynb
│   └── 03_Model_training.ipynb
└── requirements.txt                                                      # Project dependencies
```

## Technologies Used
- Python (pandas, numpy, matplotlib, seaborn)
- scikit-learn for data preprocessing
- XGBoost for regression modeling
- Hyperparameter tuning with GridSearchCV

## Results
The final model accurately predicts property values across diverse markets and property types, with feature importance analysis revealing key price drivers in the real estate market.

## Future Work
- Integration with geospatial data for neighborhood analysis
- Time-series analysis for price trend forecasting
- Deployment as a web API for real-time property valuation
