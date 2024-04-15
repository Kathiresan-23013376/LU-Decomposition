# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4. print the variable 'X'
## Program:
(i) To find the L and U matrix
```
Program to find L and U matrix using LU decomposition.
Developed by: Kathiresan K
RegisterNumber: 212223110021
```
```
import numpy as np
from scipy.linalg import lu
matrix=np.array(eval(input()))
pivot,l_matrix,u_matrix=lu(matrix)
print(l_matrix)
print(u_matrix)
```
(ii) To find the LU Decomposition of a matrix
```
Program to solve a matrix using LU decomposition.
Developed by: Kathiresan K
RegisterNumber: 212223110021
```
```
import numpy as np
import scipy.linalg as la
A=np.array(eval(input()))
B=np.array(eval(input()))
LU,piv=la.lu_factor(A)
x=la.lu_solve((LU,piv),B)
print(x)
```
## Output:
1)L and U matrix:
![Screenshot 2024-04-14 175139](https://github.com/Kathiresan-23013376/LU-Decomposition/assets/150008375/3850197c-2a5f-43a7-b751-600ccb71fce5)

![image](https://github.com/Kathiresan-23013376/LU-Decomposition/assets/150008375/a04e3748-8113-4229-b664-ff55e4ce6dcf)
2)LU decompositon of matrix:
![Screenshot 2024-04-14 175239](https://github.com/Kathiresan-23013376/LU-Decomposition/assets/150008375/d7e145c0-ba27-4700-af8c-3df0b2da7145)

![image](https://github.com/Kathiresan-23013376/LU-Decomposition/assets/150008375/8936a9d0-892f-48f7-ab28-d46c59f5421c)
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.
