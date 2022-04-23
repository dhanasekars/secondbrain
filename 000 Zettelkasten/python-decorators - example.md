`22-Apr-2022 | 21:27`

---
# python-decorators - example

Mistakes made - the decorator should return the value not the counter function.
You have to call  *fast_function()* and *slow_function()*

```py
import time  
  
current_time = time.time()  
print(current_time)  
  
  
def speed_calc_decorator(function):  
    def counter():  
        start_time = time.time()  
        function()  
        stop_time = time.time()  
        execution_time = stop_time - start_time  
        print(f"{function.__name__} run speed : {execution_time}")  
  
    return counter  
  
  
@speed_calc_decorator  
def fast_function():  
    for i in range(10000000):  
        i * i  
  
  
@speed_calc_decorator  
def slow_function():  
    for i in range(100000000):  
        i * i  
  
  
fast_function()  
slow_function()
```

---
# Reference
