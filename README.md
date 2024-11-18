# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. find the l and u matirx by using numpy and linalg from scipy
2. print the l matrix and u matirx
3. find the lu decomposition by using numpy and lu_factor and lu_solve 
4. print the the following matrix 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: AKASH CT
RegisterNumber: 24901150
*/
import numpy as np 
from scipy.linalg import lu
matrix=np.array(eval(input()))
piv,l_matrix,u_matrix=lu(matrix)
print(l_matrix)
print(u_matrix)

```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: AKASH CT
RegisterNumber: 24901150
*/
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
B = np.array(eval(input()))
X = lu_factor(A)
solution =lu_solve(X,B)
print(solution)

```

## Output:
![OUTPUT](<Screenshot 2024-11-18 213625.png>)
![oUTPUT](<Screenshot 2024-11-18 213635.png>)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

