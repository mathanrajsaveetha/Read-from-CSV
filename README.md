# Read-from-CSV

## AIM:

## ALGORITHM:
### Step 1:
Load the CSV into a DataFrame.

### Step 2:
Print the number of contents to be displayed using df.head().

### Step 3:
The number of rows returned is defined in Pandas option settings.

### Step 4:
Check your system's maximum column with the pd.options.display.max_column statement.

### Step 5:
Increase the maximum number of rows to display the entire DataFrame.

## PROGRAM:
`
```
DEVELOPED BY : MATHAN RAJ E
REGISTER NUMBER : 22008971

import pandas as pd
df= pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("column",len(df.axes[0]))
print("rows",len(df.axes[1]))
```
## OUTPUT:
![Screenshot (51)](https://user-images.githubusercontent.com/119560501/215308239-2c6ec8b7-5fa7-4d1b-b59d-5d582ee6244b.png)


## RESULT:
Thus the program is successfully executed.

