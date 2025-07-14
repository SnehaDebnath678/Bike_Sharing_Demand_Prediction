🚲 Bike Sharing Demand Prediction with Machine Learning

This project applies machine learning techniques to predict bike rental demand using historical usage patterns and weather data. It is based on a dataset that contains hourly and daily counts of rental bikes, along with associated weather and seasonal information.

📌 Project Objective
The objective of this project is to build a predictive model that estimates the number of bike rentals based on features like temperature, humidity, wind speed, season, time of day, etc.

📊 Dataset Overview
The dataset includes the following key features:

datetime: hourly or daily timestamp

season: spring, summer, fall, winter

holiday: whether the day is a holiday

workingday: whether the day is a working day

weather: categorical weather situation

temp/atemp: actual and "feels like" temperature

humidity

windspeed

count: total rentals (target variable)

🛠️ Techniques & Tools Used
Python & Pandas for data manipulation

Seaborn & Matplotlib for visualization

Scikit-learn for model building:

Linear Regression

Random Forest Regressor

Gradient Boosting

Feature Engineering for extracting hour, day, month from datetime

Evaluation Metrics: RMSE, MAE, R² Score

🔍 Key Steps
Data Cleaning & Exploration

Feature Engineering

Exploratory Data Analysis (EDA)

Model Training & Evaluation

Model Comparison & Final Prediction

📈 Results
The best-performing model was able to predict bike rental demand with good accuracy. Visualizations of predicted vs actual values help understand model performance in depth.
