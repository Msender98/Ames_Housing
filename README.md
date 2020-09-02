Using the Ames, Iowa Housing Price dataset from kaggle for a machine learning project completed as a student at the NYC Data Science Academy.

We used an ensemble model, first modeling the price as a function of a houses location (latitude, longitude) and then modeling the residuals from that model with a ridge regression. In this way we separate the location's effect on price.  This can be useful for a developer planning on buying, renovating and reselling property. 

The project was completed with a series of jupyter notebooks. Analysis.ipynb shows the final analysis using the models and cleaned sales data built in other notebooks in the Archive folder. Final_Model.ipynb builds and outputs the models used in Analysis. Other notebooks include other models and analysis that were not used in the end. 

The pickles folder includes saved model and dataframe objects.  Location_model and final_model are the final trained models. 

