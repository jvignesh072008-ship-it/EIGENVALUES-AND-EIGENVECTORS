# EIGENVALUES-AND-EIGENVECTORS

## Aim:

To write a python program to find the Eigenvalues and Eigen Vectors

## Equipment’s required:

1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:

### Step1 : Import Library: Import the numpy library and alias it as np to enable mathematical and array operations.
### Step 2: Define Matrix: Create a 2D NumPy array a and initialize it with the given matrix values.
### Step 3: Compute Eigenvalues and Eigenvectors: Utilize the np.linalg.eig(a) function to perform the calculation. The function returns the eigenvalues as a 1D array and the corresponding eigenvectors as a 2D array, which are stored in the variables eigenvalues and eigenvectors, respectively.
### Step 4: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 5:Print Results: Use an f-string to print the computed eigenvalues and eigenvectors to the console. The output will show the eigenvalues followed by the eigenvectors (where each column of the eigenvectors array corresponds to an eigenvector).
 
## Program:

```
#Program to find the eigen values and eigen vectors.
#Developed by: VIGNESH J
#RegisterNumber: 212225230297
#RefNumber: 25014705

import numpy as np
a = np.array([[4,2],[2,4]])
eigenvalues, eigenvectors = np.linalg.eig(a)
print(f"Eigen values are {eigenvalues} and Eigen Vectors are {eigenvectors}")
```
## Output:

<img width="1187" height="797" alt="Screenshot 2026-02-03 114336" src="https://github.com/user-attachments/assets/c97c9e92-2fc0-4b1f-9e6b-42e249ff24f5" />

## Result:

Thus the Eigenvalue and Eigenvector is successfully solved using python program
