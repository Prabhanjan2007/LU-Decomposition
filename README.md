# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable
4. print the variable 'X'

## Program:
(i) To find the L and U matrix
```

Program to find the L and U matrix.
Developed by: B Prabhanjan
RegisterNumber: 212225040305

import numpy
from scipy.linalg import lu
a=eval(input())
P,L,U = lu(a)
print(L)
print(U)



```
(ii) To find the LU Decomposition of a matrix
```


Program to find the LU Decomposition of a matrix.
Developed by: B Prabhanjan
RegisterNumber: 212225040305

import numpy 
from scipy.linalg import lu
a=eval(input())
b=eval(input())
p,l,u = lu(a)
y=numpy.linalg.solve(l,p@b)
x=numpy.linalg.solve(u,y)
print(x)



```

## Output:

![alt text](<Screenshot 2026-03-23 194229.png>)

![alt text](<Screenshot 2026-03-23 194515.png>)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

