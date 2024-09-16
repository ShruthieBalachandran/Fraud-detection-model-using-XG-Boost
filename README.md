**Fraud Detection Project:**

**Overview:**
This project implements a fraud detection system using machine learning techniques. 
The system utilizes XGBoost for classification, PCA for dimensionality reduction, and various preprocessing steps to handle missing values, outliers, and categorical variables. 
The goal is to accurately detect fraudulent transactions from a financial dataset.

**Project Structure:**

1. fraud_detection.py: The main script that includes data cleaning, preprocessing, model training, and evaluation.
2. Fraud.csv: The dataset used for training and testing the model.
3. requirements.txt: A file listing the Python packages required for running the project.

**Prerequisites:**
Make sure you have Python installed along with the necessary packages. You can install the required packages using pip.

Install Dependencies: pip install -r requirements.txt

Dataset:
The dataset used in this project is Fraud.csv, which contains information about transactions including various features and the target variable isFraud.

**Features:**
1. Data Cleaning: Handles missing values, outliers, and performs feature engineering.
2. Preprocessing: Includes one-hot encoding of categorical variables, standardization, and dimensionality reduction using PCA.
3. Model: Uses XGBoost for classification, with hyperparameter tuning performed using RandomizedSearchCV.
4. Evaluation: Provides classification report, confusion matrix, ROC AUC score, and feature importance.

**Run the Script:**

Execute the fraud_detection.py script using Python:
python fraud_detection.py

**This will perform the following:**
1. Load and clean the dataset.
2. Preprocess the data, including scaling and PCA.
3. Train the XGBoost model with hyperparameter tuning.
4. Evaluate the model and print performance metrics and feature importances.
   
**Code Explanation:**
1. Data Cleaning: Handles missing values and outliers. New features are engineered to enhance fraud detection capabilities.
2. Preprocessing: Standardizes data and applies PCA to reduce dimensionality.
3. Model Training: Uses XGBoost with hyperparameter tuning to find the best model.
4. Evaluation: Outputs performance metrics including classification report, confusion matrix, and ROC AUC score.
