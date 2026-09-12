# Student Mental Health Prediction

## 📌 Project Overview

This machine learning project predicts a student's mental health score using social media usage, lifestyle, academic, and stress-related factors.

The target variable is `Mental_Health_Score`, making this a regression problem.

## 📊 Dataset

The dataset contains 5,000 student records and 13 features, including:

- Age
- Gender
- Country
- Academic Level
- Most Used Platform
- Purpose of Use
- Average Daily Usage Hours
- Daily Unlocks
- Study Hours
- Physical Activity Hours
- Sleep Hours Per Night
- Stress Level
- Mental Health Score

## 🔍 Project Workflow

1. Data Loading
2. Data Understanding
3. Data Cleaning
4. Exploratory Data Analysis
5. Feature Engineering
6. Data Preprocessing
7. Model Training
8. Model Evaluation
9. Model Comparison
10. Final Model Selection

## 🤖 Machine Learning Models

The project compares:

- Linear Regression
- Random Forest
- Tuned Random Forest

## 📈 Model Performance

| Model | R² Score | MAE |
|---|---:|---:|
| Linear Regression | 0.7398 | 0.5362 |
| Random Forest | **0.8776** | **0.3472** |
| Tuned Random Forest | 0.8650 | 0.3689 |

Random Forest achieved the best test performance among the evaluated models.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook

## 📁 Repository Structure

```text
Mental-health-prediction/
│
├── data/
│   └── Student Social Media And Mental Health Impact.csv
│
├── Mental Health Prediction Model (1).ipynb
│
└── README.md
