# Bike-Sharing-Demand-Prediction (Machine Learning Regression)
The SEOUL bike sharing demand prediction project aims to predict the hourly bike rental demand for a bike-sharing system in Seoul, South Korea. The dataset used in the project contains hourly data on weather, temperature, humidity, windspeed, and other factors, as well as the corresponding bike rental demand.

The project uses various data preprocessing techniques to clean and transform the data, and several machine learning algorithms are used to build predictive models. These include linear regression, decision trees, random forests, lasso, ridge, and elasticnet.

The project also includes feature engineering techniques to extract additional information from the data, such as creating new variables to capture the effects of weather and time on the bike rental demand.
# Findings:-
* Weather variables such as temperature, humidity, windspeed, and weather condition, as well as time variables such as hour, day, and month, have a significant impact on the bike rental demand.
* The Random Forest Regressor algorithm produces the best predictive model.
* Feature engineering techniques, such as creating new variables to capture the effects of weather and time on the bike rental demand, can improve the accuracy of predictive models.
* Data preprocessing techniques, such as cleaning and transforming the data, are crucial for building accurate predictive models. Day is the feature that has the most influence, while Working Day comes in second for Linear and Ridge Regressor.
For Lasso, ElasticNet, Decision Tree, and Random Forest Regressor, the month is the most significant feature.

Visualization of Actual vs. Prediction is performed for all 6 models.

R2 Comparisons:

Linear Regressor R2 : 0.9538193994196074

Lasso Regressor R2 : 0.9244548788202334

Ridge Regressor R2 : 0.9538192431473912

ElasticNet Regressior R2 : 0.8196626252780658

Decision Tree Regressor R2 : 0.8804737719065344

Random Forest Regressor R2 : 0.981668168270039

*Random Forest Regression is the best-performing model with an r2 score of 0.981668168270039. 
*ElasticNe Regression is the worst-performing model with an r2 score of 0.8196626252780658.
