# StockX Sneaker Predictions for Profits
## About
This is our StockX Sneaker Predictions Mini Project for SC1015 - Introduction to Data Science & Artificial Intelligence. Data taken is from the [StockX Sneaker Data Contest](https://www.kaggle.com/datasets/hudsonstuck/stockx-data-contest). Please view our project code in order from:
1. [Data Extraction & Preparation](https://github.com/klaustan/StockX-Sneaker-Predictions/blob/main/data-preparation.ipynb)
2. [Exploratory Data Analysis](https://github.com/klaustan/StockX-Sneaker-Predictions/blob/main/exploratory-data-analysis.ipynb)
3. [Outlier Identification](https://github.com/klaustan/StockX-Sneaker-Predictions/blob/main/outlier-identification.ipynb)
4. [Outlier Prediction Classifier Models](https://github.com/klaustan/StockX-Sneaker-Predictions/blob/main/outlier-prediction-classifier-models.ipynb)

## Project Collaborators
- @klaustan - Outlier Prediction Classifier Models
- @Frogopot - Data Preparation, Outlier Identification
- @shermaineng - Exploratory Data Analysis

## Problem
- How do we know which new releases of sneakers can be sold for abnormally high profits?

## Models
1. Random Forests
2. XGBoost Classifier
3. DBScan
4. Recursive Feature Elimination
5. Logistic Regression

## Other Techniques
1. SMOTEENN Sampling
2. Cost Complexity Pruning
3. k-Fold Cross Validation

## Conclusion & Insights
- Shoe Sizes -- 8.75  to 10.75 most likely to yield unusually high profits due to high market demand, above 15 is also highly profitable due limited market supply
- Shoe Colours -- White / Colourful most likely to yield unusually high profits due to them being popular colourways, Grey most likely to yield sub-par profits and should be avoided

## References
- https://machinelearningmastery.com/smote-oversampling-for-imbalanced-classification/
- https://matplotlib.org/3.5.0/tutorials/index.html
- https://www.analyticsvidhya.com/blog/2020/10/cost-complexity-pruning-decision-trees/
- https://machinelearningmastery.com/rfe-feature-selection-in-python/
- https://machinelearningmastery.com/xgboost-for-imbalanced-classification/
-- https://machinelearningmastery.com/avoid-overfitting-by-early-stopping-with-xgboost-in-python/
- https://towardsdatascience.com/ensemble-methods-in-machine-learning-what-are-they-and-why-use-them-68ec3f9fef5f
- https://towardsdatascience.com/building-a-logistic-regression-in-python-step-by-step-becd4d56c9c8


