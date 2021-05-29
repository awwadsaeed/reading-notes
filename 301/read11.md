# Authentication
- What is OAuth?  
OAuth is an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential.  

- Give an example of what using OAuth would look like.  
loggin in to a website using another webite's **that you already have an account authintecated in it** authentication.  
- How does OAuth work? What are the steps that it takes to authenticate the user?  
 1. The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity.  
 2. The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.  
 3. The first site gives this token and secret to the initiating user’s client software.  
 4. The client’s software presents the request token and secret to their authorization provider (which may or may not be the second site).  
 5. If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.  
 6. The user approves (or their software silently approves) a particular transaction type at the first website.  
 7. The user is given an approved access token (notice it’s no longer a request token).  
 8. The user gives the approved access token to the first website.  
 9. The first website gives the access token to the second website as proof of authentication on behalf of the user.  
 10. The second website lets the first website access their site on behalf of the user.  
- What is OpenID?  
OpenID is about authentication.  
- What is the difference between authorization and authentication?  
authoriztion is to provide access to someone who is already authenticated while authentication means for someone to prove the identey they present.  
- What is Authorization Code Flow?  
Because regular web apps are server-side apps where the source code is not publicly exposed, they can use the Authorization Code Flow, which exchanges an Authorization Code for a token.  
- What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?  
a version of the Authorization Code Flow which makes use of a Proof Key for Code Exchange.  
- What is Implicit Flow with Form Post?  
Implicit Flow with Form Post flow uses OIDC to implement web sign-in that is very similar to the way SAML and WS-Federation operates.  
- What is Client Credentials Flow?  
machine to machine authentication.   
- What is Device Authorization Flow?  
With input-constrained devices that connect to the internet, rather than authenticate the user directly, the device asks the user to go to a link on their computer or smartphone and authorize the device.  
- What is Resource Owner Password Flow?  
highly-trusted applications can use the Resource Owner Password Flow, which requests that users provide credentials (username and password), typically using an interactive form. The Resource Owner Password Flow should only be used when redirect-based flows (like the Authorization Code Flow) cannot be used.