# Code 301 - Intermediate Software Development

## Class 10 - In memory storage

Block intro

> I love it when a plan comes together - John "Hannibal" Smith

### Understanding the JavaScript Call Stack ([Article](https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4/))

* What is a ‘call’?
* How many ‘calls’ can happen at once?
* What does LIFO mean?
* Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
* What causes a Stack Overflow?

A call is a data strucuture that uses the LIFO (last In First Out) priciple.
It is single threaded call, one is processed at a time
stack overflow occurs when there is a recursive function. A self repeating function.

### JavaScript error messages ([Article](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c))

* What is a ‘refrence error’?
* What is a ‘syntax error’?
* What is a ‘range error’?
* What is a ‘type error’?
* What is a breakpoint?
* What does the word ‘debugger’ do in your code?

Reference errors are thrown when a variable is used prior to its defining.
Syntax errors occur when code cannot be parsed correctly within the realm of syntax
Range errors occur when the attempted manipulation of an object with length is given an invalid length
Type errors occur when the types of variables or objects are incompatible. ('String' !== 4)
A breakpoint is a location in the code that the app ceases to run and hits an error in a debugger.
A debugger takes you through line by line to look for breakpoints in your code.

### Things I want to know more about

* 


Go [Home](index.md)