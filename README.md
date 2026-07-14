# Responsible AI & Model Interpretation

## 📌 Project Overview

This project focuses on interpreting a Machine Learning model for Heart Disease Prediction using Responsible AI techniques. The project analyzes feature importance, explains model predictions using SHAP, evaluates fairness across gender groups, and provides mitigation recommendations.

---

## 🎯 Objectives

- Interpret model predictions using SHAP
- Analyze feature importance
- Evaluate model fairness across sensitive groups
- Recommend bias mitigation strategies

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- SHAP
- Jupyter Notebook

---

## 📂 Project Structure

```
Responsible AI & Model Interpretation/
│
├── Responsible_AI_Model_Interpretation.ipynb
├── heart_disease_uci.csv
├── README.md
├── writeup.md
└── Images/
    ├── feature_importance.png
    ├── shap_summary.png
    ├── shap_bar.png
    └── shap_waterfall.png
```

---

## 📊 Analysis Performed

- Feature Importance Analysis
- SHAP Summary Plot
- SHAP Feature Importance Bar Plot
- SHAP Waterfall Plot
- Gender Bias Analysis
- Mitigation Recommendations

---

## 📈 Bias Analysis

Model Accuracy:

- Male: **85.00%**
- Female: **81.82%**

The observed difference is relatively small, indicating no strong evidence of significant gender bias on the available test dataset.

---

## 💡 Mitigation Recommendations

- Collect more balanced datasets.
- Continuously monitor fairness metrics.
- Evaluate model performance across demographic groups.
- Retrain models if bias increases.
- Use explainability tools such as SHAP during model evaluation.

---

## 👨‍💻 Author

**Yash Kumar**

InternSpark Artificial Intelligence Internship