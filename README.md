PROGRAM 1

Aim:

To develop a C++ program that takes input for a matrix from the user and displays it in matrix format.


Tools Required:

Programiz

Theory:

A matrix is a two-dimensional array consisting of rows and columns. In C++, matrices can be represented using 2D arrays. Nested loops are used to access each element by its row and column index. This program uses basic C++ concepts such as arrays, loops, and standard input/output to take input and display a matrix in tabular format.


Algorithm:

1. Start
  
2. Declare integer variables `rows`, `cols`, and a 2D array `matrix[100][100]`

3. Prompt the user to enter the number of rows and columns
 
4. Use nested loops to input matrix elements:

   * Outer loop for rows
   * Inner loop for columns
  
5. Use nested loops to display the matrix:

   * Outer loop prints each row
   * Inner loop prints each element followed by a tab space
  
7. End



Conclusion:

The program successfully takes a matrix as input from the user and displays it in matrix format. It demonstrates the use of 2D arrays and nested loops, which are fundamental in handling structured data like matrices in C++.


PROGRAM 2 

Aim:

To write a C++ program to perform the addition of two matrices.


Software Used:
Programiz

Theory:

Matrix addition is performed by adding corresponding elements from two matrices of the same dimensions. If matrix A and B are both of size *m × n*, then their sum C = A + B is also an *m × n* matrix, where each element C\[i]\[j] = A\[i]\[j] + B\[i]\[j].


Algorithm:

1. Start
2. Input number of rows and columns
3. Input elements of the first matrix
4. Input elements of the second matrix
5. Add corresponding elements and store in a new matrix
6. Display the resultant matrix
7. End


Conclusion:

The program successfully takes two matrices as input and displays their sum, demonstrating basic matrix operations using C++.

PROGRAM 3

Aim:

To write a C++ program to perform matrix multiplication of two matrices.



Software Used:

Programiz


Theory:

Matrix multiplication is defined only when the number of columns of the first matrix equals the number of rows of the second matrix.
If matrix **A** is of size *(m × n)* and matrix **B** is of size *(n × p)*, the product matrix **C = A × B** will be of size *(m × p)*, where each element is calculated as:


C[i][j] = \sum_{k=0}^{n-1} A[i][k] \times B[k][j]



Algorithm:

1. Start
2. Input dimensions of the first and second matrices
3. Check if multiplication is possible (c1 == r2)
4. Input elements of both matrices
5. Multiply matrices using nested loops
6. Store the result in a new matrix
7. Display the product matrix
8. End


Conclusion:

The program correctly multiplies two matrices using nested loops, verifying the fundamental logic of matrix multiplication in C++.


PROGRAM 4

Aim:

To write a C++ program to compute the sum of the main and secondary diagonals of a square matrix.

Software Used:

Programiz

Theory:

In a square matrix of size **n × n**:

* Main diagonal** elements are of the form `matrix[i][i]`
*Secondary diagonal** elements are of the form `matrix[i][n - i - 1]`

The program reads the matrix and iterates once through the rows to compute both diagonal sums.

Algorithm:

1. Start
2. Input size `n` of the square matrix
3. Input matrix elements
4. Initialize `mainDiagonalSum` and `secondaryDiagonalSum` to 0
5. Loop from `i = 0` to `n-1`

   * Add `matrix[i][i]` to `mainDiagonalSum`
   * Add `matrix[i][n - i - 1]` to `secondaryDiagonalSum`
6. Display both sums
7. End

Conclusion:

The program correctly calculates and displays the sums of the main and secondary diagonals of a square matrix using a single loop.


PROGRAM 5

Aim:

To write a C++ program to find the transpose of a given matrix.

Software Used:

Programiz

Theory:

The transpose of a matrix is obtained by swapping its rows with columns. If matrix **A** is of size *m × n*, its transpose **Aᵀ** will be of size *n × m*, where:


Aᵀ[j][i] = A[i][j]

Algorithm:

1. Start
2. Input number of rows and columns
3. Input matrix elements
4. For each element at position `[i][j]`, assign it to `[j][i]` in the transpose matrix
5. Display the original matrix
6. Display the transpose matrix
7. End

Conclusion:

The program successfully computes and displays the transpose of the given matrix by interchanging rows and columns.








