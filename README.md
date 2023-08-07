**Taxi Fare Estimation for NYC**

This repository contains the code and data used to build a regression model for estimating taxi fares in New York City (NYC). The model is developed using the 2017 Yellow Taxi Trip Data from the NYC Taxi and Limousine Commission (TLC).

**Project Overview:**
The goal of this project is to create a robust regression model that accurately predicts taxi fares based on various factors, such as trip distance, pickup and drop-off locations, tip amount, and pickup time. The model's performance is evaluated using metrics like Mean Squared Error and R-squared.

**Project Workflow:**
1. Data Preparation: Importing and inspecting the dataset to understand its structure, check for missing values, and handle data cleaning tasks.
2. Feature Engineering: Creating new features from existing ones, such as deriving pickup hour, month, and trip duration from timestamps.
3. Exploratory Data Analysis: Visualizing data to gain insights, analyze relationships between variables, and understand fare distribution patterns.
4. Model Building: Utilizing XGBoost regression to build a predictive model for taxi fares, selecting relevant features based on importance scores.
5. Hyperparameter Tuning: Performing grid search with cross-validation to optimize the model's hyperparameters for better performance.
6. Model Evaluation: Assessing the model's accuracy using metrics like Mean Squared Error and R-squared.

**Results:**
The final XGBoost regression model achieved a Mean Squared Error of 2.3392 and an R-squared of 0.8841, indicating accurate fare predictions. The top features influencing fare amounts were found to be trip distance, tip amount, and pickup hour.

**Conclusion:**
This project provides an effective taxi fare estimation model that can be utilized by stakeholders in the NYC taxi industry. By understanding the key factors affecting fare amounts, taxi companies and drivers can optimize pricing strategies and enhance customer experience.


![pexels-david-buchi-1054417](https://github.com/lacomaofficial/Taxi-Fare-Estimation-for-NYC-/assets/132283879/ffdf61f4-913a-4ae7-b660-fd3a84ed4d9b)
