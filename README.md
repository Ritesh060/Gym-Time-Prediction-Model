# Gym-Time-Prediction-Model
This model predicts the time at which the gym will be the least crowded. 
Various algorithms were applied after doing exploratory data analysis and the one with least Mean Squared Error was chosen.

## How it works?
The dataframe is made for the program using Pandas and then the data was cleaned for any NULL values. 
Then using the Seaborn library the data visualised in various forms for different columns and values.
Then after analysing the points in the graphs made earlier, machine learning algorithms are applied.
The machine learning algorithms applied are Linear Regression, Random Forest Regressor and XGB Regressor.
Then each model made is evaluated using Mean Squared Error.
The lowest Mean Squared Error was found to be of Random Forest Regressor.
Then to optimise the model more Feature Selection is done. This was the final step in making the model
