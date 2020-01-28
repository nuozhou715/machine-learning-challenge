# Machine-Learning-Challenge Report

## Background
Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.

To help process this data, and predict the accuracy of the station observation disposition, I created machine learning models capable of classifying candidate exoplanets from the raw dataset.

## Candidate Models
Since the interest is to build classification models, the logistic regression and neural network models will be applied.

Grid Searching method will be used to tune model parameters.
* The regulization and penalty parameters will be tuned for the logistic regression model.

* The first layer neuron number and epoch amount will be tuned for the neural network model.

Further, this case study can be served as an example to compare the performance of the traditional and relatively modern tools for classification analysis with fairly rich amount of observations and variables.

## Result
Based on the accuracy of the tuned logistic and neural network models on test data predictions, it is hard to say which one is better than the other, as the accuracy score of the neural network tuned model (0.887) is just slightly higher than the logistic model's (0.883). However, such conclusion does not have generalizability power as the nature of the empirical case study.

However, by increasing the number of hidden layers in the neural network model, we are likely to rise the prediction power further.
