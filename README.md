# Predicting California Housing Prices with Machine Learning

## Overview
This project analyzes California housing data to predict median house values using key features such as ocean proximity, housing age, and number of bedrooms. The goal is to combine exploratory data analysis (EDA) with machine learning models to understand what factors most strongly influence housing prices and how accurately those prices can be predicted.

---

## Research Question
Can housing prices be accurately predicted using features like proximity to the ocean, average number of bedrooms, and housing age?

---

## Hypothesis
Homes that are closer to the ocean, have more bedrooms, and are newer are expected to have higher median house values.

---

## Dataset
- **Source:** Kaggle – California Housing Prices  
  https://www.kaggle.com/datasets/shibumohapatra/house-price
- **Observations:** Approximately 20,600 housing blocks
- **Target Variable:** `median_house_value`

### Key Features
- `longitude`, `latitude`
- `housing_median_age`
- `total_bedrooms`
- `total_rooms`
- `households`
- `population`
- `median_income`
- `ocean_proximity`

---

## Data Cleaning & Preparation
- Removed unused variables
- Dropped rows with missing values
- Encoded categorical variables
- Prepared features for modeling and evaluation

---

## Exploratory Data Analysis (EDA)
Key findings from the EDA include:
- Geographic location strongly influences housing prices, with higher values clustered near major cities and coastal areas
- Homes closer to the ocean tend to have higher median values
- Housing age and bedroom count show non-linear relationships with price
- Median income alone does not fully explain housing price variation

---

## Models Implemented
### Linear Regression
- Strong alignment between predicted and actual house values
- Provided interpretable coefficients
- Best overall performance among tested models

### K-Nearest Neighbors (KNN)
- Weak correlation between predicted and actual values
- Higher mean squared error
- Poor generalization performance

### Bootstrap Analysis
- Showed limited variability in predictions
- Suggested limited predictive signal for certain feature combinations

---

## Results & Conclusions
- Linear regression outperformed more complex models on this dataset
- Location and ocean proximity were among the strongest predictors
- Housing prices depend on multiple interacting factors rather than a single variable
- Simpler, interpretable models can perform competitively on structured tabular data

---

## Tools & Technologies
- Python
- pandas, NumPy
- scikit-learn
- matplotlib, seaborn
- Jupyter Notebook

---

## Files
- `housing_prices.ipynb` – Full analysis, EDA, and modeling workflow

---

## Authors
- Shenova Davis
- Lauren Lui
- Vincent Sgherzi
