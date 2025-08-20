# TitanicPrediction
This challenge aims to predict whether a Titanic passenger survived the disaster, based on available information such as passenger class, sex, and age.   
We will use labeled training data to build a classification model, and then apply it to unlabeled test data to predict survival outcomes.

The code used for the final prediction is found in file "titanicPredict.ipynb", where the whole data pipeline, from data loading and exploration to evaluation is found. The steps carried are:
- Loading and exploring the data
- Feature engineering
- Data Cleaning
- Fitting of multiple models for classification (decision tree, random forest and XGBoost)
- Pre-processing of test data
- Perform predictions with test data and conclusions

Predictions obtained a final accuracy of 76% on the test data from Kaggle, which is comparable to the baseline approach that uses only passenger sex as a predictor.  

However, the results in this project were obtained through a full machine learning pipeline, including data cleaning, feature engineering, hyperparameter tuning and model evaluation. This gives the used model the ability to generalize to a broader set of features such as age, ticket class, and name-derived titles, offering greater flexibility and interpretability.  

Overall, the project not only demonstrates predictive performance, in this case of XGBoost, but also shows a robust approach to prepare tabular data and training explainable models, which is transferable to a large number of real-world machine learning scenarios.
