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
 Register No:25017435
 Developed By:VAISHNAVI T
# 1-Norm of a Matrix
```
import numpy as np
a=np.array(eval(input()))
norm1=np.linalg.norm(a,1)
print(norm1)
```


# 2-Norm of a Matrix
```
import numpy as np
a=np.array(eval(input()))
norm2=np.linalg.norm(a,2)
print(f"{norm2:.2f}")
```



# Infinity Norm of a Matrix
```
import numpy as np
a=np.array(eval(input()))
b=np.linalg.norm(a,np.inf)
print(f"{b:.2f}")
```




## Output:
### 1-Norm of a Matrix
<img width="1920" height="1080" alt="Screenshot (81)" src="https://github.com/user-attachments/assets/931784dc-463b-47b4-876f-4c730b9ff4e8" />


### 2-Norm of a Matrix

<img width="1920" height="1080" alt="Screenshot (82)" src="https://github.com/user-attachments/assets/7b9d115b-a1f0-43be-bda8-3e846427e81b" />

### Infinity Norm of a Matrix
<img width="1920" height="1080" alt="Screenshot (83)" src="https://github.com/user-attachments/assets/463aae2e-1fe0-4539-94d3-38d3b9e33a69" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
