#Titanic Survival Prediction 

📌 Project Overview

This project aims to predict whether a passenger survived the Titanic disaster using machine learning techniques. It is a classification problem where the output is binary (Survived or Not Survived).

🎯 Objective

To build a predictive model using the Weighted K-Nearest Neighbors (WKNN) algorithm to determine passenger survival based on various features.

📊 Dataset Description

The dataset used is the Titanic dataset containing information about passengers such as:

Passenger Class (Pclass)
Gender (Sex)
Age
Fare
Number of Siblings/Spouses (SibSp)
Number of Parents/Children (Parch)
🔹 Feature Engineering

A new feature was created:

FamilySize = SibSp + Parch + 1

*Exploratory Data Analysis (EDA)

The following analysis was performed:

Survival distribution
Survival based on gender
Survival based on passenger class

📈 Key Insights
Females had higher survival rates than males
Passengers in higher classes had better survival chances
Family size influenced survival probability

⚙️ Methodology
Data Cleaning (handling missing values)
Feature Engineering
Encoding categorical variables
Feature Scaling using StandardScaler
Model Training using WKNN
Model Evaluation

🤖 Model Used
Weighted K-Nearest Neighbors (WKNN)
Parameters:
n_neighbors = 5
weights = distance

📊 Results
Accuracy: ~75% – 80%

📌 Evaluation Metrics
Confusion Matrix
Classification Report

🛠️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn

📂 Project Structure

Titanic-Survival-Prediction/
│── Titanic.ipynb
│── train.csv
│── report.pdf
│── README.md

🚀 How to Run the Project
Open the notebook file Titanic.ipynb
Ensure train.csv is in the same folder
Run all cells step by step

📌 Applications
Risk prediction
Healthcare survival analysis
Customer behavior prediction
Decision-making systems


📚 References
Kaggle Titanic Dataset
Scikit-learn Documentation
Machine Learning Tutorials
