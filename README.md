# Fraud Transaction Detection using Machine Learning

This repository contains a comprehensive machine learning project aimed at detecting fraudulent financial transactions. With the increasing digitization of payments, detecting fraud accurately is critical to protect consumers and businesses.

Objective

To build an accurate, interpretable, and interactive classification model that can effectively distinguish between legitimate and fraudulent transactions using real-world inspired features. Special focus is given to minimizing false negatives to ensure maximum fraud catch rate.

Dataset Overview

The dataset includes:

Transaction amounts

Customer and terminal identifiers

Timestamps and datetime features

Binary labels (fraud or not fraud)

Exploratory Data Analysis (EDA)

Overview of data using .head(), .info(), .describe()

Missing value inspection

Class imbalance visualization (fraud vs legit)

Transaction amount distributions

Temporal analysis (fraud by hour)

Feature correlation heatmap

Preprocessing

Feature scaling using StandardScaler

Train/test split with stratified sampling

Handling SettingWithCopyWarning properly

Machine Learning Models

Implemented and evaluated three models:

Logistic Regression

Decision Tree

Random Forest

Evaluation Metrics

Accuracy, Precision, Recall, F1-Score

Confusion Matrix (interactive using Plotly)

Classification Report

Feature Importance Plots

Visualizations

Count plots for class distribution

Histograms for transaction amounts

Correlation heatmap

Interactive confusion matrix via Plotly

Feature importance using bar plots

Outcome: Achieved high accuracy and strong recall, with well-visualized results and clear interpretability. This project serves as a solid foundation for building more complex fraud detection systems.
