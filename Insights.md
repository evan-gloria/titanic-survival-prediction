## 🔍 Model Evaluation Summary

### 🧪 Logistic Regression

**Validation Accuracy:** 81.0%  
**Cross-Validation Accuracy (mean):** 81.4%  
**Kaggle Public Score:** 0.75598

**Confusion Matrix:**

| Class | Precision | Recall | F1-Score | Support |
|-------|-----------|--------|----------|---------|
| 0 (Died)     | 0.83      | 0.87   | 0.85     | 110     |
| 1 (Survived) | 0.78      | 0.71   | 0.74     | 69      |

---

### 🌲 Random Forest

**Validation Accuracy:** 79.3%  
**Cross-Validation Accuracy (mean):** 81.9%  
**Kaggle Public Score:** **0.78229**

**Confusion Matrix:**

| Class | Precision | Recall | F1-Score | Support |
|-------|-----------|--------|----------|---------|
| 0 (Died)     | 0.78      | 0.92   | 0.85     | 110     |
| 1 (Survived) | 0.82      | 0.59   | 0.69     | 69      |

---

### ⚡ XGBoost

**Validation Accuracy:** 79.9%  
**Cross-Validation Accuracy (mean):** **83.3%**  
**Kaggle Public Score:** 0.76555

**Confusion Matrix:**

| Class | Precision | Recall | F1-Score | Support |
|-------|-----------|--------|----------|---------|
| 0 (Died)     | 0.81      | 0.88   | 0.84     | 110     |
| 1 (Survived) | 0.78      | 0.67   | 0.72     | 69      |

---

### 📌 Insights

- Random Forest had the **best Kaggle score** despite slightly lower validation accuracy.
- XGBoost had **strong cross-validation**, but slightly underperformed on Kaggle.
- Logistic Regression was stable and balanced, but had lower overall Kaggle performance.

---


## 🔍 Model Evaluation Summary After Adding `Title` Feature

### 🧪 Logistic Regression

**Validation Accuracy:** 83.2%  
**Cross-Validation Accuracy (mean):** 82.6%  
**Kaggle Public Score:** 0.77511

**Confusion Matrix:**

| Class | Precision | Recall | F1-Score | Support |
|-------|-----------|--------|----------|---------|
| 0 (Died)     | 0.85      | 0.88   | 0.87     | 110     |
| 1 (Survived) | 0.80      | 0.75   | 0.78     | 69      |

---

### 🌲 Random Forest

**Validation Accuracy:** 82.7%  
**Cross-Validation Accuracy (mean):** 82.4%  
**Kaggle Public Score:** **0.77990**

**Confusion Matrix:**

| Class | Precision | Recall | F1-Score | Support |
|-------|-----------|--------|----------|---------|
| 0 (Died)     | 0.84      | 0.89   | 0.86     | 110     |
| 1 (Survived) | 0.81      | 0.72   | 0.76     | 69      |

---

### ⚡ XGBoost

**Validation Accuracy:** 81.6%  
**Cross-Validation Accuracy (mean):** **83.95%**  
**Kaggle Public Score:** 0.77033

**Confusion Matrix:**

| Class | Precision | Recall | F1-Score | Support |
|-------|-----------|--------|----------|---------|
| 0 (Died)     | 0.83      | 0.88   | 0.85     | 110     |
| 1 (Survived) | 0.79      | 0.71   | 0.75     | 69      |

---

### 📌 Insights

- `Title` is a **strong predictor** and improved all models.
- **Random Forest** currently performs best **overall** (highest Kaggle score).
- **XGBoost** shows the highest CV accuracy, but may need tuning to avoid overfitting.

---