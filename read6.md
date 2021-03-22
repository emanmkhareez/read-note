# Comparison and logical operators

to create variable using javascript write var +the Name of this var to write inside page use document.write(" write inside this") if you want write inside the element such as div using this command
document.getElementById(write the id ).innerHTMl('write inside this')
function is collection of statements  that releated to each other to excute  task.
Functions can take parameters (informatiorJ required
to do their job) and may return a value
Objects are variables too. But objects can contain many values.
In an object, variables are known as properties of the
object; functions are known as methods of the object. 
 exampleBooleans can be objects (if defined with the new keyword)
JavaScript also has several built-in objects such as
String, Number, Math, and Date. 
compartion  opereator
this use to compare any two or more varible with other
 example 
 var x='10',
     y=10
x==y this operator compare the value without datatype result to this = true
x===y this  operator compare the value with datatype result to this= false
# if statment & switch
tow check anything using javascript use the if statement for example two check if the student pass in the exam or fail write this statement
var stuGrade =59
if (stu>50 ){
document.write("this stu is pass")
} else {
document.write("this stu is fial")
}
The switch statement is used to perform different actions based on different conditions.
switch(expression) {
  case x:
    // code block
    break;
  case y:
    // code block
    break;
  default:
    // code block
}
This is how it works:

The switch expression is evaluated once.
The value of the expression is compared with the values of each case.
If there is a match, the associated block of code is executed.
If there is no match, the default code block is executed.
# TYPE COERCION
JavaScript can convert data
types behind the scenes to
complete an operation. This is
known as type coercion. For
example, a string 'l ' could be
converted to a number 1 in the
following expression:(' 1' > 0).
As a result, the above expression
would evaluate to true. 
javascript not require defined the data type
# Logical operators(||, &&,! )
this operators 
this operator processed from left to right
example 
if(x==0&&y==1){
code.....}
if x==0 equle true ...>go to rigtht side if y==1 equl  true the end result equl true execute the condition

if x==0 equle false  ...>Get out of the condition
if x==0 equle true ...>go to rigtht side if y==1 equl  false the end result equl false  Get out of the condition
[Logical operators](https://cnx.org/resources/0d6b87c996be8ae6d0efc70c073db6c59a8ce817/scr0360-02.jpg)


