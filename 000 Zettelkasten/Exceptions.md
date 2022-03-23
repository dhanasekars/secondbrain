`20-Mar-2022 | 19:11`


---
# Exceptions


Try:
except: 
else: - > gets in when no exceptions is raised
finally: --> No matter what run this, like closing a file that was opened early. Do all clean up work here before exiting.

We can raise our own excpetions

### Exceptions as a control flow mechanism

Don't think exceptions block is only for errors, they are more powerful. We can use them to control flows. Remember using it in [[CS50]] [[Flask]] exercise? Where a type casting error was captured and used to control the flow.

In [[Phython - Dictionaries]] we can use keyerror to control the flow. 

The best practical scenario is while dealing with lists or list of lists that don't have standard items in a list. 

Here use relevant logics and capture **index-error** exception and use that to control the flows.

[[Assertions]]

---
# Reference
[[Computational Thinking MOC]]
[[Introduction to Computation and Programming using Python]] Chapter 7