# House Price Prediction Project

This project demonstrates the use of linear regression to predict house prices based on various features, including square footage, number of bedrooms and bathrooms, location, etc. The dataset used is from the Zillow Zestimate Kaggle dataset.

---

## Problem Statement

The goal is to develop a linear regression model that accurately predicts house prices based on given features.  
Performance is evaluated using metrics such as:  
- **Mean Squared Error (MSE)**  
- **R-squared**

---

## Dataset

The dataset consists of the following files:  
- **`train.csv`**: Used for training the model.  
- **`test.csv`**: Used for evaluating the model.  
- **`data_description.txt`**: Contains details about the features in the dataset.

---

## Steps Performed

### 1. Data Loading
- Loaded training and test datasets using `pandas`.

### 2. Data Preprocessing
- **Handled Missing Values**:
  - Filled numeric columns with mean values.
  - Filled categorical columns with mode values.
- Converted categorical variables into numerical values using `LabelEncoder`.

### 3. Feature Scaling
- Used `StandardScaler` to normalize numeric features.

### 4. Model Building
- Built a linear regression model using `scikit-learn`.
- Trained the model on the preprocessed training dataset.

### 5. Evaluation
- Evaluated model performance on the test dataset using:
  - **Mean Squared Error (MSE)**  
  - **R-squared**

---

## How to Run the Code

1. **Clone the repository:**
    ```bash
    git clone https://github.com/sushant1217/ML_Assignment_01.git
    ```

2. **Navigate to the project directory:**
    ```bash
    cd ML_Assignment_01
    ```

3. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Python script:**
    ```bash
    python house_price_prediction.py
    ```

## Results

- **Mean Squared Error (MSE):** 873726843.7410611
- **R-squared Score:** 0.8860900018929605

 ## Dependencies

- **Python 3.x**
- **Pandas**
- **Numpy**
- **Scikit-learn**
