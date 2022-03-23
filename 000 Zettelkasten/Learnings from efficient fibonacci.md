`22-Mar-2022 | 15:23`

Status: 
Tags: #Learnings 

---
# Learnings from efficient fibonacci


When working with logic of checking a collection and updating it - is a simple if & else loop.

if exist , do something
if not - add to the collection.

working simpler version

```py
def eff_fib(n, d):

if n in d:
	return d[n]
else:
	ans = eff_fib(n-1, d) + eff_fib(n-2, d)
	d[n] = ans
	return ans
  
d = {0:1, 1:1, 2:1 }
print(eff_fib(34,d))
```

The messy program

```py
def eff_fib(x):

fib_dict = {'0': 0, '1': 1}

if x == 0:
	return fib_dict['0']
elif x == 1:
	return fib_dict['1']
else:
	if (x-1) in fib_dict.keys():
		minus1 = fib_dict['(x-1)']
	else:
		minus1 = eff_fib(x-1)
		fib_dict['(x-1)'] = minus1
	if (x-2) in fib_dict.keys():
		minus2 = fib_dict['(x-2)']
	else:
		minus2 = eff_fib(x-2)
		fib_dict['(x-2)'] = minus2
		return minus1 + minus2


print(eff_fib(5))
```


---
# Reference
[[Computation thinking - Learnings]]