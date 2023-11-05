# New York Taxi Fare prediction
This project performs exploratory data analysis and modelling on NYC Taxi Fares. The New York City Taxi Fare Prediction dataset from Google Cloud hosted on Kaggle and a NYC weather dataset from NOAA were used.
- The 2 datasets were cleaned by removing NULL and negative values, and pickup dates and times were extracted.
- Further cleaning was performed to ensure that only entries within New York's Longitude AND Lattitude were selected.
- Data visualizations were done with the help of seaborn, mathplotlib and statsmodels libraries.
- The following prediction models were used - Linear Regression, Random Forest Regression and XGBoost.
- XGBoost with hyperparameter tuning gave the best RMSE value among all the models.
