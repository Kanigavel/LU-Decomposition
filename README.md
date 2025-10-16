# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Start the program.

2.Import the required library scipy.linalg and numpy.

3.Create a square matrix using np.array().

4.Compute the LU Decomposition using scipy.linalg.lu(), which returns P, L, U matrices.

 P: Permutation matrix,
 L: Lower triangular matrix,
 U: Upper triangular matrix,

5.Display the matrices P, L, and U.

6.Stop the program.

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Kanigavel M
RegisterNumber: 212224240070 
*/

import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

```
<img width="1075" height="698" alt="image" src="https://github.com/user-attachments/assets/215f516a-3151-4e55-9ac7-028dd0fcddc5" />

(ii) To find the LU Decomposition of a matrix

~~~
Program to find the LU Decomposition of a matrix.
Developed by:  Kanigavel M
RegisterNumber: 212224240070  

import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
X = lu_solve((lu , piv),b)
print(X)
~~~
<img width="875" height="594" alt="image" src="https://github.com/user-attachments/assets/b66439ce-0f53-43c0-b5fa-b97905eb2435" />

## Output:
## (i) To find the L and U matrix
<img width="1102" height="519" alt="image" src="https://github.com/user-attachments/assets/cc469868-4b1d-4935-afc8-a3a473b211c5" />

  ## (ii) To find the LU Decomposition of a matrix

  <img width="892" height="283" alt="image" src="https://github.com/user-attachments/assets/7411c57d-2353-4195-a927-cdd8292d113c" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

