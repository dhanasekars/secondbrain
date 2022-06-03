`03-Jun-2022 | 09:01`

---
# Data Selection in Pandas


There are native accessors used to select column, like df['column_name']
[[Pandas]] has its own accessors 

### Indexed based accessor

$iloc$ is used for index based selection. Selection here is based on numerical position.
This excludes the last item [0:100] select up-to 99 not including index 100. This will return 100 elements


### Label based accessor

$loc$ is used to select based on label.  This selection includes the last item in the list. [0:100] will return 101 items from zero to 100 inclusive.

---
# Reference
