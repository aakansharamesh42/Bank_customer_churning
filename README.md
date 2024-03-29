# README for Bank Customer Churn Prediction Project

## Introduction

This project focuses on the banking sector, aiming to predict customer churn based on historical data. Understanding and preventing customer churn is crucial for maintaining business and customer relationships. Additionally, identifying potential defaulters allows for preemptive actions to prevent financial losses.

## Problem Statement

The objective is to analyze and predict whether a bank customer will churn, utilizing previous customer data. By identifying the factors contributing to customer churn, banks can implement targeted strategies to retain their clientele.

## Key Objectives

1. **Identify and Visualize Contributing Factors**: Determine and illustrate the variables that lead to customer churn.
2. **Build a Prediction Model**:
   - Classify customers into churners and non-churners.
   - Attach a probability score to the churn prediction to prioritize customer service interventions.

## Methodology

### Data Analysis

Investigate the dataset to understand the demographics and behaviors of the customers, especially focusing on churned customers. Key factors include gender, credit card ownership, and account activity levels.

### Model Selection

The project utilizes the Random Forest algorithm, a Supervised Machine Learning technique, known for its effectiveness in Classification and Regression problems. It combines multiple decision trees to improve classification accuracy and prevent overfitting.

### Analysis of Results

Findings from the analysis indicate:
- A higher churn rate among customers with lower population densities.
- Female customers exhibit a higher churn rate than male customers.
- Customers possessing credit cards and those less active are more likely to churn.

## Conclusion

The Random Forest model demonstrates higher precision in predicting customer churn (class 1). Although the model shows high accuracy, it still fails to identify approximately half of the customers at risk of churning. Improvements can be made by retraining the model with updated data and leveraging current predictions to retain at-risk customers.

## Installation and Setup

1. Clone the repository to your local machine.
2. Ensure Python and necessary libraries (pandas, numpy, scikit-learn, matplotlib, seaborn) are installed.
3. Run the Jupyter notebooks to train the model and make predictions.

## Usage

- Analyze the provided Jupyter notebooks to understand the data processing and model training steps.
- Utilize the model to predict churn on new customer data.
- Apply the insights from the data analysis to devise customer retention strategies.
