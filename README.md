# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Use import numpy as np to gain access to linear algebra operations.
### Step 2: 
Create a 2D NumPy array representing the matrix.
### Step 3: 
Use np.linalg.eig(A) to calculate both:
eig_values contains the eigenvalues.
eig_vectors contains the corresponding eigenvectors (as columns).
### Step 4:
Use print() or format() to show the eigenvalues and eigenvectors.
## Program:
#Program to find the eigen values and eigen vectors.
#Developed by:Hemalatha A 
#RegisterNumber:212224240056
import numpy as np
A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
eig_values,eig_vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(eig_values,eig_vectors))
## Output:
![alt text](<Screenshot 2025-03-30 192810.png>)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
