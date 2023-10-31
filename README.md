# Matrix Multiplication Python Program Explanation

This Markdown document explains a Python program for matrix multiplication. The program takes two matrices, `A` and `B`, as input and calculates their matrix multiplication. Additionally, it includes functions for matrix input and matrix printing.

## `multiply_matrices(A, B) Function`

The `multiply_matrices(A, B)` function performs the matrix multiplication between matrices `A` and `B`. Here's a step-by-step explanation of the function:

1. **Input Validation:** It first checks if the number of columns in matrix `A` is equal to the number of rows in matrix `B`. If not, it prints a message stating that matrix multiplication is not possible and returns `None`.

2. **Result Initialization:** The function initializes an empty list called `result` to store the result of matrix multiplication.

3. **Matrix Multiplication:** It uses nested loops to iterate through the rows of matrix `A` and the columns of matrix `B`. For each element in the resulting matrix, it uses a third nested loop to perform the summation of the products of corresponding elements in matrices `A` and `B`.

4. **Result Formation:** The result is a list of lists, representing the resulting matrix. The function returns this result.

## `input_matrix() Function`

The `input_matrix()` function is responsible for taking user input to create a matrix. Here's how it works:

1. It asks the user for the number of rows and columns for the matrix.

2. It collects the elements for each cell in the matrix using nested loops.

3. The function returns the matrix as a list of lists.

## `Matrix Input and Calculation`

1. `A = input_matrix()`: This line of code collects user input to create matrix `A`.

2. `B = input_matrix()`: This line of code collects user input to create matrix `B`.

3. `print_matrix(matrix)` Function: This function takes a matrix as input and prints it row by row.

4. `result_matrix = multiply_matrices(A, B)`: This line of code calls the `multiply_matrices` function to perform matrix multiplication on matrices `A` and `B` and stores the result in the `result_matrix` variable.

5. `print_matrix(result_matrix)`: Finally, it prints the resulting matrix to the console using the `print_matrix` function.

The program collects user input for two matrices, performs matrix multiplication if possible, and then prints the resulting matrix.

---
