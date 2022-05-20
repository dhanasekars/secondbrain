`10-Apr-2022 | 07:42`

---
# Pandas

The most critical package for [[Data Science MOC]] 

Two primary [[Data structures]]

[[Data Frame]] (df) a two dimensional data.  It is as good as [[Python - Dictionaries]]

[[Series]] - one dimensional data - can be treated like any python [[Loops|iterable]]

```ad-tip
title: attributes

Pandas take the column name (series) and convert that to an attribute. So we can access that using dot notations

```

Assume a $csv$ has columns *day, temperature* and *condition*. 
Let's create a data frame 

```py

df = pandas.read_csv("file_name.csv")
df.condition 

-- other way is --

df["condition"]
```


---
# Reference

[[Data Science MOC]]

