# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
<br>Import pandas as pd and from sklearn import linear_model

### Step2
<br>Read the csv file from the drive

### Step3
<br>Drive the required list from the file

### Step4
<br>Print the list of the program

### Step5
<br>End the program

## Program:
```
#Python program to implement multivariate linear regression and predict the output.
#Developed by: M.Mugunthan
#Register Number: 24005593

import pandas as pd
from sklearn import linear_model

df=pd.read_csv("cars.csv")
a=df[['Weight','Volume']]
b=df[['CO2']]
regr=linear_model.LinearRegression()
regr.fit(a,b)
print("coefficient",regr.coef_)
print("Intercept:",regr.intercept_)
print("Amount:",regr.predict([[3300,1300]]))






```
## Output:
![Screenshot 2024-12-01 165506](https://github.com/user-attachments/assets/870207de-e920-4425-8238-8f98c5ddc8be)
![Screenshot 2024-12-01 165528](https://github.com/user-attachments/assets/31656d40-60a8-417f-84c4-5023dba70aa5)







## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
