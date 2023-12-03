# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Define the package as scipy.linalg import lu.

2.Get input from user and print L and U matrix by 'print'.

3.Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.

4.print the variable 'X'.

## Program:
(i) To find the L and U matrix
Program to find L and U matrix using LU decomposition.

Developed by: Narra Akhil

RegisterNumber: 23003406
```
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
Program to solve a matrix using LU decomposition.

Developed by: Narra Akhil

RegisterNumber: 23003406

To print X matrix (solution to the equations
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
x = lu_solve((lu,piv),b)
print(x)
```
## Output:
i)To find the L and U matrix
![image](https://github.com/NARRAAKHIL/LU-Decomposition/assets/144979843/cf9690ec-9378-4347-9d88-3c92912b0d4c)




ii)To find the LU Decomposition of a matrix
![image](https://github.com/NARRAAKHIL/LU-Decomposition/assets/144979843/2d16721d-069f-4434-a31a-b6825cc640c9)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

