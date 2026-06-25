Customer Dataset
        │
        ▼
Git + DVC
        │
        ▼
Data Preprocessing
        │
        ▼
Feature Engineering
        │
        ▼
Model Training
        │
        ▼
MLflow Experiment Tracking
        │
        ▼
Best Model
        │
        ▼
MLflow Model Registry
        │
        ▼
FastAPI
        │
        ▼
Docker
        │
        ▼
GitHub Actions
        │
        ▼
Google Cloud Run
        │
        ▼
Prediction Logging
        │
        ▼
Monitoring 


# Customer Churn Prediction MLOps Pipeline

## Project Overview

This project aims to develop a production-ready machine learning system that predicts whether a bank customer is likely to churn. The system follows an end-to-end MLOps workflow, including data versioning, experiment tracking, model training, deployment, and monitoring.

---

# Business Problem

Customer churn is one of the biggest challenges faced by financial institutions. Losing an existing customer is significantly more expensive than retaining one. By accurately identifying customers who are likely to leave, the bank can take proactive retention measures such as personalized offers, customer engagement campaigns, and improved support.

---

# Objective

Build a scalable and reproducible machine learning pipeline that predicts customer churn and deploy it as a REST API using modern MLOps practices.

---

# Dataset

Source:
Kaggle Playground Series - Binary Classification with a Bank Churn Dataset

Training Samples:
165,034

Problem Type:
Binary Classification

Target Variable:
Exited

---

# Success Metrics

Primary Metric

- F1 Score

Secondary Metrics

- ROC-AUC
- Precision
- Recall
- Accuracy
- Confusion Matrix

F1 Score is selected as the primary metric because customer churn datasets are typically imbalanced. It provides a balanced measure of Precision and Recall.

---

# Technology Stack

Programming Language

- Python

Libraries

- Pandas
- NumPy
- Scikit-learn
- Matplotlib

MLOps

- Git
- DVC
- MLflow
- FastAPI
- Docker
- GitHub Actions
- Google Cloud Run

Testing

- Pytest

---

# Expected Deliverables

- Trained Machine Learning Model
- MLflow Experiment Tracking
- Registered Production Model
- FastAPI Prediction API
- Dockerized Application
- CI/CD Pipeline
- Cloud Deployment
- Prediction Logging
- Monitoring Report