# Disease-Prediction-Rest-API

## 📌 Overview

Disease-Prediction-ML is a machine learning classification project that predicts a possible disease based on user-provided symptoms. The project uses multiple trained machine learning models and saved preprocessing components to generate predictions.

## 🎯 Objective

The objective of this project is to apply machine learning classification techniques to symptom-based data and build a system that can predict the most likely disease from the selected symptoms.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Pickle
- Jupyter Notebook

## ⚙️ Key Features

- Symptom-based disease prediction
- Data preprocessing
- Feature encoding
- Multiple machine learning models
- Saved trained models for prediction
- Model-based classification
- Reusable preprocessing components

## 🤖 Machine Learning Models

The project includes trained models using different classification techniques:

- Naive Bayes
- Random Forest
- Support Vector Machine (SVM)

The trained models are stored as `.pkl` files and loaded during prediction.

## 📂 Project Structure

```text
Disease-Prediction-ML/
│
├── main.py
├── encoder.pkl
├── symptoms.pkl
├── nb_model.pkl
├── rb_model.pkl
├── svm_model.pkl
├── README.md
└── .gitignore

#Run the Application
python main.py
