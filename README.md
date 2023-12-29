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
# 1-Norm of a Matrix
```Python
program to find 1-norm of a matix
Developed by : Aravindkumar ss
RegisterNumber : 23004721

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```



# 2-Norm of a Matrix
```python
Program to find 2-norm of a matrix.
Developed by: yourname
RegisterNumber: 

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```


# 3-Infinity Norm of a Matrix
```python
Program to find 2-norm of a matrix.
Developed by: yourname
RegisterNumber: 

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![Screenshot 2023-12-29 213542](https://github.com/aravindkumar23004721/Norm-of-a-matrix/assets/148962674/09f305e8-68c4-443f-bb62-a9d48e7e3414)


### 2-Norm of a Matrix
![Screenshot 2023-12-29 213609](https://github.com/aravindkumar23004721/Norm-of-a-matrix/assets/148962674/8b6e6102-5464-4052-8249-22f72a62ccd4)


### 3-Infinity Norm of a Matrix
![Screenshot 2023-12-29 213626](https://github.com/aravindkumar23004721/Norm-of-a-matrix/assets/148962674/f5d19b00-1bfb-46fc-8a8d-f979ba617ff6)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
