# Machine Learning-Based Financial Assistant

**Project Description:**  
This project is a machine learning-powered financial assistant that analyzes credit card spending and account transactions to provide personalized financial insights. Since real data was not available, I generated the entire dataset, simulating 510 users with diverse characteristics, including spending habits, account balances, and demographic features. Additional attributes, such as occupation, were randomly assigned following rules based on age, gender, income, and credit limits.  

The system predicts future spending, offers personalized budgeting suggestions, and presents visual reports to help users understand their financial behavior and make informed decisions.

---

## Technologies Used
- **Programming Language:** Python  
- **Data Processing:** Pandas, NumPy  
- **Machine Learning:** Scikit-Learn, XGBoost, Random Forest  
- **Visualization:** Matplotlib, Seaborn  
- **Application Interface:** Streamlit  

---

## Dataset
- Base dataset: [Credit Card Customers on Kaggle](https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers)  
- Custom-generated dataset with 510 users, extended with demographic features and simulated transaction histories  

---

## Methodology

### 1. Data Research and Preparation
- Simulated user dataset preserving the original data distributions  
- Added additional features like occupation based on rules considering age, income, gender, and credit limit  
- Created meaningful transaction histories for credit card spending and account movements using Python  

### 2. Exploratory Data Analysis & Visualization
- Conducted various exploratory data analyses to identify trends, anomalies, and patterns  
- Generated visual reports to better understand customer behavior and spending habits  

### 3. Data Preprocessing & Feature Engineering
- Added new features to the dataset to improve model performance, including:
  - Most frequent and highest spending categories (monthly and overall)  
  - Ratios of monthly spending changes  
- Handled missing values, data type conversions, and scaling  
- Applied encoding techniques (label, one-hot, ordinal) for categorical variables  

### 4. Machine Learning Model Training
- Trained regression models to predict next-month account balance, credit card spending, and transaction totals  
- Used grid search to optimize model parameters  
- Evaluated model performance with cross-validation and metrics such as R², MAE, and MSE  
- Selected the best-performing models for deployment in the application  

### 5. Application
- Developed a Streamlit-based interface to:
  - Provide predictions for new users  
  - Compare actual vs. predicted transactions  
  - Offer personalized suggestions and warnings  
  - Display interactive visual reports for financial insights  

