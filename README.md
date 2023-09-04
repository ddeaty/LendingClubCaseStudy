# Lending Club Case Study
================================================================================================================================

## General Information

### Project Information

> The project is a data science project that uses the lending club data set to predict whether a loan will be defaulted or not.

### Project Statement

> Find the driving factors which lead to the defaulted loans which are major source of loss for the company.

### Data Set

> The data set is a csv file with the loan data for the Lending Club.

### Methods Usedology
* Exploratory Data Analysis
* Data Visualization

### Technologies Used

- Python -version 3.11.3
- Pandas - version 1.5.3
- NumPy - version 1.23.5
- Seaborn - version 0.12.2
- MatplotLib - version 3.4.3
- Plotly - version 5.7.0
- Jupyter Notebook - Version 6.5.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

=================================================================================================================================


## Objective

Lending Club is a marketplace for personal loans that matches borrowers who are seeking a loan with investors looking to lend money and make a return. For lending companies, lending loans to risky applicants is the largest source of financial loss. The credit loss is the amount of money lost by the lender when the borrower defaults to a loan payment. In such a case, the concerned person is labelled as **charged-of** and **defaulters**. 

If one is able to *identify these risky loan applicants*, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

In other words, **the company wants to understand the driving factors (or driver variables)** behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment.



## Project Description and Understanding

You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

	 If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
	 If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

The data given contains the information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

In this case study, we used EDA to understand how consumer attributes and loan attributes influence the tendency of default.
 
When a person applies for a loan, there are two types of decisions that could be taken by the company:

### Loan accepted: ### 
	If the company approves the loan, there are 3 possible scenarios:

      * Fully paid: Applicant has fully paid the loan (the principal and the interest rate)
      * Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.
      * Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 

### Loan rejected: ### 
	The company rejects the loan application in possible scenarios:
    
      * Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

 **Thus company wants to understand the driving factors behind loan default.**
 

## Problem Statement
When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

	If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company.

	If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.

So, company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilize this knownledge for its portfolio and risk assessment. 

<br>


## Problem Solving Methodology
* Data Understanding-
> Understanding and working with data dictionary and getting good knowledge of all the columns and their domain specific uses. Understand the key characteristics, such as data volume and the total number of variables in the data. Understand the problems with the data, such as missing values, inaccuracies, and outliers.
* Data Cleaning-
> Removing null valued columns, single uniques columns, unnecessary columns then manipulation of data such as conversion of data types, removing outliers, deriving new variables and many more.
* Data Manuplation-
> Understanding the process of organizing or arranging data in order to make it easier to interpret and make reading or interpreting the insights from the data more structured and comprises of having better design.
* Derived Variables
> These are computed from one or more variables in the dataset. They are created by calculating or categorizing variables that already exist in your data set to get more presise information. 
* Univariate Analysis-
> Analysing each columns and plotting the distribution of each to get more information.
* Segmented Univariate Analysis-
> To get more insight of single data variables in the form of segments.
* Bivariate Analysis-
> Through this we can analyse two variables and determine empirical relationship between them.
* Multivariate Analysis-
> Through this we can analyse more then two variables and determine correlation matrix between them.
* Recommendations-
> Atlast we can recommend the investor what all variables to be considered while approving the loan so that loss of the company can be reduced. 

<br>

## Conclusions

- Major Driving factor which can be used to predict the chance of defaulting and avoiding Credit Loss:
  1. DTI
  2. Grades
  3. Verification Status
  4. Annual income
  5. Interest rates
  6. Loan Term
- Other considerations for 'defaults' :
  1. Borrowers are taking loans for a term of 60 months.
  2. Borrowers whose loan status is ‘Verified’ as they took a high loan amount with 60 months tenure.
  3. Borrowers who have home ownership as ‘Rent’ and take loans for the purpose of debt consolidation.
  4. Borrowers whose annual income is low i.e. (0-20000).
  5. Borrowers who take loan amounts in the range of 0 to 14000.
  6. Borrowers who receive interest at the rate of 15-20%.
  7. Borrower who takes a loan for the purpose of small business.
  8. Borrowers with lower Grades i.e., F<G.
  9. Borrower’s whose subgrade is F5, G3, G5.


## Acknowledgements

This project was inspired by UpGrad IITB Programme as a case study for the Machine Learning and Artificial Intelligence course.

=====================================================================================================================================

## Contributors
* [Debasish Deaty] 
Email: ddeaty@gmail.com 
(https://github.com/ddeaty/)

======================================================================================================================================

