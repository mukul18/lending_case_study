# Project Name
Lending Club Case Study.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A finance company named 'Lending Club' specialises in lending various types of loans to customers. When the company receives a loan application, it has to make a decision for loan approval based on the applicant’s profile. <br>

There are two types of risks are associated with the bank’s decision:

(i) If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company.<br>
(ii) If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company<br>

Based on the dataset "loan.csv" company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
Python3 and below pyhton libraries -
- pandas: A fast, powerful, flexible and easy to use open source data analysis and manipulation tool. (To work with dataset)
- numpy: The fundamental package for scientific computing in Python. (Math Library)
- datetime: The datetime module supplies classes for manipulating dates and times.  
- matplotlib: A comprehensive library for creating static, animated, and interactive visualizations in Python. (To plot graphs)
- seaborn: A data visualization library built on top of matplotlib (To plot graphs)


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Conclusions
DrivingFactors(or driver variables):
- Grade :-Default Rate is high in high risk loan applicants. It would be important for LC to thoroughly vet high risk loan applications.
- Annual Income :-Applicants from 'Low'(<=45K USD) and 'Medium'(45K-90K USD) income group have a greater share of defaulted loans.
- Employment Length : Maximum number of defaulters have 10/10+ years of experience and 0 to 2 years of experience. Hence, LC should be take this aspect into consideration while lending loans.
- Loan Purpose :-The top two reasons for loans are debt consolidation and credit card. Such applications should be carefully assessed.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Acknowledgements
This project is part of "Executive PG Programme in Machine Learning & AI" sponsed through UPGRAD with Joint collaboration of IIIT-B

## Summary of the analysis and key take-aways
- Univariate Analysis
- Segmented Univariate Analysis
- Bi-variate Analysis

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy
- pandas 
- matplotlib.pyplot
- missingno
- seaborn
- datetime 

## Contact
Created by -

- Mukul Patel (mukul18@gmail.com)
- Nagaraj Gandge (gandge.nagraj11@gmail.com)


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
