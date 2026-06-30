# 📊 Telecom Customer Churn Analysis using Python, SQL & Power BI

## 📌 Project Overview

Customer churn is one of the biggest challenges faced by telecom companies. Retaining existing customers is significantly more cost-effective than acquiring new ones. This project analyzes customer behavior, identifies the key factors influencing churn, predicts customer churn using Machine Learning, and presents business insights through an interactive Power BI dashboard.

---

## 🎯 Objectives

- Analyze telecom customer data to identify churn patterns.
- Perform Exploratory Data Analysis (EDA) to uncover business insights.
- Execute SQL queries for customer and revenue analysis.
- Build Machine Learning models to predict customer churn.
- Interpret model predictions using SHAP Explainability.
- Design an interactive Power BI dashboard for business decision-making.
- Provide actionable recommendations to improve customer retention.

---

## 📂 Dataset

- **Dataset:** IBM Telco Customer Churn Dataset
- **Total Records:** 7,032 Customers
- **Features:** 21
- **Target Variable:** Churn (Yes / No)

### Key Features

- Gender
- Senior Citizen
- Partner
- Dependents
- Tenure
- Contract Type
- Internet Service
- Payment Method
- Monthly Charges
- Total Charges

---

## 🛠️ Technologies Used

### Programming
- Python

### Python Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SHAP

### Database
- SQLite
- DB Browser for SQLite

### Visualization
- Power BI

### Development Environment
- Jupyter Notebook

---

```text

```

## 📈 Project Workflow

```text
Dataset
      ↓
Data Cleaning
      ↓
Exploratory Data Analysis
      ↓
SQL Analysis
      ↓
Feature Engineering
      ↓
Machine Learning
      ↓
Model Evaluation
      ↓
SHAP Explainability
      ↓
Power BI Dashboard
      ↓
Business Recommendations
```

---

# 🔍 Exploratory Data Analysis

The dataset was explored to identify trends and patterns influencing customer churn.

### Key Findings

- Customers with month-to-month contracts exhibit the highest churn rate.
- Customers with shorter tenure are more likely to leave the service.
- Higher monthly charges are associated with increased churn.
- Fiber Optic users experience relatively higher churn.
- Customers using Electronic Check show a higher churn rate.
- Gender has minimal impact on customer churn.

---

# 🗄️ SQL Analysis

Business-oriented SQL queries were performed to analyze customer behavior.

### SQL Operations

- Customer Count
- Churn Percentage
- Contract-wise Analysis
- Payment Method Analysis
- Revenue Analysis
- Customer Segmentation
- Window Functions
- Common Table Expressions (CTE)
- CASE Statements

More than **25 SQL queries** were executed to derive actionable business insights.

---

# 🤖 Machine Learning

### Models Implemented

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

### Model Performance

| Model | Accuracy |
|--------|----------|
| Logistic Regression | **78.75%** |
| Random Forest | **78.54%** |
| Decision Tree | **72.49%** |

Logistic Regression achieved the highest predictive accuracy for this dataset.

---

# 🔍 Explainable AI

SHAP (SHapley Additive Explanations) was used to interpret model predictions and identify the most influential features contributing to customer churn.

---

# 📊 Power BI Dashboard

The interactive dashboard provides business users with real-time insights into customer churn.

### Dashboard Features

- Total Customers
- Churned Customers
- Churn Rate
- Average Monthly Charges
- Average Customer Tenure
- Contract Type vs Customer Churn
- Internet Service vs Customer Churn
- Payment Method vs Customer Churn
- Gender vs Customer Churn
- Interactive Filters

---

# 💡 Business Recommendations

- Encourage customers to adopt long-term contracts.
- Improve customer retention strategies during the initial months.
- Review Fiber Optic service quality and pricing.
- Promote automatic payment methods.
- Introduce loyalty programs for long-term customers.
- Offer personalized retention campaigns for high-risk customers.
- Optimize pricing for customers with higher monthly charges.
- Enhance customer support services.

---

# 📌 Conclusion

This project successfully analyzed telecom customer churn using Python, SQL, Machine Learning, SHAP Explainability, and Power BI. The analysis identified key factors influencing churn and developed predictive models to support proactive customer retention strategies. The interactive dashboard enables business stakeholders to monitor churn trends and make informed decisions.

---

# 🚀 Future Enhancements

- Hyperparameter tuning for improved model performance.
- Deployment using Streamlit or Flask.
- Real-time churn prediction.
- Integration with cloud databases.
- Automated reporting dashboard.

---

# 👩‍💻 Author

**Rowthu Kalyani**

B.Tech - Information Technology

Vignan's Institute of Information Technology

📧 Connect with me on LinkedIn and GitHub.
