# deep-learning-challenge
Data Preprocessing

What variable(s) are the target(s) for your model?
  The target or dependent variable is the "IS_SUCCESSFUL" column from the dataframe.
What variable(s) are the features for your model?
  The features or the independent variables are all the other columns that are not the "IS_SUCCESSFUL" column from the dataframe.
What variable(s) should be removed from the input data because they are neither targets nor features?
  The "EIN" and "NAME" columns were removed because they were not target variables. In the future runs, other columns such as "STATUS", "SPECIAL_CONSIDERATIONS", and "ASK_AMT".


Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
  The first run had four layers, with the first layer having 110 units, 100 in the second, 80 in the third, and 1 in the fourth. I selected higher unit numbers because I thought it would run the model in a more accurate way, I added more layers in the re-runs for the same reason.
Were you able to achieve the target model performance?
  I was unable to achieve 75%.
What steps did you take in your attempts to increase model performance?
  I tried to add more layers, change the activation type, and also change the number of units.

Summary:
  The average of accuracy of the model is 73% for prediction. Possibly using a larger dataset with a stronger correlation between target varibles and running the model with more iterations could possibly increase the accuracy percent.
