# Pandas **DataFrame**

- Pandas `DataFrame` is a powerful tool that allows us to store and manipulate data in a **structured** way, similar to an `Excel spreadsheet` or a `SQL Table`. A `DataFrame` is similar to a table with **rows** and **columns**. It helps in handling **large amounts of data**, **performing calculations**, **filtering information** with ease.

# Creating an Empty DataFrame

- An empty `DataFrame` in **pandas** is a table with no data but can have defined **column** names and indexes. It is useful for setting up a structure before adding data dynamically. An empty `DataFrame` can be created just by calling a **dataframe constructor**.

> Import Pandas library shown as below
```python
import pandas as pd
``` 

```python
df = pd.DataFrame()
```

> If you print `df`, following will be the output
```
Empty DataFrame
Columns: []
Index: []
```
