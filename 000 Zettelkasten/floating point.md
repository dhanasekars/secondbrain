15-Mar-2022 | 15:04


---
# floating point

```ad-caution
title: approximation

float values should be treated as approximations to real values. These approximations have only a finite amount of precision.

```


execute this code to refresh the memory on how floats are stored 
```
x = 0.0
for i in range(10):
	x = x + 0.1

print(x)

>>0.9999999999999999999
```

The output of above will not be  `1`


Floating points are stored by converting them into the whole number by raising it to two to power of N.

For example 0.625 can be converted to a whole number by multiplying it with 2 ** 3 ( 8) 

```
0.625 is
0.625 * 2 ** 8 = 5
0.625 = (5, 2 pow -3)
```

---
# Reference
[[Computational Thinking MOC]]

[15. Floating Point Arithmetic: Issues and Limitations — Python 3.10.4 documentation](https://docs.python.org/3/tutorial/floatingpoint.html)