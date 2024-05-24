# Norm of a matrix
# Date:
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
# Register No: Kavya T
# Developed By:2305003004
# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)


# 2-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans= np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)


# Infinity Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/Ayvak16122005/Norm-of-a-matrix/assets/147690197/0c7a9fa3-b3d9-4107-b054-2577bcd19a3d)

### 2-Norm of a Matrix
![image](https://github.com/Ayvak16122005/Norm-of-a-matrix/assets/147690197/f3491a4a-b86c-41d5-a599-c2e515866576)

### Infinity Norm of a Matrix
![image](https://github.com/Ayvak16122005/Norm-of-a-matrix/assets/147690197/e0087ac2-1922-4d73-96a7-b2a6d0fc4e74)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
