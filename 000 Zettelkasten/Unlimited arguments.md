`11-Apr-2022 | 16:24`

---
# Unlimited arguments

Unlimited positional arguments 

```py 
def i_sum(*args):  
    total = 0  
 for i in args:  
        total += i  
    return total  
  
  
print(i_sum(1, 2, 3, 4, 5, 6, 7, 8, 9, 10))
```

The type of ***args**  is tuple 

Unlimited keyword arguments 
The type of **\*\*kwargs** is dictionary 
you can use dict.get("key") so a missing key will return $None$ instead of erroring out.

---
# Reference
