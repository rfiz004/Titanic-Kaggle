# 🧠 Machine Learning Ensemble Methods — From Bagging to Stacking

This repository contains a complete exploration of **ensemble learning methods** in machine learning — including Bagging, Random Forest, Boosting (AdaBoost, Gradient Boosting), and XGBoost — all demonstrated through real **Kaggle datasets** and combined using **Stacking**.

---

## 📘 Project Overview

The goal of this project is to understand how combining multiple models can improve accuracy and robustness compared to individual learners.  
Each algorithm is implemented, explained, and tested on real datasets with clear results and visual comparisons.

### 🔹 Implemented Algorithms
- **Random Forest** — bagging with random feature selection  
- **AdaBoost** — adaptive boosting that focuses on difficult samples  
- **Gradient Boosting** — sequential correction of previous errors using residuals  
- **XGBoost** — optimized version of Gradient Boosting with high speed and regularization  
- **Stacking** — combining multiple models’ outputs via a meta learner (Logistic Regression)

---

## 📊 Datasets Used

| Dataset | Source | Goal | Algorithm Focus |
|----------|---------|------|-----------------|
| 💰 Adult Income | [UCI Adult Income Dataset](https://archive.ics.uci.edu/ml/datasets/adult) | Predict if income exceeds 50K per year | Random Forest, AdaBoost, Gradient Boosting, XGBoost (Boosting & Bagging) |
| 🧬 Combined Project | — | Merge all models via Stacking | StackingClassifier |

---

## ⚙️ Installation

```bash
pip install scikit-learn xgboost pandas numpy matplotlib seaborn
