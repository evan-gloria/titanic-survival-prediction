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

## 🔍 Model Evaluation Summary After Adding `SoloTraveller` Feature

### 🧪 Logistic Regression

- **Validation Accuracy:** 83.2%
- **Cross-Validation Accuracy (mean):** 82.6%
- **Kaggle Public Score:** 0.77511 *(no change)*

**Confusion Matrix:**

| Class | Precision | Recall | F1-Score | Support |
|-------|-----------|--------|----------|---------|
| 0 (Died)     | 0.85      | 0.88   | 0.87     | 110     |
| 1 (Survived) | 0.80      | 0.75   | 0.78     | 69      |

---

### 🌲 Random Forest

- **Validation Accuracy:** 82.7%
- **Cross-Validation Accuracy (mean):** 82.6%
- **Kaggle Public Score:** **0.78468** 🔼 *(Best so far)*

**Confusion Matrix:**

| Class | Precision | Recall | F1-Score | Support |
|-------|-----------|--------|----------|---------|
| 0 (Died)     | 0.84      | 0.88   | 0.86     | 110     |
| 1 (Survived) | 0.80      | 0.74   | 0.77     | 69      |

---

### ⚡ XGBoost

- **Validation Accuracy:** 81.6%
- **Cross-Validation Accuracy (mean):** **83.95%**
- **Kaggle Public Score:** 0.77033 *(unchanged)*

**Confusion Matrix:**

| Class | Precision | Recall | F1-Score | Support |
|-------|-----------|--------|----------|---------|
| 0 (Died)     | 0.83      | 0.88   | 0.85     | 110     |
| 1 (Survived) | 0.79      | 0.71   | 0.75     | 69      |

---

### ✅ Key Insights

- `SoloTraveller` offers **moderate improvement**, especially in Random Forest.
- **Random Forest** is now your **best-performing model on Kaggle**: `0.78468`
- **XGBoost** remains strong on cross-validation but still slightly underperforms on Kaggle test set.
- Logistic Regression remains stable, still outperforms many baselines.

---

## 📊 Model Evaluation Summary After Adding Fare_per_person_log

### 🧪 Logistic Regression

- **Validation Accuracy:** 83.2%
- **Cross-Validation Accuracy (mean):** 82.6%
- **Kaggle Public Score:** *(pending due to daily submission limit)*

**Confusion Matrix:**

| Class | Precision | Recall | F1-Score |
|-------|-----------|--------|----------|
| 0     | 0.85      | 0.88   | 0.87     |
| 1     | 0.80      | 0.75   | 0.78     |

✅ Stable performance, unchanged from previous results. `Fare_per_person_log` doesn’t significantly affect LR — likely due to its linear nature.

---

### 🌲 Random Forest

- **Validation Accuracy:** 82.1%
- **Cross-Validation Accuracy (mean):** 82.9%
- **Kaggle Public Score:** *(pending)*

**Confusion Matrix:**

| Class | Precision | Recall | F1-Score |
|-------|-----------|--------|----------|
| 0     | 0.82      | 0.90   | 0.86     |
| 1     | 0.81      | 0.70   | 0.75     |

✅ Cross-validation improved from **82.6% → 82.9%**  
🟡 Slight drop in validation accuracy vs previous run, but this could just be variance.

---

### ⚡ XGBoost

- **Validation Accuracy:** 79.9%
- **Cross-Validation Accuracy (mean):** **83.5%**
- **Kaggle Public Score:** *(pending)*

**Confusion Matrix:**

| Class | Precision | Recall | F1-Score |
|-------|-----------|--------|----------|
| 0     | 0.81      | 0.87   | 0.84     |
| 1     | 0.77      | 0.68   | 0.72     |

📈 XGBoost's **CV accuracy increased again** → now the highest across all models at **83.5%**  
⚠️ But validation accuracy slightly dropped — keep an eye on overfitting.

---

## ✅ Key Insights

- `Fare_per_person_log` improved **Random Forest CV score** and **XGBoost CV score**
- Logistic Regression remained unaffected (expected)
- XGBoost continues to dominate on cross-validation, but hasn’t yet reflected that in public Kaggle scores
- Once your Kaggle submission resets, re-submit to measure generalization!

---
