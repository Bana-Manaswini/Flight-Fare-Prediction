✈️ Flight Fare Prediction using Machine Learning

This project predicts airline ticket prices based on various features such as airline, source, destination, duration, stops, and time using regression models. It leverages feature engineering, data visualization, and machine learning to build an accurate price prediction system.

📌 Objective
To build a machine learning model that predicts flight fares given various inputs such as airline, travel date/time, stops, source, and destination.

📁 Dataset

File: Flight_Fare.xlsx

Target Variable: Price

Features Used:
Airline
Source and Destination
Route
Total Stops
Duration
Date of Journey
Departure and Arrival Times

📊 Exploratory Data Analysis (EDA)
Handled null values and cleaned inconsistent duration formats.
Converted categorical variables using label encoding and one-hot encoding.
Created new features like journey day, month, and duration in minutes.

🧠 Machine Learning Models Used

Model	R² Score	RMSE

Linear Regression	~0.61	~2600, 

Decision Tree	~0.78	~2000, 

Random Forest	~0.85	~1600

✅ Random Forest Regressor performed the best based on evaluation metrics.

🛠 Tech Stack

Language: Python

Notebook: Jupyter Notebook

Libraries:

Pandas, NumPy (data manipulation)

Seaborn, Matplotlib (visualization)

Scikit-learn (ML models, preprocessing)
