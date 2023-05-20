# Uber Fare Price Prediction
This project focuses on predicting Uber fare prices using machine learning techniques. The goal is to develop a model that accurately estimates the fare amount based on various input features.

### Dataset
The dataset used for this project contains the following columns:

* Unnamed: 0: Index column
* key: Unique identifier for each Uber trip
* fare_amount: Fare amount (target variable)
* pickup_datetime: Date and time of the trip
* pickup_longitude: Longitude of the pickup location
* pickup_latitude: Latitude of the pickup location
* dropoff_longitude: Longitude of the dropoff location
* dropoff_latitude: Latitude of the dropoff location
* passenger_count: Number of passengers
* Preprocessing and Feature Engineering
* The following preprocessing steps and feature engineering techniques were applied to the dataset:
![image](https://github.com/Aftabbs/Uber-Fare-Price-Prediction/assets/112916888/d0f96582-b515-4006-9fe6-df98f25d2956)

Cleaning: Any missing or irrelevant data was removed or filled appropriately.

# Feature Engineering:
Distance Travelled: Calculated the distance between pickup and dropoff coordinates using appropriate formulas.
Extracted additional temporal features from the pickup_datetime column, such as month, year, day of the week, and pickup hour.
![image](https://github.com/Aftabbs/Uber-Fare-Price-Prediction/assets/112916888/b242aa0c-2462-4ccc-8cdc-e9840e219955)

Exploratory Data Analysis

Performed exploratory data analysis to gain insights into the dataset and the relationship between different variables. Some of the aspects visualized include:
![image](https://github.com/Aftabbs/Uber-Fare-Price-Prediction/assets/112916888/2dace326-eea3-4744-80f0-074bcf20e769)

Analysis of fare_amount with respect to time and date, month, etc.
Relationship between passenger_count and fare_amount.
![image](https://github.com/Aftabbs/Uber-Fare-Price-Prediction/assets/112916888/6062442f-8317-4474-b399-057cb1ae40b1)

Distribution of the distance_travelled feature.
# Regression Models
Built multiple regression models to predict the fare_amount:

* Linear Regression: A basic linear regression model.
* Random Forest Regression: Utilized the Random Forest algorithm for improved accuracy.
* XGBoost Regression: Employed XGBoost, a powerful gradient boosting algorithm.
* Decision Tree Regression: Implemented a decision tree-based regression model.

# Model Evaluation and Tuning
Evaluated the performance of each regression model using the following metrics: RMSE (Root Mean Squared Error), MAE (Mean Absolute Error), and MSE (Mean Squared Error). Identified Random Forest Regression as the best-performing model based on the evaluation metrics.
![image](https://github.com/Aftabbs/Uber-Fare-Price-Prediction/assets/112916888/448eb96c-0ba0-4dd7-aabf-bdc31043c0b3)

Performed hyperparameter tuning on the Random Forest Regression model to optimize its performance further. Notable improvements were observed after tuning the model.

# Industrial Use Case
This project demonstrates the application of machine learning techniques to predict Uber fare prices. The developed model can be used by Uber or similar ride-sharing companies to estimate fare amounts for their customers. This prediction can help improve pricing strategies, enhance customer satisfaction, and optimize business operations.

* Dependencies
List the dependencies required to run the project. Include libraries and their versions used in the project.

* Usage
Provide instructions on how to run the project and reproduce the results. Include any necessary steps or commands.

# Conclusion
Summarize the project, its objectives, and the key findings. Discuss the performance of the best model and its potential real-world applications. Highlight any future work or improvements that can be made.

Feel free to modify and expand upon this template based on your specific project details and findings. Add relevant visuals, code snippets, and explanations to make the README.md file informative and engaging.





