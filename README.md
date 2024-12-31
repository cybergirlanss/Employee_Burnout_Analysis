# Employee Burnout Analysis

# Project Overview

Employee burnout is a significant issue in the modern workplace, affecting both employee well-being and organizational productivity. This project uses machine learning regression techniques to predict employee burnout rates based on various factors such as workload, mental fatigue, job designation, and work-life balance.

By analyzing these factors, we aim to develop a predictive model to identify employees at risk of burnout. Organizations can use this model to take proactive measures to prevent burnout and promote a healthier work environment.

# Features

**Exploratory Data Analysis (EDA):**
Insights into the dataset using bar plots, histograms, pair plots, correlation heatmaps, and scatter plots.
**Regression Models Evaluated:**
Linear Regression (final deployed model).
K-Nearest Neighbors (KNN).
Support Vector Regression (SVR).
**Performance Metrics:**
Comprehensive evaluation using Mean Squared Error, Mean Absolute Error, Root Mean Squared Error, and R².
**Deployment:**
The Linear Regression model, with an R² score of 0.92, is deployed as the final predictive solution.

# Dataset

The dataset includes the following features:

**Employee ID:** Unique identifier for each employee.
**Date of Joining:** The date the employee joined the organization.
**Gender**:Male/Female.
**Company Type**: Service/Product.
**WFH Setup Available**: Yes/No.
**Designation**: Employee designation in the range [0.0, 5.0].
**Resource Allocation**: Working hours allocated to the employee, in the range [1.0, 10.0].
**Mental Fatigue Score**: Fatigue level, in the range [0.0, 10.0].
**Burn Rate**: Target variable, representing the rate of burnout, in the range [0.0, 1.0].

# Installation
1. clone the repository:
   ```git clone https://github.com/yourusername/employee-burnout-analysis.git
      cd employee-burnout-analysis
```
3. 
