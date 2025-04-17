# 🫀 Heart Disease Prediction using Machine Learning

This project uses **supervised machine learning algorithms** to predict the presence of heart disease based on patient health data from the **UCI Cleveland Heart Disease Dataset**.

---

## 📊 Problem Statement

Cardiovascular diseases are one of the leading causes of death worldwide. Early prediction of heart disease can significantly improve outcomes by enabling timely intervention. This project explores the use of machine learning models to predict the presence of heart disease using features like age, blood pressure, cholesterol, and more.

---

## 📁 Dataset

- **Source**: [UCI Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/Heart+Disease)
- **File used**: `processed.cleveland.data`
- **Total samples**: 297
- **Target**: Binary classification (0 = No heart disease, 1 = Presence of heart disease)

---

## ⚙️ Algorithms Implemented

This project applies and compares four supervised learning algorithms:

- ✅ **Logistic Regression**
- ✅ **Random Forest**
- ✅ **K-Nearest Neighbors (KNN)**
- ✅ **Support Vector Machine (SVM)**

Each model was evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## 📈 Results

All four models performed well, with **Logistic Regression** and **Random Forest** achieving an accuracy of approximately **88%**. The models showed balanced precision and recall, with only minor misclassifications.

Confusion matrices were used to visually compare model performance, confirming their reliability and consistency across the board.

---

## 🔍 Key Learnings

- Logistic Regression, while simple, performed as well as Random Forest for this dataset.
- Random Forest added robustness and feature handling but didn't significantly outperform the linear model.
- KNN and SVM provided useful points of comparison, demonstrating how different algorithmic approaches perform under the same conditions.

---

## 🧠 Future Improvements

- Hyperparameter tuning using `GridSearchCV`
- Try ensemble methods like XGBoost
- Add cross-validation
- Explore feature engineering for better model interpretability

---

## 🎥 Demo

Watch the full walkthrough and explanation of this project on YouTube:  
📺 [Your YouTube Link Here]

---

## 📌 Author

**Dilshan**  
Machine Learning Enthusiast | Data Science Explorer  
🔗 [LinkedIn Profile](https://linkedin.com/in/YOUR-LINKEDIN)  
🌐 [GitHub](https://github.com/Dilshan-686)

---

## 🗂️ Files in this Repo

- `heart_disease_classification.ipynb` – The full Jupyter Notebook with all models and results
- `processed.cleveland.data` – The dataset used
- `README.md` – This file

---

If you like this project or found it useful, feel free to ⭐️ the repo and connect with me on LinkedIn!
