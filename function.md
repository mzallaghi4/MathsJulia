 # Function in Julia
 Creating and using functions with Julia programming language.

Step 1: Syntax of Function Declaration:
In Julia, functions are declared using the `function` keyword. 

```julia
function function_name(argument1, argument2, ...)
    # function body
    # statements to be executed
    # optional return statement
end
```

Step 2: Function Arguments:
Functions can take zero or more arguments. Arguments are enclosed within parentheses after the function name. 

```julia
function greet(name)
    println("Hello, $name!")
end
```

Step 3: Function Body:
The function body contains the statements that need to be executed. 
This is where the logic of the function resides. 
In Julia, the function's body is defined using indentation. 

```julia
function square(x)
    result = x * x
    return result
end
```

Step 4: Calling Functions:
To use a function, you need to call it by using its name along with the correct number and order of arguments.


```julia
greet("Julia User")  # Output: Hello, Julia User!
```

```julia
output = square(5)
println(output)  # Output: 25
```

Step 5: Return Statement:
The `return` statement is used to return a value from a function.
You can specify what the function should return by using the `return` keyword followed by the desired value. 
If no `return` statement is used, the function will return the value of the last evaluated expression. Here's an example:

```julia
function add(x, y)
    return x + y
end

result = add(3, 5)
println(result)  # Output: 8
```

Step 6: Optional Arguments:
You can define functions with optional arguments by assigning default values to some or all of the arguments. 
This allows you to call the function without providing certain arguments. Here's an example:

```julia
function power(base, exponent=2)
    return base^exponent
end

result1 = power(3)    # Output: 9 (3^2)
result2 = power(3, 3) # Output: 27 (3^3)
```
