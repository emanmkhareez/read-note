Authentication
What is OAuth

What is OAuth?
It is an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential.
Give an example of what using OAuth would look like.
When I go to log onto a website and it offers one or more opportunities to log on using another website’s/service’s logon.
How does OAuth work? What are the steps that it takes to authenticate the user?
After the two sites connect to each other, the client’s software presents the request token and secret to their authorization provider (which may or may not be the second site).
If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.
The user approves (or their software silently approves) a particular transaction type at the first website.
The user is given an approved access token (notice it’s no longer a request token).
The user gives the approved access token to the first website.
What is OpenID?
Is a simple identity layer on top of the OAuth 2.0 protocol, it allows clients to verify the identity of the End-User based on the authentication performed by an Authorization Server,
Authorization and Authentication flows

What is the difference between authorization and authentication?
Authentication confirms that users are who they say they are. Authorization gives those users permission to access a resource.
What is Authorization Code Flow?
Because regular web apps are server-side apps where the source code is not publicly exposed, they can use the Authorization Code Flow, which exchanges an Authorization Code for a token
What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
A version of the Authorization Code Flow, to mitigate the single-page apps' special challenges and for additional security when using mobile and native applications.
What is Implicit Flow with Form Post?
Is a simplified OAuth flow recommended for native apps and JavaScript apps where the access token was returned immediately without an extra authorization code exchange step.
What is Client Credentials Flow?
M2M apps use the Client Credentials Flow (defined in OAuth 2.0 RFC 6749, section 4.4), in which they pass along their Client ID and Client Secret to authenticate themselves and get a token.
What is Device Authorization Flow?
Is an OAuth 2.0 extension that enables devices with no browser or limited input capability to obtain an access token.
What is Resource Owner Password Flow?
It requests that users provide credentials (username and password), typically using an interactive form. The Resource Owner Password Flow should only be used when redirect-based flows (like the Authorization Code Flow) cannot be used.
Things I want to know more about
Actually, I want to know more about all these stuff, they are totally new new.