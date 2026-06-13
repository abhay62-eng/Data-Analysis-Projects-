
# Titanic Dataset Analysis

## Overview
This project performs Exploratory Data Analysis (EDA) on the Titanic dataset using Python, Pandas, NumPy, Matplotlib, and Seaborn.

Dataset: `tested.csv`

## Objectives
- Understand dataset structure and data types
- Identify missing values and their percentages
- Analyze passenger survival distribution
- Explore age distribution
- Compare survival across:
  - Gender (Sex)
  - Passenger Class (Pclass)
  - Embarkation Port (Embarked)
- Study correlations among numerical features
- Visualize relationships using pairplots and heatmaps

## Dataset Information
- Rows: 418
- Columns: 12

### Features
- PassengerId
- Survived
- Pclass
- Name
- Sex
- Age
- SibSp
- Parch
- Ticket
- Fare
- Cabin
- Embarked

## Analysis Performed
1. Basic dataset inspection (`shape`, `info`, `dtypes`, `head`)
2. Missing value analysis
3. Missing-value heatmap
4. Survival count analysis
5. Survival bar chart
6. Age distribution visualization
7. Categorical feature analysis (Sex, Pclass, Embarked)
8. Correlation matrix and heatmap
9. Pairplot visualization

## Libraries Used
- pandas
- numpy
- matplotlib
- seaborn

## Run
```bash
pip install -r requirements.txt
jupyter notebook
```
