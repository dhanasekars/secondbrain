14-Mar-2022 | 12:31


---
# Calculating square root of a number

This is best way to illustrate [[Knowledge#^9ec506]]


STEP 1 : Define the algorithm

In order to determine a square root of any number say X, for start with guessing the square root of X, let say Y. 

Let say X = 55
guessing Y to be 8

Now average Y and X/Y 

(Y + X/Y) / 2 

(8+ (55/8)) / 2  = 7.4375

7.4162

Y.0000 then stop

55

### Pseudo code 

1. Get user to provide the number to which square root is to be calculated and store it in X. 
2. Now Start with Y = 1
3. Calculate Z =  (Y + X/Y) / 2 
4. Calculate Z * Z and compare with X.
5. Continue until Z * Z == X.0000  

---
# Reference
[[Algorithms]]

[[Computational Thinking MOC]]