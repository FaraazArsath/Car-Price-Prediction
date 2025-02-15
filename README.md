# 🚗 Car Price Prediction 💰
This project analyzes data from 2005 General Motors (GM) cars to predict their resale price using linear regression. The dataset includes factors such as mileage, engine size, number of doors, and additional features like leather seats and cruise control.

## 📌 Project Overview
To build a linear regression model to predict car prices based on various factors and evaluate its performance using the R² score.

## 🔹 Dataset (car_data.csv)
The dataset contains the following columns:

Price: Suggested retail price of the used car in excellent condition

Mileage: Number of miles driven

Make: Manufacturer (e.g., Chevrolet, Pontiac, Saturn)

Model: Specific model name

Trim: Car model variant (e.g., SE Sedan 4D)

Type: Body type (sedan, coupe, etc.)

Cylinder: Number of engine cylinders

Liter: Engine size

Doors: Number of doors

Cruise: Whether the car has cruise control (1 = Yes, 0 = No)

Sound: Whether the car has an upgraded sound system (1 = Yes, 0 = No)

Leather: Whether the car has leather seats (1 = Yes, 0 = No)

## 🛠 Tasks and Implementation
✅ Part 1: Simple Linear Regression

Build a linear regression model using Mileage as the independent variable.

Find the linear equation for predicting car price.

Visualize the regression line along with original data.

Calculate the R² score to measure model accuracy.

✅ Part 2: Multiple Linear Regression

Use multiple factors (Mileage, Cylinders, Engine Size, Doors, Cruise, Sound, Leather) to predict car price.

Evaluate the best feature combination for predicting price.

Compute the R² score to determine how well the model fits the data.

✅ Advanced Mode: Categorical Variables & Feature Engineering

Convert categorical features (Make, Model, Body Type) into dummy variables using scikit-learn.

Identify the most important factors influencing car price.

Train an improved model using all relevant features.

