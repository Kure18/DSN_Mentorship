Project Title: 
Predicting Increase in the usage of Electric Vehicles (EV) in Washington D.C
Business Problem and Context :
The business problem  in this case has to do with a utility company which wants to be provided with a forecast on the increase in the use of EV’s so as to make provision for power stations in all county’s based on the distances traveled from one station to another.
Data Architecture :
Data source link : https://catalog.data.gov/dataset/electric-vehicle-population-size-history?from_hint=eyJxIjoiZWxlY3RyaWMgdmVoaWNsZSBwb3B1bGF0aW9uICJ9
Model  and Evaluation :
Model
For the dependent variable which is y I used the linear regression but the model perform poorly in which the outcome was either greater than 1 or below 0.01 using metrics such mean squared error and mean absolute error.
Furthermore I decided to use the logic regression and decision tree classifier model and found out that the model performed perfectly for both the base line model and the main model using the entire dataset.
The metrics used were accuracy, precision , f1 score and recall in which the all values were very close to the value of 1 that is 0.995 …………….. etc
Key findings:
Since the y variable is a continuous value, the linear regression model performed poorly so I had to use the mean of the column to creating a column “success threshold” with Boolean values in which the logical regression and decision tree classier model gave us an accurate result.


