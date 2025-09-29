# Task 5: Decision Trees and Random Forests

## Objective
The goal of this task is to **learn tree-based models** for classification and regression, specifically:
- Train and visualize a **Decision Tree Classifier**
- Analyze **overfitting** and control tree depth
- Train a **Random Forest Classifier** and compare accuracy
- Interpret **feature importances**
- Evaluate models using **cross-validation**

---

## Dataset
**Heart Disease Dataset (UCI)**  
- Contains patient data and target variable indicating presence of heart disease (`target: 0 = No Disease, 1 = Disease`)  
- Features include: age, sex, cholesterol, blood pressure, chest pain type, etc.  
- Dataset file: `heart.csv` (stored in folder `week 5/`)

---

## Environment Setup
The task was performed in a **conda environment named `aiml`**.  

Required packages:
```bash
conda install pandas numpy matplotlib seaborn scikit-learn graphviz ipykernel jupyter -y
