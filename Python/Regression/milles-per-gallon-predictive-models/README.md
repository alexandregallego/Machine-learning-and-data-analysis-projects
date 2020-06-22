# Miles-per-gallon-predictive-models

Given a dataset of different cars within a city, with some information regarding their characteristics such as: cylinders, weight, displacement, acceleration plus other 4 features, it was needed to predict the outcome of the dependent variable (miles per gallon or mpg). The factors that I had to take into account are available in the Jupyter notebook’s code, as well as in the following webpage: https://data.world/uci/auto-mpg/.

In order to try to predict the future consumption on miles per gallon of the city, I decided to train 9 different models and compared them based on its root-mean-squared-error, which is a measure that represents the difference between the values that a model has predicted and the values observed (the ones we have available on our dataset). Therefore, the higher the value of this metric, the lower the predictive capabilities of a model. The 9 different models that I have trained are the following:

* Linear regression
* Ridge regression
* Lasso regression
* Decision tree regressor
* Random forest regressor
* Bagging regressor
* Adaboost regressor
* Gradient Boosting regressor
* Stochastic gradient boosting regressor

