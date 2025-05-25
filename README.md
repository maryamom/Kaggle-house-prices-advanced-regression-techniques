
# Kaggle House Prices: Advanced Regression Techniques

## Project Overview

This project is my submission for the Kaggle competition ["House Prices: Advanced Regression Techniques"](https://www.kaggle.com/c/house-prices-advanced-regression-techniques). The goal is to predict the final price of homes based on 79 explanatory variables describing various aspects of residential homes.

## Notebook Features

* **Data Exploration**: Comprehensive analysis of the dataset including missing values, outliers, and feature distributions
* **Feature Engineering**: Handling of missing values, transformation of skewed features, and creation of new relevant features
* **Modeling**: Implementation of various regression techniques including:

  * Ridge Regression
  * Lasso Regression
  * Stacking Regressor (combining XGBoost, LightGBM, and CatBoost)
* **Cross-Validation**: K-Fold cross-validation to evaluate model performance
* **Submission**: Final predictions submitted to Kaggle

## Performance

My best submission achieved a **0.12021** on the Kaggle leaderboard (include your actual score here). You can view my ranking on the competition leaderboard.

![Score](https://github.com/user-attachments/assets/84e4a207-f2ab-495d-b746-6ded6485253d)

## Dataset

The **training** and **test** data used in this project are already provided within the Kaggle competition page. 

## Requirements

To run this project, you need Python 3.x and the following libraries:

```bash
pip install pandas numpy scikit-learn xgboost lightgbm catboost matplotlib seaborn
```

## How to Use

1. Clone this repository
2. Install the required packages
3. Open and run the `KaggleFinalNotebook.ipynb` notebook
4. The notebook includes all steps from data loading to final submission

## Key Insights

* The most important features for predicting house prices were:

  1. Overall quality
  2. Living area
  3. Garage size
  4. Year built
* The stacking ensemble approach provided the best performance among tested models
* Feature engineering (particularly handling skewed features) significantly improved model accuracy

## Future Improvements

* Experiment with more advanced feature engineering
* Try additional ensemble methods
* Perform more thorough hyperparameter tuning
* Explore neural network approaches
