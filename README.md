# Project_Phase-3
# Decoding Telecom Customer Churn Prediction
## Project Overview
This project focuses on predicting customer churn for a telecommunications company using machine learning. Customer churn—the loss of clients—directly impacts a business's profitability. By understanding the patterns and factors that lead to churn, companies can take proactive steps to retain valuable customers and improve their service offerings.

This notebook walks through the end-to-end process of exploring a real-world churn dataset, building predictive models, and generating business insights and recommendations.

## Business Problem
Churn is a critical issue in the telecommunications industry, where competition is fierce and retaining customers is more cost-effective than acquiring new ones. The business goal is to identify patterns in customer behavior that predict whether a customer is likely to churn, enabling targeted retention strategies.

## Objectives

You will be able to:
* Clean and explore the SyriaTel customer churn dataset.
* Single out patterns or features correlated with churn.
* Build machine learning models to predict churn.
* Evaluate model performance and provide actionable business recommendations.

## Dataset
Filename: Churn data.csv

Target Variable: churn (1 = churned, 0 = retained)

Features include:

Customer plans (e.g., international plan, voice mail plan)

Call usage statistics (day/evening/night/intl minutes and calls)

Number of customer service calls

Categorical columns like states

## Notebook Structure
1. Business Understanding
Problem statement and objectives
Stakeholder identification
2. Data Preparation
Loading datasets from multiple sources
Data cleaning and preprocessing
3. Data Analysis & Visualization
Multiple Linear Regression analysis
Train, Test and Split Data
Model Training
Evaluation
Visualization ROC Curve

![alt text](image.png)


![alt text](image-1.png)


![alt text](image-2.png)


![alt text](image-3.png)


![alt text](image-4.png)

## Requirements
To run this notebook, you'll need:

Python 3.7+
Libraries: pandas, numpy, matplotlib, seaborn, requests, sqlite3, gzip, scipy, sklearn

## How to Run
Install requirements: pip install -r requirements.txt
Place your main dataset as:

 project-folder/
- churn_data.csv
- Project_Phase-3.ipynb
- images

Run the Notebook

Open Project_Phase-3.ipynb in Jupyter Notebook, VSCode, or Google Colab.

Run each cell sequentially from top to bottom to:

Load and clean the dataset

Explore class imbalance

Visualize important features

Run logistic regression and random forest models

Apply ROC-AUC evaluations

Output actionable business recommendations

## Key Findings
**14.5%** of customers in the dataset churned.

High churn risk linked to:

Short account length

High day-time usage

International plans

Frequent customer service calls

## Actionable Recommendations
Target customers with high usage and frequent service calls.

Improve support satisfaction for these groups.

Provide personalized offers to reduce churn likelihood.

Continuously update model with new data.

