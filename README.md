# 🚢 Titanic Survival Prediction - ML Project

A machine learning classification project that predicts whether a passenger survived the Titanic disaster using the Titanic dataset. This project is part of a hands-on learning initiative to explore data preprocessing, feature engineering, and model building using Python.

---

## 🧠 Objective

Build a predictive model that determines if a passenger survived the Titanic shipwreck based on features such as age, gender, class, fare, and family connections.

---

## 📁 Repository Structure

Titanic-Survival-ML/
│
├── data/ # Raw and preprocessed data files
├── notebooks/ # Jupyter notebooks for EDA and modeling
├── outputs/ # Model outputs, saved predictions, plots
├── requirements.txt # Python dependencies
└── README.md # Project overview and usage

---

## 🔍 Dataset

- **Source**: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic)
- **Target Variable**: `Survived` (0 = No, 1 = Yes)

### Key Features:
- `Pclass`: Passenger class
- `Sex`: Gender
- `Age`: Age in years
- `SibSp`: # of siblings/spouses aboard
- `Parch`: # of parents/children aboard
- `Fare`: Ticket fare
- `Embarked`: Port of Embarkation

---

## 🚀 Workflow Summary

### 1. Data Cleaning & EDA
- Handled missing values (Age, Embarked, etc.)
- Visualized survival distributions
- Detected outliers and skewness

### 2. Feature Engineering
- Categorical encoding (Sex, Embarked)
- Created `FamilySize` and `IsAlone` features
- Scaled numerical features

### 3. Model Training
- Tested models: Logistic Regression, Random Forest, XGBoost
- Used cross-validation for evaluation
- Selected model based on F1-Score & ROC-AUC

---

## 📊 Results

| Model              | Accuracy | F1-Score | ROC-AUC |
|-------------------|----------|----------|---------|
| Logistic Regression | 78.4%    | 77.1%    | 81.0%   |
| Random Forest       | 80.2%    | 78.9%    | 84.3%   |
| XGBoost             | **82.1%**| **81.2%**| **86.5%**|

---

## ⚙️ How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/Ganeshlakshmana/Titanic-Survival-ML.git
   cd Titanic-Survival-ML
🔮 Future Improvements
Hyperparameter tuning using GridSearchCV

Streamlit app for interactive predictions

Use SHAP or LIME for model interpretability

👨‍💻 Author
Ganeshlakshmana
Linkedin:https://www.linkedin.com/in/ganesh-lakshmana-71085b224/
