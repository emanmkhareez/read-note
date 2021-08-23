JSON Web Token 

(JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. This information can be verified and trusted because it is digitally signed. JWTs can be signed using a secret (with the HMAC algorithm) or a public/private key pair using RSA or ECDSA.

What is the JSON Web Token structure?

In its compact form, JSON Web Tokens consist of three parts separated by dots (.), which are:

Header
Payload
Signature
Therefore, a JWT typically looks like the following.

xxxxx.yyyyy.zzzzz

Let's break down the different parts.

JWTs can be either signed, encrypted or both. If a token is signed, but not encrypted, everyone can read its contents, but when you don't know the private key, you can't change it. Otherwise, the receiver will notice that the signature won't match anymore.

Answer to your comment: I'm not sure if I understand your comment the right way. Just to be sure: do you know and understand digital signatures? I'll just briefly explain one variant (HMAC, which is symmetrical, but there are many others).

Let's assume Alice wants to send a JWT to Bob. They both know some shared secret. Mallory doesn't know that secret, but wants to interfere and change the JWT. To prevent that, Alice calculates Hash(payload + secret) and appends this as signature.

When receiving the message, Bob can also calculate Hash(payload + secret) to check whether the signature matches. If however, Mallory changes something in the content, she isn't able to calculate the matching signature (which would be Hash(newContent + secret)). She doesn't know the secret and has no way of finding it out. This means if she changes something, the signature won't match anymore, and Bob will simply not accept the JWT anymore.

Let's suppose, I send another person the message {"id":1} and sign it with Hash(content + secret). (+ is just concatenation here). I use the SHA256 Hash function, and the signature I get is: 330e7b0775561c6e95797d4dd306a150046e239986f0a1373230fda0235bda8c. Now it's your turn: play the role of Mallory and try to sign the message {"id":2}. You can't because you don't know which secret I used. If I suppose that the recipient knows the secret, he CAN calculate the signature of any message and check if it's correct.

Write the following steps in the correct orderLinks to an external site.
1.Register your application to get a client_id and client_secret

2.Ask the client if they want to sign in via a third party

3.Make a request to a third-party API endpoint

4.Redirect to a third party authentication endpoint

5.Make a request to the access token endpoint

6.Receive access token

7.Receive authorization code*

What can you do with an access token? 

Links to an external site.
Access tokens are the thing that applications use to make API requests on behalf of a user.