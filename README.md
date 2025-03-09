The aim of this project is to forecast the price of a car.
To achieved this goal, I found a dataset from Kaggle published in 2022 which contain more than 818,000 rows of records.
Each row represents one vehicle with more than 30 columns each represents a attribute oif the advert, such as the price, car make, model, variant, transmission, engine size, body type etc.. 
The main challenges in this project was the nature of the data. 
First, the data contains a lot of categorical features which are complicated to use in state-of-the-art models.
Secondly, the the target (price) and the other numerical features are not meeting normal distribution. 
To handled the categorical features, a deep exploration of the nature of the features has been applied, including handling missing data,
remove categorical data with high number of uniques values, remove features with high correlation, codding etc.
To handled the anormal distribution, I try to remove outliers and see if the distribution has improved.
The optimal multiplier has been found and use. After pre-processing, model selection, fine tuning, and exploration of feature importance I found an accuracy of 97% of the forecasting.

As part of this project, many experiments were conducted to improve the prediction of the target column, but I did not mention them to avoid overloading the notebook.
