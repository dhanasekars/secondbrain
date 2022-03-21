09-Mar-2022 | 16:04

Status : #SlipBox 
Tags :#CS #Python/Composing-Programs 


# Expressions

primitive expression: number is one kind of primitive expression
compound expression:  ```-1 - -1``` 
	here the operator are mathematical, *infix* - appears in between operands(numbers)

**call expression** most important kind of compound expression
eg: ``` max(7.5,10)```
  here operator specifies a *#function*, 

The functions ```max```  is called (Call expression) with arguments ( 7.5 and 10) and returns 10.

Advantages of functions notion over mathematical infix notation

1.  Functions may take an arbitrary number of arguments.    ```max(4,6,-5.6,9)```
2.  Functions nested expression are straightforward  
		 ```max(min(4,5), min(pow(5,6),-4))```
3. All complexities of mathematical notations that are hard to type ( like square root, subscripts) can be unified via call expression

```ad-tip
In #Python/Composing-Programs, any (mathematical) operator can be expressed as a function with a name.
```


---

# Reference
[[1.2 Elements of programming]]