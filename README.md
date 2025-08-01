# Predicting Country Happiness
This project aims to predict country-level happiness scores (Life Ladder) using socio-economic and well-being indicators. We apply machine learning regression models to data inspired by the World Happiness Report, exploring how different factors influence life satisfaction globally.

# Project Overview
Goal: Predict the Life Ladder score for each country-year
Data: World Happiness Report
Target Variable: Life Ladder (Happiness Score)

# Key Features:
year, Log GDP per capita, Social support, Healthy life expectancy at birth, Freedom to make life choices, Generosity, Perceptions of corruption, Positive affect, Negative affect, Confidence in national government, Democratic Quality, Delivery Quality, GINI Index: GINI index (World Bank estimate), GINI index (World Bank estimate), GINI of household income reported

# Methodology
- Data Cleaning & Feature Engineering
- Handle missing values (replacing with mean)
- Remove or cap outliers detected via bargraphs
- Normalize/scale continuous variables
- Address potential class or distribution imbalance

# Exploratory Data Analysis (EDA)
- Visualize feature distributions and correlations
- Identify outliers and influential features

# Model Training
Model Type: RandomForestRegressor 
Hyperparameter tuning via GridSearchCV with 5‑fold CV

# Model Evaluation
Metrics:
- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)
- R² Score (Goodness of Fit)
Steps:
- Compare RMSE and R² on cross-validation and test sets
- Analyze feature importances to interpret influential factors

# How to Run
## Download the Jupyter notebook file (.ipynb) from this repository.
```
jupyter notebook predicting-country-happiness.ipynb
```

Run the cells sequentially to execute the analysis.
The notebook handles all data loading, preprocessing, modeling, and visualization steps.
Results and plots will display automatically as you run the cells.
