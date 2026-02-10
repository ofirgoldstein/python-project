# Loan Approval Analysis

## Project Overview
This project performs a comprehensive Exploratory Data Analysis on a dataset of 45,000 loan applications. 
The goal is to uncover patterns and relationships between demographic profiles, financial status, and loan outcomes, rather than just predicting approval.

## Dataset
- Source: Synthetic dataset based on Kaggle's Credit Risk data.
- Size: 45,000 records.
- Variables: 14 financial and personal features.

### Data Dictionary
| Variable Name | Description |
| :--- | :--- |
| `age` | Age of the customer |
| `person_gender` | Gender (0 = Female, 1 = Male) |
| `person_education` | Education level (High School to Doctorate) |
| `person_income` | Annual income |
| `person_emp_exp` | Years of employment experience |
| `person_home_ownership` | Home ownership status (OWN, RENT, MORTGAGE, OTHER) |
| `loan_amnt` | Amount of loan requested |
| `loan_intent` | Purpose of the loan (Education, Medical, Venture, etc.) |
| `loan_int_rate` | Interest rate of the loan |
| `credit_score` | Customer's credit score |
| `loan_status` | **Target Variable** (0 = Rejected, 1 = Approved) |

## Tools Used
- Language: Python
- Libraries: Pandas (Data Manipulation), Matplotlib & Seaborn (Data Visualization)
- Environment: Google Colab
