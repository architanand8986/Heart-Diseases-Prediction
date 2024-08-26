# Heart Disease Prediction using Logistic Regression

## Overview

This project aims to predict the likelihood of heart disease in patients using logistic regression. By analyzing various patient parameters such as age, sex, and chest pain type, the model provides a probability score indicating the risk of heart disease. This tool can be helpful in early detection and treatment planning.

## Dataset

The dataset used in this project is sourced from the UCI Machine Learning Repository and is available on Kaggle. You can access the dataset [here](https://www.kaggle.com/datasets/priyanka841/heart-disease-prediction-uci/data).

### Features

The dataset includes the following features:

1. **Age**: Age of the patient in years.
2. **Origin**: The place where the study was conducted.
3. **Sex**: Gender of the patient (Male/Female).
4. **Chest Pain Type (cp)**:
    - **Typical Angina**: Chest pain related to the heart.
    - **Atypical Angina**: Chest pain not related to the heart.
    - **Non-anginal**: Not heart-related chest pain.
    - **Asymptomatic**: No chest pain.
5. **Resting Blood Pressure (trestbps)**: Blood pressure (in mm Hg) on admission to the hospital.
6. **Serum Cholesterol (chol)**: Cholesterol level in mg/dl.
7. **Fasting Blood Sugar (fbs)**: Indicator for fasting blood sugar > 120 mg/dl.
8. **Resting Electrocardiographic Results (restecg)**:
    - **Normal**: Normal ECG.
    - **ST-T Wave Abnormality (stt abnormality)**: Abnormality in the T-wave.
    - **Left Ventricular Hypertrophy (lv hypertrophy)**: Enlarged heart muscle.
9. **Maximum Heart Rate Achieved (thalach)**: Maximum heart rate achieved during exercise.
10. **Exercise-Induced Angina (exang)**: Whether the patient has exercise-induced angina (True/False).
11. **ST Depression (oldpeak)**: ST depression induced by exercise relative to rest.
12. **Slope of the Peak Exercise ST Segment (slope)**: The slope of the peak exercise ST segment.
13. **Number of Major Vessels (ca)**: Number of major vessels (0-3) colored by fluoroscopy.
14. **Thalassemia (thal)**:
    - **Normal**: No thalassemia.
    - **Fixed Defect**: Defect present even when not exercising.
    - **Reversible Defect**: Defect that disappears after exercise.

      
## Dependencies

To run this project, you need the following dependencies:

- Python 
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Jupyter Notebook (optional, for running the notebooks)

