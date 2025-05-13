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
# Register No: 212224100036
# Developed By: MOHANRAJ.S

# 1-Norm of a Matrix:

import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,1)
print(result)

# 2-Norm of a Matrix

import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,2)
print(f"{result:.2f}")

# Infinity Norm of a Matrix

import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,2)
print(f"{result:.2f}")

```
## Output:
### 1-Norm of a Matrix

![image](https://github.com/user-attachments/assets/609f6d44-b060-456a-9efc-dbf4ec27d72c)

### 2-Norm of a Matrix

![image](https://github.com/user-attachments/assets/fdcaf3e9-64ee-4f72-9512-cb4d3712f900)

### Infinity Norm of a Matrix

![image](https://github.com/user-attachments/assets/c9d3a594-4376-45cd-88c4-aa87a9b6528b)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
