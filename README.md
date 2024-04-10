# Boombikes Linear regression assignment
> The assignment is to build a multiple linear regression model for the prediction of demand for shared bikes dataset and identify the independent variables which have influence on demand of bike hire.


## Table of Contents

## General Information

Multiple linear regression is performed on the bike rental dataset to understand the relationship between various independent variable and predict the number of rentals issued from the company.

We are trying to find the number of rentals issued from the company based on numerous independent values such as temperature, season,day of the week, weather, humidity, holiday, etc.

The Boombikes bike rental dataset is being used to for this assignment.

## Technologies Used

numpy
pandas
seaborn
matplotlib
statsmodels
sci-kit learn

## Conclusions

1) The model which is biult has R-squared value of the train set is 82.18% and test set has a value of 79.47%, which suggests that  model broadly explains the variance accurate and we can conclude that it is a good model.
 
 2) Mean squared error is almost 0 on both the training and testing datasets for the developed model which suggests that the variance prediction is accurate on the test set. Significant variables are identified by using p-values and VIF and RFE was also performed for selecting variables automatically.

 3) Based on the model developed we can conclude that the bike demands of BoomBikes company is dependent on the temperature, day of the week, season and weather type. Demand is low on non-working days,during summer and when weather is not clear like snowy, misty or cloudy.

 4) The above interpretations help us derive meaningful insights in the bike rental market. We can conclude and recommend the biker rental comanies to do aggressive marketing with good incentive or strategy deals during Summer or when the weather is not clear. They can look into a better approach to introduce more users on days when the weather is less clear. Rentals were more in 2019 than 2018 suggests that over time people are exposed to this idea and are willing to try the bike renting options, so company can look for better marketing and make use customers can look forward to rent the bikes again and become repeat customers.




## Contact
Created by [@sireeshatumpati9] - feel free to contact me!