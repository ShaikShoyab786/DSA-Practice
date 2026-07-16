Day -1 
append()
- Adds one element

extend()
- Adds multiple elements

return
- Returns value from function

print()
- Displays output

Difference between append and extend function

append will take only one argument it can only one item whereas extend can mulitple items
if we append list into the list it will become nested, if we extend into the list it will remain single list 

arr = []

arr.append([10,20])

print(arr)
#output:
[[10,20]]  --> nested list

arr = []

arr.extend([10,20])

print(arr)
#output
[10,20]   -->single list 

