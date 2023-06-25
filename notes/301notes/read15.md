# Reading

## What is OAuth

1. What is OAuth?
   - OAuth is a standardized authorization that allows unrelated servers or services from companies to give a user access with a single sign-on for their services. 
   
2. Give an example of what using OAuth would look like.
  - When you try to log in to a website or application it may appear like you're about to log in with your github or google account. The OAuth will request authentication from that "provider" and grant permission via an access token. The website uses this token as verification.
3. How does OAuth work? What are the steps that it takes to authenticate the user?
  - User initiates a request to access a website service
  - The website redirects the user to an authentication provider.
  - The user provides their credentials and grants permission to the authentication provider.
  - The authenticator provides a token.
  - The token is sent to the website's server.
  - The website understands what the token is, and will then grant the requester with access, or whatever.

4. What is OpenID
  - The authentication protocol tghat allows users ot use a single set of credential to access multiple websites or services provided. It allows users to use a single OpenID to authenticate instead of making a new account for each website. OpenID is used in conjunction with OAuth to provide authentication and authorization.

## Authorization and Authentication flows

What is the difference between authorization and authentication?
  - Authenticaiton is the process of verifying identity of the user or requester, authorization is granting permission to that user to do what they're wanting to do.

What is Authorization Code Flow?
  - Authorization Code Flow is used by server-side applications in which the client redirects the user to the authorization provider's server, then the users authenticates themselves and grants permissions to the client. The authorization server then returns a code to the client which is exchanged for an access token, which is then exchanged for goods and services. Like Homer thought about that one time.

What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
  - It is an extension to the ACF designed for mobile or native applications (which I think means things built for a specific operating system?) It send an extra code for the verify to go through to get access, like those numbers I gotta go find on my github app sometimes. I assume.

What is Implicit Flow with Form Post?
  - This is a fancy way for web applications to authenticate users without exposing sensitive information in the URL. It's mostly used by single-page applications (you know, those fancy apps that don't require page refreshes what are they called again?). Instead of going through the usual steps of exchanging an authorization code, the access token and ID token are returned directly from the authorization server. These tokens are then delivered as a result of submitting a form, which keeps things secure and hidden from prying eyes.

What is Client Credentials Flow?
  - Client Credentials Flow is a way for machines to authenticate themselves. Yeah, you heard it right, machines talking to other machines. It's like a secret language only they understand. In this flow, the machine proves its identity directly to the authorization server using its own credentials, such as a client ID and client secret. Once authenticated, the machine gets an access token that it can use to access protected resources without bothering any humans. It's like machines having their very own secret handshake.

What is Device Authorization Flow?
  - Device Authorization Flow is a cool way for devices with limited input capabilities to authenticate themselves. Like smart TVs or game consoles. So, this flow allows these devices to display a code to the user and ask them to enter it on another device, like their phone or computer. Once the user enters the code and authenticates themselves, the device can obtain an access token to access protected resources. It's like a team effort between devices, working together to get things done.

What is Resource Owner Password Flow?
  - Resource Owner Password Flow is like the wildcard of authentication flows. It's there for those highly-trusted applications that need to collect the good ol' username and password directly from the user. It's not the most recommended approach, but sometimes there's no other choice. In this flow, the application asks the user for their credentials, typically through a login form. Then, the application sends those credentials to the authorization server to get an access token.
