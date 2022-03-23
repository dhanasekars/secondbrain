`17-Mar-2022 | 17:14`



---
# Function scope

Inside a function CANNOT modify a variable defined outside -- Second example.
Where as you can use the variable defined outside -- first example.


``` py

def g(y):

print(x)

print(x+1)
 
x = 5

g(x)
# in this case function will print the global value of x
 

def h(y):
x = x + 1
x = 5
h(x)
print(x)

  

# This will through UnboundLocalError because X is not assigned before it can be executed [ x =x + 1]
```


---
# Reference

[[Defining functions]]
