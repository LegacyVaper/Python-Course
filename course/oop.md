# **🧬 Object-Oriented Programming**


## **📚 Classes and Objects**
Classes and objects are the building blocks of Object-Oriented Programming. A class is a blueprint for creating objects, and an object is an instance of a class.
```py
# Example of a class in Python
class Person:
    def __init__(self, name, age):
        self.name = name
        self.age = age
    
    def say_hello(self):
        print(f"Hello, my name is {self.name} and I'm {self.age} years old.")

# Example of creating an object from a class
person1 = Person("Alice", 25)
person1.say_hello() # Output: "Hello, my name is Alice and I'm 25 years old."
```

## **🔗 Inheritance**
Inheritance allows us to create new classes that are a modified version of an existing class. The existing class is called the parent or base class, and the new class is called the child or derived class.
```py
# Example of inheritance in Python
class Animal:
    def __init__(self, name):
        self.name = name
    
    def make_sound(self):
        print("Some generic animal sound")

class Dog(Animal):
    def __init__(self, name, breed):
        super().__init__(name)
        self.breed = breed
    
    def make_sound(self):
        print("Woof!")

# Example of creating objects from parent and child classes
animal1 = Animal("Generic animal")
dog1 = Dog("Fido", "Labrador")
animal1.make_sound() # Output: "Some generic animal sound"
dog1.make_sound() # Output: "Woof!"
```

## **🤹 Polymorphism**
Polymorphism is the ability of objects of different classes to be treated as if they were of the same class. This is useful when we want to write code that can work with different types of objects.
```py
# Example of polymorphism in Python
class Shape:
    def area(self):
        pass

class Rectangle(Shape):
    def __init__(self, width, height):
        self.width = width
        self.height = height
    
    def area(self):
        return self.width * self.height

class Circle(Shape):
    def __init__(self, radius):
        self.radius = radius
    
    def area(self):
        return 3.14 * self.radius * self.radius

# Example of using polymorphism with objects of different classes
shapes = [Rectangle(5, 10), Circle(7)]
for shape in shapes:
    print(shape.area()) # Output: 50, 153.86...
```

## **🧩 Encapsulation**
Encapsulation is the practice of hiding the internal workings of an object from the outside world. This is achieved by making the object's properties and methods private, so that they can only be accessed from within the object.
```py
# Example of encapsulation in Python
class BankAccount:
    def __init__(self, balance):
        self.__balance = balance
    
    def deposit(self, amount):
        self.__balance += amount
    
    def withdraw(self, amount):
        if amount > self.__balance:
            print("Insufficient funds")
        else:
            self.__balance -= amount
    
    def get_balance(self):
        return self.__balance

# Example of accessing private properties and methods
account1 = BankAccount(1000)
account1.deposit(500)
account1.withdraw(200)
print(account1.get_balance())
```

