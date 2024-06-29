# stress level check!!
# Overview
This project analyzes a health-related dataset to understand various factors affecting individuals stress level. The dataset includes information such as sleep duration, physical activity levels, stress levels, BMI categories, and more.

# Dataset
Source: The dataset was obtained from kaggle

# Contents:
Columns: Occupation, Sleep Duration, Physical Activity Level, Stress Level, BMI Category, Heart Rate, Sleep Disorder, Systolic, Diastolic, and BP Category.

# Data Cleaning and Preprocessing
Columns like Person ID, Gender, and Quality of Sleep were removed for analysis purposes.
Blood Pressure was split into Systolic and Diastolic values, then categorized into BP Category.
Categorical variables like Occupation, BMI Category, Sleep Disorder, and BP Category were encoded for analysis.
# Exploratory Data Analysis (EDA)
Visualizations highlighted correlations between variables, such as stress levels varying by occupation and sleep duration impacting stress levels .
# Machine Learning Model
Model: Logistic Regression was chosen for its interpretability and achieved 91% accuracy after StandardScaler preprocessing.
Metrics: Accuracy was used to evaluate model performance on predicting health metrics based on input features.
# Results
Key findings include significant stress differences across occupations and the impact of sleep duration on stress levels.
Challenges included data cleaning complexities and ensuring model robustness.
Dependencies
Python 3.7+
pandas, numpy, scikit-learn for data manipulation and modeling.
Usage
Install Dependencies: pip install -r requirements.txt
Run the Code: Use Jupyter Notebook or any Python IDE to execute analysis.ipynb for detailed analysis steps.
