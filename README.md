# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
 TO find L and U matrix:
 ```
   1.import numpy as np
   2.from scipy.linalg import lu
   3.get input as np.array()
   4.now use the lu() and print the  output
```
program to solve matrix using LU decomposition:
```
1.import numpy as np
2.from scipy.linalg import lu
3.get input as np.array()
4.give variable name and use lu_factor and for another variable give lu_solve()
5.now,print the output
```
## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by:jeyaarikaran
RegisterNumber:24002171

  import numpy as np
  from scipy.linalg import lu 
  matrix=np.array(eval(input()))
  piv,l_matrix,u_matrix=lu(matrix)
  print(l_matrix)
  print(u_matrix)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by:jeyaarikaran 
RegisterNumber: 24002171

  import numpy as np
  from scipy.linalg import lu_factor,lu_solve
  matrix=np.array(eval(input()))
  b=np.array(eval(input()))
  x=lu_factor(matrix)
  solution=lu_solve(x,b)
  print(solution)
*/
```

## Output:
![lu decomposition]()
![image 1](https://github.com/user-attachments/assets/3df28646-0a58-428b-bb50-b1abed26e331)
![image 2](https://github.com/user-attachments/assets/f86a63f0-6afc-428b-9a72-3143756236fb)
![image 3](https://github.com/user-attachments/assets/d2da54fe-bd35-40ac-bf0c-9b19c18c06be)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

