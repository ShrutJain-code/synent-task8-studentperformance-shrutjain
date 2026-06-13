# Student Performance Prediction using Machine Learning

## Problem Statement

Student performance depends on different academic and lifestyle factors such as study hours, previous scores, sleep hours, extracurricular activities, and practice. The objective of this project is to build a machine learning model that predicts a student's performance index using these factors.

## Dataset

The Student Performance Dataset contains information about students and their academic habits. The dataset includes:

* Hours Studied
* Previous Scores
* Extracurricular Activities
* Sleep Hours
* Sample Question Papers Practiced
* Performance Index

The target variable for prediction is Performance Index.

## Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

## Approach

### 1. Data Loading

Loaded the dataset using Pandas.

### 2. Data Cleaning

Checked missing values, duplicate records, and cleaned column names.

### 3. Data Preprocessing

Converted categorical values into numerical format using Label Encoding.

### 4. Exploratory Data Analysis

Created visualizations to understand feature relationships and data distribution.

### 5. Feature Selection

Selected input features and target variable for prediction.

### 6. Train-Test Split

Split the dataset into training and testing sets.

### 7. Model Training

Trained three machine learning models:

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor

### 8. Model Evaluation

Evaluated models using RMSE and R² Score.

## Results

The models were compared based on RMSE and R² Score. The best model was selected using lower RMSE and higher R² Score.

## Key Insights

* Previous scores and hours studied are important factors in predicting student performance.
* RMSE helps measure how far predictions are from actual values.
* R² Score shows how well the model explains the target variable.
* Machine learning can be useful for estimating student performance.
* The project demonstrates regression modeling on real-world educational data.

## Conclusion

This project successfully builds and evaluates machine learning models for student performance prediction. The final model can predict performance index based on student-related features and shows how machine learning can support data-driven educational analysis.

## Author

Shrut Jain

Data Science Internship Program – Synent Technologies
