# NYC-Taxi-Fare-Prediction

# Problem Statement

1. To predict the fare amount based on geographical and datetime features

# Dataset Description
1. The dataset consists of 50,000 rows and 8 different columns(features)

2. The dataset is splitted into 80:20 ratio.80% of the data is kept for training and 20% for test

# Approach Used

1. Used feature engineering to create new features out of existing features

2. Trained Using Random Forest Algorithm

3. Used GridSearch Hyperparameter Tuning to find the appropriate hyperparameters for Random Forest Algorithm

4. Used K Fold Cross Validation to cross validate the model

# Results Achieved

1. Achieved an overall RMSE(Root Mean Squared Error) of 4.75 on the Training Set and 4.44 on the Test Set

2. Achieved Mean RMSE(Root Mean Squared Error) of 4.99 on the cross validation

# Model Explainability

1. Used Shapely values to interpret the model

![shap_1](https://user-images.githubusercontent.com/37527532/107843024-9d612c00-6ded-11eb-8773-dccc072239e1.png)

![shap_2](https://user-images.githubusercontent.com/37527532/107843026-9e925900-6ded-11eb-836e-1174b015b45f.png)

![shap_3](https://user-images.githubusercontent.com/37527532/107843029-9fc38600-6ded-11eb-8e6c-cbe4c6bb1e61.png)


