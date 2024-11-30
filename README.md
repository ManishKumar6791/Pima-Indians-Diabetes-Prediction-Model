# Pima Indians Diabetes Prediction Model

This project builds a machine learning model to predict the likelihood of diabetes in Pima Indians based on several medical diagnostic features. The model uses various algorithms like Logistic Regression, Random Forest, Gradient Boosting, and Deep Neural Networks (DNN). The dataset used is the [Pima Indians Diabetes Database](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database) from Kaggle.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Algorithms](#algorithms)
- [Model Evaluation](#model-evaluation)
- [Getting Started](#getting-started)
- [Dependencies](#dependencies)
- [Results](#results)

## Project Overview
This project aims to predict the occurrence of diabetes based on input features such as glucose, BMI, age, and insulin. It compares multiple machine learning models and provides detailed performance metrics for each.

## Features
The dataset contains the following features:
1. **Pregnancies**: Number of pregnancies
2. **Glucose**: Plasma glucose concentration
3. **Blood Pressure**: Diastolic blood pressure
4. **Skin Thickness**: Triceps skin fold thickness
5. **Insulin**: 2-Hour serum insulin
6. **BMI**: Body mass index
7. **Diabetes Pedigree Function**: A function that scores the likelihood of diabetes based on family history
8. **Age**: Age in years
9. **Outcome**: Whether the patient has diabetes (1) or not (0)

## Algorithms
The following algorithms are used to train the models:
- **Logistic Regression**: A statistical model used for binary classification.
- **Random Forest**: An ensemble of decision trees for classification.
- **Gradient Boosting**: An ensemble method that builds models sequentially.
- **Deep Neural Network (DNN)**: A multi-layer neural network for classification.
- **Stacking Ensemble**: A combination of the above models to improve prediction accuracy.

## Model Evaluation
The models are evaluated based on several performance metrics:
- Accuracy
- F1 Score
- Precision
- Recall
- AUC (Area Under the Curve)
- Matthews Correlation Coefficient (MCC)
- ROC and Precision-Recall Curves

## Getting Started

### Prerequisites
Before running this code, ensure you have the following installed:

1. Python 3.6+
2. An IDE or text editor (e.g., VSCode, PyCharm)

### Installation
Clone this repository to your local machine:

```bash
git clone https://github.com/yourusername/pima-indians-diabetes.git
cd pima-indians-diabetes
