# Linear Algebra with Julia

Julia is a powerful language for linear algebra computations.
We will cover Julia's linear algebra basics.

## Vectors

### Creating a Vector

To create a vector in Julia, use the square bracket notation:

```julia
x = [1, 2, 3]
```

This will create a vector `x` with the values `[1, 2, 3]`.

### Vector Operations

Julia supports many vector operations such as addition, subtraction, and dot products. For example:

```julia
x = [1, 2, 3]
y = [4, 5, 6]

# Addition
z = x + y   # returns [5, 7, 9]

# Subtraction
z = x - y   # returns [-3, -3, -3]

# Dot product
z = dot(x, y)   # returns 32
```

### Vector Functions

Julia also provides many built-in functions for working with vectors. For example:

```julia
x = [1, 2, 3]

# Length of vector
n = length(x)   # returns 3

# Sum of vector elements
s = sum(x)      # returns 6

# Mean of vector elements
m = mean(x)     # returns 2.0
```

## Matrices

### Creating a Matrix

To create a matrix in Julia, use the square bracket notation with semicolons to separate rows:

```julia
A = [1 2 3; 4 5 6; 7 8 9]
```

This will create a 3x3 matrix `A` with the values `[1 2 3; 4 5 6; 7 8 9]`.

### Matrix Operations

Julia supports many matrix operations such as addition, subtraction, multiplication, and transposition. For example:

```julia
A = [1 2; 3 4]
B = [5 6; 7 8]

# Addition
C = A + B    # returns [6 8; 10 12]

# Subtraction
C = A - B    # returns [-4 -4; -4 -4]

# Multiplication
C = A * B    # returns [19 22; 43 50]

# Transposition
C = A'       # returns [1 3; 2 4]
```

### Matrix Functions

Julia also provides many built-in functions for working with matrices. For example:

```julia
A = [1 2; 3 4]

# Determinant of matrix
d = det(A)   # returns -2.0

# Inverse of matrix
B = inv(A)   # returns [-2.0 1.0; 1.5 -0.5]
```

## Eigenvalues and Eigenvectors

Julia provides built-in functions for computing the eigenvalues and eigenvectors of a matrix. For example:

```julia
A = [1 2; 3 4]

# Eigenvalues and eigenvectors
eigenvalues, eigenvectors = eig(A)
```

This computes the eigenvalues and eigenvectors of the matrix `A`.
The eigenvalues are stored in the `eigenvalues` variable and the eigenvectors are stored in the columns of the `eigenvectors` matrix.
