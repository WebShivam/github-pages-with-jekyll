---
title: "A Guide to JavaScript for Beginners"
date: 2021-09-20
---

# Introduction
JavaScript is the Programming Language for the Web. <img src="https://i.imgur.com/utpmCAz.png" alt="js-logo" align="right" width="250"/>

## Why to study JavaScript?
JavaScript is one of the 3 languages all web developers must learn:
   1. HTML to define the content of web pages
   2. CSS to specify the layout of web pages
   3. JavaScript to program the behavior of web pages
#### A Simple JavaScript Document
Example
 
<br>The example above "finds" an HTML element (with id="demo"), and changes the element content (innerHTML) to "Hello JavaScript".

Example Explained <br>
●	The <!DOCTYPE html> declaration defines that this document is an HTML5 document <br>
●	The <html> element is the root element of an HTML page <br>
●	The <body> element defines the document's body, and is a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc. <br>
●	The `<h2>` element defines a second-level heading <br>
●	The `<p>` element defines a paragraph <br>
●	The `<button>` element defines a clickable button where the JavaScript method document.getElementById() is introduced by using an onclick event. <br>
## Properties of JavaScript
1.	In HTML, JavaScript code is inserted between <script> and </script> tags. You can place any number of scripts in an HTML document.
        Example
      
2.	Scripts can be placed in the <body>, or in the <head> section of an HTML page, or in both.
## Advantages of JavaScript
1.	JavaScript accepts both double and single quotes.
2.	JavaScript Can Change HTML Attribute Values
3.	JavaScript Can Change HTML Styles (CSS):
Changing the style of an HTML element, is a variant of changing an HTML attribute
Example
 
<br>4.	JavaScript Can Hide HTML Elements:
Hiding HTML elements can be done by changing the display style
Example
 
5.	JavaScript Can Show HTML Elements:
Showing hidden HTML elements can also be done by changing the display style
Example 
## External JavaScript
1.	External scripts are practical when the same code is used in many different web pages.
2.	JavaScript files have the file extension .js.
3.	To use an external script, put the name of the script file in the src (source) attribute of a <script> tag
Example:
 
4.	External scripts can be referenced with a full URL or with a path relative to the current web page.
Example:
 
5.	Several script files can be included to one page by using several script tags at once.
Example:
 
## External JavaScript Advantages
Placing scripts in external files has some advantages:
1.	It separates HTML and code.
2.	It makes HTML and JavaScript easier to read and maintain.
3.	Cached JavaScript files can speed up page loads.
## Execution of a JavaScript file
JavaScript can "display" data in different ways:
1.	Writing into an HTML element, using innerHTML.
2.	Writing into the HTML output using document.write().
3.	Writing into an alert box, using window.alert().
4.	Writing into the browser console, using console.log().
### Various executable JavaScript methods:
#### innerHTML
To access an HTML element, JavaScript can use the document.getElementById(id) method. The id attribute defines the HTML element. The innerHTML property defines the HTML content.
Example
 
#### document.write()
For testing purposes, it is convenient to use document.write()
Example
 
Note: 
1.	Using document.write() after an HTML document is loaded, will delete all existing HTML.
2.	The document.write() method should only be used for testing.

#### window.alert()
You can use this method as an alert box to display data
Example
 
Here, you can skip the window keyword. In JavaScript, the window object is the global scope object, that means that variables, properties, and methods by default belong to the window object. This also means that specifying the window keyword is optional. Consider the following example for the better understanding:
 


#### console.log()
For debugging purposes, you can call the console.log() method in the browser to display data.
Example
 


#### window.print()
JavaScript does not have any print object or print methods. You cannot access output devices from JavaScript. The only exception is that you can call the window.print() method in the browser to print the content of the current window.
Example
 

## JavaScript Statements
In a programming language, these programming instructions are called statements.
1.	A JavaScript program is a list of programming statements.
2.	In HTML, JavaScript programs are executed by the web browser.
3.	JavaScript statements are composed of Values, Operators, Expressions, Keywords, and Comments.
4.	JavaScript programs (and JavaScript statements) are often called JavaScript code.
5.	Semicolons separate JavaScript statements.
6.	When separated by semicolons, multiple statements on one line are allowed.
Example
 
