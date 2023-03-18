# **🎓 Control Flow**
In this course, you will learn about control flow statements in Python.

## **🚦 Control Flow**
Control flow is the order in which statements are executed in a program. In Python, you can use control flow statements like conditional statements and loops to control the flow of your program.

## **Conditional statements - if, elif, else**
Conditional statements allow you to execute different blocks of code based on whether a certain condition is true or false. Here's an example:
```py
if x > 0:
    print("x is positive")
elif x < 0:
    print("x is negative")
else:
    print("x is zero")
```

## **Loops - for, while**
Loops allow you to repeat a block of code multiple times. In Python, you can use for and while loops to accomplish this. Here's an example:
```py
for i in range(5):
    print(i)

while x < 10:
    print(x)
    x += 1
```

## **Loop control statements - break, continue, pass**
Loop control statements allow you to modify the behavior of loops. Here are some examples:
```py
# break statement
for i in range(10):
    if i == 5:
        break
    print(i)

# continue statement
for i in range(10):
    if i == 5:
        continue
    print(i)

# pass statement
for i in range(10):
    pass
```
