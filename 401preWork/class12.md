 # Socket.io
 

Review, Research, and Discussion
What is the benefit of transforming data into packets?
to divide data into small pieces, allowing the network to accommodate various bandwidths, to allow for multiple routes to a destination, and to retransmit the pieces of data which are interrupted or lost.‏
UDP is often refereed to as a connectionless protocol. Why is this?
UDP does not have a mechanism to make sure that the payload is not corrupted. ... It includes only source and destination port numbers, length of the frame, and a UDP message checksum.
Can a socket server application have multiple socket connections?
Yes. Can a socket connection application be connected to multiple socket servers?
Yes. Can an application be both a socket server and a socket connection?
No.
Document the following Vocabulary Terms
Observer Pattern: s a software design pattern in which an object, named the subject, maintains a list of its dependents, called observers, and notifies them automatically of any state changes, usually by calling one of their methods.
Listener: is a procedure in JavaScript that waits for an event to occur. The simple example of an event is a user clicking the mouse or pressing a key on the keyboard.
Event Handler: scripts / functions that are automatically executed when an event occurs.
Event Driven Programming: is a programming paradigm in which the flow of program execution is determined by events.
Event Loop: is a programming construct or design pattern that waits for and dispatches events or messages in a program.
Event Queue: is responsible for sending new functions to the track for processing. It follows the queue data structure to maintain the correct sequence in which all operations should be sent for execution.
Call Stack: is a mechanism for an interpreter (like the JavaScript interpreter in a web browser) to keep track of its place in a script that calls multiple functions.
Subscribe: is an object that represents a disposable resource, usually the execution of an Observable.
database: is an organized collection of structured information, or data, stored electronically in a computer system.
Preview
Which 3 things had you heard about previously and now have better clarity on? - Event Driven Programming. - Node js events. Which 3 things are you hoping to learn more about in the upcoming lecture/demo? - Socket. io What are you most excited about trying to implement or see how it works? - Implimenteing an app using Socket.

Preparation Materials
WebSocket is a computer communications protocol, providing full-duplex communication channels over a single TCP connection.

What Socket.IO is? Socket.IO is a library that enables real-time, bidirectional and event-based communication between the browser and the server. It consists of:

a Node.js server: Source | API
a Javascript client library for the browser (which can be also run from Node.js): Source | API
What Socket.IO is not? Socket.IO is NOT a WebSocket implementation. Although Socket.IO indeed uses WebSocket as a transport when possible, it adds additional metadata to each packet. That is why a WebSocket client will not be able to successfully connect to a Socket.IO server, and a Socket.IO client will not be able to connect to a plain WebSocket server either.