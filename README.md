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
# Register No:212223110019
# Developed By:Goutham.K
# 1-Norm of a Matrix
  '''
  #Program to find 1-norm of a matrix.
  #Developed by:Goutham.K
  #RegisterNumber:212223110019

  '''
  import numpy as np
  value=eval(input())
  arr=np.array(value)
  norm=np.linalg.norm(arr,1)
  print("{:.2f}".format(norm))

    



# 2-Norm of a Matrix
  '''
  Program to find 2-norm of a matrix.
  Developed by: Goutham.K
  RegisterNumber: 212223110019
  '''
  import numpy as np
  value=eval(input())
  arr=np.array(value)
  norm=np.linalg.norm(arr,2)
  print("{:.2f}".format(norm))





# Infinity Norm of a Matrix
  '''
  Program to find infinity of a matrix.
  Developed by:Goutham.K
  RegisterNumber:212223110019
  '''
  import numpy as np
  value=eval(input())
  arr=np.array(value)
  norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))




```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/Goutham2306/Norm-of-a-matrix/assets/138971154/e9b9925b-00e7-47a6-90bc-7320f2c40e00)


### 2-Norm of a Matrix
![image](https://github.com/Goutham2306/Norm-of-a-matrix/assets/138971154/a5e11f3c-10b6-495e-89e5-df48146c4605)


### Infinity Norm of a Matrix
![image](https://github.com/Goutham2306/Norm-of-a-matrix/assets/138971154/c85fafcc-5553-443d-8276-3cac56e3eea6)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
