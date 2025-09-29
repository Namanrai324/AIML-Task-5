# Task 5: Decision Trees and Random Forests

## Objective
The goal of this task is to **learn tree-based models** for classification and regression. Specifically, we aim to:
- Train and visualize a **Decision Tree Classifier**
- Analyze **overfitting** and control tree depth
- Train a **Random Forest Classifier** and compare accuracy
- Interpret **feature importances**
- Evaluate models using **cross-validation**

---

## Dataset
**Heart Disease Dataset (UCI)**
- Contains patient data and a target variable indicating the presence of heart disease (`target: 0 = No Disease, 1 = Disease`).
- Features include age, sex, cholesterol, blood pressure, chest pain type, etc.
- Dataset file: `heart.csv` (stored in folder `week 5/`)

---

## Environment Setup
This task was performed in a **conda environment named `aiml`**.

Required packages:
```bash
conda install pandas numpy matplotlib seaborn scikit-learn graphviz ipykernel jupyter -y
```

---

## Steps Performed

### 1. Load Dataset
```python
import pandas as pd
df = pd.read_csv("week 5/heart.csv")
df.head()
```

### 2. Decision Tree Classifier
- Split the dataset into train and test sets (80-20 split).
- Train a Decision Tree Classifier.
- Evaluate using accuracy, confusion matrix, and classification report.
- Visualize the tree using:
  - `matplotlib` (`plot_tree`)
  - `graphviz` (`export_graphviz` and render as PDF)

### 3. Overfitting Analysis
- Controlled tree depth using `max_depth`.
- Plotted train and test accuracy vs tree depth to analyze overfitting.

### 4. Random Forest Classifier
- Trained a Random Forest Classifier with 100 trees.
- Compared accuracy with Decision Tree.
- Evaluated feature importances and plotted a bar chart.

### 5. Cross-Validation
- Used 5-fold cross-validation to assess model stability.
- Compared Decision Tree and Random Forest CV accuracies.

---

## Results
- **Decision Tree Accuracy:** XX% (replace with your result)
- **Random Forest Accuracy:** XX% (replace with your result)
- **Cross-validation** shows Random Forest performs better and is more stable.
- **Top features influencing heart disease prediction** include: age, cp, thalach, oldpeak (from feature importance analysis).

### Visualizations
- Decision Tree structure (PDF via Graphviz)
- Train vs Test Accuracy vs Tree Depth
- Random Forest Feature Importances

---

## Conclusion
- Decision Trees are simple and interpretable but prone to overfitting.
- Random Forest reduces overfitting and improves accuracy.
- Feature importance analysis helps identify the most influential factors for heart disease prediction.
- Cross-validation confirms the reliability of model performance.

