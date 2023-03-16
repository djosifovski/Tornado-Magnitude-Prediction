# Tornado Magnitude Prediction

## Motivation
The motivation of the project is to predict the magnitude of a tornado from historical data collected of various tornadoes in the USA from 1950 to 2019 by the National Weather Service.

## Methodology
This is a regression type of problem, and the following regressors are built: lasso regression, multilayer perceptron, XGBoost regressor, and by combining the models with stacking regressor. As a single number evaluation metric $R^2$ is used.

## Results
The most optimal model for this application is the stacking regressor which has the highest $R^2=0.595533$.

## Technologies
Technologies used in this project are: scikit-learn, XGBoost, mlxtend, ensemble learning, Jupyter Notebook.
