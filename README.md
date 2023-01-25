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

# 1-Norm of a Matrix
# Register No: 22009393
# Developed By: S.Premalatha
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: PREMA LATHA S
RegisterNumber: 22009393
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)


# Infinity Norm of a Matrix
# Register No: 22009393
# Developed By: S.Premalatha
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

```

## Output:
### 1-Norm of a Matrix
<br>![image](https://user-images.githubusercontent.com/120620842/213923965-97ba571f-0940-4ef5-b44c-3a37787a47de.png)


### 2-Norm of a Matrix
<br>![image](https://user-images.githubusercontent.com/120620842/213923995-53378b09-8af6-442d-95df-dada7a7fa866.png)


### Infinity Norm of a Matrix
<br>![image](https://user-images.githubusercontent.com/120620842/213924022-d43d0848-1164-414b-aa0a-0f6e2b3e8630.png)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
