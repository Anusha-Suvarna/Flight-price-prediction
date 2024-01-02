<div >
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=40&pause=1000&color=B48FF7&random=false&width=460&height=70&lines=Flight+Price+Prediction "></div>

# Flight Price Prediction 

## Description
This project aims to predict flight prices based on various input parameters such as airline, date of journey, source, destination, duration, and other flight-related information. The predictive model utilizes historical flight data to forecast prices for future bookings.


## Table of Contents

- [Dataset](#Dataset)
- [Analysis Goals](#Analysis-Goals)
- [Project Structure](#Project-Structure)
- [Installation](#Installation)
- [Modeling](#Modeling)
- [How to Use](#How-to-Use)
- [Usage](#Usage)


## Dataset
##### The dataset used in this project comprises flight booking records with several columns:
##### https://github.com/Anusha-Suvarna/flight___price___prediction/tree/main/dataset
##### •	Records : Number of records in train dataset = 10683 , test dataset = 2671
### •	Features : 
1. Airline - The airline carrier for the flight.
2. Date_of_Journey - The date of the flight journey.
3. Source - The departure city.
4. Destination - The arrival city.
5. Route - Flight route information.
6. Dep_Time - Departure time of the flight.
7. Arrival_Time – Arrival time of the flight.
8. Duration – Flight duration.
9. Total_Stops - The number of stoppages during the flight.
10. Additional_Info - Extra flight-related information.
11. Price - Flight price in the respective currency. (dependent variable)

    
## Analysis Goals
-	Explore descriptive statistics of flight prices, durations, and popular routes
-	Identify patterns and trends in flight pricing and travel times
-	Compare flight options based on various criteria
-	Detect anomalies or outliers in the data
-	Generate informative visualizations to communicate findings
-	Build predictive models for future flight prices


## Project Structure:
#### The project is structured into different sections :
1. Data Preprocessing and Feature Engineering:  
  This section involves cleaning and preparing the dataset for model training. Tasks  include handling missing values, converting date and time columns, encoding categorical variables, and deriving new features if necessary.

2. Model Training: 
   The machine learning model is trained using the preprocessed dataset. This step involves selecting appropriate features, splitting the dataset into training and testing sets, and training the model using regression or another suitable algorithm.

3. Web Application Development:  
   The project includes a web interface built using HTML, CSS, and JavaScript (`index.html`). The backend of the web application is developed using Flask (`app.py`). This enables users to input flight parameters through the interface, and the trained model predicts the flight price based on these inputs.


## Installation
##### •	Jupyter Notebook 
##### •	PyCharm Community version 


## Modeling
### Models used and Accuracy results: 
1.  Extra Trees Regressor :   Accuracy 96.33%
2. 	Random Forest Regressor :   Accuracy 79.10%
3. 	Randomized Search CV :   Accuracy 79.83%
4. 	Cat Boost Regressor :   Accuracy 82.73%
5. 	LGBM Regressor :   Accuracy 80.30%
6. 	XG Boost Regressor :   Accuracy 82.12%


## How to Use
1.	Clone the repository: `git clone https://github.com/your_username/Flight-price-prediction.git`
2.	Navigate to the project directory:  `cd Flight-price-prediction`
3.	Install required libraries: pip install `pandas` `numpy` `matplotlib` `seaborn` `plotly` `sklearn flask`
4.	Run the analysis notebook: `jupyter notebook`  ([Project - Flight Price Prediction ,   By Anusha S Suvarna.ipynb](https://github.com/Anusha-Suvarna/flight___price___prediction/blob/main/Project%20-%20Flight%20Price%20Prediction%20%2C%20%20%20By%20Anusha%20S%20Suvarna.ipynb))
5.	Deployment and integration: Generating a `model.pkl` pickle file for the trained model and utilizing `Flask` to deploy the model as a web application, allowing users to input flight-related parameters for future prediction.


 ## Usage:
 1. Dataset Usage:
- Utilize the dataset Data_Train for training machine learning models aimed at predicting flight prices.
- Employ the data preprocessing steps outlined in the project to clean and prepare new flight data for analysis or model training.
- Utilize the dataset Test_set for testing machine learning models aimed at predicting flight prices.
2. Code Sections: 
- Run the data preprocessing section to clean and preprocess datasets.
- Train the model using the appropriate section for model building.
- Launch the web application section to deploy the trained model, enabling users to predict flight prices via a user-friendly interface.


