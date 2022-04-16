`10-Apr-2022 | 22:15`

---
# comprehension structure

List comprehension : 

```py
new_list = [new_list for item in list {more for can come here as part of test p} if test]
```

Dictionary comprehension

```py

new_dict = {new_key: new_value for(key, value) in dict.items() if test }
```

Pandas DataFrame comprehension

```py

new_dict = {new_key: new_value for(index, row) in dataframe.iterrows() if test}

```



multiple for loop example 

```py
nato_result = [value for letter in user_name_list for (key, value) in nato_dict.items() if letter == key]
```

---
# Reference


[[List comprehension]]
[[Dict comprehension]]
[[Pandas]]