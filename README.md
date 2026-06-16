# 🚗 Car Price Prediction using Linear Regression

## 📌 Project Overview
This project predicts the selling price of used cars using Linear Regression.

## Dataset
- Source: CarDekho Used Car Dataset
- Records: 4,340
- After removing duplicates: 3,550

## Data Preprocessing
- Removed duplicate records
- Created `age` feature from manufacturing year
- Investigated `km_driven` outliers
- Tested models with and without outliers
- Kept outliers because they improved model performance

## Features Used
- Brand
- Age
- Kilometers Driven
- Fuel Type
- Seller Type
- Transmission
- Owner Type

## Model
- Linear Regression (Scikit-learn)

## Results
- MAE: 181,133
- RMSE: 357,707
- R² Score: 0.621

## Key Learning
Removing outliers is not always beneficial. After experimentation, retaining realistic high-mileage vehicles resulted in better model performance.
