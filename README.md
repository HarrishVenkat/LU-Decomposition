# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import the numpy module
2. imorting ly from scipy.linalg
3. getting input
4. eval and print the output

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Harrish Venkat V
RegisterNumber: 23013973

from scipy.linalg import lu
import numpy as np
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: 
RegisterNumber:
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)

*/
```

## Output:
![image](https://github.com/HarrishVenkat/LU-Decomposition/assets/144979588/b8161c0a-0d6e-426a-9c58-37c608492201)
![image](https://github.com/HarrishVenkat/LU-Decomposition/assets/144979588/dceb959c-1f99-44f3-8960-2a0cb647356b)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

