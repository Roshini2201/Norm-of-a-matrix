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
````
# Register No: ROSHINI S
# Developed By: 21223240142
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
![Screenshot 2024-04-08 184506](https://github.com/Roshini2201/Norm-of-a-matrix/assets/154105318/927acc02-42fc-4fc6-970f-fd63233cb20d)


### 2-Norm of a Matrix
![Screenshot 2024-04-08 184520](https://github.com/Roshini2201/Norm-of-a-matrix/assets/154105318/b5eb328e-e921-4b09-be3a-199a50a5cbcb)

### Infinity Norm of a Matrix

![Screenshot 2024-04-08 184549](https://github.com/Roshini2201/Norm-of-a-matrix/assets/154105318/5cd63229-ff44-4420-9b31-4ca3a70304cc)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
