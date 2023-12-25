# Flight Price Prediction Project

## Description
This project aims to predict flight prices based on various input parameters such as airline, date of journey, source, destination, duration, and other flight-related information. The predictive model utilizes historical flight data to forecast prices for future bookings.

## Dataset
##### The dataset used in this project comprises flight booking records with several columns:
##### •	Source: Downloaded from the internet (https://github.com/Anusha-Suvarna/flight___price___prediction/tree/main/dataset)
##### •	Records: Number of records in train dataset = 10683 , test dataset = 2671
#### •	Features: 
##### o	Airline - The airline carrier for the flight.
##### o	Date_of_Journey - The date of the flight journey.
##### o	Source - The departure city.
##### o	Destination - The arrival city.
##### o	Route - Flight route information
##### o	Dep_Time - Departure time of the flight.
##### o	Arrival_Time – Arrival time of the flight
##### o	Duration – Flight duration
##### o	Total_Stops - The number of stoppages during the flight.
##### o	Additional_Info - Extra flight-related information.
##### o	Price - Flight price in the respective currency. (dependent variable)
## Analysis Goals
•	Explore descriptive statistics of flight prices, durations, and popular routes
•	Identify patterns and trends in flight pricing and travel times
•	Compare flight options based on various criteria
•	Detect anomalies or outliers in the data
•	Generate informative visualizations to communicate findings
•	Build predictive models for future flight prices

##Project Structure:
The project is structured into different sections:
1. **Data Preprocessing and Feature Engineering: **  
  This section involves cleaning and preparing the dataset for model training. Tasks may include handling missing values, converting date and time columns, encoding categorical variables, and deriving new features if necessary.

2. **Model Training: **  
   The machine learning model is trained using the preprocessed dataset. This step involves selecting appropriate features, splitting the dataset into training and testing sets, and training the model using regression or another suitable algorithm.

3. **Web Application Development: **  
   The project includes a web interface built using HTML, CSS, and JavaScript (`index.html`). The backend of the web application is developed using Flask (`app.py`). This enables users to input flight parameters through the interface, and the trained model predicts the flight price based on these inputs.

## Installation
•	Jupyter Notebook 
•	PyCharm Community version 
## Modeling
•	Models used and Accuracy results: 
o	Extra Trees Regressor:  Accuracy 96.33%
o	Random Forest Regressor:  Accuracy 79.10%
o	Randomized Search CV:  Accuracy 79.83%
o	Cat Boost Regressor:  Accuracy 82.73%
o	LGBM Regressor:  Accuracy 80.30%
o	XG Boost Regressor:  Accuracy 82.12%

## How to Use
1.	Clone the repository
2.	Install required libraries: pip install -r requirements.txt (as mentioned in Project - Flight Price Prediction ,   By Anusha S Suvarna)
3.	Run the analysis notebook: jupyter notebook (Project - Flight Price Prediction ,   By Anusha S Suvarna.ipynb)

 ## Usage:
1. **Dataset Usage: **  
        - Utilize the dataset Data_Train for training machine learning models aimed at predicting flight prices.
        - Employ the data preprocessing steps outlined in the project to clean and prepare new flight data for 
analysis or model training.
        - Utilize the dataset Test_set for testing machine learning models aimed at predicting flight prices.

2. **Code Sections: **  
        - Run the data preprocessing section to clean and preprocess datasets.
        - Train the model using the appropriate section for model building.
        - Launch the web application section to deploy the trained model, enabling users to predict flight prices via a user-friendly interface.

