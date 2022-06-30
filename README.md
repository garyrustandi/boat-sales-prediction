# Regression with Python: Boat View Prediction

Boatee is a website platform for people to list out their boats.  After some years experience, we have learned that there are several boats that are not high in demand. Product Manager wants to prevent listing boats that have less view in order to boost website traffic. 

The **goal** of the analysis is to create a model that can predict number of views and to determine which features that can be removed based on the importance.

The raw data is very **messy**. Some data cleanings are required before entering the model creation which include splitting columns, handling missing data, handling outliers, and removing unnecessary data.

Example of the [raw data](https://www.kaggle.com/code/karthikbhandary2/boat-analysis/data)
![boat_explore](https://github.com/garyrustandi/boat-view-prediction/blob/main/images/boat_explore.jpg)

The model is a **supervised machine learning regression model**. The best model chosen is **Random Forest Regressor** with RMSE of 66.7. This model prediction error is 50% than the actual value.

The most important features are location and price while the least important features are type, material, and fuel. We can consider to remove the least important features from the survey.

![feature_importance](https://github.com/garyrustandi/boat-view-prediction/blob/main/images/Feature%20Importance.png)

Hopes you enjoy the publication! 
Thank you.
