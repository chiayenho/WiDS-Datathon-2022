# WiDS-Datathon-2022
I attended the WiDS Datathon 2022 competition, the first machine learning competition I joined.

The main goal is to predict building energy consumption by analyzing differences in building energy efficiency and weather variables. Accurate predictions of energy consumption can help policymakers target retrofitting efforts to maximize emissions reductions.

### For data exploration part:
I created some plots to understand the data distribution and correlation better. Further, I made some new features based on my understanding.

### For model building part:
First, I built linear regression and decision tree as the baseline model. Then, I tried ensembling models such as XGBoost, LightGBM, and Catboost. After hyperparameter tuning and feature selection, the LightGBM model performed the best overall. However, due to the computing limitation of my laptop, I was not able to conduct a more comprehensive grid search.

### For model evaluation part:
I plotted the feature importance to see which feature played an important part. Moreover, I evaluated the results by plotting graphs for actual and predicted values, finding that the model still went wrong on outliers. The model still got space to improve.



Link to my Kaggle notebook: https://www.kaggle.com/viviho/wids-datathon-2022-lightgbm

Kaggle Dataset: https://www.kaggle.com/c/widsdatathon2022/overview

Inspired by Google WiDS conference: https://github.com/michevan/WIDS-Google
