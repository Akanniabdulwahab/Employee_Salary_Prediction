# Employee_Salary_Prediction

https://www.google.com/imgres?q=employee%20attribution&imgurl=http%3A%2F%2Fonline.hbs.edu%2FStyle%2520Library%2Fapi%2Fresize.aspx%3Fimgpath%3D%2FPublishingImages%2Fblog%2Fposts%2FOffice%2520with%2520Window.png%26w%3D1200%26h%3D630&imgrefurl=https%3A%2F%2Fonline.hbs.edu%2Fblog%2Fpost%2Fthe-fundamental-attribution-error&docid=GFipla5mHGsCwM&tbnid=D7UaPUqttLrqnM&vet=12ahUKEwitwvyPgYaIAxU2UUEAHQ8cC0MQM3oECGYQAA..i&w=1200&h=630&hcb=2&ved=2ahUKEwitwvyPgYaIAxU2UUEAHQ8cC0MQM3oECGYQAA

## Table of Cotents
- [Project Objective](#project-objective)
- [Data Overview](#data-overview)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-EDA)
- [Data Preprocessing](#data-preprocessing)
- [Machine Learning Models](#machine-learning-models)
- [Evaluation Metrics](#evaluation-metrics)
- [Recommendation](#recommendation)
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

## Recommendation
Continuous Improvement of model: Implement a feedback loop where the model can be continuously improved and updated with new data. This will ensure that the salary prediction system remains relevant and accurate over time.

## Conclusion
This project aims to provide a robust predictive model that accurately estimates employee salaries based on various factors, including education level, attributions, and other relevant features. By identifying and analyzing the key determinants of salary, the project will offer valuable insights into the relationship between employee characteristics and compensation. These insights can aid HR professionals in making data-driven decisions related to compensation strategies, employee retention, and talent management, ultimately contributing to a more informed and equitable workplace.
