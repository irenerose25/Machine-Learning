Obseity Prediction

🎯 Purpose
To build a machine learning model that can accurately predict an individual’s obesity level based on their lifestyle habits and physical attributes. This supports early risk detection, personalized health recommendations, and promotes preventive healthcare decisions.

📘 Overview
This project uses data from 2,111 individuals across Mexico, Peru, and Colombia, with 17 features related to eating habits, physical activity, and personal metrics (like age, weight, etc.). The objective is to classify individuals into one of seven obesity categories, ranging from Insufficient Weight to Obesity Type III, using machine learning models like Random Forest and SVM.
A web-based interface is built using Gradio to make the model accessible and user-friendly.

⭐ Features
ML Models Used:

Random Forest (Accuracy: 96.2%)

SVM (Accuracy: 87.6%)

Logistic Regression (Accuracy: 82.2%)

User Interface:

Developed using Gradio

Accepts inputs like gender, age, height, weight, food habits, physical activity, smoking/alcohol use, etc.

Visual Outputs:

Confusion matrix, classification report, model comparison graphs

Target Variable: Predicts one of the 7 obesity levels

🛠️ Tools Used
Python: Core language for development

Machine Learning Libraries: scikit-learn, pandas, numpy

Frontend: Gradio (for creating the user-friendly interface)

Visualization: matplotlib, seaborn

Dataset Source: Kaggle – Obesity Level Estimation

