# Prediction of Voluntary Employee Attrition

Project Overview
This project aims to predict voluntary employee attrition using machine learning techniques. By analyzing employee data, the model identifies key factors that influence voluntary turnover, helping organizations proactively implement retention strategies. The project employs various data preprocessing techniques, feature selection methods, and multiple machine learning algorithms to build a robust predictive model.

Key Features
Exploratory Data Analysis (EDA): Understanding the distribution and relationship of variables such as salary, work tenure, and employee benefits.
Feature Selection: Selection of key features using Pearson correlation and Chi-square tests to enhance model performance.
Modeling: Development of machine learning models including Support Vector Machine (SVM), Decision Tree, and Logistic Regression, combined using a Soft Voting Classifier to improve predictive accuracy.
Performance Evaluation: Evaluation of model performance based on accuracy, precision, recall, and F1-score using cross-validation.
Dataset
The dataset consists of employee information from various categories including:

Salary and Benefits
Distance from Work
Position and Work Tenure
Marital Status and Educational Background
The data was processed to remove missing values, handle outliers, and standardize the format.

Project Structure
The project is divided into the following sections:

Exploratory Data Analysis (EDA):

Understand the distribution and relationships between variables.
Visualize key trends using plots and charts.
Feature Selection:

Selection of relevant features using Pearson correlation and Chi-square tests.
Data Preprocessing:

Handling missing values and outliers.
Feature scaling and encoding categorical variables.
Modeling:

Train and compare models such as Support Vector Machine (SVM), Decision Tree, and Logistic Regression.
Implement a Soft Voting Classifier for ensemble learning.
Model Evaluation:

Evaluate model accuracy, precision, recall, and F1-score.
Cross-validation to ensure model robustness.
Dependencies
The following libraries are required to run this project:

pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
