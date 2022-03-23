15-Mar-2022 | 07:44

---
# Questions to ask while doing computational thinking
---


```ad-question
title: Common

1. What are the failure conditions?
2. What did I miss to think of ? 
3. What else is not implemented?
4. What can I do in v2.0 ?
5. Are you aware of [[floating point]] comparision? [ when *x* and *y* are float then compare  x == y rather do abs(x-y) < 0.000001 kind of comparision]
6. Did you make a simpler version of the problem to understand how computation works? [ Eg to know if comparion of tuple it True in a larger set did we apply that in smaller set applying [[Tuples#^8c5ebc]]

```

```ad-question
title: Loops

1. Did you initialise count before the loop?
2. Is the loop creation done as per syntax?
3. Are you decrementing the loop counter inside the loop?
4. Do you have a condition to check to terminate the loop?
5. Bonus : In #Python a loop variable can iterate over any iterable objects

```

^5ca036

```ad-question
title: [[Functions]]

1. Did I give an appropriate **name** to the function?
2. Is the function defined?
3. How many **parameters** [ zero or more ]
4. is the **[[docstring]]** meanigful?
5. is the function **body** preforming intented functionality? 
6. is your funtion **return** a value ? [ If not Python will return `None`]
7. Are you following practising of using keyword arguments while calling any function ? [ practise using this than positiional arguments]
8. While defining a function are you having default value for all your formal parameters?
9. Can I use recursive function in this context? 
10. 


```

^162e52

```ad-question
title: Objects

1. What type it is? use 
    >type(object)
3. is it scalar or non-scalar object
4. Is it mutable or immutable? 
5. is it Iterable ? 
6. What methods do I have

```

```ad-question
title: Data Structures

1. Are you iterating list and mutating it ? [ WARNING]. If required to iterate a list that is mutating , then first clone the list.
2. is the DS list of lists ? List of list of lists? and on and on and on...
3. 


```


---
# Reference
[[Computational Thinking MOC]]