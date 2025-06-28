# ElevateLabs_task4
# Logistic Regression on Diabetes Dataset
This project demonstrates the process of building a Logistic Regression model to predict whether a person has diabetes based on various medical predictor variables. The analysis is performed using the well-known Diabetes dataset from the National Institute of Diabetes and Digestive and Kidney Diseases, commonly found on Kaggle.

## Project Overview
- **Goal:** Predict diabetes occurrence using patient data with Logistic Regression.
- **Dataset:** Sourced from [Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database) (Pima Indians Diabetes Dataset).
- **Tech stack:** Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Plotly.

## Notebook Structure
1. **Problem Statement**
   - Build a model to predict diabetes status given medical input features.
2. **Data Collection & Import**
   - Reads the CSV dataset into a pandas DataFrame.
   - Data preview using `head()` and `tail()`.
3. **Data Cleaning**
   - Checks for null values and duplicates.
   - Confirms data types and dataset shape.
   - Verifies the absence of missing or duplicate records.
4. **Exploratory Data Analysis (EDA)**
   - Examines columns, data types, and memory usage.
   - Provides a statistical summary of the dataset.
   - Feature information:
     - Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age, Outcome (target).
5. **Model Building**
   - Data preprocessing (scaling, train-test split).
   - Logistic Regression model training.
   - Model evaluation using accuracy, confusion matrix, ROC curves, and AUC.
6. **Visualization**
   - Uses Matplotlib, Seaborn, and Plotly for insights and results visualization.
