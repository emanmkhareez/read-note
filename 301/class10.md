# In memory storage

## Understanding the JavaScript Call Stack

### What is a ‘call’?

At the most basic level, a call stack is a data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call).


### How many ‘calls’ can happen at once?

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