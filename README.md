# Lecture 3

1)Functions   2)Scope   3)Hoisting   4)Hoisting

# 1)Functions

![](/Function%20JS.jpg)

>Function – Declaration

• A function is declared using the function keyword.

• The basic rules of naming a function are similar to naming a variable. It is 
better to write a descriptive name for your function. For example, if a 
function is used to add two numbers, you could name the function add or 
addNumbers

• The body of function is written within {}.

In previous page , we have declared a function named 
greet(). To use that function, we need to call it.
 
Here's how you can call the above greet() function.

![](/func1.png)


>Function – Expression

Variable x is used to store the function. 
Here the function is treated as an 
expression. And the function is called 
using the variable name.

The function is called an anonymous 
function.

# Scope

The building our represents program's nested 
scope ruleset. The first floor of the building 
represents your currently executing scope, 
wherever you are. The top level of the building is 
the global scope.

![](/OIP%20JS.jpg)

>Scope – Lexical Scope

Lexical scope is scope that is defined
at lexing time. In other words, lexical 
scope is based on where variables
and blocks of scope are authored, by 
you, at write time, and thus is
(mostly) set in stone by the time the lexer
processes your co.

![](/blob.jpg)

>Scope –Global Scope

A variable declared at the top of a 
program or outside of a function is 
considered a global scope variable.

![](/blob%202.jpg)

>Scope – Local Scope

The variable can also have a local scope, 
it can only be accessed within a function.

In the below program, variable a is a 
global variable and variable b is a local 
variable. The variable b can be accessed 
only inside the greet function. Hence, 
when we try to access variable b outside 
of the function, an error occurs.


