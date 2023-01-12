# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### Step 1: Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.solve(), we can find the solutions.
### Step 4: End the program


## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by:AJAY ASWIN.M
RegisterNumber: 22009241
*/
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: AJAYASWIN.M
RegisterNumber: 22009241
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)


```

## Output:
![lu decomposition](PRO1.png)
![lu decomposition](PRO2.png)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

