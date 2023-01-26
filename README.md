# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file.



## ALGORITHM:
### Step 1:
Import pandas as pd.
### Step 2:
Read the CSV file using read_csv method.


### Step 3:
Use head and tail method to get the required contents from the file.
### Step 4:
Use len() method to get the number of rows and columns.
### Step 5:
Print the output.

## PROGRAM:
```python
'''
Developed by : Gumma Dileep Kumar
Reference number : 22007129
'''
import pandas as pd
df = pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("column", len(df.axes[0]))
print("rows", len(df.axes[1]))
```

## OUTPUT:


![Screenshot from 2023-01-26 14-17-03](https://user-images.githubusercontent.com/118707761/214809630-3a6a80d0-30bf-432a-82f5-ea44b4dc0575.png)

## RESULT:
Thus a python program is written to read the contents of a CSV file.
