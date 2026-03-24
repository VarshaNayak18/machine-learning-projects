# Netflix Content Analysis

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-yellow)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-lightblue)
![WordCloud](https://img.shields.io/badge/WordCloud-Text%20Visualization-green)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-red)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

## Overview

Cracking the Code: An Inside look at Netflix's Content Strategy

This project performs an Exploratory Data Analysis (EDA) on the Netflix Movies and TV Shows dataset to uncover patterns in content distribution, ratings, production trends, and textual descriptions.
The analysis focuses on understanding how Netflix’s catalog has evolved over time using data cleaning, visualization, and text analysis techniques.

## Objectives

- Analyze the distribution of Movies vs TV Shows
- Study content ratings trends over time
- Examine the relationship between release year and year added to Netflix
- Identify top directors on the platform
- Extract most common words and phrases from content descriptions
- Perform time-series analysis on Netflix content growth

## Dataset

Netflix Movies and TV Shows Dataset (Kaggle)

https://www.kaggle.com/datasets/shivamb/netflix-shows

## Project Structure

```
02-netflix-content-analysis/
│── titanic-survival-analysis.ipynb
│── titanic-dataset.csv
│── README.md
└── requirements.txt
```

## Tech Stack

- Python
- Pandas
- Matplotlib
- Seaborn
- WordCloud
- Jupyter Notebook


## Core Concepts

1. Data Cleaning & Transformation: Handling missing values and converting data types.

2. Time-Series Analysis: Analyzing how content has been added to Netflix over the years.

3. Text Data Manipulation: Parsing and analyzing columns with multiple values.

4. Geographical & Rating Analysis: Understanding where content comes from and its maturity level.

5. Feature Engineering: Creating new, insightful features.

6. Advanced Visualization: Creating insightful plots to understand distributions and      relationships in the data.

## Key Insights

1. Movies make up the majority of Netflix content, though TV Shows have steadily increased.
2. Mature-audience content (TV-MA) has grown significantly in recent years.
3. TV Shows are typically added to Netflix soon after release, while Movies are often older when added.
4. Certain directors appear frequently due to multiple contributions to Netflix content.
5. Common description themes include family, love, young, life, crime, and friendship.
6. Netflix has increasingly focused on recent productions and original content.

## How to Run

1. Clone the Repository

   git clone https://github.com/VarshaNayak18/Machine-Learning-Projects.git
   
   cd Machine-Learning-Projects/02-netflix-content-analysis

2. Install Dependencies

   pip install -r requirements.txt

3. Run the Notebook

## Future Improvements

- Build a recommendation system
- Perform sentiment analysis on descriptions
- Predict content popularity using machine learning
- Create an interactive dashboard