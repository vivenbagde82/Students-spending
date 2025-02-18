# Students Spending Analytics

This project focuses on analyzing the spending habits of students. The analysis involves cleaning the data, visualizing various aspects of the data, and applying statistical models to draw insights.

## Table of Contents
- [Introduction](#introduction)
- [Data Cleaning](#data-cleaning)
- [Data Visualization](#data-visualization)
- [Statistical Analysis](#statistical-analysis)
- [Conclusion](#conclusion)
- [How to Run the Project](#how-to-run-the-project)
- [References](#references)

## Introduction
The aim of this project is to analyze the spending patterns of students and understand the relationships between different spending categories. The project involves data cleaning, aggregation, visualization, and statistical modeling to uncover insights.

## Data Cleaning
The data was first cleaned by handling missing values and changing datatypes to ensure consistency and accuracy for analysis.

## Data Visualization
The visualization process included:
- Aggregating value counts of categorical columns.
- Plotting graphs to understand the distribution of each column.
- Plotting side-by-side boxplots for monthly income, financial aid, tuition, housing, and food.
  - **Inference:** Tuition is where students spend the highest.
- Plotting a combined graph with a bar graph for tuition and a line graph for financial aid.

## Statistical Analysis
- **Linear Regression Model:**
  - **Features (X):** `[['financial_aid', 'monthly_income', 'books_supplies', 'personal_care', 'entertainment', 'tuition', 'housing', 'food', 'transportation', 'miscellaneous']]`
  - **Target (y):** `['health_wellness']`
  - Studied the coefficients (`coef_`) and their relationships.

- **OLS Model:**
  - Calculated R-square and Adjusted R-square metrics.
  - **Conclusion:** The model is a very poor fit due to very low metric values.

## Conclusion
This project provides insights into students' spending habits and highlights the importance of understanding financial priorities. The analysis shows that tuition is a significant expense for students, and the linear regression model indicates that the selected features are not good predictors of health and wellness spending.

## How to Run the Project
1. Clone the repository: `git clone <repository-url>`
2. Install the required dependencies: `pip install -r requirements.txt`
3. Run the data cleaning script: `python data_cleaning.py`
4. Run the data visualization script: `python data_visualization.py`
5. Run the statistical analysis script: `python statistical_analysis.py`
