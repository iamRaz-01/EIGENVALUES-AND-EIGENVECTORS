# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

Step 1. **Import Library**: Import `numpy` for matrix operations.
   ```python
   import numpy as np
   ```

Step 2. **Define Matrix**: Create a 2D array `matrix`.
   ```python
   matrix = np.array([[4, 2], [2, 4]])
   ```

Step 3. **Calculate Eigenvalues and Eigenvectors**:
   - Use `np.linalg.eig(matrix)` to compute the eigenvalues and eigenvectors of the matrix.
   - `eigenvalues` contains the eigenvalues.
   - `eigenvectors` contains the corresponding eigenvectors as columns.

   ```python
   eigenvalues, eigenvectors = np.linalg.eig(matrix)
   ```

Step 4. **Print Results**: Display the eigenvalues and eigenvectors.
   ```python
   print('Eigen values are {} and Eigen Vectors are {}'.format(eigenvalues, eigenvectors))
   ```

## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by: Abdul Rasak N
#RegisterNumber: 24002896
import numpy as np
matrix = np.array([[4, 2], [2, 4]])

# Compute eigenvalues and eigenvectors
eigenvalues, eigenvectors = np.linalg.eig(matrix)
print('Eigen values are {} and Eigen Vectors are {} '.format(eigenvalues,eigenvectors))
```

## Output:
![image](https://github.com/user-attachments/assets/94cfc500-75fc-4991-bf8c-a724e3e8065e)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
