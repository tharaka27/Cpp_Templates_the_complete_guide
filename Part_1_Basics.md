# Why templates ?
C++ requires to declare entities(variables, functions) using specific types. 
But some implementations (Ex. quick sort) are independent of the type. Hence there should be a method to 
generalize the code such that it works for wide variety of types.

bad alternatives:
1. You can implement the same behavior again and again for each type that needs this behavior.
- you reinvent the wheel. You make the same mistakes,
and you tend to avoid complicated but better algorithms because they lead to even more mistakes.
2. You can write general code for a common base type such as Object or void*.
- you lose the benefit of type checking. In
addition, classes may be required to be derived from special base classes, which makes it more
difficult to maintain your code.
3. You can use special preprocessors.
- code is replaced by some “stupid text replacement mechanism” that has no idea of scope and types, 
which might result in strange semantic errors.

Templates ->
1. Function templates
2. Class templates

# Function templates
Function templates are functions that are parameterized so that they represent a family of functions.
















