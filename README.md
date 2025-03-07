# Ex.No: 01A PLOT A TIME SERIES DATA
###  Date: 07-03-2025
### NAME : YENUGANTI PRATHYUSHA

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
df.head()

```
![image](https://github.com/user-attachments/assets/b86bda39-e6d0-4d75-958c-1c657948d25b)


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

![image](https://github.com/user-attachments/assets/650c7562-e35b-44da-8ad1-1a4b9f4a8aa9)




# RESULT:
Thus we have created the python code for plotting the time series of given data.
