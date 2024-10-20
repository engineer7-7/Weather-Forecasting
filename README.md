Weather Forecasting with Linear Regression
Project Overview
This project focuses on predicting the mean temperature (meantemp) based on various weather-related features such as humidity, wind speed, mean pressure, and the date (year, month, and day). The machine learning model used for this project is Linear Regression, and we evaluate the performance of the model using metrics like Mean Squared Error (MSE).

Features
The dataset contains the following columns:

meantemp: The target variable, representing the mean temperature.
humidity: The relative humidity in percentage.
wind_speed: Wind speed in km/h.
meanpressure: The atmospheric pressure in millibars (mb).
year: Year of the recorded data.
month: Month of the recorded data.
day: Day of the recorded data.
Workflow
Data Preprocessing:

Features such as humidity, wind speed, mean pressure, and date (year, month, day) are used as input variables.
The target variable is the meantemp, which represents the mean temperature that we aim to predict.
Model Training:

We use Linear Regression from the scikit-learn library to train the model.
The dataset is split into training and test sets to evaluate the performance of the model on unseen data.
Evaluation:

We evaluate the model's performance using the Mean Squared Error (MSE), which measures the average squared difference between the predicted and actual temperature values.
