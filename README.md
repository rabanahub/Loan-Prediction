# Loan-Prediction

**Dataset Information**

Dream Housing Finance company deals in all home loans. They have presence across all urban, semi urban and rural areas. Customer first apply for home loan after that company validates the customer eligibility for loan.Company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. To automate this process, they have given a problem to identify the customers segments, those are eligible for loan amount so that they can specifically target these customers.

This is a standard supervised classification task.A classification problem where we have to predict whether a loan would be approved or not. Below is the dataset attributes with description.

Variable	Description
	
Loan_ID	Unique Loan ID
Gender	Male/ Female
Married	Applicant married (Y/N)
Dependents	Number of dependents
Education	Applicant Education (Graduate/ Under Graduate)
Self_Employed	Self employed (Y/N)
ApplicantIncome	Applicant income
CoapplicantIncome	Coapplicant income
LoanAmount	Loan amount in thousands
Loan_Amount_Term	Term of loan in months
Credit_History	credit history meets guidelines
Property_Area	Urban/ Semi Urban/ Rural
Loan_Status	Loan approved (Y/N)
![image](https://github.com/user-attachments/assets/483dea41-60ad-4535-9d75-b80b24b05f52)


Import modules
1
import pandas as pd
2
import numpy as np
3
import seaborn as sns
4
from matplotlib import pyplot as plt
5
import matplotlib
6
%matplotlib inline
7
import warnings
8
warnings.filterwarnings('ignore')

**steps**

Loading the dataset

Preprocessing the dataset

Exploratory Data Analysis

Creation of new attributes¶

Log Transformation¶

Coorelation Matrix

Label Encoding

Train-Test Split

Hyperparameter tuning

Confusion Matrix


