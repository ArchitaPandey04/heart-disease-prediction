# HEART DISEASE PREDICTION

A machine learning project that predicts teh likelihood of heart disease using patient medical data. 

## DATASET
- Source: [Kaggle - Heart Disease Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)
-Rows: 1025 | Columns: 14


## 📊 Features Used
| Feature | Description |
|---------|-------------|
| `age` | Age of patient |
| `sex` | Gender (1 = Male, 0 = Female) |
| `cp` | Chest pain type |
| `trestbps` | Resting blood pressure |
| `chol` | Cholesterol level |
| `fbs` | Fasting blood sugar |
| `restecg` | Resting ECG results |
| `thalach` | Max heart rate achieved |
| `exang` | Exercise induced angina |
| `oldpeak` | ST depression induced by exercise |
| `slope` | Slope of the peak exercise ST segment |
| `ca` | Number of major vessels |
| `thal` | Thalassemia |
| `target` | 1 = disease present, 0 = no disease |

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

## 📈 Model Performance
| Algorithm | Accuracy |
|-----------|----------|
| Logistic Regression | ~86% |
| Random Forest ✅ | ~91% |
| KNN | ~84% |
| SVM | ~87% |

**Best Model** → **Random Forest Classifier**


## HOW TO RUN
'''bash
pip install -r requirements.txt
jupyter notebook notebook/heart_disease.ipynb

  
