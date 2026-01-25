# Flight-Booking-price_prediction

Project Overview:
This project analyzes a flight booking dataset to predict ticket prices using machine learning algorithms. The dataset contains approximately 300,000 records with 11 attributes from a flight booking platform. Through exploratory data analysis, statistical methods, and machine learning models, we extract valuable insights to help passengers make informed booking decisions.

Problem Statement:
The objective is to analyze flight booking data and predict ticket prices by discovering patterns and relationships between various features such as airline, departure time, number of stops, travel class, and days left before departure. This analysis aims to provide passengers with insights that can help them find the best flight deals.

Dataset Information
The dataset contains the following features:

Airline: Name of the airline company
Flight: Plane's flight code
Source City: Departure city
Departure Time: Time of departure
Stops: Number of stops between source and destination
Arrival Time: Time of arrival
Destination City: Arrival city
Class: Seat class (Economy/Business)
Duration: Total travel time in hours
Days Left: Days remaining between booking and departure date
Price: Ticket price (Target variable)


**Tech Stack:**

Python: Programming language
Pandas & NumPy: Data manipulation and analysis
Matplotlib & Seaborn: Data visualization
Scikit-learn: Machine learning algorithms and preprocessing



**Methodology**

1. Data Preprocessing
Loaded the dataset and removed unnecessary columns
Checked for missing values and data types
Performed statistical analysis of the data


2. Exploratory Data Analysis (EDA)
Key findings from visualization:

Price varies significantly across different airlines
Ticket prices increase as departure date approaches (fewer days left)
Business class tickets are notably more expensive than Economy.
Price ranges differ based on source and destination cities.


3 .Feature Engineering

Applied One Hot Encoding for categorical features
Created correlation matrix to identify relationships between features
Used Variance Inflation Factor (VIF) for feature selection
Removed multicollinear features (VIF > 5)

Linear Regression
RMSE: 7259.93
MAPE: 34%
Baseline model for comparison

Decision Tree Regressor
RMSE: 3620
MAPE: 7.7%
Significant improvement over Linear Regression


**Results**

Random Forest Regressor achieved the best performance with MAPE of 7.3% and RMSE of 2824
The model successfully predicts flight prices with high accuracy
Key factors influencing price: days left before departure, airline, class, and route


Key Insights

Booking flights well in advance results in lower prices
Different airlines have varying pricing strategies
Business class tickets cost significantly more than Economy
Number of stops initially showed correlation but was removed due to multicollinearity



**Future Enhancements**

Incorporate additional features like seasonality and holidays
Experiment with ensemble methods and hyperparameter tuning
Deploy the model as a web application for real-time predictions
Add time-series analysis for price trends

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

NAME-SABYASACHI PALITA
EMAIL:sabyasachipalita2006@gmail.com
