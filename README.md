# Introduction to python
Python is one of the most popular and beginner-friendly programming languages in the world
# What Is Python?
Created by: Guido van Rossum in 1991

Type: High-level, interpreted, general-purpose language

Used for: Web development, data analysis, machine learning, automation, scripting, and more
# Why Learn Python?
Simple syntax: Reads almost like English

Cross-platform: Works on Windows, macOS, Linux, and more

Versatile: Supports multiple programming paradigms (procedural, object-oriented, functional)

Massive ecosystem: Thousands of libraries for everything from AI to web app.
# Key Concepts to Explore
1.Variables and Data Types

2.Control Structures: if, for, while

3.Functions and Modules

4.Lists, Tuples, Dictionaries

5.Object-Oriented Programming

6.File Handling

7.Error Handling

8.Libraries: NumPy, Pandas, Flask, Django, etc.
#What is OOP in Python?
Object-Oriented Programming (OOP) is a programming style that organizes code around objects and classes, rather than functions and logic. Python supports OOP and makes it easy to model real-world entities.
# Core Concepts of Python OOP
# 1.Class
A blueprint for creating objects. It defines attributes and behaviors.

    class Car:
        def __init__(self, brand, model):
            self.brand = brand
            self.model = model

        def drive(self):
            print(f"{self.brand} {self.model} is driving.")
# 2. Object
An instance of a class. It contains real data and can perform actions defined by its class.

    my_car = Car("Toyota", "Camry")
    my_car.drive()  # Output: Toyota Camry is driving.
# 3. Encapsulation
Hiding internal state and requiring all interaction to be performed through an object's methods.

        class BankAccount:
            def __init__(self, balance):
            self.__balance = balance  # private attribute

        def deposit(self, amount):
            self.__balance += amount
# 4. Inheritance
Allows one class to inherit attributes and methods from another.

    class ElectricCar(Car):
    def charge(self):
        print(f"{self.brand} {self.model} is charging.")
# 5. Polymorphism
Different classes can define methods with the same name, and Python will call the appropriate one.

    class Dog:
        def speak(self):
            print("Woof!")

    class Cat:
         def speak(self):
            print("Meow!")

    def animal_sound(animal):
        animal.speak()

    animal_sound(Dog())  # Woof!
    animal_sound(Cat())  # Meow!
# Why Use OOP?
Modularity: Code is organized into classes.

Reusability: Classes can be reused across projects.

Scalability: Easier to manage large codebases.

Maintainability: Changes are easier to implement.

