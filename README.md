# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable
4. print the variable 'X
 
 
 

## Program:
(i) To find the L and U matrix
```python
/*
Program to find the L and U matrix.
Developed by: R.Rubasri
RegisterNumber: 212224240139
*/
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```python
/*
Program to find the LU Decomposition of a matrix.
Developed by: R.Rubasri
RegisterNumber: 212224240139
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
```

## Output:
<img width="896" height="598" alt="image" src="https://github.com/user-attachments/assets/3dc39d53-a711-4d29-b7ea-fbcc492bd6a5" />


<img width="872" height="487" alt="image" src="https://github.com/user-attachments/assets/e09599a0-1583-416e-9395-21b62f608e19" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

