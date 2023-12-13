# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program
2. Using library scipy.linalg,import lu to find l and u matrices and lu_factor,lu_solve to find result
3. Prepare the lists from given matrix
4. Using lu(),l and u matrices can be printed and using lu_factor() and lu_solve() to find resultant matrix

## Program:
### (i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: Prajin S
RegisterNumber: 23012918
'''
from scipy.linalg import lu
import numpy as np
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
```
### (ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: Prajin S
RegisterNumber: 23012918
'''
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)
```

## Output:
### (i)
![Screenshot 2023-12-13 180620](https://github.com/Prajin19/LU-Decomposition/assets/144979377/025f2cb5-9899-4150-9953-afe8d11f7feb)
### (ii)
![Screenshot 2023-12-13 180641](https://github.com/Prajin19/LU-Decomposition/assets/144979377/a79e6ab8-709f-4820-86fb-9330506cd149)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

