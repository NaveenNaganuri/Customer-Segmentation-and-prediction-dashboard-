# Customer-Segmentation-and-prediction-dashboard-
This is customer segmentation project 

## 📌 Overview

This dashboard analyzes customer data to:
- Segment customers based on demographics and purchasing behavior
- Predict customer responses using a machine learning model
- Help businesses design **targeted marketing strategies**

Built using **Python**, **Pandas**, **Scikit-learn**, **Matplotlib**, **Seaborn**, and **Streamlit**.

---

## 🧠 Key Features

- **Interactive Dashboard** built with Streamlit
- Dynamic filters for **Education**, **Marital Status**, **Income Range**
- Summary of:
  - Income outliers removed
  - Spending values capped
  - Features used vs columns dropped
- **Machine Learning Models** with dynamic toggles:
  - 🌲 Random Forest Classifier *(Main Model)*  
  - 🎯 KMeans Clustering *(k=2)*  
  - 🧩 Agglomerative Clustering *(k=2)*  
  - 🎲 Gaussian Mixture Model *(k=2)*  
  - 🌌 DBSCAN  

- Visualizations:
  - 📈 Confusion Matrix
  - 📉 ROC Curve
  - 🔍 Feature Importance
  - 🌀 Cluster Visualizations

---

## 📊 Data Preprocessing Summary

- Handled missing values in **Income**
- Capped extreme values in **Total Spending**
- Removed **Income outliers** using IQR
- Created new features: `Age`, `Children`, `Total_Spending`, `Marital_Group`
- Converted `Education` and `Marital_Status` to meaningful categories
- Dropped unnecessary columns like `ID`, `Dt_Customer`, etc.
