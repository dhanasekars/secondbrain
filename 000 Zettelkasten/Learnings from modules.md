`19-Mar-2022 | 19:09`

Status:  #SlipBox 
Tags: #CS #Python 

---
# Learnings from modules
-   Assume the two files below are in the same folder. You run inventory.py. What happens?

**TWO FILES**

FILE: batteries.py

aa = "AA"
aaa = "AAA"
c = "C"
d = "D" 

FILE: inventory.py

from batteries import *
aa = "aa"
print(aa, aaa, c, d)


> prints `aa AAA C D`


When not sure how modules are called and work, create these kind of simple files, with variables and explore to understand how modules work.

---
# Reference


[[Introduction to Computer Science and Programming Using Python MIT 6.00.1x]]