

### What does REST stand for?

 ***Representational State Transfer***

 as an architectural approach to designing web services. REST is an architectural style for building distributed systems based on hypermedia. REST is independent of any underlying protocol and is not necessarily tied to HTTP. However, most common REST API implementations use HTTP as the application protocol, and this guide focuses on designing REST APIs for HTTP.



### REST APIs are designed around a

 HTTP.

### What is an identifer of a resource? Give an example.

 is a URI that uniquely identifies that resource. For example, the URI for a

 particular customer order might be: https://adventure-works.com/orders/1


###  are the most common HTTP verbs?

GET ,post delete,patch,put

###  What should the URIs be based on?

nouns

### Give an example of a good URI.

GET https://adventure-works.com/products/10?fields=productImage HTTP/1.1
Range: bytes=0-2499

### What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

web APIs that expose a large number of small resources. Such an API may require a client application to send multiple requests to find all of the data that it requires

### What status code does a successful GET request return?

returns HTTP status code 200 (OK).

### What status code does an unsuccessful GET request return?

It should return 404 (Not Found).


### What status code does a successful POST request return?

It returns HTTP status code 201 (Created), the response body contains a representation of the resource.

### What status code does a successful DELETE request return?

The web server should respond with HTTP status code 204, but that the response body contains no further information.

## Things I want to know more about
