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
```
# Register No: 212225040359
# Developed By:V G SAIRAIMA
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array(eval(input()))
one_norm=np.linalg.norm(a,1)
print(f"{one_norm:.2f}")


# 2-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array(eval(input()))
twonorm=np.linalg.norm(a,2)
print(f"{twonorm:.2f}")

# Infinity Norm of a Matrix



import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=eval(input())
inf=np.linalg.norm(a,np.inf)
print(f"{inf:.2f}")

```
## Output:
### 1-Norm of a Matrix
![alt text](<Screenshot 2026-03-22 170037.png>)

### 2-Norm of a Matrix
![alt text](<Screenshot 2026-03-22 170100.png>)

### Infinity Norm of a Matrix
![alt text](<Screenshot 2026-03-22 170107.png>)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
