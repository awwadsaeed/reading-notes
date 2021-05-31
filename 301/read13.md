# CRUD
- In your own words, describe what each group of status code represents:  
 - 100’s = These are informational status codes.  
 - 200’s = These are the success codes.  
 - 300’s = These are redirection codes.  
 - 400’s = These are the client error codes.  
 - 500’s = These are the server error codes.  
- What is a status code 202?  
It’s the basic status code to tell the client everything went good.  
- What is a status code 308?  
This tells the client to use another URL to access the resource and not use the current URL anymore.  
- What code would you use if an update didn’t return data to a client?  
204 No Content.  
- What code would you use if a resource used to exist but no longer does?  
410 Gone.  
- What is the ‘Forbidden’ status code?  
403 Forbidden:  The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.