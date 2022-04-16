`21-Mar-2022 | 11:50`


---
# Dictionaries

It's similar to [[Lists]]  but index through key value. So indexing can be any key not necessarily an integer as in lists.

- Dict is mutable.
- Can be tested using 'in' 
- keys() & values() method returns all keys & values as a view (iterable / collections)
	- No guaranteed order of the collections returned though


$dict.get("key")$  Returns the value of the key is present,  will return $None$ if the key is missing.


### KEY

- must be **unique**
- **immutable type** (string, int, tuple, float, bool)
- careful with **float** key

### VALUE
- any type
- duplicates allowed
- it can be a list or dictionary (as this is mutable)

Looping dictionary
```py
for (key, value) in student_dict.items():
```


---
# Reference
[[Data structures]]