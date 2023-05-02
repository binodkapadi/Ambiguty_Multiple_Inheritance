# Ambiguty_Multiple_Inheritance
This is about ambiguous behavior of multiple inheritance while calling function from two base classes. I have given solution how to resolve this behavior of multiple inheritance.

In case of multiple inheritance::

if both base class have same function then while calling these functions with the help of object of base class the compiler will confused either which function you are calling so the compiler will show the error message.

This Ambigiuous behavour of multiple inheritance can be solved by using scope resolution operator(::) and then calling function of each classes.
