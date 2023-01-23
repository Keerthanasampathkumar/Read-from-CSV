# Read-from-CSV

## AIM:
To write a python to read data from CSV files.

## ALGORITHM:
### Step 1:
start python.

### Step 2:
import pandas.

### Step 3:
the number of rows returned is defined in pandas option settins

### Step 4:
read the contents of the CSV file using the df.read function.

### Step 5:
increase the maximum number of rows to display the entire dataframe.

## PROGRAM:
```
### NAME:Keerthana S
### REGISTER NUMBER:22009006
import pandas as pd
df=pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("Column",len(df.axes[0]))
print("Rows",len(df.axes[1]))
```
## OUTPUT:
![cs](https://user-images.githubusercontent.com/119477890/214050639-84375d37-79ae-4181-a58a-e242108bb9bc.png)


## RESULT:
Therefore the above code is successfully executed to read a csv file using pandas.
