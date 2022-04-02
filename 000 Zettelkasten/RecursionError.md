`29-Mar-2022 | 10:52`

---
# RecursionError


An error when the program cross the [[Recursive function]] limit.
By default the limit is set to 3000 in Pyhton3 
```py

import sys

sys.getrecursionlimit() # check the current limit

sys.setrecursionlimit(4000) # to change the limit to new value
```

