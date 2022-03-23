`20-Mar-2022 | 11:47`

---
# Tuples

- These are [[Data structures]]  similar to functions, grouping together data.
- Similar to strings they are immutable. 
- A singleton tuple is represented as a(r,)
- Tuples help swapping numbers with out a temp variable.
- Helps in returning more than one value from functions.

### Repetition is possible

```py

>>3* ('a' , 2 )
>> ('a',2, 'a', 2, 'a', 2)

```

Like strings concatenation, indexing and slicing is possible.

```py

>>> x = (1, 2, (3, 'John', 4), 'Hi')
>>> 2 in x
True
>>> 3 in x 
False --> **important**
>>> 3 in x[2]
True 
```

^8c5ebc

 A slicing of tuple of length one will be (1,) [ with a comma]

---
# Reference

[[Introduction to Computation and Programming using Python]] Chapter 5