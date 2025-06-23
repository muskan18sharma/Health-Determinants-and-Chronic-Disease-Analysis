# Health-Determinants-and-Chronic-Disease-Analysis
A data-driven analysis of chronic disease risk factors using health data from 25 countries. Includes EDA, clustering, classification models (Logistic Regression, Random Forest), and geospatial mapping to uncover key patterns and support public health interventions. Built with Python, Tableau, and Power BI.
# 🌍 Health Determinants and Chronic Disease Analysis

## 📘 Project Overview
This project investigates the underlying causes of chronic diseases—such as **obesity**, **diabetes**, **hypertension**, and **high cholesterol**—using a comprehensive dataset from **25 countries**. By applying data analysis, machine learning, and geospatial visualization techniques, we aim to identify behavioral and demographic risk factors and highlight disparities in global health outcomes. The goal is to provide data-driven insights for effective public health interventions.

---

## 🎯 Objectives
- Identify behavioral and demographic factors influencing chronic diseases.
- Examine correlations between lifestyle choices and health markers.
- Model and predict individuals at high risk of chronic disease.
- Analyze global disparities in health outcomes and access to healthcare.
- Recommend actionable public health strategies based on findings.

---

## 📊 Dataset
- **Source**: [Kaggle - Heart Attack Risk Predictions](https://www.kaggle.com/datasets/ankushpanday1/heart-attack-risk-predictions)
- **Rows**: 623,028  
- **Columns**: 30  
- **Includes**: Demographics, lifestyle behaviors, biometric health metrics, environmental exposure, healthcare access.

---

## 🧪 Methodology

### 🔧 Data Preprocessing
- Imputation: Mean, median, and mode-based handling of missing values.
- Normalization: Standardized blood pressure and cholesterol levels.
- Encoding: One-hot and label encoding of categorical features.
- Outlier Detection: Z-score and IQR methods.

### 📈 Exploratory Data Analysis (EDA)
- Visualizations: Histograms, boxplots, heatmaps, scatter plots.
- PCA: Principal Component Analysis for dimensionality reduction.

### 🧩 Pattern Recognition
- Clustering: K-Means and Hierarchical Clustering to group similar profiles.
- Association Mining: Apriori and FP-Growth algorithms to identify frequent risk behavior combinations.

### 🤖 Predictive Modeling
- Models Used: Logistic Regression, Decision Trees, Random Forest, SVM, Gradient Boosting.
- Evaluation Metrics: Accuracy, Precision, Recall, F1 Score, ROC-AUC, Confusion Matrix.

### 🌐 Geospatial Analysis
- Tools: Choropleth maps to visualize regional health disparities.
- Focus: Areas with high disease burden and limited healthcare access.

---

## 🛠 Tools & Technologies
- **Languages**: Python  
- **Libraries**: `pandas`, `NumPy`, `scikit-learn`, `seaborn`, `matplotlib`, `geopandas`, `folium`  
- **Visualization**: Tableau, Power BI  
- **Statistical Analysis**: SciPy, Statsmodels  
- **Geospatial Mapping**: GeoPandas, Folium  

---

## ✅ Expected Outcomes
- Insight into the most influential health determinants.
- Disease prediction models for early detection and intervention.
- Comparative global health analysis.
- Data-backed policy recommendations for public health organizations.

---

## 📂 Repository Structure
📁 data/ → Raw and cleaned datasets
📁 notebooks/ → EDA, modeling, and clustering notebooks
📁 visualizations/ → Charts, plots, maps
📄 README.md → Project overview and documentation
📄 requirements.txt → Python package dependencies
