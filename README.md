# 🚢 Titanic Survival Prediction using Random Forest 🌲

## 📌 Project Overview
This project analyzes the famous Titanic dataset and applies a **Random Forest** 🌳 machine learning algorithm to predict passenger survival. The goal is to uncover key factors influencing who survived and who didn't aboard the Titanic.

---

## 📊 Dataset Overview
The Titanic dataset contains information on **891 passengers**, including their age, gender, ticket class, fare paid, cabin allocation, and family members onboard. The dataset contains some missing values (particularly for `Age`, `Cabin`, and `Embarked`), which were carefully handled during preprocessing. 🛠️

---

## 🔍 Exploratory Data Analysis (EDA)
Several key questions were addressed through data analysis:

1. **👫 Gender Distribution:** Were there more male or female passengers onboard?
2. **💳 Class vs. Survival:** Did passenger class affect survival chances?
3. **👶 Age Distribution:** What age groups were most common on the ship?
4. **🏠 Cabin Assignments:** How were passengers distributed across cabins?
5. **⚓ Ports of Embarkation:** From which ports (Cherbourg, Queenstown, Southampton) did most passengers board?
6. **👨‍👩‍👧 Family Impact:** Did traveling alone or with family influence survival rates?

---

## 🤖 Machine Learning Approach
- **Algorithm:** Random Forest Classifier 🌲
- **Feature Engineering:** Managed missing values, performed label encoding for categorical variables (like gender and embarkation port), and engineered new features such as family size. 🧩
- **Model Evaluation:** Assessed using accuracy, precision, recall, and confusion matrix. 📈

---

## 🛠️ Tech Stack
- **Programming Language:** Python 🐍  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn 📚  
- **Data Handling:** CSV files and Excel 📂  
- **Visualization:** Matplotlib and Seaborn 📊  

---

## 🎯 Results
The Random Forest model identified critical survival factors, including passenger class (`Pclass`), gender (`Sex`), age, family size, and embarkation port. The final model achieved an accuracy of approximately **80%**, showing solid predictive performance. ✅  

Detailed metrics and visualizations are provided within the project notebook.

---

## 🚀 Future Improvements
- **Hyperparameter Tuning:** Optimize Random Forest parameters to potentially boost accuracy. ⚙️
- **Feature Engineering:** Investigate new or refined features for improved predictive power. 🔧
- **Alternative Models:** Evaluate models like XGBoost or Gradient Boosting for comparative analysis and performance improvements. 🔍

---
