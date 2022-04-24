# StockX Sneaker Predictions for Profits
## About
Hello! This is our StockX Sneaker Predictions Mini Project for SC1015 - Introduction to Data Science & Artificial Intelligence. Dataset taken is from the [StockX Sneaker Data Contest](https://www.kaggle.com/datasets/hudsonstuck/stockx-data-contest). Please view our project code in order from:
1. [Data Extraction & Preparation](https://github.com/klaustan/StockX-Sneaker-Predictions/blob/main/data-preparation.ipynb)
2. [Exploratory Data Analysis](https://github.com/klaustan/StockX-Sneaker-Predictions/blob/main/exploratory-data-analysis.ipynb)
3. [Outlier Identification](https://github.com/klaustan/StockX-Sneaker-Predictions/blob/main/outlier-identification.ipynb)
4. [Outlier Prediction Classifier Models](https://github.com/klaustan/StockX-Sneaker-Predictions/blob/main/outlier-prediction-classifier-models.ipynb)

## Project Collaborators
- @klaustan - Outlier Prediction Classifier Models
- @Frogopot - Data Preparation, Outlier Identification
- @shermaineng - Exploratory Data Analysis

## Motivation
This is a pair of Nike x Off-White Air Jordan 1 Chicago. It is currently retailed at USD$23,769, a more than 125 times markup from its initial price in 2017 which was USD$190. The reselling of sneakers have been up and rising. The once niche market of sneakers resale has been growing into a USD$79 billion business.


![Sneaker](https://github.com/klaustan/StockX-Sneaker-Predictions/blob/main/Slides/Sneaker.png)
## Problem
- Anomaly identification: Through the analysis of historical transaction data, are we able to identify sneakers that were sold at disproportionally high prices

- Predictive analysis: Can we build a predictive model to identify the pattern behind these highly profitable sneakers, allowing sneakerheads to exploit opportunities in future sneaker launches and resell for high profits

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

## What we have learned
- Usage of various outside sources to improve data preparation for analysis
- Further understanding of various visualisation tools like MatPlotLib and SeaBorn
- MatPlotLib style sheets
- Other visualisation models such as further multi-variate visualisations
- Unsupervised Learning Models such as DBScan in order to cluster data and find outliers
- Gradient Boosting Algorithms such as XGBoost Classifiers
- Ensemble Learning such as Random Forest Classifiers
- Recursive Feature Elimination & Logistic Regression, including other Learning techniques
- K-Fold Cross Validations to verify model across the entire dataset
- Collaboration on Google Colab and GitHub

## Conclusion & Insights
- Shoe Sizes: 8.75  to 10.75 most likely to yield unusually high profits due to high market demand, above 15 is also highly profitable due limited market supply
- Shoe Colours: White / Colourful most likely to yield unusually high profits due to them being popular colourways, Grey most likely to yield sub-par profits and should be avoided

## Future Implementations of the Project
- Our models are unable to perform a time-dependent or sequential analysis to predict when is the optimal time in selling the sneakers, despite being able to identify sneakers that have potential to achieve highly profitable returns.
- Our models are unable to identify the similarities and differences in the design elements across different models, and quantify these design variables into our predictions. 
- Future models can consider analysis convolutional neural networks by looking at design elements which give rise to popularities of shoes.

Thank you!

## References
- https://machinelearningmastery.com/smote-oversampling-for-imbalanced-classification/
- https://matplotlib.org/3.5.0/tutorials/index.html
- https://www.analyticsvidhya.com/blog/2020/10/cost-complexity-pruning-decision-trees/
- https://machinelearningmastery.com/rfe-feature-selection-in-python/
- https://machinelearningmastery.com/xgboost-for-imbalanced-classification/
- https://machinelearningmastery.com/avoid-overfitting-by-early-stopping-with-xgboost-in-python/
- https://towardsdatascience.com/ensemble-methods-in-machine-learning-what-are-they-and-why-use-them-68ec3f9fef5f
- https://towardsdatascience.com/building-a-logistic-regression-in-python-step-by-step-becd4d56c9c8
- https://medium.com/@dilip.voleti/dbscan-algorithm-for-fraud-detection-outlier-detection-in-a-data-set-60a10ad06ea8
- https://medium.com/@tarammullin/dbscan-parameter-estimation-ff8330e3a3bd



