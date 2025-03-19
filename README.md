# 📊 Predictive Analytics on Household Income Dataset 

This project demonstrates **predictive analytics techniques** on a household dataset to 
predict **income levels** based on various demographic and socioeconomic features.  

We implement and compare two different machine learning algorithms: 

- **Decision Trees**  
- **XGBoost (GradientBoostingRegressor from scikit-learn)**  

Through **feature engineering, feature selection, and hyperparameter tuning**, we determine 
which model delivers the best performance for predicting household income. 

## Description

The models struggled with low R² values, indicating poor predictive power due to missing 
socioeconomic factors. XGBoost outperformed Decision Tree, but both under predicted high 
incomes. The models’ low predictive power suggests income is influenced by unaccounted 
socioeconomic factors like education, job sector, and economic conditions. The 
underprediction of high incomes implies bias, limiting real-world applicability for 
policy-making, credit risk assessment, and wage forecasting.

## 🛠️ Methodology  

This project follows a structured machine-learning pipeline:  

1. **Data Preprocessing**  

   - Handling missing values  
   - Encoding categorical variables  
   - Feature scaling  

2. **Exploratory Data Analysis (EDA)**  

   - Distribution of household income  
   - Identifying outliers (box plots, histograms)  
   - Correlation analysis  

3. **Feature Engineering & Selection**  

   - Creating polynomial features  
   - Recursive Feature Elimination (RFE)  
   - Feature importance analysis (XGBoost)  

4. **Model Training & Tuning**  

   - **Algorithms:** Decision Trees & XGBoost  
   - Hyperparameter tuning using **GridSearchCV**  
   - Model evaluation with **RMSE and R²**  

5. **Results & Model Comparison**  

   - Performance visualization (RMSE comparison, scatter plots)  
   - Residual analysis  
   - Feature importance insights 

## 📊 Key Findings  

- **XGBoost outperformed Decision Tree** in terms of RMSE and R² but still struggled 
with higher-income predictions.  
- **Both models under predicted high incomes**, indicating missing influential variables.  
- **Residual analysis** showed heteroscedasticity, implying the need for log 
transformations or additional socioeconomic variables.  

## 📂 Dataset  

The dataset is sourced from **Kaggle** and contains various household and individual 
income-related features.  
📌 **Dataset link**: [Kaggle Dataset](https://www.kaggle.com)  

## 💻 How to Run the Project  
### **1️⃣ Clone the Repository**

   ```bash
   git clone git@github.com:ahmeraza/Predictive_Analytics_Income_Data.git
```
