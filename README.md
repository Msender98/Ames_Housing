# Predicting Investment Properties
## About:
Using the [Ames, Iowa House Price dataset](https://www.kaggle.com/c/house-prices-advanced-regression-techniques) we build machine learning models to predict investment properties. 

## Model:
We used an ensemble model, first modeling the price as a function of a houses location (latitude, longitude) using kNN and then modeling the residuals from that model with a ridge regression. In this way we separate the location's effect on price and mimic how many people judge a home's value; location first and then comparing to other properties. 

## Analysis:
Then using the model we can predict the potential increase in price by changing features in a home (i.e. increasing the quality of the kitchen, curb appeal, etc.). Then, with given homes for sale, we can output the homes with the most potential for profit (currently not taking into account the cost of renovations, but that can be estimated for a more holistic prediction).  

## What's in the repo:
The project was completed with a series of jupyter notebooks. Analysis.ipynb shows the final analysis using the models and cleaned sales data built in other notebooks in the Archive folder. Final_Model.ipynb builds and outputs the models used in Analysis. Other notebooks include other models and analysis that were not used in the end. 

The pickles folder includes saved model and dataframe objects.  Location_model and final_model are the final trained models. 

