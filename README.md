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


🌳 2. Decision Tree Classifier

Split data into 80% training and 20% testing

Trained a Decision Tree Classifier

Evaluated using:

Accuracy Score

Confusion Matrix

Classification Report

Visualized the tree using:

Matplotlib (plot_tree)

Graphviz (export_graphviz)

📉 3. Overfitting Analysis

Controlled model complexity using max_depth

Plotted:

Training Accuracy vs Tree Depth

Testing Accuracy vs Tree Depth

Observed overfitting at higher depths

🌲🌲 4. Random Forest Classifier

Trained a Random Forest Classifier with 100 trees

Compared performance with Decision Tree

Extracted feature importances

Visualized important features using a bar chart

🔁 5. Cross-Validation

Applied 5-Fold Cross-Validation

Compared average accuracy of:

Decision Tree

Random Forest

Confirmed better stability of Random Forest

📈 Results

(Replace XX with actual values)

🌳 Decision Tree Accuracy: XX%

🌲🌲 Random Forest Accuracy: XX%

✅ Random Forest achieved higher accuracy and stability

🔑 Top Influential Features

age

cp (chest pain type)

thalach

oldpeak

📊 Visualizations

📄 Decision Tree Structure (Graphviz PDF)

📉 Train vs Test Accuracy vs Tree Depth

📊 Random Forest Feature Importance Plot

🧠 Conclusion

Decision Trees are simple and interpretable but prone to overfitting

Random Forests reduce overfitting and improve prediction accuracy

Feature importance analysis highlights key health indicators

Cross-validation confirms model reliability

🧰 Technologies Used

Python

Pandas & NumPy

Scikit-Learn

Matplotlib & Seaborn

Graphviz

Jupyter Notebook

👤 Author
Naman Kumar Rai
