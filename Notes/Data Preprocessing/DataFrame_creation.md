To create a DataFrame, you can use various programming languages like Python (using libraries such as Pandas), R, or Julia. I'll provide an example using Python and Pandas since it's a popular choice for data manipulation and analysis tasks:

```python
import pandas as pd

# Creating a DataFrame from a dictionary
data = {'Name': ['Alice', 'Bob', 'Charlie', 'David'],
        'Age': [25, 30, 35, 40],
        'City': ['New York', 'Los Angeles', 'Chicago', 'Houston']}

df = pd.DataFrame(data)
print(df)
```

This will output:

```
      Name  Age         City
0    Alice   25     New York
1      Bob   30  Los Angeles
2  Charlie   35      Chicago
3    David   40      Houston
```

You can also create a DataFrame from a list of lists, a list of dictionaries, or by reading data from external sources like CSV files, Excel files, SQL databases, etc. The Pandas library provides various functions for these tasks. Here are some examples:

```python
# Creating DataFrame from a list of lists
data = [['Alice', 25, 'New York'],
        ['Bob', 30, 'Los Angeles'],
        ['Charlie', 35, 'Chicago'],
        ['David', 40, 'Houston']]

df = pd.DataFrame(data, columns=['Name', 'Age', 'City'])
print(df)
```

```python
# Creating DataFrame from a list of dictionaries
data = [{'Name': 'Alice', 'Age': 25, 'City': 'New York'},
        {'Name': 'Bob', 'Age': 30, 'City': 'Los Angeles'},
        {'Name': 'Charlie', 'Age': 35, 'City': 'Chicago'},
        {'Name': 'David', 'Age': 40, 'City': 'Houston'}]

df = pd.DataFrame(data)
print(df)
```

```python
# Creating DataFrame by reading from a CSV file
df = pd.read_csv('example.csv')
print(df)
```

Replace `'example.csv'` with the path to your CSV file. Similarly, you can use `pd.read_excel()` to read from Excel files, `pd.read_sql()` to read from SQL databases, etc.