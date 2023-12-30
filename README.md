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
# Register No:23014037
# Developed By:SAI GURU CHANDRAN G

# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)



# 2-Norm of a Matrix
import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)




# Infinity Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix= "{:.2f}".format(ans)
print(Norm_of_matrix)





```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/Saiguruchandran/Norm-of-a-matrix/assets/144870946/32122015-a942-432b-87ee-5454d99fe9ed)

<br>
<br>
<br>

### 2-Norm of a Matrix
![image](https://github.com/Saiguruchandran/Norm-of-a-matrix/assets/144870946/03f08050-9d0f-415f-baa3-2d1642fda77e)

<br>
<br>
<br>

### Infinity Norm of a Matrix
![image](https://github.com/Saiguruchandran/Norm-of-a-matrix/assets/144870946/0ea70d16-bda8-4789-ba06-020cc1116367)

<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