7.	JavaScript ignores multiple spaces. You can add white space to your script to make it more readable.
8.	JavaScript statements can be grouped together in code blocks, inside curly brackets {...}.
9.	The purpose of code blocks is to define statements to be executed together.
10.	JavaScript statements often start with a keyword to identify the JavaScript action to be performed.
Here is a list of some of the keywords with its corresponding description given aside:
 
Note: 
1.	JavaScript keywords are reserved words.
2.	Reserved words cannot be used as names for variables.
## JavaScript Syntax
1.	The JavaScript syntax defines two types of values:
a.	Fixed values which are also called as Literals.
b.	Variable values which are also called as Variables.
2.	In JavaScript, numbers can be written with or without decimals and strings are text, written within double or single quotes.
3.	JavaScript uses the var keyword to declare variables and equal sign (=) is used to assign values to variables.
4.	In JavaScript, double slashes (//) or /* and */ are used as the single commented lines and as the multiple commented lines.
5.	In JavaScript, identifiers are used to name variables (and keywords, and functions, and labels). Here, the first character must be a letter, or an underscore (_), or a dollar sign ($) and the subsequent characters may be letters, digits, underscores, or dollar signs. All JavaScript identifiers are case sensitive. 
6.	Hyphens are not allowed for variable declarations in JavaScript. They are reserved for subtractions.
7.	JavaScript uses the Unicode character set.

## JavaScript Variables
In JavaScript, we have various operators such as follows:
1.	Arithmetic operators
2.	Assignment operators
3.	String operators
4.	Comparison operators
5.	Logical operators
6.	Type operators
7.	Bitwise operators
### Arithmetic operators
Arithmetic operators perform arithmetic on numbers (literals or variables). A typical arithmetic operation operates on two numbers. The numbers (in an arithmetic operation) are called operands. The operation (to be performed between the two operands) is defined by an operator.

Here is the list of arithmetic operators with their corresponding description:
 


### Assignment operators
Assignment operators assign values to JavaScript variables.
Here is the list of assignment operators with an example:
 

### String operators
The + operator can also be used to add (concatenate) strings.
For example,
 

HackerEarth will be printed as an output for this string concatenation

### Comparison operators
Comparison operators are used in logical statements to determine equality or difference between variables or values. These operations return a boolean value on applying on the conditional statements. 
Here is the list of few comparison operators with their corresponding description:
 


### Logical operators
Logical operators are used to determine the logic between variables or values. These operations return a boolean value on applying on the conditional statements. Here is the list of logical operators with their corresponding description:
 

### Type operators
Type operators are used to return the data type of a particular variable or to type a variable from one datatype to another datatype. Here is the list of type operators with their corresponding description:
 

### Bitwise operators
Bit operators work on 32 bits numbers. Any numeric operand in the operation is converted into a 32 bit number. The result is converted back to a JavaScript number. Here is the list of bitwise operators with their corresponding description:
 
## JavaScript Data Types
In JavaScript, we have various data types such as Number, String, object etc., JavaScript has dynamic types. This means that the same variable can be used to hold different data types.
For example,
 

## JavaScript Numbers
1.	JavaScript has only one type of number. Numbers can be written with or without decimals.
2.	Extra large or extra small numbers can be written with scientific (exponent) notation
Example:
 
3.	Unlike many other programming languages, JavaScript does not define different types of numbers, like integers, short, long, floating-point etc. JavaScript numbers are always stored as double precision floating point numbers, following the international IEEE 754 standard. This format stores numbers in 64 bits, where the number (the fraction) is stored in bits 0 to 51, the exponent in bits 52 to 62, and the sign in bit 63
4.	Integers (numbers without a period or exponent notation) are accurate up to 15 digits.
Example:
 
5.	NaN is a JavaScript reserved word indicating that a number is not a legal number.
Example:
 
6.	Infinity (or -Infinity) is the value JavaScript will return if you calculate a number outside the largest possible number.
Example:
 
and the output will be as follows:
 
7.	JavaScript interprets numeric constants as hexadecimal if they are preceded by 0x.
Example:
 

## JavaScript Number methods
Primitive values (like 3.14 or 2014), cannot have properties and methods (because they are not objects). But with JavaScript, methods and properties are also available to primitive values, because JavaScript treats primitive values as objects when executing methods and properties.
Here is the list of number methods:
1.	The toString() method returns a number as a string. All number methods can be used on any type of numbers (literals, variables, or expressions).
2.	The toExponential() method returns a string, with a number rounded and written using exponential notation.
3.	The toFixed() method returns a string, with the number written with a specified number of decimals.
4.	The toPrecision() method returns a string, with a number written with a specified length.
5.	The valueOf() method returns a number as a number. In JavaScript, a number can be a primitive value (typeof = number) or an object (typeof = object). The valueOf() method is used internally in JavaScript to convert Number objects to primitive values.

## Global JavaScript methods
JavaScript global methods can be used on all JavaScript data types.
These are the most relevant methods, when working with numbers:
 

### Number properties
Here is the list of number properties with their corresponding descriptions:
 

## JavaScript Strings
1.	JavaScript strings are used for storing and manipulating text.
2.	To find the length of a string, use the built-in length property.
Example:
 
3.	The backslash (\) escape character turns special characters into string characters
Example:
 
### JavaScript String methods
1.	The length property returns the length of a string.
2.	The indexOf() method returns the index of (the position of) the first occurrence of a specified text in a string. The lastIndexOf() method returns the index of the last occurrence of a specified text in a string. Both of these methods return -1 if the text is not found.
3.	The search() method searches a string for a specified value and returns the position of the match.
4.	There are 3 methods for extracting a part of a string: <br>
  a.	The slice() method extracts a part of a string and returns the extracted part in a new string. This method takes 2 parameters: the start position, and the end         position (end not included). <br>
  b.	The substring() method is similar to slice(). The difference is that substring() cannot accept negative indexes. If you omit the second parameter, substring()         will slice out the rest of the string. <br>
  c.	The substr() method is similar to slice(). The difference is that the second parameter specifies the length of the extracted part. If you omit the second             parameter, substr() will slice out the rest of the string.
5.	The replace() method replaces a specified value with another value in a string. This method does not change the string it is called on. It returns a new string. By default, this method is case sensitive. To replace case insensitive, use a regular expression with an /i flag (insensitive). To replace all matches, use a regular expression with a /g flag (global match). 
6.	The concat() method joins two or more strings.
7.	The trim() method removes whitespace from both sides of a string
8.	There are 2 methods for extracting string characters:
  a.	The charAt() method returns the character at a specified index (position) in a string
  b.	The charCodeAt() method returns the unicode of the character at a specified index in a string
9.	A string can be converted to an array with the split() methods.
## JavaScript Arrays
JavaScript arrays are used to store multiple values in a single variable.
## Creating an Array
Using an array literal is the easiest way to create a JavaScript Array.
Example:
 

## Accessing an element from an Array
You access an array element by referring to the index number.
Example:
 

## Changing an Array element
 

### Arrays are Objects
1.	Arrays are a special type of objects. The typeof operator in JavaScript returns "object" for arrays.
2.	Arrays use numbers to access its "elements".
### Array Elements Can Be Objects
1.	JavaScript variables can be objects. Arrays are special kinds of objects.
2.	You can have variables of different types in the same Array.
3.	You can have objects in an Array. You can have functions in an Array. You can have arrays in an Array
### The Difference Between Arrays and Objects
1.	In JavaScript, arrays use numbered indexes.  
2.	In JavaScript, objects use named indexes.
### When to Use Arrays. When to use Objects.
1.	JavaScript does not support associative arrays.
2.	You should use objects when you want the element names to be strings (text).
3.	You should use arrays when you want the element names to be numbers.

## JavaScript Array Methods
1.	The JavaScript method toString() converts an array to a string of (comma separated) array values.
2.	The join() method also joins all array elements into a string. It behaves just like toString(), but in addition you can specify the separator.
3.	The pop() method removes the last element from an array
4.	The push() method adds a new element to an array (at the end)
5.	The shift() method removes the first array element and "shifts" all other elements to a lower index.
6.	The unshift() method adds a new element to an array (at the beginning), and "unshifts" older elements
7.	The splice() method can be used to add new items to an array
8.	The concat() method creates a new array by merging (concatenating) existing arrays
9.	The slice() method slices out a piece of an array into a new array.
10.	JavaScript automatically converts an array to a comma separated string when a primitive value is expected.
11.	The sort() method sorts an array alphabetically.
12.	The reverse() method reverses the elements in an array.
13.	The forEach() method calls a function (a callback function) once for each array element. This function takes 3 arguments such as the item value, the item index, and the array itself.
14.	The map() method creates a new array by performing a function on each array element. It does not execute the function for array elements without values. This method does not change the original array. his function takes 3 arguments such as the item value, the item index, and the array itself.
15.	The filter() method creates a new array with array elements that passes a test. This method does not change the original array. his function takes 3 arguments such as the item value, the item index, and the array itself.
16.	The reduce() method runs a function on each array element to produce (reduce it to) a single value. It runs a function on each array element to produce (reduce it to) a single value.This method does not change the original array. This function takes 4 arguments such as the total, the item value, the item index, and the array itself.
17.	The reduceRight() method runs a function on each array element to produce (reduce it to) a single value. It works from right-to-left in the array. This function takes 4 arguments such as the total, the item value, the item index, and the array itself.


## JavaScript Functions
JavaScript functions are defined with the function keyword.
Example:
 

## Function Expressions
1.	A JavaScript function can also be defined using an expression.
2.	A function expression can be stored in a variable.
3.	The function above is actually an anonymous function (a function without a name).
4.	Functions stored in variables do not need function names. They are always invoked (called) using the variable name.
Example:
 
## The Function() Constructor
Functions can also be defined with a built-in JavaScript function constructor called Function().
Example:
 

## Self-Invoking Functions
1.	Function expressions can be made "self-invoking".
2.	A self-invoking expression is invoked (started) automatically, without being called.
3.	Function expressions will execute automatically if the expression is followed by ().
4.	You cannot self-invoke a function declaration.
5.	You have to add parentheses around the function to indicate that it is a function expression
Example:
 

## Functions are Objects
1.	The typeof operator in JavaScript returns "function" for functions.
2.	But, JavaScript functions can best be described as objects.
3.	JavaScript functions have both properties and methods.
4.	The arguments.length property returns the number of arguments received when the function was invoked
Example:
 

## Arrow Functions
1.	Arrow functions allow a short syntaxArrow functions do not have their own this. They are not well suited for defining object methods.
2.	Arrow functions are not hoisted. They must be defined before they are used.
3.	Using const is safer than using var, because a function expression is always constant value.
4.	You can only omit the return keyword and the curly brackets if the function is a single statement.
Example:
 

## Function Parameters and Arguments
A JavaScript function does not perform any checking on parameter values (arguments).
1.	Function parameters are the names listed in the function definition.
2.	Function arguments are the real values passed to (and received by) the function.
### Parameter Rules
1.	JavaScript function definitions do not specify data types for parameters.
2.	JavaScript functions do not perform type checking on the passed arguments.
3.	JavaScript functions do not check the number of arguments received.
### Parameter Defaults
If a function is called with missing arguments (less than declared), the missing values are set to: undefined. Sometimes this is acceptable, but sometimes it is better to assign a default value to the parameter
Example:
 


## The Arguments Object
1.	JavaScript functions have a built-in object called the arguments object.
2.	The argument object contains an array of the arguments used when the function was called (invoked).
Example:
 

## Arguments are Passed by Value
1.	The parameters, in a function call, are the function's arguments.
2.	JavaScript arguments are passed by value: The function only gets to know the values, not the argument's locations.
3.	If a function changes an argument's value, it does not change the parameter's original value.
4.	Changes to arguments are not visible (reflected) outside the function.
## Objects are Passed by Reference
1.	In JavaScript, object references are values.
2.	Because of this, objects will behave like they are passed by reference:
3.	If a function changes an object property, it changes the original value.
4.	Changes to object properties are visible (reflected) outside the function.

## JavaScript Function Call
With the call() method, you can write a method that can be used on different objects.

### All Functions are Methods
1.	In JavaScript all functions are object methods.
2.	If a function is not a method of a JavaScript object, it is a function of the global object
The JavaScript call() Method
1.	The call() method is a predefined JavaScript method.
2.	It can be used to invoke (call) a method with an owner object as an argument (parameter).
3.	With call(), an object can use a method belonging to another object.
Example:
 
4.	The call() method can accept arguments
Example:
 
5.	With the apply() method, you can write a method that can be used on different objects. The difference between call() method and apply() method is that the call() method takes arguments separately whereas the apply() method takes arguments as an array.
6.	The apply() method accepts arguments in an array
Example:
 
7.	You can find the largest number (in a list of numbers) using the Math.max() method.
8.	In JavaScript strict mode, if the first argument of the apply() method is not an object, it becomes the owner (object) of the invoked function. In "non-strict" mode, it becomes the global object.
