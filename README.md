# Business_Analytics_Bootcamp_9

# Random Forest


# 🌲 Random Forest Classifier — Credit Card Application Prediction

Welcome to our project on **Random Forest**, where we use this powerful ensemble technique to predict **Credit Card Application Approvals** based on customer expenditure and default data. This repository is part of a hands-on learning exercise under **Predictive Analytics**.

---

## 📌 Project Overview

Many financial institutions face the challenge of determining which customers are likely to be approved for a credit card. This project solves that challenge using a **Random Forest Classifier**, a robust and widely-used machine learning algorithm.

> 🔍 **Goal:** Classify whether a customer is likely to get their credit card application approved, using behavioral and financial features.

---

## 🧠 Key Concepts Covered

- Data Preprocessing & Encoding
- Handling Imbalanced Classes (Stratified Split)
- Building and Evaluating Random Forest Classifier
- Model Evaluation using F1-Score
- Feature Importance Visualization
- Hyperparameter Tuning using Grid Search

---

## 📂 Repository Structure

| File Name                             | Description |
|--------------------------------------|-------------|
| `Random Forest.ipynb`                | 📓 Main Python notebook containing the full workflow |
| `CreditCard.csv`                     | 📊 Dataset used for training and testing |
| `R_ Expenditure and Default Data.pdf`| 📄 Detailed explanation of each feature in the dataset |
| `README.md`                          | 🧾 Project documentation (this file) |

---

## 🧪 Tools & Libraries Used

- Python 🐍 (Jupyter Notebook)
- pandas, numpy
- scikit-learn (RandomForestClassifier, train_test_split, classification_report)
- matplotlib (for feature importance visualization)

---

## 📈 Model Performance

- **Imbalanced Dataset Considered**: Only ~78% of applicants were approved.
- **F1-Score Focused Evaluation**: Since data is imbalanced, we prioritized the **F1-Score** over accuracy.
- **Best Parameters Found**: `n_estimators = 50`

---

## 📊 Top Influential Features (Feature Importance)

The model revealed the top financial behaviors that influence credit card approval, helping organizations understand what matters most.

> Want to know which features mattered the most?  
> 📈 Check the notebook for a clear **bar chart of top 5 features**!

---

## 🔍 Challenge Highlights

✅ Implemented a **parameter tuning loop** using `ParameterGrid`  
✅ Achieved **optimized performance** using Grid Search  
✅ Ensured a **balanced train-test split** with stratification  
✅ Focused on **model interpretability** through feature importance

---

## 💡 Why Random Forest?

Random Forests are:
- ✅ Robust to noise
- ✅ Handle multicollinearity well
- ✅ Provide great accuracy out-of-the-box
- ✅ Offer interpretability through feature importance

---

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   [git clone https://github.com/Binny007/Business_Analytics_Bootcamp_9.git]
)
