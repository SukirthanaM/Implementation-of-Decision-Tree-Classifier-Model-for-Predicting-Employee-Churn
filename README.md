# Implementation-of-Decision-Tree-Classifier-Model-for-Predicting-Employee-Churn

## AIM:
To write a program to implement the Decision Tree Classifier Model for Predicting Employee Churn.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. 
2. 
3. 
4. 

## Program:
```
/*
Program to implement the Decision Tree Classifier Model for Predicting Employee Churn.
Developed by: Sukirthana.M
RegisterNumber: 212224220112

import pandas as pd
data=pd.read_csv("Employee.csv")

data.head()

data.tail()

data.isnull().sum()

data["left"].value_counts()

from sklearn.preprocessing import LabelEncoder
le=LabelEncoder()

data["salary"]=le.fit_transform(data["salary"])
data.head()

x=data[["satisfaction_level", "last_evaluation", "number_project", "average_montly_hours", "time_spend_company", "Work_accident", "promotion_last_5years","salary"]]
x

y=data["left"]
y

from sklearn.model_selection import train_test_split
x_train, x_test, y_train, y_test=train_test_split(x,y, test_size=0.2, random_state=100)

from sklearn.tree import DecisionTreeClassifier
dt=DecisionTreeClassifier(criterion="entropy")
dt.fit(x_train,y_train)
y_pred=dt.predict(x_test)

from sklearn import metrics
accuracy=metrics.accuracy_score(y_test, y_pred)
accuracy

dt.predict([[0.5, 0.8, 9, 260, 6, 0, 1, 2]])
*/
```

## Output:
![image](https://github.com/user-attachments/assets/e114d948-f652-49b5-811a-8af0323f1910)
![image](https://github.com/user-attachments/assets/1c38e87d-3513-4dc1-be78-05c8e1f3a092)
![image](https://github.com/user-attachments/assets/1316571b-b745-4550-99c5-9d2ada0fa273)
![image](https://github.com/user-attachments/assets/8941d23c-29b2-46df-93b0-34376d28b899)
![image](https://github.com/user-attachments/assets/8b06194d-4619-4946-9b90-b4f8893182ab)
![image](https://github.com/user-attachments/assets/95acf10b-d39d-4c39-a7c4-6242158855eb)
![image](https://github.com/user-attachments/assets/8c33cd4a-e49e-43f8-938c-54d0c25c650f)
![image](https://github.com/user-attachments/assets/9e743458-02b2-460c-9bb6-37fc88097a9e)
![image](https://github.com/user-attachments/assets/1d7b5c21-5fe6-487f-80b1-49b486cef75a)




## Result:
Thus the program to implement the  Decision Tree Classifier Model for Predicting Employee Churn is written and verified using python programming.
