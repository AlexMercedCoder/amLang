# amLang
### Basic file structure

The file extension for amlang documents is .am and html and css can be included. To identify the syntax being used the following is used to distinguish.

To start parsing in amlang, HTML or css

===amlang===
===html===
===css===

to close the last opened parse indicator

To inject bound variable into html (data binding assumes front-end WASM implementation)
<{variable}>

======

### comments

inline comments are made with ///

multi-line comments are surrounded with //////

### print to console

print('string')

### Variable assignment

variableName <: value

This is used for variables, collections, functions and classes

### Multi-Variable assignment

var1,var2,var3 <: val1, val2, val3

This can be used for variables and collections, not functions and classes

### Math Operators

Addition: +

Subtraction: -

Multiplication: *

Division: /

Floor Division: //

Modulus: %

increment: ++

decrement --

Exponent: ^

### Boolean operators

Equality: =

Greater than: >

Less that: <

Greater/Equal: >=

Less/Equal: <=

Not: !=

### Example Code

example.am
```
===amlang===

myInt <: 1
myFloat <: 55.5
myString <: "Hello World"
myBoolean <: 5 > 6 /// Equals false

print(myString) ///Prints "Hello World"

//Addition

print(2+2) ///prints 4
print(+ 2 2 2) /// prints 6

///Subtraction

print(2-2) ///prints 0
print(- 2 2 2) /// prints -2

///Multiplication

print(2*2) ///prints 4
print(* 2 2 2) /// prints 8

//Division

print(2/2) ///prints 1
print(/ 2 2 2) /// prints .5

//Floor Division

print(2//2) ///prints 1
print(// 2 2 2) /// prints 0

===html===

<div>

<{myString}>

</div>

======

//Modulus

print(2%2) ///prints 0
print(% 2 2 2) /// prints 0


======


```
