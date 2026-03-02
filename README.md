Diabetes Prediction System 🩺
This repository contains a Machine Learning project designed to predict whether a person is diabetic based on several medical diagnostic measurements. The model utilizes a Support Vector Machine (SVM) classifier to achieve high accuracy in medical diagnosis.

📊 Project Overview
Predictive modeling in healthcare helps in early diagnosis and better patient management. This project follows a complete machine learning workflow:

Data Collection: Using the Pima Indians Diabetes Dataset.

Exploratory Data Analysis (EDA): Statistical analysis and grouping to understand feature relationships.

Data Preprocessing: Standardizing data to a common scale for better model performance.

Model Training: Implementing a Support Vector Machine (SVM) with a linear kernel.

Predictive System: Building a system that takes new medical input and returns a diagnosis.

🛠️ Technical Stack
Language: Python

Libraries: * Pandas & NumPy: For data manipulation and analysis.

Scikit-learn: For model training, data scaling (StandardScaler), and evaluation.

SVM: Support Vector Machine classifier for classification.

📈 Model Performance
The model was evaluated using accuracy scores on both training and testing datasets to ensure it generalizes well to new data:

Training Accuracy: ~78.6%

Test Accuracy: ~77.3%

🚀 How it Works
The predictive system follows these steps:

Input: User provides medical metrics (Pregnancies, Glucose, Blood Pressure, BMI, etc.).

Reshaping: The input is converted into a NumPy array and reshaped for a single instance prediction.

Standardization: The input data is transformed using the same StandardScaler used during training.

Prediction: The trained SVM model predicts the outcome (0 for Non-Diabetic, 1 for Diabetic).

📂 Dataset Features
The dataset includes the following medical predictors:

Glucose: Plasma glucose concentration.

BloodPressure: Diastolic blood pressure (mm Hg).

BMI: Body mass index.

DiabetesPedigreeFunction: A function that scores the likelihood of diabetes based on family history.

Age: Age in years.

(And other diagnostic measurements).
