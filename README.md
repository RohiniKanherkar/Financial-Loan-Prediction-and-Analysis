# Financial Loan Prediction and Analysis  

**Overview**  
This repository contains Python code and a Power BI dashboard for a project that analyzes financial loan data and classifies loan statuses. The project provides actionable insights and predictive capabilities using machine learning and interactive visualizations.  

---  

**Dataset**  
The dataset consists of **38,576 rows** and **14 columns**, covering various financial and demographic attributes.  

* **Numerical Features:**
  * **`id`**: Unique identifier for each loan record.  
  * **`member_id`**: Identifier for the loan applicant.  
  * **`annual_income`**: Applicant's annual income.  
  * **`dti`**: Debt-to-income ratio.  
  * **`installment`**: Monthly installment amount.  
  * **`int_rate`**: Interest rate for the loan.  
  * **`loan_amount`**: Total loan amount applied for.  
  * **`total_acc`**: Total number of credit accounts.  
  * **`total_payment`**: Total payment made on the loan.  

* **Categorical Features:**
  * **`address_state`**: State of residence of the applicant.  
  * **`application_type`**: Type of loan application (individual or joint).  
  * **`emp_length`**: Employment length in years.  
  * **`grade`**: Overall grade of the loan.  
  * **`home_ownership`**: Home ownership status.  
  * **`loan_status`**: Loan status (target variable).  
  * **`purpose`**: Loan purpose.  
  * **`sub_grade`**: Subgrade of the loan.  
  * **`term`**: Loan term duration.  

---  

**Data Cleaning and Preprocessing**  
The dataset was cleaned and preprocessed to handle missing values, outliers, and inconsistencies.  

---  

**Feature Importance**  
Feature importance analysis identified the following top features as the most influential in predicting loan approval:  

* **`emp_title`**: The job title of the applicant.  
* **`dti`**: The debt-to-income ratio.  
* **`annual_income`**: The annual income of the applicant.  
* **`loan_amount`**: The amount of the loan.  
* **`int_rate`**: The interest rate of the loan.  
* **`sub_grade`**: The loan subgrade.  

---  

**Model Training**  
Several machine learning models were trained and evaluated on the selected features:  

* **Linear Regression**  
* **Ridge Regression**  
* **Lasso Regression**  
* **Decision Tree Regressor**  
* **Random Forest Regressor**  

The best-performing model was selected based on metrics like accuracy, precision, recall, and F1-score.  

---  

**Power BI Dashboard**  
An interactive Power BI dashboard was created to visualize key insights, including:  

* Loan status distribution.  
* Feature importance analysis.  
* Model performance metrics.  
* Trends in loan issuance and repayment.  

---  

**Prerequisites**  

* **Python 3.x**  
* **Required Libraries:**  
  * `pandas`  
  * `numpy`  
  * `matplotlib`  
  * `seaborn`  
  * `sklearn`  
  * Power BI Desktop  

---  

**Installation and Usage**  

1. Clone the repository:  
   ```bash  
   git clone https://github.com/RohiniKanherkar/Financial-Loan-Prediction-and-Analysis.git  
