# EmployeeTurnover-TechInnovations
Tech innovations Inc. is a leading technology company at the forefront of digital transformation and innovation whose objective is to develop predictive models and actionable insights that will enhance employee recruitment and retention strategies using HR data and Advance Analytics

![image](https://github.com/uzilon/CustomerChurnPrediction/assets/111258660/e3c0bb5e-0a36-4494-b0b5-2f39685558f9)


## Table of contents
- [Project Overview](#project-overview)
- [Project Objective](#project-objective)
- [Data Sources](#data-sources)
- [Data Cleaning](#data-cleaning)
- [Explorative Data Analysis and Insights](#explorative-data-analysis-&-insights)
- [Data Preprocessing](#data-preprocessing)
- [Machine Learning](#machine-learning)
- [Evaluation Metrics](#evaluation-metrics)
- [Conclusion and Recommendation](#conclusion-and-recommendation)


## Project Overview

Tech Innovations Inc is experiencing high turnover rates and struggles to attract and retain top talent in key positions. 

## Project Objective

This project aims to is to leverage HR data and advanced analytics to develop predictive models and actionable insights that will enhance employee recruitment and retention strategies

## Data Sources 

The dataset used in this project was provided by Tech Innovations Inc. The Dataset contains a collection of 1000 Records and 19 features 

## Data Cleaning

Dataset was clean, There were no missing data, however Satisfaction_Score had 13 Outliers which were removed during preprocessing in preparation for machine learning

## Exploratory Data Analysis & Insights
- Total number of employees was 1000 
- Average Age of Employees was 43
- Turnover rate was 19.3%
- Average yearly Salary was $74,000 with $30,287 and 119,954 as minimum and maximum respectively.
- Average Tenure is 14 years
- Employee Turnover correlates with Job Satisfaction inversely, i.e, Employee Turnover increased with low Job Satisfaction
- Employee Turnover was much more with employees with newer employees than older ones
- Although employee turnover was more for employees in the low salary class, data shows it takes a longer time for employees to be promoted

## Data Preprocessing

Label Encoding was carried out on all Categorical Variable. Feature Engineering was carried out and 10 new features were added, making it a total of 29 features in which they were all standardized. Data was split into train and test data in a ratio of 80 20 However 5 features were rejected as they had anomalies Thus, 24 Features were used to train and test data. 

## Machine Learning 

Dataset was trained on the following six models 
- Random Forest
- XG Boost
- SGD  
- SVM
- Decision Tree
- Logistic Regression

Feature Importance was carried out and the top five features having two of the Engineered features. Hyper parametric finetuning of the decision tree model (Best Model) was carried out.

## Evaluation Metrics

For this project, Decision Tree would be the best model with Best Hyperparameters *{ccp_alpha: 0.0, max_depth: 10, min_samples_leaf: 2, min_samples_split: 2}* for Employee Turnover Prediction though with an accuracy of 71%

## Conclusion and Recommendation

- Tech innovation should investigate their onboarding process and their work environment to find out why newer employees are prone to leave
  
- Job promotion process should be streamlined and if possible employees should be incentivized to give a sense of belonging, while encouraging employee performance and retention

