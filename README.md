# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy and scipy packages
2. Read the input matrix as two dimensional array
3. Call the Built in function lu() to decompose the array
4. print the output

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: b.barathraj
RegisterNumber: 22008848
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: b.barathraj
RegisterNumber: 22008848
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
x = lu_solve((lu, piv), b)
print(x)
*/
```

## Output:
![lu decompositon 1](https://user-images.githubusercontent.com/121490575/214912631-bc863b1f-1460-4c54-99ea-c62994f5d46c.png)
![lu decompositon 2 ](https://user-images.githubusercontent.com/121490575/214912690-154f27b7-1d43-4089-a6de-20f439d045a5.png)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

