 # CRUD


## HTTP response status codes indicate whether a specific HTTP request has been successfully completed. Responses are grouped in five classes:

Informational responses (100–199)

Successful responses (200–299)

Redirects (300–399)

Client errors (400–499)

Server errors (500–599)

 ## In your own words, describe what each group of status code represents:

100’s =This interim response indicates that everything so far is OK and that the client should continue the request, or ignore the response if the request is already finished.

200’s =This class of status codes indicates the action requested by the client was received, understood, and accepted

300’s =This class of status code indicates the client must take additional action to complete the request. Many of these status codes are used in URL redirection.[2]

A user agent may carry out the additional action with no user interaction only if the method used in the second request is GET or HEAD. A user agent may automatically redirect a request. A user agent should detect and intervene to prevent cyclical redirect

400’s =his class of status code is intended for situations in which the error seems to have been caused by the client. Except when responding to a HEAD request, the server should include an entity containing an explanation of the error situation, and whether it is a temporary or permanent condition. These status codes are applicable to any request method. User agents should display any included entity to the user.[30]

500’s = The server failed to fulfil a request

Response status codes beginning with the digit "5" indicate cases in which the server is aware that it has encountered an error or is otherwise incapable of performing the request. Except when responding to a HEAD request, the server should include an entity containing an explanation of the error situation, and indicate whether it is a temporary or permanent condition. Likewise, user agents should display any included entity to the user. These response codes are applicable to any request method.

## What is a status code 202?

202 (Accepted)

A 202 response is typically used for actions that take a long while to process. It indicates that the request has been accepted for processing, but the processing has not been completed. The request might or might not be eventually acted upon, or even maybe disallowed when processing occurs.

## What is a status code 308?

This tells the client to use another URL to access the resource and not use the current URL anymore

## What code would you use if an update didn’t return data to a client?

Code 204 No Content.

## What code would you use if a resource used to exist but no longer does?

414 Request-URI Too Long.

## What is the ‘Forbidden’ status code?

403 Forbidden.