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
/*
Program to find the L and U matrix.
Developed by: Naneshvaran C
RegisterNumber:212224110038 
*/
```
'''Program to find L and U matrix using LU decomposition.
Developed by:Naneshvaran C
RegisterNumber:212224110038 
'''
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Naneshvaran C
RegisterNumber: 212224110038
*/
'''Program to solve a matrix using LU decomposition.
Developed by: Naneshvaran C
RegisterNumber: 212224110038
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu,lu_solve,lu_factor
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
![lu decomposition]()
![Screenshot 2025-05-20 213741](https://github.com/user-attachments/assets/77508576-3ccf-4a96-9690-94c9511ec164)
![Screenshot 2025-05-20 213750](https://github.com/user-attachments/assets/09687ab5-1538-4bb4-905c-8e33e71a1200)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

