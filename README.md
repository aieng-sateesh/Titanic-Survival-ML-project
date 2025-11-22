# Titanic-Survival-ML-project
Completed my Titanic Survival Prediction Machine Learning Project!

🚢 Titanic Survival Prediction – Machine Learning Project
🔍 Project Overview

This project builds a Machine Learning model to predict whether a passenger survived the Titanic disaster.
It includes data cleaning, EDA, feature engineering, model building, and evaluation using Python and Scikit-Learn.

📂 Dataset

The dataset contains passenger information such as:

Passenger class

Sex

Age

Fare

Siblings/spouses

Parents/children

Embarkation port

Cabin/Deck

Dataset Source: Kaggle Titanic Dataset.

🛠️ Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-Learn

Jupyter Notebook

🧹 Data Preprocessing

Handled missing values in Age, Cabin, Embarked

Extracted Deck from Cabin

Encoded categorical features (Sex, Embarked, Deck)

Dropped irrelevant columns (Name, Ticket)

📊 Exploratory Data Analysis

Survival comparison by gender, class, embarkation

Age distribution

Correlation heatmap

Key insights:

Women had higher survival rate

First-class passengers survived more

Younger passengers had better chances

Fare correlated with survival

🤖 Models Used

Logistic Regression (Baseline Model)

Random Forest Classifier (Improved Accuracy)

📈 Model Evaluation

Accuracy Score

Confusion Matrix

Classification Report

Feature Importance (Random Forest)

🧠 Key Learnings

Proper data preprocessing improves model accuracy

Feature engineering (Deck extraction) adds strong predictive power

Random Forest significantly outperforms Logistic Regression

📦 How to Run
pip install -r requirements.txt
jupyter notebook


Open titanic_project.ipynb and run all cells.

🗂️ Author

Sateesh Kumar Doultani
LinkedIn: https://www.linkedin.com/in/sateeshkumarai/

GitHub: https://github.com/aieng-sateesh
