# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## STEP 1:
Import the numpy module to use the built-in functions for calculation
## STEP 2:
from scipy.linalg module import lu to find the L and U matrix
## STEP 3:
get input from the user and apply lu function
## STEP 4:
print L for L matrix and print U for U matrix
## STEP 5:
End of program 

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: vignesh v
RegisterNumber: 23002301
'''
import numpy as np
from scipy.linalg import lu
A=eval(input())
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```

'''Program to solve a matrix using LU decomposition.
Developed by: 
RegisterNumber: 
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=eval(input())
B=eval(input())
lu=lu_factor(A)
x=lu_solve(lu,B)
print(x)

```

## Output:
<img width="566" alt="image" src="https://github.com/Vickyy-0/LU-Decomposition/assets/110780412/b4255b17-df2f-4ae6-a2ec-fdb96e7e7ceb">
<img width="579" alt="image" src="https://github.com/Vickyy-0/LU-Decomposition/assets/110780412/dae53265-1b85-4f2c-a8de-6cf06230d1d7">




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

