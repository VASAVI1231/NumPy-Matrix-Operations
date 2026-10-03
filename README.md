
# Task 14 - NumPy Matrix Operations

## AI & ML Internship - VEDA Technology

This project demonstrates basic matrix operations using Python and NumPy.


## Objective

The objective of this project is to create two matrices and perform the following operations:

- Matrix Addition
- Matrix Subtraction
- Matrix Multiplication
- Matrix Transpose

These operations help in understanding basic linear algebra concepts used in Artificial Intelligence and Machine Learning.

---

## Technologies Used

- Python
- NumPy
- Google Colab
- GitHub

## Matrices Used

### Matrix A

```text
[[1 2 3]
 [4 5 6]
 [7 8 9]]

Matrix B

[[9 8 7]
 [6 5 4]
 [3 2 1]]


Operations Performed

1. Matrix Addition

Matrix addition is performed using the + operator.

addition = A + B

Result

[[10 10 10]
 [10 10 10]
 [10 10 10]]


2. Matrix Subtraction

Matrix subtraction is performed using the - operator.

subtraction = A - B

Result

[[-8 -6 -4]
 [-2  0  2]
 [ 4  6  8]]


3. Matrix Multiplication

Matrix multiplication is performed using the @ operator.

matrix_multiplication = A @ B

Result

[[ 30  24  18]
 [ 84  69  54]
 [138 114  90]]

Matrix multiplication is also verified using NumPy's np.dot() function.

dot_multiplication = np.dot(A, B)


4. Matrix Transpose

The transpose of a matrix changes its rows into columns and columns into rows.

transpose_A = A.T
transpose_B = B.T

Transpose of Matrix A

[[1 4 7]
 [2 5 8]
 [3 6 9]]

Transpose of Matrix B

[[9 6 3]
 [8 5 2]
 [7 4 1]]


NumPy Functions Used

Function / Operator	Purpose

np.array()	Creates NumPy arrays/matrices
+	Matrix addition
-	Matrix subtraction
@	Matrix multiplication
np.dot()	Matrix multiplication
.T	Matrix transpose



Difference Between Element-wise and Matrix Multiplication

Element-wise multiplication multiplies corresponding elements of two matrices.

A * B

Matrix multiplication follows the row-by-column multiplication rule.

A @ B

Therefore, * and @ perform different operations in NumPy.



Why Matrices Are Important in Machine Learning

Matrices are widely used in Machine Learning and Artificial Intelligence.

They are used to represent:

Datasets

Features

Model weights

Images

Transformations

Neural network calculations


Understanding matrix operations provides a foundation for learning Machine Learning algorithms and linear algebra.



Interview Questions

1. What is a matrix?

A matrix is a rectangular arrangement of values organized into rows and columns.

2. What is matrix multiplication?

Matrix multiplication is a mathematical operation where the elements of rows of the first matrix are multiplied with the corresponding elements of columns of the second matrix and summed.

3. What is the difference between A * B and A @ B in NumPy?

A * B performs element-wise multiplication, while A @ B performs matrix multiplication.

4. What is the transpose of a matrix?

The transpose changes the rows of a matrix into columns and the columns into rows.

5. Why are matrices important in Machine Learning?

Matrices provide an efficient way to represent and process numerical data, features, weights, images, and model calculations.


Learning Outcomes

After completing this project, I learned how to:

Create matrices using NumPy

Perform matrix addition

Perform matrix subtraction

Perform matrix multiplication

Calculate matrix transpose

Use np.dot() for matrix multiplication

Understand the difference between element-wise and matrix multiplication

Understand the importance of matrices in Machine Learning



Conclusion

This project provided practical experience with basic matrix operations using Python and NumPy. The concepts learned in this task form an important foundation for Machine Learning, Artificial Intelligence, Data Science, and Linear Algebra.

