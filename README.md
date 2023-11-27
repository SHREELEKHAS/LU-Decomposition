# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3.  Define a package as "from scipy.linalg import lu_factor, lu_solve" and  create the variable as 'X' include the package in that variable.
4. print the variable 'X
  

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: SHREE LEKHA.S
RegisterNumber: 23014046
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: Shree Lekha.S
RegisterNumber: 23014046
'''
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=eval(input())
B=eval(input())
lu,piv=lu_factor(A)
P=lu_solve((lu,piv),B)
print(P)

```

## Output:
### Program to find L and U matrix using LU decomposition.
![output](/find%20lu.png)
### To find the LU Decomposition of a matrix
![output](/solve%20lu.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

