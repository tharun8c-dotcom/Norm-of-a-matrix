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
#Developed by: R Tharun Rathish
#RegisterNumber: 212225230284
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
InputArray=np.array(eval(input()))
OneNorm=np.linalg.norm(InputArray,1)
print(OneNorm)

# 2-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
Inputarray=np.array(eval(input()))
Twonorm=np.linalg.norm(Inputarray,2)
print(f"{Twonorm:.2f}")


# Infinity Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
Inputarray=np.array(eval(input()))
Infinitynorm=np.linalg.norm(Inputarray,np.inf)
print(Infinitynorm)

```
## Output:
### 1-Norm of a Matrix
<br>
<img width="550" height="192" alt="image" src="https://github.com/user-attachments/assets/4f919139-24c8-4b07-ba75-abef0cc3b073" />

<br>

### 2-Norm of a Matrix
<br>
<img width="545" height="264" alt="image" src="https://github.com/user-attachments/assets/2ce4d27b-579b-4a10-8960-3093dde5bd09" />

<br>

### Infinity Norm of a Matrix
<br>
<img width="589" height="207" alt="image" src="https://github.com/user-attachments/assets/33660c82-1c55-428e-9a35-b19398548eba" />

<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
