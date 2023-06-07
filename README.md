# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
Define the package as scipy.linalg import lu. Get input from user and print L and U matrix by 'print'. Define a package as "from scipy.linalg import lu_factor,lu_solve" and create the variable as "X" include the package in that variable. 4.Print the variable "X".

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: Surendhar A
RegisterNumber: 212222110049
'''
import numpy as np
from scipy.linalg import lu
arr=np.array(eval(input()))
P,L,U=lu(arr)
print(L)
print(U)
```

(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: Surendhar A
RegisterNumber: 212222110049
'''
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=eval(input())
B=eval(input())
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),B)
print(X)
```

## Output:
(i) To find the L and U matrix
![image](https://github.com/Surendhar6/LU-Decomposition/assets/118352907/d0667678-993b-447a-92b4-162c3adcdfca)

(ii) To find the LU Decomposition of a matrix
![image](https://github.com/Surendhar6/LU-Decomposition/assets/118352907/b5c7e2dc-1366-453b-8a49-b2ceea2c62a4)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.
