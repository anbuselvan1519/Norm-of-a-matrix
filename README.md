# Norm of a matrix
### Name: Anbuselvan.S
### Reference No : 23005959
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
Program to find 1-norm of a matrix.
Developed by: Anbuselvan.S
Reference No: 23005959
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm="{:.2f}".format(ans)
print(norm)

# 2-Norm of a Matrix
Program to find 2-norm of a matrix.
Developed by: Anbuselvan.S
Reference No: 23005959
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm="{:.2f}".format(ans)
print(norm)

# Infinity Norm of a Matrix
Program to find Infinity of a matrix.
Developed by: Anbuselvan.S
Reference No: 23005959
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm="{:.2f}".format(ans)
print(norm)

```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/anbuselvan1519/Norm-of-a-matrix/assets/139841744/b1662c6c-bbb0-446d-baf2-a4edd0a3d715)

### 2-Norm of a Matrix
![image](https://github.com/anbuselvan1519/Norm-of-a-matrix/assets/139841744/059b9466-93d8-4361-8629-a822920e0b67)

### Infinity Norm of a Matrix
![image](https://github.com/anbuselvan1519/Norm-of-a-matrix/assets/139841744/57381594-abc9-4ed8-bc6d-1395fbac9608)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
