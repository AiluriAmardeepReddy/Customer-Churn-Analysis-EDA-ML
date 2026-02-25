# Customer Churn Analysis using EDA and Machine Learning

## 📌 Project Overview
Customer churn is a critical problem for subscription-based businesses, where retaining existing customers is often more cost-effective than acquiring new ones.  
This project focuses on analyzing customer behavior through **deep Exploratory Data Analysis (EDA)** and building a **baseline Machine Learning model** to predict customer churn.

The project follows an **EDA-driven Machine Learning approach**, where data understanding and feature insights are prioritized before model development.

---

## 🎯 Problem Statement
The objective of this project is to:
- Understand customer behavior and churn patterns
- Identify key factors that influence customer churn
- Build a baseline ML classification model to predict whether a customer is likely to churn

---

## 📂 Dataset Information
- **Dataset Name:** Telco Customer Churn Dataset
- **Source:** Kaggle (IBM Sample Dataset)
- **Description:**  
  Each row represents a customer, and each column contains customer demographic details, service usage, contract information, and billing data.

### Key Columns:
- Demographics: gender, SeniorCitizen, Partner, Dependents  
- Services: InternetService, OnlineSecurity, TechSupport, StreamingTV  
- Account Info: Contract, PaymentMethod, MonthlyCharges, TotalCharges  
- Target Variable: `Churn` (Yes / No)

---

## 🧹 Data Preprocessing
The following preprocessing steps were performed:
- Converted `TotalCharges` to numeric format
- Handled missing values and removed invalid records
- Removed identifier column (`customerID`)
- Encoded categorical variables using Label Encoding
- Ensured data consistency before analysis and modeling

---

## 🔎 Exploratory Data Analysis (EDA)
EDA was performed to deeply understand customer behavior and churn patterns.

### EDA Techniques Used:
- Univariate analysis for numeric and categorical features
- Bivariate analysis between features and churn
- Distribution analysis using histograms and countplots
- Boxplots to analyze churn vs numeric variables
- Crosstab analysis for categorical features vs churn
- Correlation analysis for numeric variables

### Key EDA Insights:
- Customers with **shorter tenure** are more likely to churn
- **Month-to-month contracts** have the highest churn rate
- Higher **MonthlyCharges** increase churn probability
- Long-term contracts significantly reduce churn
- Certain payment methods show higher churn tendencies

---

## 🤖 Machine Learning Model
After completing EDA, a **baseline Machine Learning model** was developed to validate insights.

### Model Details:
- Algorithm: Logistic Regression
- Type: Binary Classification
- Train-Test Split: 80% training, 20% testing
- Evaluation Metrics:
  - Accuracy
  - Precision
  - Recall
  - Confusion Matrix

### Model Outcome:
- The baseline Logistic Regression model achieved approximately **80% accuracy**
- The model performance confirms that insights obtained during EDA are meaningful for churn prediction

---

## 🛠️ Tools & Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook
- Git & GitHub

---

## 📌 Project Structure
Customer-Churn-Analysis-EDA-ML/
│
├── Customer Churn Analysis.ipynb
├── customer_churn.csv
├── README.md
## 📌 Repository Contents
- `Customer Churn Analysis.ipynb` – Jupyter notebook with EDA and ML workflow  
- `customer_churn.csv` – Dataset used for analysis  
- `README.md` – Project documentation  

---

## 🧠 Key Learnings
- Importance of EDA before applying Machine Learning
- Handling categorical data for ML models
- Understanding evaluation metrics beyond accuracy
- Building interpretable baseline ML models
- Translating data insights into business understanding

---

## 🚀 Future Improvements
- Try advanced models like Random Forest or XGBoost
- Handle class imbalance using resampling techniques
- Perform feature selection and scaling
- Hyperparameter tuning for improved performance

---

## 📬 Contact
**Ailuri Amardeep Reddy**  
- GitHub: https://github.com/AiluriAmardeepReddy  
- LinkedIn: https://linkedin.com/in/amardeep-reddy-ailuri-814908281  

---

⭐ If you find this project useful, feel free to explore or provide feedback.
