# snake_charmer
A Repo to Experiment with Python Language. Why? you may ask..... Well because I suck at it. Lets see how complicated we can make things

Python:
Dynamically typed. 
That means it dosent give shit about what "type" of variable it is. Its value determines its "type" whether it is string, number etc. So no enforcing of type. Python changes the type of the varable dynamically. No declaration of variables needed

Interpreted.
That mean no compiling. The code is run directly by the interpreter. Thus Python makes a good language for scripting things. Thus Type checking is also done at run time.

High Level:
So faaaaar from the microchip. High Level datastructures like List and Dictionaries are available.

Modular:
So you can split your big ass program into smaller components athat can be reused in different projects.

No Brackets:
Python code is written without brackets. But on the downside, indentation matters a lot. Upside, forces you to keep your code pretty.

Extensibility:
You can link the python interpreter to an application written in C. (!READ UP ON THIS!)

Encoding:
Python source files are always treated as UTF-8 encoded. The standard Library uses ANSCII encoding for identifiers.

* in the python interpreter the last shown result is stored in _ . Keep _ read only. Dont re-assign it. you'll lose the magic ability

* Strings in python are immutable. If you try to reassign the variable with a different value it will give an error

Data Strucures in Python:
Number
String
List
Dictionaries

** range function: range(5) or range(5,10)
** pass function: used as a placeholder for a function to do nothing and only used for syntactical reasons

Function calls are all call by value..Where the value is the reference of the object.

Note: Diffrence between a function, Method and procedure.
Function: block of code that does some functionality and returns a value
Method: A function of an Object
Procedure: block of code that does some functionality only

Python doesnot have procedures..all procedures are function as all 'non-return' procedures retrun a value..A value called "None"

**DEFAULT ARGUMENT VALUES
The default values are evaluated at the point of function definition in the defining scope (READ ON THIS!)

i = 5
def f(arg=i):
    print(arg)
i = 6
f()

will print 5.

