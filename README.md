# disease-prediction-system

# Disease Prediction Using Machine Learning

## Overview

This project is a Machine Learning-based Disease Prediction System that predicts potential diseases based on user-provided symptoms. The system also calculates a risk level and provides basic health recommendations.

The goal of this project is to demonstrate how machine learning can be applied in healthcare to assist in preliminary disease screening and risk assessment.

---

## Features

- Predicts disease based on symptoms
- Interactive symptom input
- Risk level assessment (Low, Medium, High)
- Basic health recommendations
- Simple and beginner-friendly implementation

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Jupyter Notebook

---

## Dataset

The dataset contains symptom-related information including:

- Fever
- Cough
- Fatigue
- Headache
- Body Pain
- Breathing Issues

Each record is associated with a disease label used for training the machine learning model.

---

## Project Workflow

1. Data Collection
2. Data Preprocessing
3. Feature Selection
4. Model Training
5. Disease Prediction
6. Risk Assessment
7. Recommendation Generation

---

## How It Works

The user enters symptoms as:

- 1 = Symptom Present
- 0 = Symptom Absent

Example:

Fever: 1
Cough: 1
Fatigue: 1
Headache: 0
Body Pain: 1
Breathing Issue: 0

The trained machine learning model predicts the most likely disease and generates a risk score.

---

## Risk Assessment

| Risk Score | Risk Level |
|------------|------------|
| 0 - 2 | Low |
| 3 - 4 | Medium |
| 5 - 6 | High |

Recommendations are generated based on the calculated risk level.
