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
# Register No: 212224230220
# Developed By: RANJANI K
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)


# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix
<img width="1079" height="344" alt="image" src="https://github.com/user-attachments/assets/edc6143a-5cc5-4a60-b12f-6e73377b8e97" />


### 2-Norm of a Matrix
<img width="960" height="363" alt="image" src="https://github.com/user-attachments/assets/e846dcab-b50d-4f4a-87bc-9012c9900a3a" />

### Infinity Norm of a Matrix
<img width="1147" height="311" alt="image" src="https://github.com/user-attachments/assets/8a06ab2d-455c-4997-8e8a-4e875b833e8b" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
