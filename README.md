# Credit Risk Prediction Model

Finance capstone project that predicts loan default risk using Machine Learning, helping financial institutions make data-driven lending decisions.

## 📌 Project Overview
This project builds and compares two classification models to predict whether a borrower is likely to default on a loan, based on financial and demographic features.

## 🛠️ Tools & Libraries
- Python
- Pandas, NumPy
- Scikit-learn (Logistic Regression, Random Forest)
- Matplotlib, Seaborn

## 📊 Steps Performed
1. Generated/collected borrower dataset with 10 financial features
2. Checked data quality and visualized risk distribution
3. Split data into training (80%) and testing (20%) sets
4. Scaled features for model training
5. Trained Logistic Regression and Random Forest classifiers
6. Evaluated both models using ROC-AUC score and classification reports
7. Compared models using ROC curves
8. Analyzed feature importance to identify key risk drivers

## 📈 Key Results
| Model | ROC-AUC Score |
|-------|---------------|
| Logistic Regression | 0.89 |
| **Random Forest** | **0.97** |

**Best Model:** Random Forest — achieved strong predictive performance suitable for real-world deployment.

**Top Risk Factors:**
1. Number of Credit Lines (33%)
2. Employment Years (16%)
3. Debt-to-Income Ratio (12.5%)

## 💡 Key Insight
Random Forest significantly outperformed Logistic Regression, demonstrating that ensemble methods capture complex patterns in credit risk data more effectively. The model provides actionable insights for loan approval decision support.

## 📁 Files
- `Credit_Risk_Model.ipynb` — Full analysis notebook with code, visualizations, and results
