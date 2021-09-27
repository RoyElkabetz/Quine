# Quine

[pyquine](pyquine.py) is a Quine written in Python. 
```python
# This is a python quine
# the variables
q = chr(39)
idx = 8
 
 
# the string list
a = [
'# This is a python quine',
'# the variables',
'q = chr(39)',
'idx = 8',
' ',
' ',
'# the string list',
'a = [',
']',
' ',
' ',
'# the print',
'for i in range(idx):',
'    print(a[i])',
'for s in a:',
'    print(q + s + q + ",")',
'for i in range(idx, len(a)):',
'    print(a[i])',
]
 
 
# the print
for i in range(idx):
    print(a[i])
for s in a:
    print(q + s + q + ",")
for i in range(idx, len(a)):
    print(a[i])
```
 
