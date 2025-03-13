# Matrices

## Explanation
Matrices are rectangular arrays of numbers, symbols, or expressions, arranged in rows and columns. They are used to represent linear transformations and are fundamental in linear algebra and various machine learning algorithms.

### Properties of Matrices
- **Dimensions**: The size of a matrix is defined by the number of rows and columns it contains.
- **Square Matrix**: A matrix with the same number of rows and columns.
- **Identity Matrix**: A square matrix with ones on the diagonal and zeros elsewhere.
- **Transpose**: The transpose of a matrix is obtained by swapping its rows and columns.

### Matrix Operations
1. **Addition**: The sum of two matrices is a new matrix obtained by adding the corresponding elements of the original matrices.
2. **Subtraction**: The difference between two matrices is a new matrix obtained by subtracting the corresponding elements of the original matrices.
3. **Scalar Multiplication**: The product of a matrix and a scalar is a new matrix obtained by multiplying each element of the original matrix by the scalar.
4. **Matrix Multiplication**: The product of two matrices is a new matrix obtained by multiplying the rows of the first matrix by the columns of the second matrix.
5. **Determinant**: The determinant is a scalar value that can be computed from the elements of a square matrix and encodes certain properties of the matrix.
6. **Inverse**: The inverse of a matrix is a matrix that, when multiplied by the original matrix, yields the identity matrix.

### Examples
- **Addition**: If **A** = [[1, 2], [3, 4]] and **B** = [[5, 6], [7, 8]], then **A + B** = [[6, 8], [10, 12]].
- **Subtraction**: If **A** = [[1, 2], [3, 4]] and **B** = [[5, 6], [7, 8]], then **A - B** = [[-4, -4], [-4, -4]].
- **Scalar Multiplication**: If **A** = [[1, 2], [3, 4]] and **c** = 3, then **c * A** = [[3, 6], [9, 12]].
- **Matrix Multiplication**: If **A** = [[1, 2], [3, 4]] and **B** = [[5, 6], [7, 8]], then **A * B** = [[19, 22], [43, 50]].
- **Determinant**: If **A** = [[1, 2], [3, 4]], then **det(A)** = 1*4 - 2*3 = -2.
- **Inverse**: If **A** = [[1, 2], [3, 4]], then **A^(-1)** = [[-2, 1], [1.5, -0.5]].

## Practice
For practice, refer to the [Matrices Notebook](02_matrices.ipynb).
