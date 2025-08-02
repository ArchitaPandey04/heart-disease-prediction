# HEART DISEASE PREDICTION

A machine learning project that predicts teh likelihood of heart disease using patient medical data. 

## DATASET
Source: Source: [Kaggle - Heart Disease Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)
Rows: 1025 | Columns: 14

## FEATURES USED
-Age
-Sex (1 = male, 0 = Female )
-chest pain type (Cp)
-Resting Blood Pressure (tresttbps)
-Cholestrol (chol)
-Fasting Blood Sugar(fbs)
-Resting ECG results (restecg)
-Maximum heart Rate Achieved (thalac)
-Exercise Induced Angina (exang)
-ST Depression (oldpeak)
-Slope of Peak Exercise (Slope)
-Number of Major Vessels (ca)
-Thalassemia(thal)


## Project workFlow
1. Load dataset and perform EDA(visulizations, correlations)
2. Data preprocessing (train-test split, scaling)
3. Train multiple models:
   - Logistic Regression
   - Random Forest (Best)
   - KNN
   - SVM
4. Evaluate models and choose the best one
5. Save best model as 'heart_disease_model.pkl'
6. Predict heart disease for new patient data


## HOW TO RUN
'''bash
pip install -r requirements.txt
jupyter notebook notebook/heart_disease.ipynb

  