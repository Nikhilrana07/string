# string
Completed  by nikhil
W=input("please enter a string")
def most_frequent(string):
d=dict()
for key in string:
if key not in d:
d[key] += 1
return d
Print(most_frequent(W))

<!---
