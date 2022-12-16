https://github.com/ashuppal/reading-notes

**What is OAuth**

What is OAuth?
OAuth is an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow 
authenticated access to their assets without actually sharing the initial, related, single logon credential.

Give an example of what using OAuth would look like.(www.w3schools.com)
For example, you can tell Facebook that it's OK for ESPN.com to access your profile or post updates to your timeline
without having to give ESPN your Facebook password.

How does OAuth work? What are the steps that it takes to authenticate the user?(oracle.com)
1.An application requests authorization on a user's behalf.
2.The application obtains a Grant Token.
3.The client requests an access token by using the Grant Token.
4.The authorization server validates the Grant Token and issues an Access Token and a Refresh Token.
5.The client requests the protected resource, authenticating using the Access Token.
6.The resource server verifies the Access Token and serves the request.

What is OpenID?
OpenID allows you to use an existing account to sign in to multiple websites, without needing to create new passwords

**Authorization and Authentication flows**

What is the difference between authorization and authentication?
Authentication verifies the identity of a user or service, and authorization determines their access rights.

What is Authorization Code Flow?
The OAuth 2.0 authorization code grant type, or auth code flow, enables a client application to obtain authorized access to protected 
resources like web APIs.

What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
The Authorization Code Flow + PKCE is an OpenId Connect flow specifically designed to authenticate native or mobile application users.

What is Implicit Flow with Form Post?
The implicit flow is a browser only flow. It is less secure than the Code Flow since it doesn't authenticate the client. 

What is Client Credentials Flow?
In the client credentials flow, permissions are granted directly to the application itself by an administrator. 

What is Device Authorization Flow?
Device Authorization Flow is an OAuth 2.0 extension that enables devices with no browser or limited input capability to obtain an access token. 

What is Resource Owner Password Flow?
The Resource Owner Password Credentials flow allows exchanging the username and password of a user for an access token and, optionally, a refresh token. 

