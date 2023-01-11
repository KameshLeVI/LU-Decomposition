# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy as np
2. get input from user
3. apply lu decomposition formula
4. print the output

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Kamesh D
RegisterNumber: 22005358
*/
```
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Kamesh D
RegisterNumber: 22005358
*/
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)

## Output:
![output](/Screenshot%20from%202023-01-11%2015-53-48.png)
![output](Screenshot%20from%202023-01-11%2015-54-04.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

