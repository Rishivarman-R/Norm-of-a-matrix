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
Python
# Register No:212224100050
# Developed By:RISHIVARMAN R
# 1-Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```



# 2-Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```



# Infinity Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```





## Output:
### 1-Norm of a Matrix

![Screenshot 2025-05-13 201828](https://github.com/user-attachments/assets/23dd3e9b-4247-42ae-8376-72c0106e4706)

### 2-Norm of a Matrix

![Screenshot 2025-05-13 201849](https://github.com/user-attachments/assets/55a35d93-526e-40be-828b-c19775745362)

### Infinity Norm of a Matrix

![Screenshot 2025-05-13 201907](https://github.com/user-attachments/assets/6c2a935b-db82-4175-a87c-802e7dd5b4c6)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
