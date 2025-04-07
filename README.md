# House-Price-Prediction
🏡 Property Price Prediction using Machine Learning

**Project Overview**

This project aims to build a predictive model that estimates property prices based on various features. Such a model can help real estate firms not only price properties more consistently but also focus on developing features that significantly impact value.

**Dataset**

housing_train.csv: Used to train and validate the model. Contains the target variable Price.

housing_test.csv: Used for final predictions. Does not include Price.

**Approach & Methodology**

Model Used: Random Forest Regressor

Performance: Achieved an R² score of 72% on the validation set

Data Pipeline:
Data preprocessing and feature engineering via pipelines
Train/Test split with validation
Hyperparameter tuning and model evaluation

**Tools & Libraries:**

pandas, numpy

scikit-learn (for preprocessing and modeling)

**Output**

A trained predictive model

Final predictions for housing_test.csv stored in a CSV file
