 11-Mar-2022 | 07:40



---
# Higher-Order [[Functions]]

[[Functions]] that manipulates functions are call [[Higher-Order Functions]]

How a function manipulates a function ?

By calling another functions as arguments.
By returning a function as return value.

Why to have higher order function ?

There are common programming pattern that recur in the code, in order to achieve abstractions assigning names for common pattern.

[[Higher order Programming]]

```ad-important
title: Patterns

express certain general patterns as named concepts, we need higher-order functions.

```

There is no ```()``` while passing function as argument, because ```()``` triggers the function call then and there. 

Example 

```py
screen.onkey(key='w', fun=user_defined)
```

Here $onkey$ is called higher order function, the one that takes function as input/argument is called as higher order function. 


---
# Reference
[[Functions]]