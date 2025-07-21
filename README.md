# 🧬 Breast Cancer Diagnosis using Machine Learning

This project implements an Intrusion Detection System for medical anomalies using the **Wisconsin Diagnostic Breast Cancer (WDBC)** dataset. The system uses advanced machine learning algorithms to classify tumors as benign or malignant, with high accuracy and insightful visualizations.

---

## 📊 Project Overview

Breast cancer is a leading global health challenge, and early detection is critical for effective treatment. This project leverages the power of **Logistic Regression**, **Random Forest**, and **K-Nearest Neighbors** to build a robust classification model for tumor diagnosis. The models are trained and evaluated using essential preprocessing, normalization, and feature analysis steps.

---

## ⚙️ Workflow

### 1. Data Preprocessing
- Cleaned and explored the WDBC dataset with 569 entries and 32 attributes.
- Handled categorical values and verified the absence of missing data.
- Normalized feature values using Standard Scaler to improve model stability.

### 2. Exploratory Data Analysis (EDA)
- Visualized class distributions (malignant vs benign).
- Explored feature correlations, histograms, and scatter plots to identify influential features.
- Identified critical variables such as **mean radius**, **mean texture**, and **worst area**.

### 3. Model Building
- **Logistic Regression**: Used as a baseline model with a test accuracy of **97.9%**.
- **Random Forest Classifier**: Achieved **96.5%** accuracy with insights into feature importance.
- **K-Nearest Neighbors (KNN)**: Applied for comparison and analysis of distance-based classification.

### 4. Evaluation Metrics
- Evaluated all models using **accuracy**, **precision**, **recall**, **F1-score**, and **confusion matrix**.
- Discussed overfitting risks and class imbalance challenges in healthcare data.

---

## 📈 Key Insights

- Malignant tumors were accurately identified based on a small set of dominant features.
- Feature importance scores from Random Forest guided medical interpretation.
- Visual storytelling and clear metric-based comparisons enabled interpretability even for non-technical users.

---



## 🧪 Dataset

- **Source:** [UCI Breast Cancer Wisconsin (Diagnostic) Dataset](https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic)
- **Instances:** 569
- **Attributes:** 32 (including diagnosis and 30 numerical features)

---


