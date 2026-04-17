# AI in Healthcare: Breast Cancer Classification using Machine Learning

## 📌 Project Overview
This project applies Machine Learning techniques to support medical diagnosis by classifying breast cancer cases as malignant or benign. Multiple classification algorithms are implemented and compared to identify the most effective model.

---

## 🧬 Dataset Information
- Source: Breast Cancer Wisconsin (Scikit-learn built-in dataset)
- Each record represents a patient’s tumor characteristics
- Features include measurements such as radius, texture, area, smoothness, and more
- Target variable:
  - 0 → Malignant (Cancerous)
  - 1 → Benign (Non-Cancerous)

---

## ⚙️ Project Workflow

### 1. Data Preparation
- Loaded dataset using Scikit-learn
- Converted into a structured Pandas DataFrame
- Performed initial data inspection

### 2. Exploratory Data Analysis (EDA)
- Analyzed dataset structure and feature distribution
- Checked for missing values (none found)
- Studied feature statistics and relationships

### 3. Feature Engineering
- Performed correlation analysis to identify important features
- Applied feature scaling using StandardScaler for normalization

### 4. Model Development
The following classification models were implemented:
- Logistic Regression (Baseline model)
- Random Forest Classifier (Ensemble method)
- Support Vector Machine (SVM)

### 5. Model Evaluation
Models were evaluated using standard performance metrics:
- Accuracy
- Precision
- Recall

### 6. Data Visualization
- Comparison of model performances using bar chart
- Confusion matrix visualization for the best model
- ROC curve analysis for performance evaluation

---

## 🏆 Best Performing Model
The model with the highest accuracy score was selected as the final model and used for further evaluation.

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## 🚀 Conclusion

This project demonstrates how machine learning can be effectively applied in healthcare to support early cancer detection by analyzing tumor-related medical data and building predictive models.
Multiple classification algorithms were implemented and evaluated using performance metrics such as accuracy, precision, and recall. Among the models, **Logistic Regression** achieved the highest performance and was identified as the top-performing model for this task.
The results highlight the potential of machine learning techniques in assisting medical professionals with accurate and efficient diagnosis.
