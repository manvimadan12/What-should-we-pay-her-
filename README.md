# What-should-we-pay-her-
This repository contains the implementation of various regression algorithms to calculate that the upcoming employee should receive based on her experience and the role she is being offered. This project was for purpose of practice only, I would not recommend the use of any ML/AI algorithm to be used for determining the salary of an employee because these algorithms can have bias in the dataset itself. The intention behind the project is just to familiarise myself and the users of the repository, with the various regression algorthms.

# Dataset
The dataset contains following features:
* Position - This is the job title for which the employee is being hired (Text)
* Level - This is some internal band kind of metric to a company defining various levels of job titles (Int)
* Salary - This represents the salary (Whole numbers)

# Requirements
[Python](https://www.python.org/downloads/)

### Install the required libraries through command line

`pip3 intsall -r requirements.txt`

# Installation
Clone this repository:
git clone https://github.com/manvimadan12/What-should-we-pay-her-.git
or click Download ZIP in right panel of repository and extract the code

# Steps to run the notebook
Open Jupyter Notebook to view the following:
* Predict salary using SVM regression - Support Vector Machines for regression analysis
* Predict salary using Random Forest regression - Random Forest for regression analysis
* Predict salary using Decision tree regression - Decision Trees for regression analysis

# Results
* Results from polynomial regression
![Results from polynomial regression](https://github.com/manvimadan12/What-should-we-pay-her-/blob/master/polunomial_regression_result.png)

* Results from polynomial regression with high resolution and smoother curve
![Results from polynomial regression with high resolution and smoother curve](https://github.com/manvimadan12/What-should-we-pay-her-/blob/master/polunomisla_regression_smooth.png)

* Results from support vector regression
![Results from support vector regression](https://github.com/manvimadan12/What-should-we-pay-her-/blob/master/support%20vector%20regression.png)

* Results with support vector regression with high resolution and smoother curve
![Results with support vector regression with high resolution and smoother curve](https://github.com/manvimadan12/What-should-we-pay-her-/blob/master/support%20vector%20regression%20smoother%20curve%20and%20higher%20resolution.png)

# Limitations
An ML algorithm for such a small dataset can be an overkill. Basic statistical measures should suffice. However, for the educational purposes, it isn't a bad example. 
