# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program.
2. Write the code appropriately.
3. Check the program
4. Run the code.

## Program:
(i) To find the L and U matrix
 '''Program to find L and U matrix using LU decomposition.
Developed by: S V SHADHANASHREE
RegisterNumber: 23013434
'''
```
import numpy as nu
from scipy.linalg import lu
a=nu.array(eval(input()))
P,l,u=lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
'''Program to solve a matrix using LU decomposition.
Developed by: S V SHADHANASHREE
RegisterNumber: 23013434
'''
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=eval(input())
b=eval(input())
A=np.array(a)
B=np.array(b)
result=lu_factor(A)
sol=lu_solve(result,B)
print(sol)
```

## Output:
![output](./lu%201.png)


![output](./lu%202.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

