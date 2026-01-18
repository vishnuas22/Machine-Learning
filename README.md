# 📘 Machine Learning Concepts Repository

<p align="center">
  <img src="https://img.shields.io/badge/Machine%20Learning-Classical-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Python-3.8+-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge">
</p>

> A structured, visual, and production-oriented collection of **classical Machine Learning concepts, algorithms, workflows, and experiments**.

---

## 🎯 Purpose

This repository is built to:

- Act as a **complete ML reference**
- Provide **concept → math → implementation**
- Support **interview preparation**
- Enable **reproducible experiments**
- Serve as a **long-term ML knowledge base**

---

🧮 Foundations
Linear Algebra
Probability
Statistics
Convex Optimization


📊 Data Processing
Missing values
Outliers
Scaling & normalization
Encoding
Feature selection
🤖 Supervised Learning
Linear & Logistic Regression
KNN
SVM
Decision Trees
Random Forest
Gradient Boosting
XGBoost / LightGBM
🧠 Unsupervised Learning
K-Means
Hierarchical Clustering
DBSCAN
PCA
t-SNE
Isolation Forest
📈 Evaluation & Optimization
Cross-validation
ROC / AUC
Bias–variance analysis
Grid & Random Search
Bayesian optimization
🚀 Deployment Basics
Pickle / Joblib
REST APIs
Inference pipelines

---

sequenceDiagram
    participant D as 🗃 Dataset
    participant C as 🧹 Cleaning
    participant E as 📊 EDA
    participant F as 🧬 Features
    participant T as 🤖 Training
    participant V as 📈 Validation
    participant S as 🏆 Selection
    participant P as 🔮 Prediction

    D->>C: Raw data
    C->>E: Clean data
    E->>F: Insights
    F->>T: Feature matrix
    T->>V: Evaluate
    V->>S: Best model
    S->>P: Predict
