`03-Apr-2022 | 12:21`

---
# Methods
methods - should always have self parameter , cannot be no parameter like [[Functions]]. This is to let the interpretor know which object is calling the method.

the below code explains the need of self

```py
class User:  
    def __init__(self, user_id, username):  
        self.id = user_id  
 self.username = username  
 self.followers = 0  
 self.following = 0  
  
 def follow(self, user):  
        self.following += 1  
 user.followers += 1  
  
  
user_1 = User("001", "angela")  
print(user_1.username)  
  
user_2 = User("002", "dhanasekar")  
print(user_2.id)  
  
user_2.follow(user_1)  
  
print(f"Followers count of {user_1.username} is {user_1.followers}")  
print(f"{user_2.username} is following {user_2.following} users and his followers count is {user_2.followers}")
```


---
# Reference

[[Object Oriented Programming]]