

10-Mar-2022 | 17:18


---
# 1.3 Defining New [[Functions]]

Environments,  frames or scope refer this example 

[pythontutor](https://pythontutor.com/composingprograms.html#code=from%20operator%20import%20add,%20mul%0Adef%20square%28x%29%3A%0A%20%20%20%20return%20mul%28x,%20x%29%0A%0Adef%20sum_squares%28x,%20y%29%3A%0A%20%20%20%20return%20add%28square%28x%29,%20square%28y%29%29%0A%0Aresult%20%3D%20sum_squares%285,%2012%29&cumulative=true&curInstr=0&mode=display&origin=composingprograms.js&py=3&rawInputLstJSON=%5B%5D)


#### Name Evaluation :
Before : We stated that name is evaluated to the value associated with that name in the current environment.

Now after looking at model in which the expression are evaluated as frames, we can make our Name evaluation more preciously

```ad-note
title: Name Evaluation
collapse: open

Name evaluates to the value bound to that name in the earliest frame of the current environment.

```


Defining function : Method 2 : Local Assignments  - Assigning values to variable locally with in the function.




choosing names [[PEP 8]]


# Reference

[[Functions]]
