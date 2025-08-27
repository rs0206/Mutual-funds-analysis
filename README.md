# 🧠 Smart Mutual Fund Analyzer for Personalized Fund Insights & Forecasting
*A Machine Learning Project for Personalized Fund Insights & Forecasting*

![Project Status](https://img.shields.io/badge/status-Completed-brightgreen)

## 📌 Project Overview

This project addresses the challenge of selecting optimal mutual funds for retail investors using machine learning. We perform classification, clustering, and regression tasks to analyze mutual fund characteristics, segment them based on risk-return profiles, and forecast future returns.

**Dataset:** [Mutual Funds India Detailed – Kaggle](https://www.kaggle.com/datasets/ravibarnawal/mutual-funds-india-detailed)

---

## 🔍 Research Questions

1. **RQ1: Classification**  
   What features are common in highly-rated mutual funds?

2. **RQ2: Clustering**  
   Can mutual funds be grouped based on their risk and return characteristics?

3. **RQ3: Regression**  
   Can we predict a mutual fund’s future returns using its past performance and financial features?

---

## 🧪 Methodology

### ✅ Data Preprocessing
- Missing value imputation (median/mode)
- Label Encoding for categorical features
- Outlier clipping using IQR
- Feature Engineering: Risk-adjusted return, size/age categories.

### ✅ Models Used
| Task | Models |
|------|--------|
| Classification (RQ1) | Random Forest, SVM, Gradient Boosting, Logistic Regression |
| Clustering (RQ2) | K-Means, DBSCAN with PCA |
| Regression (RQ3) | Random Forest Regressor, Ridge Regression, Gradient Boosting |

---

## 📊 Key Visuals

- 📈 ROC Curve & Feature Importance (RQ1)
- 📊 PCA-based Cluster Visualization (RQ2)
- 📉 Actual vs Predicted 1Y Return (RQ3)
- 🔥 Correlation Heatmap & Distribution Charts

----

## 🗂️ Project Structure

```plaintext
📁 data/
   └── processed/
       └── preprocessed_mutual_funds.csv
📁 notebooks/
   ├── classification_model.ipynb
   ├── clustering_model.ipynb
   └── forecasting_model.ipynb
📁 outputs/
   ├── plots/
   ├── predictions/
   └── leaderboard.csv
📁 src/
   ├── preprocessing.py
   ├── models/
       ├── classification.py
       ├── clustering.py
       └── regression.py
📄 main.py
📄 requirements.txt
📄 README.md
