# Numerical Mathematics with Julia

This repository provides a collection of numerical mathematics algorithms implemented using the Julia programming language. 



## Topics
- Linear algebra 
- Numerical Analysis 
- Optimization


## Getting Started with Julia

##### Installation
To use Julia, you must first download and install it on your system. 
You can download Julia from the official website: https://julialang.org/downloads/
Once you have Julia installed, you can start using it from the command line or from an integrated development environment (IDE) such as Juno or VS Code or Jupyter Notebook

##### Installing VS Code
 Download and install Visual Studio Code: https://code.visualstudio.com/


#### Example 
Here are some examples to get started with Julia:

### Hello World

The classic "Hello, world!" program in Julia is simply:

```julia
println("Hello, world!")
```

This will print the message "Hello, world!" to the console.

### Variables

Variables in Julia are created using the assignment operator `=`. For example:

```julia
x = 1
y = 2
z = x + y
```

Mathematical operators in Julia:

| Operator | Description |
|----------|-------------|
| `+`      | Addition    |
| `-`      | Subtraction |
| `*`      | Multiplication |
| `/`      | Division |
| `\`      | Left division |
| `^`      | Power |
| `sqrt()` | Square root |
| `abs()`  | Absolute value |
| `exp()`  | Exponential function |
| `log()`  | Natural logarithm |
| `log10()`| Base-10 logarithm |
| `sin()`  | Sine function |
| `cos()`  | Cosine function |
| `tan()`  | Tangent function |

These operators can be used with both scalar and array inputs. For example, to add two numbers in Julia, you would use the `+` operator:

```julia
a = 1
b = 2
c = a + b
```

This would set the value of `c` to 3. 

Similarly, to compute the element-wise product of two arrays, you would use the `.*` operator:

```julia
A = [1 2; 3 4]
B = [5 6; 7 8]
C = A .* B
```

This would set the value of `C` to `[5 12; 21 32]`.

Note that in Julia, division of integers returns a truncated integer. To perform true division, at least one of the operands must be a floating-point number. For example:

```julia
a = 3
b = 2
c = a / b   # returns 1.5
d = a ÷ b   # returns 1
```


## License

This repository is licensed under the MIT License. See [LICENSE](LICENSE) for more information.
