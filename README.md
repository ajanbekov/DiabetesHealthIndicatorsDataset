# DiabetesHealthIndicatorsDataset

## Overview

This project utilizes the Diabetes Health Indicators Dataset available on Kaggle, which can be accessed [here](https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset). The goal is to analyze the dataset and explore potential relationships between various factors by performing comprehensive data cleaning, exploratory data analysis, and visualization, followed by the development and evaluation of multiple machine learning models—including logistic regression, random forest classifiers, and neural networks—to predict diabetes, assess feature importance, and enhance model interpretability through techniques such as SHAP and LIME.

The Jupyter Notebook included in this repository contains the code for analysis. It encompasses the following key aspects:

* **Preprocessing:** Correcting and optimizing data types to ensure analysis readiness and memory efficiency.
* **Exploratory Data Analysis (EDA):** Visualizing variable distributions and analyzing lifestyle-related and risk-related factors to gain insights into the dataset.
* **Correlation Analysis:** Examining relationships between habit_cols and risk_cols to assess their association with diabetes.
* **Classification Models:** Building and evaluating multiple classification approaches, including Logistic Regression for binary diabetes prediction, hyperparameter tuning with GridSearchCV, single-patient prediction analysis using LIME with a Random Forest Classifier, and feature importance analysis using Random Forest.
* **Neural Network Modeling:** Implementing a Multi-Layer Perceptron (MLP) architecture using the Sequential model from tensorflow.keras, including data standardization, dropout regularization, and optimizer selection.
* **Model Evaluation:** Evaluating performance through explainability methods (SHAP and LIME), loss and accuracy graphs, classification reports, feature importance, and confusion matrices.

## Dataset Information

The Diabetes Health Indicators Dataset is a clean dataset of 70,692 survey responses to the CDC's BRFSS2015. It has an equal 50-50 split of respondents with no diabetes and with either prediabetes or diabetes. The target variable Diabetes_binary has 2 classes. 0 is for no diabetes, and 1 is for prediabetes or diabetes. This dataset has 21 feature variables. 

## Usage

To replicate the analysis and explore the code, follow these steps:

1. Clone this repository to your local machine.
2. Download the dataset from the Kaggle link provided above.
3. Install the required libraries listed in the requirements file.
4. Open the Jupyter Notebook and execute the cells sequentially.
