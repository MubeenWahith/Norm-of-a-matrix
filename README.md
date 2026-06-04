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
# Register No:212225040241
# Developed By:MOHAMED MUBEEN A
# 1-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"

import numpy as np

A = eval(input())

A = np.array(A)

norm = np.linalg.norm(A, 1)

print("%.2f" % norm)


# 2-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"

import numpy as np

A = eval(input())

A = np.array(A)

norm = np.linalg.norm(A, 2)

print("%.2f" % norm)


# Infinity Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"

import numpy as np

A = eval(input())

A = np.array(A)

norm = np.linalg.norm(A, np.inf)

print("%.2f" % norm)



```
## Output:
### 1-Norm of a Matrix
<img width="945" height="257" alt="image" src="https://github.com/user-attachments/assets/15796913-23ac-4275-9f75-5b2cbe3daa85" />

<br>
<br>
<br>

### 2-Norm of a Matrix
<img width="972" height="300" alt="image" src="https://github.com/user-attachments/assets/b8e62a17-b939-406e-b02d-05f3c30adfbf" />

<br>
<br>
<br>

### Infinity Norm of a Matrix
<img width="1024" height="277" alt="image" src="https://github.com/user-attachments/assets/ac3767ff-8464-417e-b453-460383a52593" />

<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
