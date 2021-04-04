# object 
object  collection of property and method to  to create a model
of a something you would recognize from the real world. 

the name of method and property called **key**.

An object cannot have two keys with the same name. This is because keys are used to access their corresponding values. 

var person={

    firstName:"eman";

    secondName:"almkhareez";

    age:22;
};
when write this

var x=person; //this not copy from person this means the same object have two name when change in x for example x.age=10 this change reflection on the person.age

# DOM
The Document Object Model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window.

this not considered part of html and not part of javascript this have collection of separate of rule .

caching  DOM queries 

Methods that find elements in the DOM tree are called DOM queries When you need to work with an element more than once , you should use a variable to store the result of this query.

SELECTING AN ELEMENT
FROM A NODELIST

the first:The item() method .

the second: and array syntax.

### note Both require the index number of the element you want.

For example, the standard DOM specifies that the querySelectorAll method in the code below must return a list of all the <p> elements in the document:


const paragraphs = document.querySelectorAll("p");
// paragraphs[0] is the first p element
// paragraphs[1] is the second p element, etc.
alert(paragraphs[0].nodeName);
