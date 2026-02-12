🚀 Income Prediction Model (Machine Learning)
📌 Project Overview

This project builds a predictive classification model to determine whether an individual's income exceeds $50K/year based on demographic and employment attributes.
It demonstrates the complete data science workflow — from data cleaning and exploratory analysis to model optimization and evaluation.

🛠️ Tech Stack
Category	Tools / Libraries
Language	Python
Data Analysis	Pandas, NumPy
Visualization	Matplotlib, Seaborn
Machine Learning	Scikit-learn, XGBoost
Model Evaluation	GridSearchCV, ROC-AUC, F1-Score
Environment	Jupyter Notebook, VS Code
🧠 Workflow & Implementation
🔎 Exploratory Data Analysis (EDA)

Analyzed distributions of age, education, occupation, and working hours.

Identified patterns strongly associated with higher income groups.

Used visualization to detect outliers and feature relationships.

⚙️ Feature Engineering

Applied One-Hot Encoding for categorical variables.

Used StandardScaler to normalize numerical features.

Prepared structured pipelines for reproducible preprocessing.

⚖️ Handling Class Imbalance

Implemented SMOTE (Synthetic Minority Over-sampling Technique)
to balance the dataset and improve minority-class prediction.

🤖 Model Development

Tested and compared multiple algorithms:

Logistic Regression

Random Forest Classifier

XGBoost Classifier

🎯 Model Optimization

Performed hyperparameter tuning using GridSearchCV.

Optimized for:

F1-Score

ROC-AUC

Generalization performance

📈 Results
Metric	Score
Accuracy	86%

🔍 Key Insights

Education Level is the strongest indicator of higher income.

Hours Worked Per Week significantly influences income classification.

Ensemble models (Random Forest / XGBoost) outperformed linear models.
