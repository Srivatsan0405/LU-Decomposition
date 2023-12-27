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
Program to find the L and U matrix.
Developed by: Kavinraja D
RegisterNumber: 22007928
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.
Developed by: Kavinraja D
RegisterNumber: 22007928
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
X = lu_solve((lu , piv),b)
print(X)
```

## Output:
![image](https://github.com/d-kavinraja/LU-Decomposition/assets/139841630/83602f1a-0dbb-4c83-90d4-9928068f3d46)

![image](https://github.com/d-kavinraja/LU-Decomposition/assets/139841630/9531237a-72fd-4c74-a1bf-c65a31956afc)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

