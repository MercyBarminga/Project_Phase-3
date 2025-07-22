# Project_Phase-3
Telecom Customer Churn Prediction
Project Overview
This project focuses on predicting customer churn for a telecommunications company using machine learning. Customer churn—the loss of clients—directly impacts a business's profitability. By understanding the patterns and factors that lead to churn, companies can take proactive steps to retain valuable customers and improve their service offerings.

This notebook walks through the end-to-end process of exploring a real-world churn dataset, building predictive models, and generating business insights and recommendations.

Business Problem
Churn is a critical issue in the telecommunications industry, where competition is fierce and retaining customers is more cost-effective than acquiring new ones. The business goal is to identify patterns in customer behavior that predict whether a customer is likely to churn, enabling targeted retention strategies.

Objectives
Understand the structure of the customer churn dataset.

Explore and visualize features for predictive relevance (trial and error).

Clean and preprocess the data.

Train and evaluate Logistic Regression and Random Forest models.

Provide clear business recommendations based on model findings.

Dataset
Filename: bigml_59c28831336c6604c800002a.csv

Target Variable: churn (1 = churned, 0 = retained)

Features include:

Customer plans (e.g., international plan, voice mail plan)

Call usage statistics (day/evening/night/intl minutes and calls)

Number of customer service calls

Categorical columns like state

Approach
Data Exploration:
Used info(), value_counts(), and isnull() to assess structure and distribution. Trial visualizations like boxplots and pairplots helped test whether features could visually separate churned vs. retained users.

Preprocessing:
Binary and categorical encoding, feature selection, and scaling were applied.

Modeling:

Logistic Regression (with feature scaling)

Random Forest (no need for scaling)

Evaluation:

Confusion Matrix

Classification Report

ROC Curve and AUC comparison

Interpretation:
Features like total day minutes and customer service calls were found to be potential churn indicators.

