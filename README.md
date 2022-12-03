# Regression-Model-for-Corn-Yield-prediction
Final Report for Stat 615

Group Members: John Li, Yaopeng Ma, Changhe Ji

Corn yield prediction is essential for decision-makers, and it is complex because so many potential explanatory variables may affect the growth of crops. Regressors represent four different aspects: weather (varies weekly), soil, scale, and growth performance (varies weekly), and the response is corn yield in BU/Acre. Data was collected from 1990 to 2018, with a total of 8,352 observations and 688 features. The goal is to forecast corn yield performance for the Corn Belt states Illinois, Iowa, and Indiana. 

After pre-processing the data, feature selection method Lasso and Recursive Feature Elimination was applied to the model and then build up linear regression model to predict. The set up for experimental setting which prediction is that using exist data from this year and combine with all available historical data as potential unobserved data to construct the prediction interval. From doing that, we achieved an accurate RRMSE( relative root mean square) of 10%, and model fitting of about 75% for both R squared and adjusted R squared for the optimal model. 
