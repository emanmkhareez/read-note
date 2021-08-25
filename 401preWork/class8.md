# Authorization/Authentication

IP Authentication Header is used to provide connection-less integrity and data origin authentication. There are two main advantages that Authentication Header provides,

Source Authentication –

It means, source is exactly source from whom we were expecting data.

Message Integrity –

It means, message is not modified while coming from source.

When packet is sent from source A to Destination B, it consists of data that we need to send and header which consist of information regarding packet. Authentication Header verifies origin of data and also payload to confirm if there has been modification done in between, during transmission between source and destination.

Authentication Header :
The question may arise, that how IP header will know that adjacent Extension header is Authentication Header. Well, there is protocol field in IP Header which tells type of header that is present in packet. So, protocol field in IP Header should have value of “51” in order to detect Authentication Header.

![Header](https://media.geeksforgeeks.org/wp-content/uploads/20200420142114/Authentication-header.png)

What is safe to put into a JWT

 put very strong secret-Key

 put encoding password



How are JWTs validated

 The Signature is created using the Header and Payload segments, 

RBAC


sort of it you know what you  do your function perghaps that may govern what kind of files you can access if your human resources or payroll or you are in a different department the set of files you can  would depend on what your role in the orgainzation

User Roles 

are permission sets that control access to areas and features within the Professional Archive Platform

 https://medium.com/dataseries/public-claims-and-how-to-validate-a-jwt-1d6c81823826
