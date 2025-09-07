# wellness-tourism-customer-prediction
Predicting customers most likely to purchase the "Wellness Tourism" travel package using machine learning and data-driven insights to optimize marketing strategies.
# Wellness Tourism Package Customer Prediction

## Project Overview
My company, **"Visit with Us"**, aims to expand its customer base by leveraging a **data-driven approach** to marketing.  
The company plans to launch a **"Wellness Tourism Package"**, designed to help travelers maintain, enhance, or kick-start a healthy lifestyle while improving overall well-being.

This project builds predictive models to identify customers most likely to purchase the Wellness Tourism Package, enabling **more efficient marketing expenditure** and **targeted campaigns**.

---

## Objectives
- Analyze customer data to understand purchase patterns.
- Build machine learning models to predict the likelihood of a customer purchasing the wellness package.
- Provide actionable insights and recommendations for **senior management**.
- Optimize marketing spend by focusing on high-probability leads.

---

## Notebook Contents
1. [Data Loading and Initial Review](#link1)  
2. [Exploratory Data Analysis (EDA): Univariate Analysis](#link2)  
3. [Exploratory Data Analysis (EDA): Multivariate Analysis](#link3)  
4. [Data Pre-Processing (for Modeling)](#link4)  
5. [Modeling: Bagging](#link5)  
6. [Modeling: Boosting](#link6)  
7. [Final Insights and Recommendations](#link7)  

---

## Methodology

### 1. Data Exploration
- Understand feature distributions, identify missing values, and detect outliers.
- Perform univariate and multivariate analysis for feature insights.

### 2. Data Preprocessing
- Encode categorical variables.
- Handle missing values and normalize data as required.
- Split data into training and testing sets.

### 3. Model Building
- **Decision Trees** and **Random Forests** for baseline modeling.  
- **Bagging and Boosting techniques**:  
  - BaggingClassifier  
  - AdaBoostClassifier  
  - GradientBoostingClassifier  
  - XGBoostClassifier  
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-Score, Confusion Matrix.

### 4. Model Tuning
- Hyperparameter tuning using GridSearchCV to optimize model performance.

### 5. Insights & Recommendations
- Identify the top predictors of customer purchase behavior.  
- Suggest targeted marketing campaigns for high-probability customers.  
- Provide actionable insights for maximizing return on marketing investment.

---

## Technologies Used
- **Python**
- **Pandas & NumPy** for data manipulation
- **Matplotlib & Seaborn** for visualization
- **Scikit-learn** for modeling and evaluation
- **XGBoost** for gradient boosting
- **Jupyter Notebook** for interactive analysis

---

## Installation

1. Clone the repository:
```bash
git clone https://github.com/mohitphulwani001/wellness-tourism-customer-prediction.git
cd wellness-tourism-customer-prediction


