# Quine

This is a Quine written in Python ([pyquine](\pyquine.py))
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
© 2021 GitHub, Inc.
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
```
 
