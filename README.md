# Customer-Churn-Prediction

📝 Telecom Customer Churn Analyzer: Hybrid Machine Learning Prediction & Comparative Intelligence System

Project Title: A Hybrid Machine Learning Approach for Telecom Customer Churn Prediction

Institution: SASTRA DEEMED UNIVERSITY
Department: School of Arts, Sciences, Humanities and Education (SASHE)
Course: MAT499 – Project Phase
Academic Year: 2025–2026

**📌 Overview**

This project presents a Hybrid Machine Learning–based Customer Churn Prediction System developed to identify telecom customers who are likely to discontinue services. Customer churn prediction plays a critical role in improving customer retention, reducing revenue loss, and enabling data-driven business decision-making.

The system analyzes telecom customer behavioral data, subscription details, and service usage patterns using advanced gradient boosting algorithms and comparative machine learning analysis.

Unlike traditional churn prediction systems that focus only on accuracy, this project evaluates models across multiple dimensions including:

Predictive performance

Computational efficiency

Training stability

Algorithm suitability for real-world deployment

The study demonstrates that algorithm selection should depend on data characteristics and operational constraints, not just accuracy metrics.

**🎯 Objectives**

Develop an intelligent churn prediction system using machine learning

Compare multiple gradient boosting algorithms systematically

Identify key customer attributes influencing churn behavior

Build a hybrid framework for optimal algorithm selection

Provide actionable business insights for customer retention strategies

**🧠 Machine Learning Components**
**Data Collection & Preparation**

Telco Customer Churn Dataset (IBM Watson Analytics)

Structured telecom customer behavioral data

Handling missing values and categorical features

Feature engineering and imbalance handling (SMOTE-ENN)

The dataset preprocessing pipeline ensured data quality validation, outlier handling, and feature optimization before model training 


**Models Implemented**

The project evaluates a portfolio of machine learning models:

Gradient Boosting Models

XGBoost

LightGBM

CatBoost


**Training Strategy**

Stratified 5-Fold Cross Validation

Bayesian Hyperparameter Optimization

Early Stopping Mechanism

GPU acceleration for boosting algorithms

Regularization techniques to prevent overfitting

Training methodology ensured reproducibility using fixed random seeds and standardized evaluation pipelines 

**📈 Features Implemented**

Customer churn classification (Churn / Non-Churn)

Automated preprocessing pipeline

Multi-model comparison framework

Feature importance analysis

Confusion matrix and error diagnostics

Computational efficiency evaluation

Business impact interpretation

**📊 Evaluation Metrics**

The models were evaluated using a comprehensive framework including:

ROC-AUC Score

Accuracy

Precision & Recall

F1-Score

Confusion Matrix Analysis

Calibration Metrics

Computational Time & Memory Usage

Cross-validation showed highly consistent AUC performance across boosting models (~0.97 average AUC)

**Conclusion**
This project successfully applies hybrid machine learning techniques to predict telecom customer churn with high reliability. The comparative study shows that while gradient boosting models achieve similar accuracy, their efficiency, stability, and data suitability differ. The system provides a practical, data-driven framework to support customer retention strategies and real-world deployment of churn prediction solutions.
