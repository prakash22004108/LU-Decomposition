# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## Step 1:
Import numpy library using import statement.

## Step 2:
From scipy package import lu().

## Step 3:
Get input from user and pass it as an array.

## Step 4:
Get P, L, U matrix using lu()

## Step 5:
Print L and U matrix

## Program:
(i) To find the L and U matrix
```

Program to find the L and U matrix.
Developed by: PRAKASH R
RegisterNumber: 22004108

import numpy as np
from scipy.linalg import lu
a=eval(input())
P,L,U=lu(a)
print(L)
print(U)

```
### OUT PUT
![lu decomposition](/OP1.png)
(ii) To find the LU Decomposition of a matrix
```

Program to find the LU Decomposition of a matrix.
Developed by: PRAKASH R
RegisterNumber: 22004108

import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=eval(input())
b=eval(input())
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)

```

## Output:
![lu decomposition](/OP2.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

