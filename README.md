# Competitive_data_science_project_housePrices

In this folder we present a full analysis of a database available on [Kaggle](https://www.kaggle.com/) with the goal to predict the house prices with machine learning regression techniques.

## How to read the project:
The project has been splitted in three different Python files to make it more readable, we suggest to start from the file:

### From eda to model selection:
In this file you can find a guided explanation of all the step from the explanatory data analysis to the test of many regressions algorithms till the choice of the best model based on the behaviour on a validation set of data.

The second file to read is:

### Prepare the test dataset for predictions:
Here we have just followed the same steps to prepare the test dataset in a form suitable to apply our machine learning selected model.

Last we have the predictions file:

## Predictions
Here we used the model to make predictions on the test dataset and we exported the predictions in a form suitable to submit our work to Kaggle. Currently we have a RMSLE of 0.1255 and we are in the TOP 15% of the leaderboard.

## Remaining file:

### regression_model.joblib:
This file contains the regression model fitted on the training dataset that we selected to make prediction. By saving the model on this file, we can just import it in the submission file to make predictions on the train dataset.
