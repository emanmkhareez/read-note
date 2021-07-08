# In memory storage

## Understanding the JavaScript Call Stack

### What is a ‘call’?

At the most basic level, a call stack is a data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call).


### How many ‘calls’ can happen at once?

It is done one at a time from top to bottom. It means the call stack is synchronous.

### What does LIFO mean?

 Last In, First Out, it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns. 

### Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

![stack](https://cdn-media-1.freecodecamp.org/images/QgR2uIk7tW0YNz0Xm8g0jAPeRFI0e4sCejsv)

### What causes a Stack Overflow?

A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.

Here is an example:


function callMyself(){

  callMyself();

}

callMyself();


## javaScript error messages

### What is a ‘refrence error’?

1-It is means you try to use a variable that is not yet declared you get this type of errors.

2-This is also a common thing when using const and let, they are hoisted like var and function but there is a time between the hoisting and being declared so when you try to access them a reference error occurs, the fact that this happens to let and const is called Temporal Dead Zone (TDZ).

***example*** console.log(foo) // Uncaught ReferenceError: foo is not defined

### What is a ‘syntax error’?

It means you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.

***example*** JSON.parse( {'foo': 'bar'} ) // Uncaught SyntaxError: Unexpected token o in JSON at position 1

### What is a ‘range error’?

Try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up.



***example*** var foo= []
foo.length = foo.length -1 // Uncaught RangeError: Invalid array length

### What is a ‘tyep error’?

This types of errors show up when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.

### What is a breakpoint?

Select a line in the cod and check if it works or no, if it works that means the error is before it.

### What does the word ‘debugger’ do in your code?

The breakpoint can also be achieved by putting a debugger statement in your code in the line you want to break.