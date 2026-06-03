# Car Price Prediction using Machine Learning

## Overview

Car price prediction is an important application of Machine Learning that helps estimate the selling price of a used car based on various features such as present price, fuel type, transmission type, ownership history, and distance traveled.

In this project, a Machine Learning model is developed to predict the selling price of a car using historical car data.

---

## Objective

The main objective of this project is to build a predictive model that can accurately estimate the selling price of a used car based on its characteristics.

---

## Dataset Description

The dataset contains information about different cars and their selling prices.

### Features

* Car_Name
* Year
* Present_Price
* Driven_kms
* Fuel_Type
* Selling_type
* Transmission
* Owner

### Target Variable

* Selling_Price

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Kaggle Notebook / Jupyter Notebook

---

## Project Workflow

### 1. Data Collection

The dataset was loaded and inspected to understand its structure and contents.

### 2. Data Cleaning

* Duplicate records were removed.
* Dataset consistency was checked.
* Relevant features were selected.

### 3. Feature Engineering

A new feature called **Car Age** was created using the manufacturing year of the vehicle.

### 4. Exploratory Data Analysis (EDA)

Various visualizations were used to understand:

* Selling price distribution
* Fuel type distribution
* Transmission type distribution
* Relationships between variables

### 5. Data Preprocessing

Categorical variables were converted into numerical format using one-hot encoding.

### 6. Model Building

A Random Forest Regressor model was trained using the processed dataset.

### 7. Model Evaluation

The model performance was evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

### 8. Prediction

The trained model was used to predict car selling prices.

---

## Machine Learning Algorithm

### Random Forest Regressor

Random Forest is an ensemble learning algorithm that combines multiple decision trees to improve prediction accuracy and reduce overfitting.

---

## Results

The model achieved strong prediction performance and was able to estimate car selling prices with high accuracy.

Performance was measured using:

* MAE (Mean Absolute Error)
* RMSE (Root Mean Squared Error)
* R² Score

---

## Conclusion

This project demonstrates how Machine Learning can be used to predict used car prices based on historical vehicle data and market-related factors.

The developed model can assist buyers, sellers, and automobile businesses in estimating vehicle prices more effectively.

---

## Future Improvements

* Use larger datasets for better accuracy.
* Compare multiple regression algorithms.
* Deploy the model as a web application.
* Add advanced feature engineering techniques.

---

## Author

Data Science Internship Project

Oasis Infobyte (OIB-SIP)

Task 3: Car Price Prediction with Machine Learning
