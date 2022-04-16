`10-Apr-2022 | 07:51`

---
# operating with file system

Getting relative path. 

```mermaid
graph TD

id1(\Root)
id2(ds)
id2.1(Desktop)
id2.2(App Brewery)
id2.2.1(my_text.file)
id2.2.2(Day 24)
id2.2.1.1(main.py)

id1-->id2
id2-->id2.1
id2-->id2.2
id2.2-->id2.2.2
id2.1-->id2.2.1
id2.2.2-->id2.2.1.1


```


From $main.py$  to access relative path of $/Desktop/my_text.file$

first $../$ makes working directory as $App Brewery$ 
next ../ makes working directory as $ds$  and this is where the common branch of the two files we are working, so now get into the path of file to be accessed, so 

from $main.py$ relative path to $my_file.txt$ will be 

$../../Desktop/my-file.txt$



---
# Reference
[[Computational Thinking MOC]]

Day 24 - [App Brewery](https://www.udemy.com/course/100-days-of-code/)
