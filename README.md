🧠 Stroke Risk Prediction with Explainable Machine Learning

This repository contains the code and report for a project completed as part of the *COMP0172: Artificial Intelligence for Biomedicine and Healthcare* MSc module at UCL.

The goal of this project is to build predictive models to assess stroke risk using a real-world clinical dataset, and apply explainable AI techniques to enhance transparency and interpretability of the predictions.

---

## 📁 Project Structure

- `Code Coursework 1 COMP0172.ipynb`: Full notebook containing data preprocessing, model training, evaluation, and explainability visualizations.
- `Coursework_1_COMP0172.pdf`: Final report detailing methodology, experiments, results, and conclusions.

---

## 🧪 Key Methods

- **Preprocessing**: 
  - Outlier removal (IQR method)
  - Missing value imputation (mean strategy)
  - Class imbalance handled using **SMOTE**
  - Categorical encoding for machine learning compatibility

- **Models Used**:
  - Logistic Regression
  - Random Forest
  - Gradient Boosting
  - XGBoost

- **Model Evaluation**:
  - F1 Score, Accuracy, Precision, Recall
  - AUC-ROC and Confusion Matrix

- **Explainable AI**:
  - **SHAP values** for global and local feature attribution
  - **Partial Dependence Plots (PDPs)** for visualizing model behavior with respect to key features

---

## 📊 Highlights

- Achieved **AUC of 0.85** with Random Forest on an imbalanced clinical dataset.
- Identified **age** and **average glucose level** as the most important predictors of stroke.
- Provided **interpretable insights** through SHAP and PD plots to support decision-making in clinical settings.

---

## 📌 Tools & Libraries

- Python (scikit-learn, imbalanced-learn, SHAP, matplotlib, pandas, numpy)
- Jupyter Notebook

---

## 📖 Report

You can find a full explanation of methodology, results, and analysis in `Coursework_1_COMP0172.pdf`.

---
