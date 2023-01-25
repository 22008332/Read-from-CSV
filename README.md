# Read-from-CSV

## AIM:
To read the csv file and bring it in the output

## ALGORITHM:

### Step 1:
Import pandas as pd.

### Step 2:
Read the CSV file using read_csv method.

### Step 3:
 Use head and tail method to get the required contents from the file.

### Step 4:
Use len() method to get the number of rows and columns

### Step 5:
Print the output

## PROGRAM:
```python
#Developed by:Preethi.A.A
#Register Number: 22008332

import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("rows",len(df.axes[0]))
print("columns",len(df.axes[1]))
```
## OUTPUT:
#Developed by:Preethi.A.A

#Reference no:22008332

![](read%20csv.png)
![](read%20csv1.png)

## RESULT:

The above data is the required result brought by reading the csv file.