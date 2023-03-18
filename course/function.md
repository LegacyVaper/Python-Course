# **🎓 Functions**
In this course, you'll learn about the fundamentals of functions and how to use them effectively in your code.

## **🚀 Defining and Calling Functions**
Functions are blocks of code that can be reused throughout your program. They can be defined using the `def` keyword, followed by the function name and its parameters. For example:
```py
def greet(name):
    print(f"Hello, {name}!")
```

## **🎯 Function Parameters and Arguments**
To call a function, simply use its name and provide any required arguments. For example:
```py
greet("Alice")
```
This will output Hello, Alice!.

Functions can take zero or more parameters, which are variables that the function can use. Arguments are the values that are passed to a function when it is called. For example:
```py
def add(a, b):
    return a + b

result = add(3, 4)
```

In this case, `a` and `b` are the parameters of the `add` function, and `3` and `4` are the arguments that are passed to the function. The `add` function returns the sum of the two arguments, which is then assigned to the `result` variable.

## **🔙 Returning Values from Functions**
Functions can return values using the `return` keyword. For example:
```py
def square(x):
    return x ** 2

result = square(3)
```


## **🐍 Lambda Functions**
Lambda functions are a way to create anonymous functions on the fly. They can be useful in situations where you need a quick function that you don't want to define separately. For example:
```py
result = (lambda x, y: x + y)(3, 4)
```
In this case, the lambda function takes two arguments, `x` and `y`, and returns their sum. The function is defined inline and then immediately called with arguments `3` and `4`.