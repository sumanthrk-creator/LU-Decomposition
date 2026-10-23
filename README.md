# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
/'''Program to find L and U matrix using LU decomposition.
Developed by: sumanth
RegisterNumber:26017294 
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)*

```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: 
RegisterNumber: 
*/
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)
```

## Output:
![lu decomposition]()<img width="1199" height="551" alt="Screenshot 2026-10-23 084953" src="https://github.com/user-attachments/assets/9cdaac33-26b0-441d-a328-4560e6b7064a" />
<img width="1450" height="376" alt="Screenshot 2026-10-23 085030" src="https://github.com/user-attachments/assets/afc6024b-b93b-4438-b633-ba35997930b7" />





## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

