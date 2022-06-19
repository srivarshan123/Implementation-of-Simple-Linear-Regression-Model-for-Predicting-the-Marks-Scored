# Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored

## AIM:
To write a program to implement the simple linear regression model for predicting the marks scored.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program.
2. Import the numpy,pandas,matplotlib.
3. Read the dataset of student scores.
4. Assign the columns hours to x and columns scores to y.
5. From sklearn library select the model to train and test the dataset.
6. Plot the training set and testing set in the graph using matplotlib library.
7. Stop the program.

## Program:
/*
Program to implement the simple linear regression model for predicting the marks scored.
Developed by: SriVarshan.S
RegisterNumber:212221040163  
*/
```
import numpy as np
import pandas as pd
import matplotlib.pyplot as py
data=pd.read_csv("/content/student_scores (2).csv")
data.head()
data.tail()
x=dataset.iloc[:,:-1].values
y=dataset.iloc[:,1].values
print(x)
print(y)
from sklearn.linear_model import LinearRegression
regressor=LinearRegression()
regressor.fit(x_train,y_train)
y_pred=regressor.predict(x_test)
plt.scatter(x_train,y_train,color='blue')
plt.plot(x_train.regressor.predict(x_train),color='black')
plt.title("h vs s(Training set)")
plt.xlabel("Hours")
plt.ylabel("Scores")
plt.show()
plt.scatter(x_test,y_test,color='red')
plt.plot(x_train,regressor.predict(x_train),color='green')
plt.title("h vs s(Testing set)")
plt.xlabel("Hours")
plt.ylabel("Scores")
plt.show()
```

## Output:
![simple linear regression model for predicting the marks scored](https://github.com/srivarshan123/Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored/blob/main/WhatsApp%20Image%202022-05-09%20at%209.37.43%20AM.jpeg)
![simple linear regression model for predicting the marks scored](https://github.com/srivarshan123/Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored/blob/main/WhatsApp%20Image%202022-05-09%20at%209.37.43%20AM.jpeg)
![simple linear regression model for predicting the marks scored](https://github.com/srivarshan123/Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored/blob/main/WhatsApp%20Image%202022-05-09%20at%209.37.47%20AM%20(2).jpeg)
![simple linear regression model for predicting the marks scored](https://github.com/srivarshan123/Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored/blob/main/WhatsApp%20Image%202022-05-09%20at%209.37.47%20AM.jpeg)
![simple linear regression model for predicting the marks scored](https://github.com/srivarshan123/Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored/blob/main/WhatsApp%20Image%202022-05-09%20at%209.38.03%20AM.jpeg)


## Result:
Thus the program to implement the simple linear regression model for predicting the marks scored is written and verified using python programming.
