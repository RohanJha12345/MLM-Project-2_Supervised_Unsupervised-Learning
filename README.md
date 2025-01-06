# 🌍 Import-Export Dataset Analysis with Supervised Learning  

![Global Trade Analysis](https://via.placeholder.com/1200x400?text=Global+Trade+Analysis+with+Machine+Learning&bg=blue)  

---

## **📄 Project Overview**  

This project leverages **supervised machine learning models** to analyze a rich dataset of **global trade transactions**, aiming to uncover patterns, classify data, and identify critical features for decision-making.  

### **Key Highlights**  
- **Dataset Size**: 5001 records (sampled from 15,000)  
- **Models Used**: Logistic Regression, SVM, Decision Trees, Random Forest, etc.  
- **Performance Metrics**: Accuracy, Recall, F1-Score, AUC, and more  

![Machine Learning Workflow](https://via.placeholder.com/800x300?text=Machine+Learning+Workflow)  

---

## **🗃️ Dataset Description**  
![Dataset Description](https://via.placeholder.com/800x400?text=Dataset+Description)  

- **Source**: [Kaggle Imports-Exports Dataset](https://www.kaggle.com/datasets/chakilamvishwas/imports-exports-15000)  
- **Key Variables**:  
  - **Transaction_ID**: Unique identifier for each transaction  
  - **Country**: Origin/Destination of trade  
  - **Product**: Item being traded  
  - **Value**: Trade value in USD  
  - **Shipping_Method**: Transport method (Air, Sea, Land)  
  - **Category**: Product type (e.g., Electronics, Clothing)  
- **Data Type**: Panel Data with categorical and numerical variables  

---

## **🎯 Project Objectives**  
- Classify the dataset using **supervised learning models**  
- Identify **significant features** for classification  
- Recommend the **best-performing model**  

---

## **🔍 Exploratory Data Analysis (EDA)**  

### **Data Preprocessing**  
- **Encoding**: Applied ordinal encoding for categorical variables  
- **Scaling**: Min-Max scaling for numerical columns  
- **Visual Checks**: Outliers and distributions analyzed  

### **Descriptive Insights**  
![Bar Chart Visualization](https://via.placeholder.com/800x400?text=Sample+Bar+Chart+of+Product+Quantities)  

- Central tendency (mean, median, mode) and dispersion analyzed  
- Correlation matrix used for identifying relationships  

### **Visualizations**  
![Heatmap](https://via.placeholder.com/800x400?text=Heatmap+of+Correlations)  
- **Heatmaps**: Relationships between variables  
- **Histograms**: Distribution of Quantity and Value  

---

## **🤖 Machine Learning Models**  
![Supervised Models](https://via.placeholder.com/800x300?text=Supervised+Learning+Models)  

### **Models Implemented**  
- **Logistic Regression**: Fast and interpretable; accuracy ~34.91%  
- **Support Vector Machines (SVM)**: Accurate but computationally intensive  
- **Decision Trees**: Moderate accuracy; highly interpretable  
- **Random Forest**: Best overall accuracy (~34.98%)  
- **K-Nearest Neighbors (KNN)**: Fast but lower accuracy  

### **Performance Metrics**  
- Accuracy, Precision, Recall, F1-Score, and AUC  
- **K-Fold Cross-Validation** ensures robustness  

---

## **📊 Key Observations**  

### **Model Comparisons**  
| Model              | Accuracy | Speed (Seconds) | Memory (MB) | Best For                   |
|--------------------|----------|-----------------|-------------|---------------------------|
| Logistic Regression | 34.91%   | 0.0255          | 0.34        | Quick Analysis            |
| Decision Trees      | 33.31%   | 0.0288          | 0.23        | Interpretability          |
| Random Forest       | 34.98%   | 1.0311          | 0.49        | Complex Datasets          |  

![Performance Graph](https://via.placeholder.com/800x400?text=Performance+Comparison+Graph)  

### **Significant Features**  
- **Country, Product, Shipping_Method, and Value**: High predictive power  
- **Customs_Code** and **Port**: Key contributors in ensemble models  

---

## **📈 Managerial Insights**  
![Managerial Insights](https://via.placeholder.com/800x400?text=Managerial+Insights)  

### **Key Recommendations**  
1. Address **class imbalance** with oversampling/undersampling.  
2. Use **Logistic Regression** for time-sensitive tasks.  
3. Leverage **Random Forest** for detailed analysis of complex datasets.  
4. Improve feature engineering for better model performance.  

### **Applications**  
- Optimizing trade routes and methods  
- Identifying high-value products and key trade partners  

---

## **📌 Getting Started**  
![Getting Started](https://via.placeholder.com/800x300?text=Start+Exploring+Trade+Data+Now)  

This repository provides a practical framework for applying **machine learning** to real-world trade datasets. Use it to:  
- Understand trade dynamics  
- Improve classification accuracy  
- Derive actionable business insights  

---

## **📂 Repository Structure**  
```plaintext
|-- data/  
|   |-- Imports_Exports_Dataset.csv  
|-- notebooks/  
|   |-- EDA_and_Models.ipynb  
|-- README.md  

