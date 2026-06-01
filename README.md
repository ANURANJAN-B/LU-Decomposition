# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program and import the required libraries (NumPy and SciPy)
2. Define the matrix using NumPy.
3. Use lu() to perform LU decomposition and display the lower and upper triangular matrices.
4. .Use lu_factor() and lu_solve() to factorize the matrix and solve the system of equations. 5.Display the solution and end the program.

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Anuranjan B
RegisterNumber: 212225040025
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
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
Developed by: Anuranjan B
RegisterNumber: 212225040025

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
X = lu_solve((lu , piv),b)
print(X)

*/
```

## Output:
1)

<img width="1918" height="1078" alt="image" src="https://github.com/user-attachments/assets/f9ffe92d-d602-49b1-9394-fe469538ca06" />

2)

<img width="1918" height="1078" alt="image" src="https://github.com/user-attachments/assets/c44cfae0-6eff-468d-8102-c62d09c83ede" />




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

