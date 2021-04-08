

the stack in javascript this means when you need call other code  this code goes  to in the top of new task  after  that the interpreter can go back to the task in hand.

the console is important way to find where the error exactly.

when use expression function the first must create  function ,after that invoke this function .

you dont able assignment value to var before declare this.

ERROR OBJECTS.

Error objects can help you find where your mistakes are
and browsers have tools to help you read them. 

When an Er ror object is created, it will contain the
following properties:
PROPERTY       DESCRIPTION

name           Type of execution

message            Description

fi le  nNumber    Name of the JavaScript file

l i neNumber     Line number of error 

### Syntax Error: 

This is caused by incorrect use of the rules of the
language. It is often the result of a simple typo.

When writing a special word incorrectly, for example a misspelling.

SyntaxError: Unexpect ed EOF
MISSING CLOSING BRACKET
document .getElementByid('page'  

 I forgot )

### ReferenceError:

When calling a function, its name is undefined
 
VARIABLE DOES NOT EXIST

This is caused by a variable that is not declared or is out of scope.
### UR I Error
INCORRECT USE OF URI FUNCTIONS If these characters are not escaped in URls, they will cause an error: / ? & I : ;

### MORE CONSOLE METHODS:
This technique is particularly helpful to show the nature of the information that you are writing to the screen.

1. con so 1 e. info() can be used for general information

2. consol e.warn() can be used for warnings

3. console .er ror() can be used to hold errors.



The **try** statement lets you test a block of code for errors.

The **catch** statement lets you handle the error.

The **throw** statement lets you create custom errors.

The **finally** statement lets you execute code, after try and catch, regardless of the result.
