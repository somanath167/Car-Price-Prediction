
**Car Price Prediction**
This project aims to predict the prices of used cars based on various features, such as the car's name, company, year of manufacture, kilometers driven, fuel type, and more. The goal is to create a machine learning model that can accurately estimate the selling price of a car using a dataset of historical car sales. The primary model used for prediction is Linear Regression.

**Dataset**
The dataset used in this project contains the following features:

name: The model name of the car
company: The manufacturer/brand of the car
year: The year of manufacture
price: The selling price of the car (target variable)
kms_driven: The total kilometers driven by the car
fuel_type: The type of fuel used (e.g., Petrol, Diesel, etc.)
Project Structure
data_preprocessing.ipynb: This notebook covers data cleaning, preprocessing, and exploratory data analysis (EDA).
model_training.ipynb: The notebook that contains the machine learning model training and evaluation.

**Key Steps**
1. Data Preprocessing
Handling missing values: Cleaning the dataset by addressing missing or erroneous data.
One-Hot Encoding: Converting categorical features (e.g., fuel type, company) into numerical form using one-hot encoding.
Feature Engineering: Extracting useful features such as car age from the 'year' column.
2. Exploratory Data Analysis (EDA)
Relationship Analysis: Plotting relationships between features like 'year', 'kms_driven', 'price', etc., using visualization libraries to understand data patterns.
3. Model Training
Train-Test Split: Splitting the dataset into training and testing sets to evaluate model performance.
Linear Regression Model: Applying Linear Regression to train the model on the training data.
Evaluation: Assessing model performance using metrics such as Mean Squared Error (MSE) and R² score.
