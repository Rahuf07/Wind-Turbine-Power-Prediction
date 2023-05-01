# Wind-Turbine-Power-Prediction

This project aims to predict the power output of a wind turbine based on weather conditions using machine learning models. The dataset used in this project contains the following features:

- Date/Time
- LV ActivePower (kW)
- Wind Speed (m/s)
- Theoretical_Power_Curve (KWh)
- Wind Direction (°)

## Data Preprocessing
The dataset was first explored and visualized using various libraries like Pandas, Matplotlib, and Seaborn. The data was then preprocessed by removing any missing values, dropping unnecessary features, and scaling the data.

## Machine Learning Models
Five machine learning models were trained and evaluated on the preprocessed data:

- XGBoost
- LightGBM
- KNeighborsRegressor
- HistGB
- Lasso Regression

The performance of each model was evaluated using the root mean squared error (RMSE) and the R-squared score. HistGB model performed the best, with an RMSE of 377.62 and an R-squared score of 0.917.

## Conclusion
In conclusion, this project demonstrates the feasibility of predicting wind turbine power output based on weather conditions using machine learning models. The HistGB model was found to be the best performing model, which can be used to optimize wind turbine operations and maintenance.





