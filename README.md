# Tornado Magnitude Prediction

## Motivation
The motivation of the project is to predict the magnitude of a tornado from historical data collected of various tornadoes in the USA from 1950 to 2019 by the National Weather Service.

## Methodology
This is a regression type of problem in which a stacking regressor with the following base regressors: Lasso regression, Linear Support Vector Regression, and `XGBoost` regressor from `scikit-learn` and `XGBoost`, and Ridge regression as a meta regressor was built. As a single number evaluation metric R^2 is used, and the most optimal model for this application is the stacking regressor which has the highest R^2=0.594053.
