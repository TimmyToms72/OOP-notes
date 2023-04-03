# Object Oriented Programing Notes 1

I think OOP is awsome

```python
# Exaple class

class Person:
    def __init__(self,name):
        self.name = name
        
    def __str__(self):
        return f'Person object called: {self,name}
        
    def __repr__(self):
        return self.__repr__()
```
Object
- is fuctional code methods and attributes
attributes is object code
methods is object code

Class 
- is a built in key word that allows you to create a class

```python
# example of setting up a class and methods
class Thing:
    def __init__(self,name,age,height):
        self.name = name
        self.age = age
        self.height = height
```

Encapsulation 
- Information hiding restricting the access to the class/objects certain attributes and methods

```python
# exaple of encapsulation

class Person:
    def __init__(self,name):
        self.__name = name
```
Overloading
- two methods have the same name in the class but different paramiters
- you cant do this in python

Overriding
- Two methods with the same method name and parameters

Polymorphism 
- A method that you can use in different classes and oject that is dependant on the parameters

__repr__()
- is a buit in function allows us to print our object

__str__()
- is a built in function that turns the object into a string

```python
# exaple of __repr__ and __str__

class Person:
    def __init__(self,name):
        self.name = name
    
    def __str_(self):
        retrun f'the persons name is {self.name}'
```

Inheritance 
- When an object or class is based on another class above it
- The fundamental flaw is that if the parent class has to get recorded the whole program has to be recorded 

Uses
- A child can receive attributes form parents
- A child can enhance itself with new methods and attributes
- A child can override methods and attributes from the parent class

```python
# exaple of inheritance

class ParentClassName:
    def __init__(self,name):
        self.name = name
        # define character class

class InheritanceClass(ParentClassName):
	def __init__(self, param, param2):
		ParentClassName.__init__(self, param)
		self.param2 = param2
```

super()
- Is a built in function that quickly access a parent class code

Iterable objects
- Object that can iterate in a sequence
- it can iterate in a string or a list

__iter__() 
- Allows the object to be iterable

__next__()
- Gets the next value when iterating

