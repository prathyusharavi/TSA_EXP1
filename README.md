# Ex.No: 01A PLOT A TIME SERIES DATA
###  Date: 

# AIM:
To Develop a python program to Plot a time series data (population/ market price of a commodity
/temperature.
# ALGORITHM:
1. Import the required packages like pandas and matplot
2. Read the dataset using the pandas
3. Calculate the mean for the respective column.
4. Plot the data according to need and can be altered monthly, or yearly.
5. Display the graph.
# PROGRAM:
```
import pandas as pd
import matplotlib.pyplot as plt

df=pd.read_csv('Toyota.csv')
```
```
x=df['Age']
y=df['HP']

plt.figure(figsize=(10, 6))
plt.bar(x,y)
plt.title('toyota')
plt.xlabel('Age')
plt.ylabel('HP')
plt.grid(True)
plt.show()
```











# OUTPUT:






# RESULT:
Thus we have created the python code for plotting the time series of given data.
