# CAPSTONE PROJECT- PREDICTING HOUSE PRICES  (ALT SCHOOL)

![](houseimage.jpg)
---

## PROBLEM STATEMENT
The prices of houses are influenced by various factors like the size, location, condition, etc. Predicting house prices is important to stakeholders who are housing developers or contractors, investors or those looking to purchase a house.

## OBJECTIVES OF THE PROJECT
1. To build a machine learning model to predict housing prices.
2. To determine the relationship between house size and prices
3. To determine whether the age of houses influence price.


## DATA COLLECTION AND PREPARATION
The dataset for this project is from https://www.kaggle.com/datasets/fratzcan/usa-house-prices

## SELECTION OF MACHINE LEARNING ALGORITHMS
In this project, a regression analysis will be carried out to estimate the relationship between the dependent(target) variable and the independent variables.
1. The linear regression model tries to predict the relationship between two or more variables and estimates the line of best fit.
2. The Gradient boosting algorithm is used to predict not only continuous but also categorical variables. Because I am trying to price which is a continuous variable, I would also use this algorithm for the estimation.
3. Decision tree regression algorithm observes features and trains a model in the structure if a tree to predict a continuous variable.
4. Random forest regression algorithm is used for predicting numerical values. It combines the prediction of decision trees to produce an accurate and stable prediction.
For the purpose of this project, I would use the four algorithms for prediction and determine the best-suited model.

The conditions for choosing the best model based on the performance metrics and normalized data are:
1. R squared shows how well the independent variables predict the target variable. R2 ranges from 0 to 1 with 1 being a perfect fit.
2. RMSE shows the accuracy of the model. The lower the RSME, the better the model and its predictions.
3. MAE score ranges from 0 to 1 with 0 being a perfect score.
Based on the metric scores I would select Random Forest Model as the best-performing model because it has the best values amongst the models.


## MODEL INTERPRETATION AND REPORTING
## INTERPRETING THE MODEL
1. R2 (Coefficient of Determination) = 0.49
This result means that the model explains that approximately 49% of the variation in house prices. It is slightly higher than the R2 values of the other models.
2. RMSE(Root Mean Square Error) = 0.72
This means that the prediction error is 0.72, indicating a poor model but relatively better than other models analysed in the project.
3. MAE (Mean Absolute Error) = 0.50
The MAE of the Random Forest Model explains that the model's predictions are off by approximately 5% indicating a significant error. However, it has the best value when compared with other models.¶


## FINDINGS OF THE PROJECT
From the visualizations above, it is discovered that;
1. There is a slightly positive correlation or relationship between house age and price.
2. Initially, lot size had a negative relationship with price, but later on, it shifted to a positive relationship.
3. There is a positive linear relationship between total square feet of the house and prices. It means that as the feature value increases, the prediicted outcome also increases.
3. The number of bedrooms, bathrooms and floors have little or no effect on the predicted outcome.
4. The residuals are normally distributed and it suggests that the model correctly captures the relationships in the data.
   
## CONCLUSIONS
From the analysis, it can be concluded that house size is a significant factor in determining house prices in the USA. Generally, larger homes tend to be more expensive, while smaller homes are typically less expensive. It proves that developers factor in house size in fixing prices.
It can be concluded that the age of the house has minimal impact on determining its price in the USA.

