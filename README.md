# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### L and U matrix
1. import numpy as np and from scipy.linalg import lu.
2.  Prompt the user to enter the matrix and convert it into a NumPy array using matrix=np.array(eval(input())).
3.  Call the lu function from scipy.linalg to decompose the matrix into piv, l_matrix, and u_matrix.
4.  Print the lower triangular matrix (l_matrix) and the upper triangular matrix (u_matrix).

### LU Decomposition
1. Get necessary libraries.
2. Get input for coefficient matrix (A) and constant vector (B).
3. Perform LU decomposition on A using lu_factor.
4. Solve the system using lu_solve with the decomposition result (X) and B.
5. Print the solution.




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

