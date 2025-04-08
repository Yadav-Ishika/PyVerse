# Pandas **DataFrame**

- Pandas `DataFrame` is a powerful tool that allows us to store and manipulate data in a **structured** way, similar to an `Excel spreadsheet` or a `SQL Table`. A `DataFrame` is similar to a table with **rows** and **columns**. It helps in handling **large amounts of data**, **performing calculations**, **filtering information** with ease.

# Creating a DataFrame from a List of Dictionaries  

- We can also create `dataframe` using **List of Dictionaries**. It represents **data** where each dictionary corresponds to a **row**. This method is useful for handling structured data from `APIs` or `JSON` files. It is commonly used in **web scraping** and **API data processing** since `JSON` responses often contain **lists of dictionaries**.

```python
dict = {'name':["aparna", "pankaj", "sudhir", "Geeku"],
        'degree': ["MBA", "BCA", "M.Tech", "MBA"],
        'score':[90, 40, 80, 98]}

df = pd.DataFrame(dict)

```

> If you print `df`, following will be the output
```
     name  degree  score
0  aparna     MBA     90
1  pankaj     BCA     40
2  sudhir  M.Tech     80
3   Geeku     MBA     98
```
