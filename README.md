# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
### Step 1: Import the numpy module and scipy.linalg to use the built-in functions for calculation
### Step 2: Prepare the list to find L and U matrix and assign in np.array()
### Step 3: Using the lu module, we can find the L and U of the given matrix.
### Step 4: End the program

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: MOHAMED ABRAR M
RegisterNumber: 25009852
'''
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: MOHAMED ABRAR M
RegisterNumber: 25009852
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,pivot= lu_factor(a)
x=lu_solve((lu,pivot),b)
print(x)
```
## Output:
<img width="1250" height="788" alt="Screenshot 2025-11-20 122523" src="https://github.com/user-attachments/assets/86fa060d-add3-4db9-9846-355c4861bd42" />
<img width="952" height="715" alt="Screenshot 2025-11-20 122542" src="https://github.com/user-attachments/assets/3b113a33-34e8-469d-9410-6d010ceed26e" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

