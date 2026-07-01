# Data-Science-Final-Project
# PSX Stock Price Prediction and Analysis

This project performs Data Preprocessing, Exploratory Data Analysis (EDA), and Machine Learning-based regression modeling to analyze and predict stock prices using Pakistan Stock Exchange (PSX) data. 

The project evaluates multiple regression algorithms to find the best-performing model for continuous stock price prediction.

## Tech Stack and Libraries
The following Python libraries are used in this project:
* Data Manipulation: pandas, numpy
* Data Visualization: matplotlib, seaborn
* Machine Learning (Scikit-Learn):
    * train_test_split, StandardScaler, LabelEncoder
    * Models: LinearRegression, DecisionTreeRegressor, RandomForestRegressor, KNeighborsRegressor, GradientBoostingRegressor
    * Metrics: mean_absolute_error, mean_squared_error, r2_score

## Project Workflow

### 1. Data Cleaning and Preprocessing
* Handling missing values (null values treatment).
* Correcting data types (converting objects to numerical features where necessary).
* Feature encoding of categorical columns (Sector and Company Name) using LabelEncoder.

### 2. Exploratory Data Analysis (EDA)
* Visualizing stock trends, distributions, and correlation matrices using seaborn and matplotlib.
* Identifying key features influencing stock prices.

### 3. Feature Scaling and Split
* Splitting the dataset into an 80% Training set and a 20% Testing set.
* Standardizing features using StandardScaler to bring all numerical inputs to a uniform scale.

### 4. Model Training and Evaluation
We trained and evaluated five different regression models based on Mean Absolute Error (MAE), Mean Squared Error (MSE), and R2 Score:
* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor
* K-Neighbors Regressor
* Gradient Boosting Regressor

## Results and Conclusion
The models are ranked based on their R2 Score. The model with the highest R2 and lowest MAE/MSE is selected as the best predictor for PSX stock prices.
