
# Car Price Prediction Using Machine Learning

This project predicts the selling price of cars based on various features such as brand, mileage, horsepower, and other specifications. It demonstrates how machine learning techniques can be applied to build a regression model for price prediction.

## Project Overview

Car price prediction is a key problem in the automobile industry as it helps buyers and sellers estimate fair market value. This project uses a supervised machine learning approach to train a model on historical car data and predict car prices accurately.

## Key Features

* Data preprocessing (handling categorical features using label encoding)
* Splitting dataset into training and testing sets
* Model training using Random Forest Regressor
* Model evaluation using **Mean Absolute Error (MAE)** and **R² Score**
* Exporting the trained model for future predictions

## Technologies Used

* Python
* Pandas, NumPy (for data handling)
* Scikit-learn (for machine learning)
* Joblib (to save the model)

## Dataset

* Input file: `car data.csv`
* Includes car details like brand, mileage, horsepower, fuel type, and selling price.

## Model Output

* Displays evaluation metrics (MAE and R² Score)
* Saves trained model as `car_price_model.pkl` for future use

## Applications

* Used by car dealers to determine fair prices
* Used by buyers to avoid overpaying
* Can be extended to real-time price prediction web apps
