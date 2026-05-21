# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
/*
'''Program to find L and U matrix using LU decomposition.
Developed by: v.priyadaarshini
RegisterNumber: 212225040317
'''
*/
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu
InputMatrix=np.array(eval(input()),dtype='i')
piv,Lmatrix,Umatrix=lu(InputMatrix)
print(Lmatrix)
print(Umatrix)
```
(ii) To find the LU Decomposition of a matrix
```
/*
'''Program to solve a matrix using LU decomposition.
Developed by: v.priyadaarshini
RegisterNumber:212225040317 
'''
*/
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu_factor,lu_solve
AMatrix=np.array(eval(input()),dtype='i')
BMatrix=np.array(eval(input()),dtype='i')
XMatrix=lu_factor(AMatrix)
Solution=lu_solve(XMatrix,BMatrix)
print(Solution)
```

## Output:
![lu decomposition]()
![alt text](<Screenshot 2026-05-21 101039.png>)
![alt text](<Screenshot 2026-05-21 101059.png>)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

