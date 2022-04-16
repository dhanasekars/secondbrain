`03-Apr-2022 | 12:10`

---
# Learning from cow transportation

Problem set 1 : Cow Transportation

Learned the usage of  $All$  and $map$  functions.

All can be used to check if all the conditions are True in iterable. I used this to check if all the weight inside a potential trip is less than the limit. By this it's not necessary to loop exclusively. 

```py
if all(p <= limit for p in weight_list):
	possible_list.append(item)
```

great example of [[map - python function]] is using it to find the length of list of lists. Call map with len function and pass the list of lists.

```py
map(len, possible_list)
```



---
# Reference
[[Introduction to Computational Thinking and Data Science 6.00.2x]]