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
# Register No:212225230240
# Developed By:sakthivel B
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np 

A = np.array(eval(input()))

norm = np.linalg.norm(A, 1)

print("{:.2f}".format(norm))



# 2-Norm of a Matrix
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np

A = np.array(eval(input()))

norm = np.linalg.norm(A, 2)

print("{:.2f}".format(norm))





# Infinity Norm of a Matrix
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np

A = np.array(eval(input()))

norm = np.linalg.norm(A, np.inf)

print("{:.2f}".format(norm))





```
## Output:
### 1-Norm of a Matrix
<img width="1920" height="1080" alt="Screenshot 2026-05-31 171608" src="https://github.com/user-attachments/assets/7a5f0a51-d92f-45cb-a45c-3cfc8d7a0862" />


### 2-Norm of a Matrix
<img width="1920" height="1080" alt="Screenshot 2026-05-31 171637" src="https://github.com/user-attachments/assets/c84a8874-0cc5-43fc-ae29-90383fe7562a" />



### Infinity Norm of a Matrix
<img width="1920" height="1080" alt="Screenshot 2026-05-31 171706" src="https://github.com/user-attachments/assets/9a536a64-d5fd-4411-88c9-4b316a8a9073" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
