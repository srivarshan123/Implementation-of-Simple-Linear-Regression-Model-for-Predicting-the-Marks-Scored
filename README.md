# Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored

## AIM:
To write a program to implement the simple linear regression model for predicting the marks scored.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
```import pandas as pd
import matplotlib.pyplot as py
data=pd.read_csv("student_scores .csv")
data.head()
data.isnull().sum()
x=data.Hours
x.head()
y=data.Scores
y.head()
n=len(x)
m=0
c=0
L=0.01
loss=[]
for i in range(10000):
    ypred=m*x+c
    MSE=(1/n)*sum((ypred-y)*2)
    dm=(2/n)*sum(x*(ypred-y))
    dc=(2/n)*sum(ypred-y)
    c=c-L*dc
    m=m-L*dm
    loss.append(MSE)
print(m,c)
y_pred=m*x+c
py.scatter(x,y,color="red")
py.plot(x,y_pred)
py.xlabel("study hours")
py.ylabel("Scores")
py.title("Study hours vs Scores")
py.plot(loss)
py.xlabel("iterations")
py.ylabel("loss")
/*
Program to implement the simple linear regression model for predicting the marks scored.
Developed by: SriVarshan.S
RegisterNumber:212221040163  
*/
```

## Output:
![simple linear regression model for predicting the marks scored](https://github.com/srivarshan123/Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored/blob/main/WhatsApp%20Image%202022-05-09%20at%209.37.43%20AM.jpeg)
![simple linear regression model for predicting the marks scored](https://github.com/srivarshan123/Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored/blob/main/WhatsApp%20Image%202022-05-09%20at%209.37.43%20AM.jpeg)
![simple linear regression model for predicting the marks scored](https://github.com/srivarshan123/Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored/blob/main/WhatsApp%20Image%202022-05-09%20at%209.37.47%20AM%20(2).jpeg)
![simple linear regression model for predicting the marks scored](https://github.com/srivarshan123/Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored/blob/main/WhatsApp%20Image%202022-05-09%20at%209.37.47%20AM.jpeg)
![simple linear regression model for predicting the marks scored](https://github.com/srivarshan123/Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored/blob/main/WhatsApp%20Image%202022-05-09%20at%209.38.03%20AM.jpeg)


## Result:
Thus the program to implement the simple linear regression model for predicting the marks scored is written and verified using python programming.
