# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file.
## ALGORITHM:
### Step 1:
Import CSV file into Python using Pandas.
### Step 2:
Read the content of the csv file using pandas.read_csv
### Step 3:
Print the first 10 rows of the dataframe ,using df.head(10).
### Step 4:
To print the last n rows use, df.tail().
### Step 5:
Print the number of Rows using len(df.axes[0]).
### Step 6:
Print the number of Rows using len(df.axes[0]).
## PROGRAM:
```python
Developed by: Adhithya.S
Register Number: 22005823
import pandas as pd
df=pd.read_csv("Downloads/nba.csv")
print(df.head(10))
print(df.tail())
print("rows",len(df.axes[0]))
print("columns",len(df.axes[1]))
```
## OUTPUT:
![output](/filename1.png)
## RESULT:
A python program for reading content from a CSV file is written.