`20-Mar-2022 | 13:32`


---
# Lists

- List are mutable objects.  List = [1, 2,  'y', True]
- List[0] is 1
- index can be variable or expression - List [i -1]
```ad-tip
title: Slicing list

- Output will be list. Same like string. Even if it's one element, the return value is a list 
-  x = [1, 2, 3,]
- x[0:1] - is list with one elemnent

```

- Concatenation doesn't mutates the list but creates a new list.  
- Similarly sorted(x) will not mutate but creates a new list. 
- All methods applied on list mutates the list 
	- x.extend('e')
	- x.pop(1) - removes second element 
	- x.remove(e)  - remove 'e' added using 'extend'
	- x.del()
	- x.reverse() - mutates
Exception here are x.count() and x.index() do not mutate.
Lists and [[Strings]]

Converting a string to list using 'list'
```py
>> s = 'abc'
>> list(s)
[ 'a', 'b', 'c']
```

converting a list to string using 'join'
```py
>> "".join(s)
'abc'
```

Multiple variables can point to same list.

cool = ['blue', 'grey' ]
Aliasing -->  chill = cool
cloning -->  chill_new = cool[:]

---
# Reference
[[Introduction to Computation and Programming using Python]]
[[Data structures]]