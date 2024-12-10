# Analysis of Medicaid Expansion Policy Adoption on the Cost of Healthcare
This repository contains all materials and outlines all requirements to complete a case study on states' adoption of the Medicaid expansion policy and its impact on the personal healthcare expenses. 

![alt text](https://media.istockphoto.com/id/1255191189/vector/vector-of-senior-and-young-people-covered-by-health-insurance-being-assisted-by-medical-staff.jpg?s=612x612&w=0&k=20&c=XvBx0C4e6GTCoFjIAKwhgkgV_5CUvcWIcN0IUIpaKjg=)

## Outline 
There are multiple data files, all of which pulled from the Centers for Medicare & Medicaid Services, United States Census, and Federal Reserve for Economic Data. 
* [medicaid_enrollment.csv](https://github.com/kaylangu/DS4002-CS3/blob/main/DATA/medicaid_enrollment.csv) details the annual enrollment in Medicaid in each state of the US from the years 2014-2020.
* [medicaid_enrollment_percentage.csv](https://github.com/kaylangu/DS4002-CS3/blob/main/DATA/medicaid_enrollment_percentage.csv) details the annual enrollment in Medicaid as a percentage of the state population from the years 2014-2020. 
* [state_healthcare_expenses.csv](https://github.com/kaylangu/DS4002-CS3/blob/main/DATA/state_healthcare_expenses.csv) details the net annual healthcare costs in each state in millions of dollars of the US from the years 2014-2020.
* [average_salary_state.csv](https://github.com/kaylangu/DS4002-CS3/blob/main/DATA/average_salary_state.csv) details the average annual income of each state in the US from the years 2014-2023.
* [state_population.csv](https://github.com/kaylangu/DS4002-CS3/blob/main/DATA/state_population.csv) details the population in each state from the years 2014-2020.

## Getting Started
I would recommend writing all source code in a Jupyter Notebook, ideally using Python. This can easily be run on a virtual machine using [Google Colab](https://colab.research.google.com/). There are a couple important things to consider:
* The state expenses file sums up all personal healthcare expenses and is given in _millions of dollars_, so the state population data can be used to estimate the household or individual healthcare expenses.
* Expenses may vary state to state based on different costs of living, so the average salary per state is provided It may be useful to utilize this data to standardize the healthcare costs.
* Any context or technical materials that may be useful are in the [REFERENCES](https://github.com/kaylangu/DS4002-CS3/tree/main/REFERENCES) folder.  

Best of luck!
