#  Heart Attack Risk Prediction using Machine Learning

This project leverages clinical data to predict the likelihood of a heart attack using supervised machine learning techniques.

## 📌 Project Overview

Heart disease remains a leading cause of mortality globally. Early prediction can save lives and reduce healthcare burdens. This project applies machine learning to patient health data to classify whether a person is at risk of a heart attack.

### Key Highlights:
- Performed detailed **Exploratory Data Analysis (EDA)** with visualizations to understand relationships between medical features and heart attack risk.
- Built and compared multiple classification models:
  - **Support Vector Machine (SVM)**
  - **Random Forest**
  - **Logistic Regression (L1 Regularized)**
- Applied **GridSearchCV** for hyperparameter tuning and performance optimization.
- Achieved **93% accuracy** using Logistic Regression, with strong precision and recall metrics.

## 📊 Dataset Information

The dataset includes 14 clinical features such as:
- Age
- Sex
- Chest Pain Type (cp)
- Resting Blood Pressure (trtbps)
- Cholesterol (chol)
- Fasting Blood Sugar (fbs)
- Resting ECG Results (restecg)
- Maximum Heart Rate Achieved (thalachh)
- Exercise-induced angina (exng)
- ST depression (oldpeak)
- Slope of peak exercise ST segment (slp)
- Number of major vessels (caa)
- Thalassemia (thall)
- Target variable: Output (0 = less chance, 1 = more chance of heart attack)

## 🧪 Machine Learning Workflow

1. **Data Cleaning & Preprocessing**
   - Removed duplicates
   - Mapped categorical variables
   - Split into train-test sets

2. **EDA & Visualization**
   - Count plots, violin plots, histograms, and bar charts
   - Insightful analysis of chest pain type, cholesterol, and ECG features

3. **Model Training**
   - Implemented and tuned three models using `GridSearchCV`

4. **Model Evaluation**
   - Confusion matrix and classification report
   - Cross-validation accuracy

