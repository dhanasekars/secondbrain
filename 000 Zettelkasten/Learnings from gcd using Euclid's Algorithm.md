`19-Mar-2022 | 20:32`



---
# Learnings from gcd using Euclid's Algorithm

Implementing [[Euclid's Algorithm]] using [[Recursive function]]


Using debugger helped to fix two logical flaws on the fly. There was one logical miss for not checking the condition when a is less than b.

Apply more [[Test as You Fly, Fly as You Test]]


---
# Code
```py
"""
Created on : 19, March 2022 20:00PM
@author : dhanasekars
"""

# Euclid's Algorithm to find GCD.
# gcd(a,b) is b if a = 0 or gcd(a,b) = gcb(a, b % a) [ where b > a ]
# Now implement the above
# First apply computational thinking.
# Since this is mathematical induction, we can use recurrsive function.
# What is the base case ? gcd(a,b) = b, when a = 0
# Inductive case is b % a where b > a
# Issue with version when, If initially a is small than b ,then it's calculating wrong
# Fix :: Set a = max(a,b) using a temp
# While debugging : Fixed swapping only when a is small, not every time
  

def gcdRecur(a,b):

"""
Finds the gcd of two given positive integer using Euclid's algorithm
a, b : Positive intergers
returns: a positive integer, the greatest common divisor of a & b
"""

if a < b:
	temp = b
	b = min(a,b)
	a = max(a,temp)
if b == 0:
	return a
else:
	return gcdRecur(b, a % b)
 
gcdRecur(140,154)


```




[[Computation thinking - Learnings]]