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
#### (i)
<img width="900" height="367" alt="Screenshot 2025-10-16 184325" src="https://github.com/user-attachments/assets/4a886de1-514b-4ff2-9c8a-7e65cbf4c135" />

#### (ii)
<img width="883" height="211" alt="image" src="https://github.com/user-attachments/assets/930f3834-993a-4053-9178-e20580142727" />




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

