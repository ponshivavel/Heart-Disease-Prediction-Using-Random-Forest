Heart Disease Prediction Using Random Forest
📖 Project Overview

This project predicts whether a person has heart disease based on medical parameters using Machine Learning.
A Random Forest Classifier is trained on a real healthcare dataset to make accurate predictions.
The project also includes a simple interactive UI using Google Colab Forms.

🎯 Objective

To build a machine learning model that can predict the presence of heart disease at an early stage using patient health data.

📊 Dataset

Source: UCI Heart Disease Dataset

Features Used (13):

age

sex

chest pain type (cp)

resting blood pressure (trestbps)

cholesterol (chol)

fasting blood sugar (fbs)

resting ECG (restecg)

maximum heart rate (thalach)

exercise-induced angina (exang)

oldpeak

slope

number of major vessels (ca)

thal

Target:

0 → No Heart Disease

1 → Heart Disease

⚙️ Technologies Used

Python

Pandas

NumPy

Scikit-learn

Matplotlib & Seaborn

Google Colab

🧠 Machine Learning Model

Algorithm: Random Forest Classifier

Why Random Forest?

Handles non-linear data well

Reduces overfitting

Works effectively with medical datasets

🔧 Project Workflow

Load and preprocess dataset

Handle missing values

Perform exploratory data analysis (EDA)

Split data into training and testing sets

Train Random Forest model

Evaluate model performance

Create a simple UI in Google Colab

Predict heart disease based on user input

📈 Model Evaluation

Accuracy Score

Classification Report

Confusion Matrix

Accuracy shows how well the model predicts heart disease from patient data.

🖥️ Simple UI (Google Colab)

A lightweight UI is created using Google Colab Form parameters, allowing users to:

Enter patient medical details

Get instant heart disease prediction

This makes the project interactive and user-friendly.

🧪 Example Output

✅ No Heart Disease Detected

❌ Heart Disease Detected

🚀 Future Improvements

Add more machine learning models for comparison

Use cross-validation for better reliability

Improve UI using Streamlit

Add model explainability (SHAP / LIME)

🧑‍🎓 Author

Ponshivavel
Student | Machine Learning Enthusiast

