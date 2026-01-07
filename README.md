# 🌳 **Decision Trees & Random Forests**
## ❤️ **Heart Disease Prediction using Machine Learning**

---

## 🎯 **Objective**
The objective of this project is to **learn, implement, and analyze tree-based machine learning models** for **classification tasks** using the **UCI Heart Disease Dataset**.

This project focuses on:
- **Training & visualizing a Decision Tree Classifier**
- **Analyzing overfitting and controlling tree depth**
- **Training a Random Forest Classifier and comparing accuracy**
- **Interpreting feature importance**
- **Evaluating model performance using cross-validation**

---

## 📊 **Dataset**
### **Heart Disease Dataset (UCI)**

- Patient medical data with a **binary target variable**
- **Target Labels:**
  - `0` → No Heart Disease
  - `1` → Presence of Heart Disease
- **Key Features:**
  - **age**, **sex**, **cp (chest pain type)**
  - **chol (cholesterol)**, **trestbps**
  - **thalach (maximum heart rate)**, **oldpeak**

📁 **Dataset Location**

---

## 🛠️ **Environment Setup**
The project was developed in a **Conda environment** named **`aiml`**.

### 🔧 **Required Libraries**
```bash
conda install pandas numpy matplotlib seaborn scikit-learn graphviz ipykernel jupyter -y

import pandas as pd
df = pd.read_csv("week 5/heart.csv")
df.head()
