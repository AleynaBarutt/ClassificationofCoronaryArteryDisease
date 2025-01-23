# Coronary Artery Disease (CAD) Classification Model

This repository contains the project work for analyzing and classifying Coronary Artery Disease (CAD) using machine learning models. The study involves data preprocessing, exploratory data analysis (EDA), and training multiple machine learning algorithms to achieve accurate predictions.

---

## 📁 **Project Overview**
- **Dataset**: Classification of Coronary Artery Disease dataset with 303 samples (216 CAD patients, 87 healthy individuals) and 55 features.
- **Goal**: To develop a reliable machine learning model that assists in the early diagnosis of Coronary Artery Disease (CAD) and supports decision-making in the healthcare sector.

---

## 🛠 **Key Steps in the Project**
### 1. Data Preprocessing  
- **Data Types**: The dataset includes categorical, numerical, and ordinal features.  
- **Data Cleaning**: No missing values, making the dataset ready for immediate use.  
- **Feature Selection**: Features highly correlated with CAD were selected using a correlation matrix.  
- **Feature Scaling**: `StandardScaler` was applied to standardize numerical features.  
- **Data Balancing**: Synthetic Minority Over-sampling Technique (SMOTE) was used to balance the dataset.

### 2. Model Training & Evaluation  
Seven machine learning algorithms were trained and evaluated on the dataset:  
1. **Logistic Regression**: Accuracy: 62%  
2. **Support Vector Machines (SVC)**: Accuracy: 54%  
3. **Decision Trees**: Accuracy: 62%  
4. **Random Forest**: Accuracy: **70%** (Best Model)  
5. **Naive Bayes**: Accuracy: 40%  
6. **K-Nearest Neighbors (KNN)**: Accuracy: 62%  
7. **Optimized KNN and SVC**: Accuracy: 63% (KNN) and 65% (SVC).  

---

## 📊 **Performance Metrics**
- **Evaluation Methods**: Confusion matrices and metrics like accuracy, precision, recall, F1-score, and specificity were used to compare model performances.  
- **Best Performing Model**: Random Forest with 70% accuracy.  

---

## 🚀 **Future Improvements**
- **Hyperparameter Optimization**: Applying techniques like Grid Search or Random Search to optimize model parameters.  
- **Ensemble Methods**: Using advanced ensemble methods like XGBoost for better results.  
- **Feature Engineering**: Adding new features such as genetic data or medical history for improved accuracy.  

---
