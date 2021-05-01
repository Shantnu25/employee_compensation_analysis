# Employee Compensation Analysis

The San Francisco Controller's Office maintains a database of the salary and benefits paid to City employees since fiscal year 2013.
The problem here is to predict the Total Compensation.

# Feature Description

Feature -	Description

Year Type -	Fiscal (July through June) or Calendar (Januar...

Year -	An accounting period of 12 months. The City an...

Organization Group -	Org Group is a group of Departments. For examp...

Department Code -	Departments are the primary organizational uni...

Union -	Unions represent employees in collective barga...

Job Family Code -	Job Family combines similar Jobs into meaningf...

Job Code -	Jobs are defined by the Human Resources classi...

Employee Identifier -	Each distinct number in the “Employee Identifi...

Retirement -	City contributions to employee retirement plans.

Health and Dental -	City-paid premiums to health and dental insura...

Other Benefits -	Mandatory benefits paid on behalf of employees...

Total Compensation (Target Variable)-	The sum of all salaries and benefits paid to C...

# Evaluation metrics

For this particular dataset, we are using r2 score as the evaluation metric.

r2_score (coefficient of determination) regression score function.

Best possible score is 1.0 and it can be negative (because the model can be arbitrarily worse).
A constant model that always predicts the expected value of y, disregarding the input features, would get a score of 0.0.

# Outcomes

In this project, I applied the following concepts:

    Train-test split
    Data Cleaning
    Linear Regression & Regularization Techniques
    r2_score Evaluation Metric

