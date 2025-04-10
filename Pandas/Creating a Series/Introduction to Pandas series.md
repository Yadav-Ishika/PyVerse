# Pandas Series
- A `Series` in `Pandas` is a **one-dimensional labeled array** that can hold any data type such as integers, strings, floats, or even Python objects. It is similar to a list or a `NumPy` array, but with an added feature — indexing.

 - Each value in a `Series` is associated with a label (index), allowing for easy data **access** and **manipulation**. By default, the index is numeric starting from 0, but **custom labels** can be assigned
 
``` Python
 # import pandas as pd
import pandas as pd

# simple array
data = [1, 2, 3, 4]

ser = pd.Series(data)
print(ser)
```

> The output of the above code would be
```
0    1
1    2
2    3
3    4
dtype: int64
```

# Key Concepts of Pandas Series & Index
  - `Pandas Series` is a **one-dimensional labeled array**, similar to a single column in a spreadsheet or `SQL table`. It can hold various data types, such as **integers**, **floats**, **strings**, or even `Python` objects.
  - The **index** in a `Series` refers to the set of axis labels used to identify and access data. It acts like row identifiers but offers **greater flexibility** compared to **standard arrays**.
  - `Index` labels can be non-unique but must be `hashable` (like **strings**, **integers**, or **tuples**), allowing them to function efficiently as keys for lookup operations.
  - `Pandas` supports both **integer-based indexing** (.iloc[]) and label-based indexing (.loc[]), offering **versatile** access patterns for **data manipulation**.
  - The `Series` object comes with a wide range of **index-related methods** such as `set_index()`, `reset_index()`, `reindex()`, and `sort_index()`, enabling powerful **data alignment** and **transformation**.


