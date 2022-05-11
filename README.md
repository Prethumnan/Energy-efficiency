# Energy-efficiency

An interesting fact is that the unique value of the data are not so many,

X1 Relative Compactness has 12 possible values

X2 Surface Area has 12 possible values
X3 Wall Area has 7 possible values
X4 Roof Area has 4 possible values
X5 Overall Height has 2 possible values
X6 Orientation has 4 possible values
X7 Glazing Area has 4 possible values
X8 Glazing Area Distribution has 6 possible values
y1 Heating Load has 586 possible values
y2 Cooling Load has 636 possible values


The histograms have already told us that our data seems to be descret , like categorical data but in numbers. We should therefore use tree based algorithms to expect the best model using those type of data. We create 3 basic models and then optimze each models using Hyperparameter Search technique. The model we used are:

*Decission Tree Regression
*Random Forest Regression


Overall, the model perform well to predict the the Heating Load and Cooling Load with R2 score >= 97%.

R2 score of Decision Tree Regressor model = 97.0%
R2 score of Random Forest Regressor model = 97.0%
