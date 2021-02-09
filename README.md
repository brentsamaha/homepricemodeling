# homepricemodeling

We took two data sets in this lab, one with 77,000+ rows of logerror values and a shared-unique identifier, and another of the same length, with the same identifier, and numerous attributes for each instance. 

After combining the data sets on the shared identifier, I randomly separated the data sets into test and train sets for future use. 

I next randomly chose five columns to build a linear regression model. I ensured these columns were not missing data by creating each a new column, and if a value was absent, the mean of the entire column replaced the NaN value.

After running the model, I looked at some quick stats - noticeably a low R^2 value, which was not surprising given my random choice of variables. After finding the RMSE and MAE for my training data, I tested the model to see how well it could predict logerror values from the training data. 

I am confident that the model is strong to a degree, given the RMSE and MAE values' closeness between the training and test data sets. With a precise model like the one I created, I would look into next, making the model accurate - by wisely choosing variables to build the model. 
