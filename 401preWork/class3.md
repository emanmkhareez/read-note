
1-Name 3 real world use cases where you’d want to change the request with custom middleware.

add Querystring into request

Track user behavior and stored

changing the request and response

 2-True or false: The route handler is middleware?

False

3-In what ways can a middleware function end the process and send data to the browser?

next()

4-At what point in the request lifecycle can you “inject” middleware?

After received  the request .

5-What can cause an error in the expression "Headers request sent twice, second response cannot be started"?

This happens when the developer treats an asynchronous response within a fast track as a synchronous response, causing it to be sent data twice

**Middleware:** 
(a piece of code ) between the server and the client can control on http request before access to server and can control on response to do to something before access to client 




It is a piece of code that comes in the middle of request and response. It kind of hijacks your request so that you can do anything that you want with your request or response eg: Modify the data or call the next middleware. Middleware functions are functions that have access to the request object (req), the response object (res), and the next middleware function in the application’s request-response cycle



**Request Object**

instance of http request object it has

body ,
Headers
 
Query params

 resources params

  and contain details about client request this means what he trying to  access what the pramter he send

  example about that 

  req.method(get ,post )

  req.Headers(use-Agent)
  
  req.ip

  req.body

  req.origenalUrl


**Response object**

instance of http response object 

that an Express app sends when it gets an HTTP request.

 example 
 res.send()
 
 res.status()

 res.redirect()

 **Application Middleware**

 
Middleware in the context of distributed applications is software that provides services beyond those provided by the operating system to enable the various components of a distributed system to communicate and manage data. Middleware supports and simplifies complex distributed applications



What is middleware application server?


Middleware is software that lies between an operating system and the applications running on it. ... This can include security authentication, transaction management, message queues, applications servers, web servers, and directories

What is middleware application examples?


Common middleware examples include database middleware, application server middleware, message-oriented middleware, web middleware and transaction-processing monitors. ... This can include security authentication, transaction management, message queues, applications servers, web servers and directories

Router

In Express, usually, we make end-points that uses HTTP verbs to denote a GET POST DELETE PUT etc requests. Router is used to manage these incoming requests. It kind of routes your requests to correct handler/code

**Rouring middelware**
Routing defines the way in which the client requests are handled by the application endpoints. And when you make some routers in separate file, you can use them by using middleware


In Express, usually, we make end-points that uses HTTP verbs to denote a GET POST DELETE PUT etc requests. Router is used to manage these incoming requests. It kind of routes your requests to correct handler/code

***Test Driven Development**
What is TDD?

Test Driven Development (TDD) is a software development practice enabling developers to create proper specifications about how their code should be written and implemented. Fundamentally, TDD is a practice when a programmer writes a functional test before building a code.

**Advantages**

it levels up the quality. You know why? Because all the possible mistakes and errors are already taken into account. Here, developers write the necessary tests, and the code, therefore, to avoid all the failures. Consequently, the code appears to give better results.


Detailed project documentation

When writing tests for particular requirements, programmers immediately create a strict and detailed specification. It already includes all the likely users’ actions.


How does it work?

To begin with, the TDD approach allows identifying any issues very fast due to fast feedback.

When writing a code without TDD, programmers need some time to understand whether the code will work right or not. With Test Driven development, when tests fall where they should pass, developers understand that something’s wrong immediately. Consequently, it saves time during the project development phase, and a team can fix the code right away when detecting a breakage.

Secondly, one of the key differences the TDD approach offers is fewer bugs or errors. Having fewer bugs, you will spend less time to fix them - it’s as simple as that.

This means that less time is spent on the bug fixing or maintenance stage if compared with other development methodologies used.

Additionally, provided that the code quality is significantly higher with TDD, this will, of course, reduce the time spent on code maintenance.

So we can say that in the long run, TDD contributes to faster project completion.

 Code flexibility and easier maintenance

**Behavioural Testing**:-

Specification-based testing technique is also known as ‘black-box’ or input/output driven testing techniques because they view the software as a black-box with inputs and outputs.

The testers have no knowledge of how the system or component is structured inside the box. In black-box testing the tester is concentrating on what the software does, not how it does it.

The definition mentions both functional and non-functional testing. Functional testing is concerned with what the system does its features or functions. Non-functional testing is concerned with examining how well the system does. Non-functional testing like performance, usability, portability, maintainability, etc.


