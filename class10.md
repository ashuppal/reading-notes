https://github.com/ashuppal/reading-notes

**Read class 10**

**Understanding the JavaScript Call Stack**

What is a ‘call’?
A call is an expression that passes control and arguments (if any) to a function.

How many ‘calls’ can happen at once?
JavaScript has no native support for running multiple functions simultaneously

What does LIFO mean?
LIFO — Last In, First Out data structure.

Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

function firstFunction(){
  console.log("Hello from firstFunction");
}

function secondFunction(){
  firstFunction();
  console.log("The end from secondFunction");
}

secondFunction();

What causes a Stack Overflow?
Stack overflow error occurs when a computer program tries to use more memory space in the call stack than has been allocated to that stack.

**JavaScript error messages**

What is a ‘reference error’?
Reference error represents an error when a variable that doesn't exist (or hasn't yet been initialized) in the current scope is referenced.

What is a ‘syntax error’?
Syntax error occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.

What is a ‘range error’?
A RangeError is thrown when trying to pass a value as an argument to a function that does not allow a range that includes the value. 

What is a ‘type error’?
The TypeError object represents an error when an operation could not be performed, typically when a value is not of the expected type. 

What is a breakpoint?
In the debugger window, you can set breakpoints in the JavaScript code.
At each breakpoint, JavaScript will stop executing, and let you examine JavaScript values. 

What does the word ‘debugger’ do in your code?
A debugger is a computer program used by programmers to test and debug a target program.
Debugging means to run your code step by step in a debugging tool like Visual Studio, to find the exact point where you made a programming mistake.

**Things I want to know more about

Detailed examples of how a call stack works.
