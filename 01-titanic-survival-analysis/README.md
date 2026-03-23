# Titanic Survival Analysis

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-blue)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-purple)

## Overview

Data Storytelling: Analysing Survival on the Titanic

This project performs Exploratory Data Analysis (EDA) on the Titanic dataset to understand the factors influencing passenger survival. The analysis includes data inspection, cleaning, visualization, and identifying meaningful patterns in the dataset. EDA helps uncover relationships between variables such as age, gender, passenger class, fare, and survival rate.

## Objectives

- Understand the structure and distribution of the Titanic dataset
- Identify and handle missing values
- Analyze survival patterns across different features
- Visualize relationships between variables
- Extract meaningful insights from the dataset

## Dataset

Source: Kaggle Titanic Dataset  

https://www.kaggle.com/c/titanic/data

## Project Structure

```
01-titanic-survival-analysis/
│── README.md
│── requirements.txt
│── titanic-dataset.csv
└── titanic-survival-analysis.ipynb
```

## Tech Stack

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Key Techniques Used

### Data Preprocessing
- Handling missing values
- Encoding categorical variables
- Feature engineering (Title extraction, FamilySize)
- Feature scaling

### Exploratory Data Analysis
- Survival distribution analysis
- Correlation analysis
- Visualization using Matplotlib and Seaborn

### Machine Learning Models
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)

### Model Evaluation
- Train-validation split
- Accuracy score
- Confusion matrix
- Cross-validation

## Key Insights
- Female passengers had higher survival rates.
- First-class passengers were more likely to survive.
- Age and fare influenced survival probability.
- Random Forest achieved the best performance among tested models.

## How to Run

1. Clone the Repository

   git clone https://github.com/VarshaNayak18/Machine-Learning-Projects.git
   
   cd Machine-Learning-Projects/01-titanic-survival-analysis

2. Install Dependencies

   pip install -r requirements.txt

3. Run the Notebook

## Future Improvements
- Implement XGBoost or LightGBM
- Build a Streamlit web app for predictions
- Perform hyperparameter tuning
- Apply ensemble learning techniques
- Create an interactive dashboard
- Deploy the model using Flask or FastAPI
- Experiment with neural networks