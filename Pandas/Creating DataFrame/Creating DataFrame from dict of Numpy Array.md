# Pandas **DataFrame**

- Pandas `DataFrame` is a powerful tool that allows us to store and manipulate data in a **structured** way, similar to an `Excel spreadsheet` or a `SQL Table`. A `DataFrame` is similar to a table with **rows** and **columns**. It helps in handling **large amounts of data**, **performing calculations**, **filtering information** with ease.

# Creating DataFrame from dict of Numpy Array

- We can create a **Pandas** `DataFrame` using a dictionary of **NumPy** arrays. Each key in the dictionary represents a **column** name and the corresponding **NumPy** array provides the values for that **column**.

```python
data = np.array([[1, 2, 3], [4, 5, 6], [7, 8, 9]])
df = pd.DataFrame(data, columns=['A', 'B', 'C'])
```

> If you print `df`, following will be the output
```
   A  B  C
0  1  2  3
1  4  5  6
2  7  8  9
```
