# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Read the elements of augumented matrix
2. calculate elements of L and U
3. print elements L and U
4. Find V by solving LV=B by forward substitution

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: E.Nandhini
RegisterNumber: 212222100030
import numpy as np
from scipy.linalg import lu
arr=eval(input())
a=np.array(arr)
p,l,u=lu(a)
print(l)
print(u)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: E.Nandhini
RegisterNumber: 212222100030
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)
*/
```

## Output:

![out 1](https://github.com/Nandhinijaya/LU-Decomposition/assets/121998147/4d4dc97c-098a-4a17-8633-86dce4f595d2)

![out 2](https://github.com/Nandhinijaya/LU-Decomposition/assets/121998147/f8d10ac7-5b6a-4dda-a7f1-63db469eaab0)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

