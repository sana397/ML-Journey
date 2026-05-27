# Titanic EDA — Exploratory Data Analysis

## Project Overview
This project explores the Titanic passenger dataset 
to find patterns that determined survival.
Dataset: 891 passengers, 12 features.

## Key Findings

### 1. Survival Rate
Only 38% of passengers survived. 
The majority (62%) did not make it.

### 2. Gender and Survival
Women had a much higher survival rate than men.
This reflects the "women and children first" 
policy during the evacuation.

### 3. Passenger Class and Survival
Higher class passengers (1st class) survived more 
than lower class (3rd class).
Pclass had a correlation of -0.34 with survival.

### 4. Fare and Survival
Passengers who paid higher fares survived more.
Fare had a correlation of +0.26 with survival.
The fare distribution was heavily right skewed 
with outliers reaching £512.

### 5. Age Distribution
Most passengers were between 20-35 years old.
Age had minimal correlation with survival (-0.077).

### 6. Missing Data
- Age: 177 missing values (20%)
- Cabin: 687 missing values (77%)
- Embarked: 2 missing values

## What I Learned
- Real datasets always have missing values
- Outliers must be detected before training ML models
- Simple charts reveal powerful insights
- Correlation shows which features matter for prediction

## Tools Used
- Python, Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

## Connection to ML
These findings directly inform feature selection 
for a survival prediction model. Gender, Pclass 
and Fare are the strongest predictors of survival.