# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```Python

Program to find 2-norm of a matrix.
Developed by: Sanjeev A
RegisterNumber: 212224230246

# 1-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
b=np.linalg.norm(a,1)
norm_of_matrix="{:.2f}".format(b)
print(norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
b=np.linalg.norm(a,2)
norm_of_matrix="{:.2f}".format(b)
print(norm_of_matrix)

# Infinity Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
b=np.linalg.norm(a,np.inf)
norm_of_matrix="{:.2f}".format(b)
print(norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/user-attachments/assets/0c3d46bf-2abe-4fc5-8634-b5ed40a31670)


### 2-Norm of a Matrix
![image](https://github.com/user-attachments/assets/e2ef1421-7fe5-43f0-bd28-079ef8122ca1)


### Infinity Norm of a Matrix
<br>
<br>
<br>
![image](https://github.com/user-attachments/assets/241cab5e-a681-4a89-9c01-1fc0d8cfa44d)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
