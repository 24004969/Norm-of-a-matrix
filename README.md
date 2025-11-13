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
# Register No: 212224110003
# Developed By: Ajay J
# 1-Norm of a Matrix

import numpy as np
matrix = eval(input())
arr=np.array(matrix)
norm=np.linalg.norm(arr,1)
print("{:2f}".format(norm))



# 2-Norm of a Matrix

import numpy as np
matrix = eval(input())
arr=np.array(matrix)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))



# Infinity Norm of a Matrix

import numpy as np
matrix = eval(input())
arr=np.array(matrix)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))


```
## Output:
### 1-Norm of a Matrix
<img width="1243" height="809" alt="Screenshot 2025-11-13 111133" src="https://github.com/user-attachments/assets/2715deab-8187-4c8b-a515-24b0fcb720e7" />

### 2-Norm of a Matrix
<img width="1244" height="847" alt="Screenshot 2025-11-13 111208" src="https://github.com/user-attachments/assets/6350e329-0ad5-407a-91ab-0df768d84363" />


### Infinity Norm of a Matrix
<img width="1244" height="807" alt="Screenshot 2025-11-13 111228" src="https://github.com/user-attachments/assets/afaab3be-1b98-4595-839c-522ef24ca1c9" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
