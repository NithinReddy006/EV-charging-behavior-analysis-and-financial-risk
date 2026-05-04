# EV Charging Behavior and Financial Risk Analysis

## 📌 Project Overview
This project analyzes electric vehicle (EV) charging behavior and predicts financial risk using machine learning techniques. The study focuses on classification, regression, and clustering models to understand user behavior, financial patterns, and charging efficiency.

---

## 📊 Dataset
- **Dataset Name:** EV Charging Behavior and Financial Risk  
- **Source:** Kaggle  
- **Link:** https://www.kaggle.com/datasets/shree0910/ev-charging-behavior-and-financial-risk-dataset  
- **Rows:** 18,946  
- **Columns:** 18  

---

## 🎯 Objectives
- Predict **High Default Risk** (Classification)
- Identify key financial predictors
- Analyze feature importance
- Study charging behavior impact
- Perform EV user segmentation
- Predict charging efficiency (Regression)

---

## 📁 Repository Structure
EV-charging-behavior-analysis-and-financial-risk/
│
├── notebooks/ # Jupyter notebooks (RQ1–RQ7)
├── results/
│ ├── figures/ # Plots and graphs
│ ├── tables/ # CSV result tables
│
├── data/ # Dataset link
├── README.md
├── requirements.txt
└── LICENSE


---

## 📚 Research Questions

1.How accurately can high default risk be predicted using EV-user financial, demographic, app-usage, and charging-behavior variables?

2.which financial indicators are the strongest predictors of high default risk among EV charging users?

3.Does adding charging-behavior and product-performance features improve default-risk prediction beyond demographic and financial variables alone?

4.Which dataset features contribute most to machine-learning predictions of high default risk?

5.How do charger working status and charging location relate to charging efficiency, charging time, charging cost, and risk rate?


---

## 🤖 Machine Learning Models Used

### Classification
- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

### Regression
- Linear Regression
- Random Forest Regressor
- Gradient Boosting

### Clustering
- K-Means Clustering

---

## 📊 Evaluation Metrics

### Classification
- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC

### Regression
- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R² Score

---

## ⚙️ How to Run the Project

1. Install dependencies:

    pip install -r requirements.txt

   
3. Open notebooks from `notebooks/`

4. Run all cells to generate results

---

## 📈 Results
- All figures are stored in `results/figures/`
- All tables are stored in `results/tables/`

---

## 📌 Dataset Access
The dataset is publicly available on Kaggle.  
Dataset link is also provided : https://www.kaggle.com/datasets/shree0910/ev-charging-behavior-and-financial-risk-dataset
