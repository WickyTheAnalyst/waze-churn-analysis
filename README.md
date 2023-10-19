# Waze App Churn Analysis 
#### **Objective:** Predicting User Churn in a Ride-Sharing Service
***[Detailed Project Implementation](https://nbviewer.org/github/WickyTheAnalyst/waze-churn-analysis/blob/main/waze-churn-analysis-stage5.ipynb)***



*Prepared by Waqas Ahmad, Data Analyst*

*Date: 14 August 2023*

## Table of Contents

1. **Executive Summary**
2. **Introduction**
3. **Objective**
5. **Project Scope**
6. **Data Overview**
7. **Data Analysis Plan**
8. **Data Collection and Preprocessing**
9. **Exploratory Data Analysis (EDA)**
10. **Data Preprocessing and Feature Engineering**
11. **Model Building and Hyperparameter Tuning**
12. **Model Evaluation**
13. **Champion Model Selection**
14. **Key Insights and Recommendations**
15. **Project Review and Next Steps**
16. **Acknowledgments**

## 1. Executive Summary

The objective of this project was to predict user churn in a ride-sharing service. The project was carried out by our data analyst team to leverage machine learning techniques for churn prediction. Key findings indicate that approximately 22% of users have churned. The best-performing model, XGBoost, achieved a recall of 18.14% on the test dataset. We recommend using the XGBoost model for proactive user retention strategies.

## 2. Introduction

In a highly competitive ride-sharing industry, predicting and mitigating user churn is of paramount importance. The purpose of this project is to harness machine learning to build a predictive model for user churn. This report provides a comprehensive overview of the project, from data collection to model evaluation and recommendations.

## 3. Objective

The primary objective of this project is to develop a predictive model that accurately identifies users at risk of churning in a ride-sharing service. By achieving this, the company can take proactive measures to retain valuable users.


## 5. Project Scope

The project scope includes the following aspects:

- Data collection
- Exploratory Data Analysis (EDA)
- Data preprocessing
- Feature engineering
- Model building
- Model evaluation
- Champion model selection
- Key insights and recommendations

## 6. Data Overview

### 6.1. Dataset Description

The dataset consists of user information and activity logs. Key features include user trip history, user activity days, and engagement metrics. The binary target variable indicates whether a user has churned (1) or not (0).

### 6.2. Data Size

The dataset consists of 14999 rows and 13 columns.

## 7. Data Analysis Plan

Our data analysis plan involved the following key steps:

1. **Data Collection**: Gathering the dataset from the ride-sharing service's records.
2. **Data Preprocessing**: Cleaning, handling missing values, encoding categorical variables, and scaling features.
3. **Exploratory Data Analysis (EDA)**: Understanding the data distribution and behavior.
4. **Model Building**: Building predictive models, including Random Forest and XGBoost.
5. **Model Evaluation**: Assessing the models' performance using various metrics.
6. **Champion Model Selection**: Identifying the best-performing model.

## 8. Data Collection and Preprocessing

Data collection involved obtaining the dataset from the company's records. Data preprocessing was essential for ensuring data quality, including addressing missing values, encoding categorical variables, and scaling features for model convergence.

## 9. Exploratory Data Analysis (EDA)

EDA revealed critical insights:

- Approximately 22% of users have churned.
- Users who churned had fewer activity days and trips, indicating the importance of user engagement.
- Engagement metrics, such as users reporting road hazards and confirming alerts, were significant predictors of churn.

## 10. Data Preprocessing and Feature Engineering

- Data cleaning was performed to address anomalies.
- Missing values were handled through imputation.
- Categorical variables were encoded.
- Feature scaling was applied to enable model convergence.

## 11. Model Building and Hyperparameter Tuning

We built and tuned the following models:

### 11.1. Random Forest Model

The Random Forest model was built and hyperparameters were tuned using GridSearchCV.

### 11.2. XGBoost Model

An XGBoost model was trained and tuned to optimize model performance.

## 12. Model Evaluation

### 12.1. Random Forest Model Performance

- Recall: 12.68 %
- F1 Score: 0.198
- Accuracy: 81.8 %

### 12.2. XGBoost Model Performance

- Recall: 18.14 %
- F1 Score: 0.244
- Accuracy: 81.18 %

## 13. Champion Model Selection

The XGBoost model outperformed the Random Forest model with a recall of 18.14% on the test dataset. We recommend using the XGBoost model for proactive user retention strategies.

## 14. Key Insights and Recommendations

### 14.1. Data Analyst's Perspective

- The XGBoost model achieved a recall of 18.14% on the test dataset.
- Feature engineering played a pivotal role in enhancing model performance.
- Diverse features in the dataset were prioritized differently by the models, underscoring the importance of feature variety.
- The predictive power of the data is limited, emphasizing the need for high-quality data.
- The XGBoost model is recommended for user churn prediction.
- Ongoing data enhancement and model monitoring are essential.
- Proactive user retention strategies should be based on model predictions.

## Recommendations
- While the champion model shows promise, it's essential to acknowledge that the recall score still has room for improvement. Further fine-tuning of hyperparameters and the addition of relevant features may lead to better predictive performance.

- The dataset could benefit from additional features, such as drive-level information, more granular user interactions, and data on unique starting and ending locations.

- Careful consideration should be given to the quality of the data as predictive power depends on data's intrinsic predictiveness. Even complex models may not overcome limitations in the dataset.

- Stakeholders can extract valuable insights from this model to inform strategic decisions and explore areas of improvement.

## 15. Project Review and Next Steps

The project successfully achieved its primary objective. Continuous monitoring and iterative improvement are recommended. Next steps include:

- Data enhancement
- Regular model updates
- User retention strategies based on model predictions


## 16. Acknowledgments

We extend our appreciation to the open-source community, platforms, and data providers that facilitated this project.

This detailed project report provides an overview of our data analysis project on predicting user churn in a ride-sharing service. The recommendations and insights aim to guide the company in retaining valuable users and enhancing the service.

**Waqas Ahmad**

*Data Analyst*
