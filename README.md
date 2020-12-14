# P15SolarPredictor
P15 Machine Learning project

This is our solar energy production predictor!

You see in our submission different files:
The Python notebook contains the data clustering and prediction part of our project.
 
The data is clustered concerning there location (to proof the functionality of our
cluster method) and the production. As you can see on the figure, the is no dependence 
between the location and the productivity. 

In the prediction part, you can choose to use the LinearRegression or the DecisionTree-
Regression for predicting a the production of a single household and the overall 
production per day. 

This algorithms are integrated in a GUI. In the GUI you can predict the production 
for a single day and the overall production and you can have a look at the cluster. 
When the GUI asks for a file, then the file "weather_data_juli.txt" must be selected. 
If the "Single Household" is used, then the household number must be entered before clicking the button.
If the number is not an integer from 1 to 100, then it will not work.
