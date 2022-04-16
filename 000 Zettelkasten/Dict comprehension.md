`10-Apr-2022 | 20:52`

---
# Dict comprehension

```py
"""  
Dictionary comprehension  
"""  
  
names = ['Alex', 'Beth', 'Caroline', 'Dave', 'Freddie', 'Eric']  
  
# from list  
"""  
new_dict = {new_key: new_value for item in list if test}  
"""  
# creating dict with random marks for the above names list  
  
students_scores = {student: random.randint(10, 100) for student in names}  
  
print(students_scores)  
  
# From dictionary  
"""  
new_dict = {new_key: new_value for (key, value) in dict.items() if test}  
"""  
  
passed_students = {student: score for (student, score) in students_scores.items() if score > 40}  
print(passed_students)  
  
  
sentence = "What is the Airspeed Velocity of an Unladen Swallow?"  
  
words = sentence.split()  
  
result = {word: len(word) for word in sentence.split()}  
print(result)
```

---
# Reference

[[List comprehension]]
[[Python - Dictionaries]]