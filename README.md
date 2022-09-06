# pay-data
In this notebook we perform data exploration for the Glassdoor salary dataset:
https://glassdoor.app.box.com/v/gender-pay-data

First I'll load the libs needed for exploration.

## The dataset

Glassdoor salaries dataset
---------------------------

Dataset characteristics
-----------------------

Number of instances: 1000
Number of attributes: 8  predictive attributes (2 numerical, 4 categorical, 2 ordinal) and the target variable
Attribute information:
jobTitle: the job titles of the employees -  ['Graphic Designer' 'Software Engineer' 'Warehouse Associate' 'IT'
 'Sales Associate' 'Driver' 'Financial Analyst' 'Marketing Associate'
 'Data Scientist' 'Manager']
gender: the gender of the employees ['Female' 'Male']
age: the age of the employees
perfEval: the performance evaluation of the employees, from 1 to 5
edu: the educational level of the employees -  ['College' 'PhD' 'Masters' 'High School']
dept: the department that the employee is working on -  ['Operations' 'Management' 'Administration' 'Sales' 'Engineering']
seniority: the seniority level of an employee, from 1 to 5
basePay: the base salary of the employee
bonus: the bonus an employee will get based on the other attributes, this is our target variable.
