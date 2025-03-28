# 🚗 Car Evaluation Classification with SVM

This project applies classification techniques to the **Car Evaluation Dataset** from UCI, where the goal is to predict the car's overall acceptability (`unacceptable`, `acceptable`, `good`, `very good`) based on 6 **ordinal input features**.

---

## 📌 Project Overview

- **Task**: Multi-class classification with ordinal target
- **Target**: Car evaluation rating (4 ordered classes)
- **Features**: Buying price, maintenance, doors, persons, luggage boot, safety
- **Final Model**: Support Vector Machine (SVM)
- **Preprocessing**: Label encoding of all ordinal features

---

## ⚙️ Tools & Libraries

- Python
- `scikit-learn`
- `matplotlib`, `seaborn`

---

## 🧠 Modeling Workflow

- Label encoding for ordinal inputs
- Train-test split
- Nested Cross-Validation for model selection
- Hyperparameter tuning
- Final model performance evaluation

---

## ✅ Results Summary

- **Best Model**: SVM
- **Evaluation Includes**:
  - Overall accuracy
  - Confusion Matrix
  - Per-class performance analysis
- Well-balanced predictions across all 4 classes

---

## 💼 Business Value

Predicting vehicle evaluation ratings based on specifications helps automotive companies align products with consumer expectations and improve segmentation, design, and marketing strategies.

> 📂 Explore the notebook: `car_evaluation_multiclass.ipynb`
