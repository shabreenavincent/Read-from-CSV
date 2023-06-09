# Read-from-CSV

## AIM:
To write a python program to read data from CSV file.
## ALGORITHM:
### Step 1:
Start the python.
### Step 2:
Import pandas.
### Step 3:
Mention the CSV file which is to be read.
### Step 4:
Read the contents of the CSV file using df.read function.
### Step 5:
End the program.

## PROGRAM:

student name:shabreena vincent
register no:212222230141

```
import pandas as pd
df = pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("column", len(df.axes[0]))
print("rows", len(df.axes[1]))
```
## OUTPUT:



![csv](https://github.com/shabreenavincent/Read-from-CSV/assets/119475721/5c39c581-9f96-47bf-af1d-39cd3224d1c6)



## RESULT:
A python program to read data from CSV files has been created successfully.
