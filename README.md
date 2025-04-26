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
4. print the variable 'X'
## Program:
(i) To find the L and U matrix
```PYTHON
/*
Program to find the L and U matrix.
Developed by: SANJAY M
RegisterNumber: 212222110038
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
```

(ii) To find the LU Decomposition of a matrix
```python
/*
'''Program to solve a matrix using LU decomposition.
Developed by: Sanjay M
RegisterNumber: 212222110038
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
x = lu_solve((lu, piv),b)
print(x)
*/
```

## Output:
![image](https://github.com/user-attachments/assets/c68f9f09-75ee-461a-8f81-b19b44b8b4a0)

![image](https://github.com/user-attachments/assets/88596f3a-bd4b-46c9-b8e1-ade7bf6b7f95)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

