# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
import pandas as pd

### Step2
read the csv file

### Step3
get the value of x and y variable

### Step4
create the linear regression model and fit

### Step5
predict the co2 emissionn of car where the weight is 2300kg and the volume is 1300cm cube

## Program:

import pandas as pd

from sklearn import linear_model

df=pd.read_csv("cars (1).csv")

a=df[['Weight','Volume']]

b=df[['CO2']]

regr=linear_model.linearRegression()

regr.fit(a,b)

print("Coefficient:",regr.coef_)

print("Intercept:",regr.intercept_)

print("Amount:",regr.predict([[3300,1300]])

## Output:

### Insert your output
![Screenshot 2024-01-01 140227](https://github.com/23004345/Multivariate-Linear-Regression/assets/138849203/9cfb1f15-1c75-4fbb-b6f9-b0f73ac2e9a0)


## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
