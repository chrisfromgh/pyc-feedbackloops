https://2023.pycascades.com/program/talks/metaprogramming-in-python-using-metaclasses/

Meta programming can be achieved using:
- decorators
descriptors
metaclasses
introspection


Wha is a singleton? a class object that defines only one object

What are descriptors? Exntending an attribute value in a class object

dunder methods "magic methods" that are magically called, but not really, just really well defined implicit calls. MetaClass.__prepare__


Second usage of type:

type(name, bases, dict) -> a new type

classes are instances of metaclasses, and objects are instances of classes

`__new__` is responsible for returning a new instance of a class
`__init__` is supposed to return a an instance with its values.



When to use metaclasses - In order to control how classes are created. 

I guess a neat way to keep track of what classes were written in our code is to make a registry of classes that re created and inherited from other classes

Screw metaclasses more than 99% of users of python don't need them LOL.

Abstract base classes: https://www.geeksforgeeks.org/abstract-base-class-abc-in-python/
Enums use metaclasses..huh interesting
Django Models also use metaclasses

Basically in short, all metaclasses that create classes are inherited from the class type. The type of type is type
