# Employee_Salary_Prediction

![image](https://github.com/user-attachments/assets/d5bb8ae9-0e3c-48a1-9bfd-06625254218f)

## Table of Cotents
- [Project Objective](#project-objective)
- [Data Overview](#data-overview)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-EDA)
- [Data Preprocessing](#data-preprocessing)
- [Machine Learning Models](#machine-learning-models)
- [Evaluation Metrics](#evaluation-metrics)
- [Conclusion](#conclusion)

## Project Objective
The primary objective of this project is to develop a predictive model that estimates employee salaries based on a range of features, including the level of education, attribution types, and other relevant factors present in the dataset. Additionally, we aim to identify and analyze the key factors that significantly influence an employee’s salary. Through this analysis, we seek to provide valuable insights that can help HR professionals make informed decisions regarding compensation and employee management.

## Data Overview
This involved importing the dataset, ivestigated if the features are in their correct datatypes, converting features into their correct datatypes, checked the shape of the dataset, investigated the missing values, visualizing the missing values, performed statistical analysis of numerical & categorical datapoints.

## Exploratory Data Analysis (EDA)
- Univariate Analysis: Exploring each features individually.
- Bivariate Analysis: Exploring each features against the profit feature.
- Multivariate Analysis: Exploring two or more features against the profit feature.

## Data Preprocessing
Extensive data-preprocessing was performed. This included handling missing values, droppig off redundant features, adding extra features for better analysis, encoded the categorical features in the data, scaled the dataset. 

## Machine Learning Models
The employee salary prediction model is built using a supervised machine learning approach. Training and test data was split 80:20. Several algorithms were experimented
- **Linear Regression**
- **DecisionTree Regressor**
- **Support Vector Regression (SVR)**
- **GradientBoosting Regressor**

After several experimentation and hyperparameter tuning, the best performing model was selected.

## Evaluation Metrics
To assess the performance of a machine learning model, the following evaluation metrics were used:
- **R-Squared score**
- **Mean square score**
- **RMSE score**

## Conclusion
This project aims to provide a robust predictive model that accurately estimates employee salaries based on various factors, including education level, attributions, and other relevant features. By identifying and analyzing the key determinants of salary, the project will offer valuable insights into the relationship between employee characteristics and compensation. These insights can aid HR professionals in making data-driven decisions related to compensation strategies, employee retention, and talent management, ultimately contributing to a more informed and equitable workplace.
