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

# Hoisting

> Hoisting - Variable

There’s a temptation to think that all of the code you see in a 
JavaScript
program is interpreted line-by-line, top-down in order, as the 
program
execute. While that is essentially true, there’s one part of that 
as‐
assumption that can lead to incorrect thinking about your 
program.

>Hoisting – Function Declaration

So, one way of thinking, sort of metaphorically, about this process, is
that variable and function declarations are “moved” from where they
appear in the flow of the code to the top of the code. This gives rise to
the name hoisting.
The function foo’s declaration (which in this case includes the implied value of 
it as an actual function) is hoisted, such that the call on the first line is able to 
execute

>Hoisting – Function Expression

Function declarations are hoisted, as we just saw. 
But function expressions are not.
The variable identifier foo is hoisted and attached to the enclosing
scope(global) of this program, so foo() doesn't fail as a ReferenceError. 
But foo has no value yet (as it would if it had been a true function
declaration instead of expression). So, foo() is attempting to invoke
the undefined value, which is a Type Error illegal operation.

# Recursion

>Recursion

![](/R1.jpg)

Recursion is a process of calling itself. A function that 
calls itself is called a recursive function.

The syntax for recursive function is:

![](/photo1.jpg)

>Recursion

A recursive function must have a condition to stop calling itself. Otherwise, 
the function is called indefinitely.

Once the condition is met, the function stops calling itself. This is called the 
base condition.

To prevent infinite recursion, you can use if...else statement (or similar 
approach) where one branch makes the recursive call, and the other 
doesn't.
