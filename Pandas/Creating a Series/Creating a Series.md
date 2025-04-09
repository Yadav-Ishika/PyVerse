# Creating a Pandas Series

- In the real world, a Pandas Series will be created by loading the datasets from existing storage, storage can be SQL Database, CSV file, and Excel file. Pandas Series can be created from the lists, dictionary, and from a scalar value etc. Series can be created in different ways.

### Creating a series from array
- In order to create a series from array, we have to import a numpy module and have to use array() function.

``` Pandas
# import pandas as pd
import pandas as pd
 
# import numpy as np
import numpy as np
 
# simple array
data = np.array(['g','e','e','k','s'])
 
ser = pd.Series(data)
print(ser)
```
> Output 
  ```
  0    g
  1    e
  2    e
  3    k
  4    s
  dtype: object
  ```

### Creating a Series from lists

- In order to create a series from list, we have to first create a list after that we can create a series from list.

```Pandas
import pandas as pd
 
# a simple list
list = ['g', 'e', 'e', 'k', 's']
  
# create series form a list
ser = pd.Series(list)
print(ser)
```

> output 
```
0    g
1    e
2    e
3    k
4    s
dtype: object
```
