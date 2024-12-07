# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy library.
2. Import lu function from scipy library.
3. Solve LU decomposition using lu_solve() function.
4. print the value.

## Program:
(i) To find the L and U matrix
```
#Program to find the L and U matrix.
#Developed by: A S GEETHAPRIYAN
#RegisterNumber: 24900874
import numpy as np 
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
#Program to find the LU Decomposition of a matrix.
#Developed by: A S GEETHAPRIYAN
#RegisterNumber: 24900874
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
x = lu_solve((lu,piv),b)
print(x)
```

## Output:
![image](https://github.com/user-attachments/assets/85fc595e-61b0-4353-b18e-427b3d5b6a26)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

