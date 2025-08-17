# ML-Prediction-of-vehicle-price
Prediction of Selling prices of the vehicle using the machine learning 

## About the Project
This project aims to predict the selling price of vehicles based on their features such as year, kilometers driven, mileage, engine capacity, power, seats, fuel type, transmission, ownership details, etc.


## What data you used
The dataset contained columns like:
--year (manufacture year)
--km_driven (how much the car has run)
--mileage, engine, max_power (performance indicators)
--seats (capacity)
--make, model, variant (categorical features)
--fuel type, seller type, transmission, owner (categorical features encoded into dummies)
--selling_price (target variable)

## What algorithms you applied
You applied two ML algorithms:

### Linear Regression
  --A simple model that assumes a linear relationship between features and price.
  --Fast and interpretable, but underperformed because car price prediction is non-linear.

### Random Forest Regressor
  --An ensemble method using multiple decision trees.
  --Captures non-linear relationships well.
  --Produced much higher accuracy in your case.

## How you evaluated models
 --Root Mean Square Error (RMSE) → penalizes large errors
 --Mean Absolute Error (MAE) → average of absolute errors
 --R² Score → how much variance is explained by the model

 Linear Regression gave R² = 0.71
 Random Forest gave R² = 0.97

 ## Train and predicted data (unseen data)

## Results and Conclusion
Linear Regression: Performed okay, but missed many non-linear patterns (R2=0.71).
Random Forest: Significantly better performance (R2 = 0.97).
For car price prediction,methods like Random Forest is better suited than simple linear models.
