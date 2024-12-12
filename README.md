# Financial-Loan-Prediction-and-Analysis
This repository contains the Python code and Power BI dashboard for a project that analyzes financial loan data and classify loan Status.

# Dataset

The dataset consists of 38576 rows and 14 columns, including:

* **Integer Columns:**
  * `id`: Unique identifier  
  * `member_id`: Member identifier  
  * `annual_income`: Annual income of the applicant  
  * `dti`: Debt-to-income ratio  
  * `installment`: Monthly installment amount  
  * `int_rate`: Interest rate  
  * `loan_amount`: Loan amount  
  * `total_acc`: Total number of credit accounts  
  * `total_payment`: Total payment amount

* **Categorical Columns:**
  * `address_state`: Applicant's state of residence  
  * `application_type`: Type of loan application  
  * `emp_length`: Employment length  
  * `grade`: Loan grade  
  * `home_ownership`: Home ownership status  
  * `issue_date`: Loan issuance date  
  * `last_credit_pull_date`: Date of last credit pull  
  * `last_payment_date`: Date of last payment  
  * `loan_status`: Loan status (target variable)  
  * `next_payment_date`: Date of next payment  
  * `purpose`: Loan purpose  
  * `sub_grade`: Loan subgrade  
  * `term`: Loan term  
  * `verification_status`: Verification status of income and assets

 **Data Cleaning and Preprocessing**

The dataset was cleaned and preprocessed to handle missing values, outliers, and inconsistencies. 

**Feature Importance**

Feature importance analysis identified the following top features as the most influential in predicting loan approval:

* **`emp_title`**: The job title of the applicant
* **`dti`**: The debt-to-income ratio
* **`annual_income`**: The annual income of the applicant
* **`loan_amount`**: The amount of the loan
* **`int_rate`**: The interest rate of the loan
* **`sub_grade`**: The loan subgrade

**Model Training**

Several machine learning models were trained and evaluated on the selected features:

* **Linear Regression**
* **Ridge Regression**
* **Lasso Regression**
* **Decision Tree Regressor**
* **Random Forest Regressor**

The best-performing model was selected based on metrics like accuracy, precision, recall, and F1-score. 

**Power BI Dashboard**

An interactive Power BI dashboard was created to visualize key insights:

* Loan status distribution
* Feature importance analysis
* Model performance metrics
* Key trends and patterns in the data
* Etc

**Prerequisites**
* **Python 3.x**
  
**Required Python Libraries:**
* **pandas**
* **numpy**
* **matplotlib**
* **seaborn**
* **sklearn**

