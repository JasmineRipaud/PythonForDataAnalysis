# PythonForDataAnalysis
Python project - RIPAUD Jasmine ROUSSELET Alexandre - Seoul Bike

-- SEOUL BIKE DATASET -- 

DATA VISUALISATION

First, we use a correlation matrix to determine the most correlated variables with the number of rented bikes.
Then, we study these values and try to understand how it's evolution does affect the rent of bikes in Seoul.
  
Conclusion :  The most releated variables with the rent are the Season, the Dew point/Temperature and the hour.
Indeed, we can observe the rents are low when the temperatures are cold (includes in Winter) and are better when the temperatures rise (reasonably).
The more of the rents are made at 8am (probably when people go to work) and between 5pm and 9pm (when people come back from work).



MODELISATION


After dividing the dataset in a training and a testing set, we apply our algorithms to determine which one is the best for predicting:
We intend to use the Linear Regression, Logistic Regression, Support Vector Regression and Random Forest Classifier.

Conclusion : Our results are distorted because of a bad implementation so the Linear Regression appears to be the best model but we can expect the Random Forest Classifier to actually be the best model. We also deleted our Support Vector Regression model as it didn't returned satisfying results.
