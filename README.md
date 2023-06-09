# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### Step 1:
We have to initialise program using import numpy to perform mathematical calculation

### Step 2:
The input from the user is stored in the variable A.

### Step 3:
from scipy.linalg import lu_factor,lu_solve and lu.

### Step 4:
Execute the program.

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: JANARTHANAN V K
RegisterNumber: 212222230051
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: JANARTHANAN V K
RegisterNumber: 212222230051
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=(eval(input()))
b=(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
![Screenshot 2023-06-09 193005](https://github.com/Janarthanan2/LU-Decomposition/assets/119393515/d5a855cb-09e6-4901-b731-9640118f8871)


![Screenshot 2023-06-09 193043](https://github.com/Janarthanan2/LU-Decomposition/assets/119393515/544529d8-b09c-43e5-81be-b2699629419d)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

