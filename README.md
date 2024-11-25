# House Price Prediction Project
This project demonstrates the use of linear regression to predict house prices based on various features, including square footage, number of bedrooms and bathrooms, location, etc. The dataset used is from the Zillow Zestimate Kaggle dataset.

# Problem Statement
The goal is to develop a linear regression model that accurately predicts house prices based on given features. Performance is evaluated using metrics such as Mean Squared Error (MSE) and R-squared.

# Dataset
The dataset consists of:

train.csv: Used for training the model.
test.csv: Used for evaluating the model.
data_description.txt: Contains details about the features in the dataset.

# Steps Performed
Data Loading:

Loaded training and test datasets using pandas.
Data Preprocessing:

# Handled missing values:
Filled numeric columns with mean values.
Filled categorical columns with mode values.
Converted categorical variables into numerical using LabelEncoder.
Feature Scaling:

Used StandardScaler to normalize numeric features.
Model Building:

Built a linear regression model using scikit-learn.
Trained the model on the preprocessed training dataset.
Evaluation:

Evaluated model performance on the test dataset using:
Mean Squared Error (MSE)
R-squared

# How to Run the Code
Clone the repository:
bash
Copy code
git clone https://github.com/sushant1217/ML_Assignment_01.git
$ Navigate to the project directory:
Copy code
$ cd ML_Assignment_01
Install dependencies:
$ pip install -r requirements.txt
Run the Python script:
$ python house_price_prediction.py

# Results
Mean Squared Error (MSE): 873726843.7410611
R-squared Score: 0.8860900018929605

# Project Structure
ML_Assignment_01/
├── data_description.txt   # Dataset description
├── train.csv              # Training dataset
├── test.csv               # Test dataset
├── house_price_prediction.py # Main script
├── README.md              # Project documentation
└── requirements.txt       # Required Python packages

# Dependencies
Python 3.x
Pandas
Numpy
Scikit-learn
