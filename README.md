# 🏥 Diabetes Prediction App

A machine learning web application that predicts diabetes risk based on patient health data.

## 📊 Project Overview
This project uses the Pima Indians Diabetes Dataset to build a predictive model 
that determines whether a patient is likely to have diabetes based on 
health measurements.

## 🗃️ Dataset
- **Source:** Pima Indians Diabetes Dataset (Kaggle)
- **Size:** 768 patients, 9 features
- **Target:** Diabetes (Yes/No)

## 🔍 Features Used
| Feature | Description |
|---|---|
| Pregnancies | Number of pregnancies |
| Glucose | Blood sugar level |
| BloodPressure | Blood pressure reading |
| SkinThickness | Skin fold thickness |
| Insulin | Insulin level |
| BMI | Body Mass Index |
| DiabetesPedigreeFunction | Genetic diabetes risk score |
| Age | Patient age |

## 🤖 Models Built
| Model | Accuracy |
|---|---|
| Logistic Regression | 68.83% |
| Random Forest | 76.62% ✅ |

## 🏆 Key Findings
- **Glucose** is the strongest predictor of diabetes (27% importance)
- **BMI** is the second most important factor (17%)
- **Age** is the third most important factor (15%)
- Random Forest outperformed Logistic Regression by ~8%

## 🛠️ Tools & Technologies
- Python
- Google Colab
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Streamlit

## 📁 Project Structure