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
'''
Program to find L and U matrix using LU decomposition.
Developed by: SRIVATSAN V
RegisterNumber: 23000970
'''
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
P,L,U=lu(a)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```
'''
Program to solve a matrix using LU decomposition.
Developed by: SRIVATSAN V
RegisterNumber: 23000970
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
c=np.array(eval(input()))
r=lu_factor(a)
sol=lu_solve(r,c)
print(sol)
```

## Output:
![image](https://github.com/Srivatsan0405/LU-Decomposition/assets/139841630/9930e10b-725d-44e8-98eb-f913de2129bb)

![image](https://github.com/Srivatsan0405/LU-Decomposition/assets/139841630/8cc2e743-e56f-46ee-91b6-837f624bab9e)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

