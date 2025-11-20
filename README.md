# Wine Quality Classifier

## Overview
Predict whether a wine is of **good quality** (1) or **not** (0) using machine learning. This project demonstrates **end-to-end data analysis, feature engineering, model training, and evaluation** on a real-world dataset.

---

## Key Highlights
- **Binary Classification Problem:** Good quality vs Not good quality  
- **Dataset:** UCI Wine Quality Dataset (11 physicochemical features)  
- **Models Used:** Logistic Regression, SVC, XGBoost Classifier  
- **Evaluation Metrics:** ROC-AUC, Confusion Matrix, Classification Report  

---

## Approach
1. **Data Exploration & Cleaning:**  
   - Handled missing values, checked distributions, converted object columns to numeric  
2. **Feature Engineering & Analysis:**  
   - Removed redundant features, analyzed correlations  
3. **Model Training:**  
   - Split dataset 80:20, scaled features, trained multiple classifiers  
4. **Evaluation & Insights:**  
   - Selected best model based on ROC-AUC and validation performance  
   - XGBoost achieved highest validation ROC-AUC (~0.805)  

---

## Key Skills Demonstrated
- Data preprocessing & cleaning  
- Exploratory Data Analysis (EDA)  
- Binary classification & model evaluation  
- Feature correlation analysis & selection  
- Use of Python ML libraries: scikit-learn, XGBoost, Matplotlib, Seaborn  

---

## Quick Results
| Model                  | Training ROC-AUC | Validation ROC-AUC |
|------------------------|-----------------|-------------------|
| Logistic Regression    | 0.698           | 0.686             |
| SVC (RBF Kernel)       | 0.720           | 0.707             |
| XGBoost Classifier     | 0.976           | 0.805             |

**Takeaway:** XGBoost provides the best balance between high accuracy and minimal overfitting. This project demonstrates **practical application of ML pipelines for binary classification tasks**.

---

## How to Run
1. Clone the repository:  
```bash
git clone https://github.com/chelsi123/Wine_Quality_Classifier.git
