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
# Register No:212225040108
# Developed By: HARI PRASATH M
# 1-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)


# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)



# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))




```
## Output:
### 1-Norm of a Matrix
<img width="815" height="227" alt="image" src="https://github.com/user-attachments/assets/87ce80b6-caaf-4b76-ad4b-9e188a5df63a" />


### 2-Norm of a Matrix
<img width="809" height="252" alt="image" src="https://github.com/user-attachments/assets/fc399ed0-b3a6-4448-981e-4c60f812492f" />


### Infinity Norm of a Matrix
<img width="809" height="252" alt="image" src="https://github.com/user-attachments/assets/75ef60ba-073a-44a7-90d6-4812ac832e34" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
