`27-Mar-2022 | 18:30`

---
# List comprehension


```py
mixed = [ 1, 2, 'a', 2.3 ]    
mylist = [x * x for x in mixed if type(x) == int ]
print(mylist)

```

A consise way of applying an operation to the values in the list. While [[map - python function]] is way to apply a function to the values in the list.

The *for* clause in the list comprehension can be followed by one or more if and for.  The additional clauses are applied first that modify the sequence applied in the first for to which the operation associated with the comprehension is applied. 

In the above if is applied first and then for the modified sequence x * x is applied.

Best use case when you want to do L1 - L2   
[Stack over flow example](https://stackoverflow.com/questions/4211209/remove-all-the-elements-that-occur-in-one-list-from-another)


```py

new_list = [ new_item for item in list if test]
```

---
# Reference

[[Python]]