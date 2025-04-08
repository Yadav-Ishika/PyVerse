# Pandas **DataFrame**

- Pandas `DataFrame` is a powerful tool that allows us to store and manipulate data in a **structured** way, similar to an `Excel spreadsheet` or a `SQL Table`. A `DataFrame` is similar to a table with **rows** and **columns**. It helps in handling **large amounts of data**, **performing calculations**, **filtering information** with ease.

# Creating a DataFrame from a List

- A simple way to create a `DataFrame` is by using a **single list**. **Pandas** automatically assigns index values to the **rows** when you pass a list.
  - Each item in the **list** becomes a **row**.
  -  The `DataFrame` consists of a single unnamed **column**.

```python
lst = ['Geeks', 'For', 'Geeks', 'is', 'portal', 'for', 'Geeks']

df = pd.DataFrame(lst)
```

> If you print `df`, following will be the output
```
       0
0   Geeks
1     For
2   Geeks
3      is
4  portal
5     for
6   Geeks
```
