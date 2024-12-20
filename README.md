# MLP-for-Employee-Leave-Prediction

## Overview
This notebook is designed for preprocessing and training a Multi-Layer Perceptron (MLP) model for binary classification(leave or not). It provides a comprehensive workflow, starting from data exploration, preprocessing, and feature engineering, to model building and evaluation. 

## Dataset

### Context

The dataset contains information about employees in a company, including their educational backgrounds, work history, demographics, and employment-related factors. It has been anonymized to protect privacy while providing valuable insights into the workforce.

### Columns

- Education: Educational qualifications of employees, including degree, institution, and field of study.
- Joining Year: Year each employee joined the company, indicating their length of service.
- City: The location or city where each employee is based or works.
- Payment Tier: Categorization of employees into different salary tiers.
- Age: The age of each employee, providing demographic insights.
- Gender: Gender identity of employees, promoting diversity analysis.
- Ever Benched: Indicates if an employee has ever been temporarily without assigned work.
- Experience in Current Domain: Number of years of experience employees have in their current field.
- Leave or Not: Target column indicating whether the employee stayed or left the organization.

## Key Features of the Notebook

### Libraries and Tools

- Data Analysis and Visualization: Pandas, NumPy, Seaborn, Matplotlib, SciPy
- Preprocessing: LabelEncoder, StandardScaler, MinMaxScaler, KBinsDiscretizer
- Modeling and Evaluation: PyTorch, Sklearn (accuracy, ROC-AUC, precision-recall metrics)
- Deep Learning Framework: PyTorch for creating and training neural networks
- Logging and Monitoring: TensorBoard integration for model performance tracking

### Steps Covered

- Data Loading and Exploration
   - Initial inspection of data, handling missing values, and descriptive statistics.

- Data Preprocessing
   - Encoding categorical variables, scaling numerical features, and addressing class imbalances.

- Exploratory Data Analysis (EDA)
   - Visualization of distributions, correlations, and feature importance.

- Model Development
   - Implementation of a Multi-Layer Perceptron (MLP) for classification using PyTorch.

- Model Evaluation
   - Evaluation metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.

- Optimization
   - Use of hyperparameter tuning and optimization techniques.
