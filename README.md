# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1

### Step2
<br>

### Step3
<br>

### Step4
<br>

### Step5
<br>

## Program:
```
#Developed by:ajina joshpin

#Registration name:23013547

import pandas as pd

from sklearn import linear_model

df=pd.read_csv('cars.csv')

a=df[['Weight', 'Volume']]

b=df[['CO2']]

regr=linear_model.LinearRegression()

regr.fit(a,b)

print("coefficient",regr.coef_)

print("Intercept:", regr.intercept_)

print("Amount:", regr.predict([[3300,1300]]))

```
## Output:

![Screenshot 2024-01-02 140430](https://github.com/ajinajoshpin/Multivariate-Linear-Regression/assets/148514578/7e75fd08-1183-4baf-8301-ec8ec9c2a7a8)

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
