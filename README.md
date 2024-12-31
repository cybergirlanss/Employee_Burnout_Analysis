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
   ```
      git clone https://github.com/cybergirlanss/Employee_Burnout_Analysis.git
      cd employee-burnout-analysis```
2. Install the required libraries:
   ```
      pip install -r requirements.txt
    ```

 # Usage

**Exploratory Data Analysis**:
Run the script eda.py to generate visualizations like bar plots, histograms, pair plots, and correlation heatmaps.
**Model Training and Evaluation**:
Use train_model.py to train Linear Regression, KNN, and SVR models.
Evaluate models using performance metrics like MSE, RMSE, and R².
**Prediction**:
Run predict.py to use the Linear Regression model for predicting burnout rates on new data.

# Results

**Final Model**: Linear Regression
**Performance Metrics**:
Mean Squared Error (MSE): 0.0031
Root Mean Squared Error (RMSE): 0.0562
Mean Absolute Error (MAE): 0.0460
R-squared Score (R²): 0.9188
**Insights from EDA**:
Burnout is strongly correlated with Mental Fatigue Score and Resource Allocation.
Employees with limited WFH access show higher burnout rates.

**Future Scope**

Incorporate real-time data streams for continuous monitoring of employee burnout.
Develop an interactive dashboard for HR professionals to visualize predictions.
Include qualitative data, such as employee feedback and surveys, to improve model accuracy.


