# Random-Forest-Regressor-KPI

10/01/2022

TO DO:
- handle NaN values by means or other method
- check for overfitting of the model


First iteration of Random Forest Regressor model done through Google Colab. 
The task the program has to acheive is to forecast Y parameter for next 12 months for given set of products based on 112 independent variables. Training data includes 112 variables with predicted Y values. Script requires no input and returns filled Ytest_filled.csv as a result of computations. Metric used to check the correctness of model was WMAPE (Weighted Mean Average Percentage Error).

In first iteration I've filled all NaN values with 0, but I should fill them with mean values for the second iteration. Testing regressor on the same data on which it was trained gives 0.0% WMAPE which could mean that the model is overfitted, so other change is to check model on smaller number of devision trees.


Requires pandas, numpy and sklearn libraries.
