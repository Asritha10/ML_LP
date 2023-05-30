# Machinelearning_Loanprediction
**Problem Statement :**

Loans are the core business of banks. The main profit comes directly from the loan’s interest. The loan companies grant a loan after an intensive process of verification and validation. However, they still do not have assurance if the applicant is able to repay the loan with no difficulties. The two most critical questions in the lending industry are:

1. How risky is the borrower?
1. Given the borrower’s risk, should we lend him/her?

In the modern era, the data science teams in the banks build predictive models using machine learning to predict how likely a client is going to default the loan when they only have a handful of information. Loan Prediction is a very common real-life problem that each retail bank faces at least once in its lifetime. If done correctly, it can save a lot of man hours at the end of a retail bank.

**Goal of this Project:**

The Dream Housing Finance Company handles all types of mortgages. All urban, semi-urban, and rural environments are home to them. After the company confirms the customer's eligibility for a loan, the customer applies for a house loan. The business wants to automate (in real-time) the loan eligibility process using the information customers supply on the online application form.

They have created a problem to help them identify the client groups that are qualified for a certain loan amount in order to automate this procedure and target these consumers in particular. This research aims to forecast whether a loan application will be granted or denied.

**Hypothesis Generation :**

The following are the variables that I believe can have an impact on loan approval, which is the dependent variable in this loan prediction problem:

• Salary: Loan approval odds should be higher for applicants with high incomes.

• Previous History: Candidates who have paid off previous debts might have a better chance of getting a loan approved.

• Loan Amount: The loan amount should also factor towards loan approval. The likelihood of loan acceptance should be high if the loan amount is less.

• Loan Term: Loans with shorter terms and smaller amounts should have a better probability of being approved.

• EMI: Lower monthly payment amounts increase the likelihood that a loan will be approved.
 **Data Source:**

For this problem, we have two CSV files: train and test. Train file will be used for training the model, i.e., our model will learn from this file. It contains all the independent variables and the target variable. Test file contains all the independent variables, but not the target variable. We will apply the model to predict the target variable for the test data. Given below is the description for each variable with its data type.We have 614 rows and 13 columns in the train dataset and 367 rows and 12 columns in the test dataset.





