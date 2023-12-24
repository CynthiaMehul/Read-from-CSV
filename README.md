# Read-from-CSV

## AIM:
To write a python program to read from a csv file

## EQUIPMENT'S	REQUIRED:
PC Anaconda - Python 3.7

## ALGORITHM:
### Step 1:
Import pandas as pd.
### Step 2:
Using pandas read the desired csv file.
### Step 3:
Print all the rows and columns to display it.
### Step 4:
Count number of rows and columns to display it.
### Step 5:
End program.

## PROGRAM:
```
#Program to read csv file.
#Developed by: Cynthia Mehul J
#Register Number: 23009725

import pandas as pd
f=pd.read_csv('nba.csv')
print(f.head(10))
print(f.tail())
print('Rows',len(f.axes[0]))
print('Columns',len(f.axes[1]))
```

## OUTPUT:
![label](/Program.jpg)

![label](/Output.jpg)

## RESULT:
Thus the program is written to read the csv file using the package pandas.
