# **🎓 Modules**
In this course, you'll learn about the fundamentals of functions and how to use them effectively in your code.

## **📥 Importing Modules**
To use a module in your Python program, you'll first need to import it. Here's how you can import a module:
```py
import module_name
```

If you want to give the module a different name in your program, you can use the as keyword:
```py
import module_name as my_module
```

You can also import specific functions or variables from a module:
```py
from module_name import function_name, variable_name
```

## **🛠️ Creating and Using Modules**
To create your own module, simply create a new .py file with your code and save it in the same directory as your main Python script. Then, you can import it just like any other module.

Here's an example of a simple module that defines a function:
```py
# my_module.py

def say_hello():
    print("Hello, world!")
```

To use this module in your program, you can import it and call the function:
```py
import my_module

my_module.say_hello()
```


## **📚 Standard Libraries**
Python comes with a set of standard libraries that provide useful functionality for a variety of tasks. Here are some examples:
`os`: Operating system interfaces
`datetime`: Date and time manipulation
`math`: Mathematical functions
`random`: Random number generation
`json`: JSON encoding and decoding

To use a standard library module, you'll need to import it just like any other module:
```py
import os

# Use os.path.join() to join file paths
file_path = os.path.join("path", "to", "file.txt")
```
