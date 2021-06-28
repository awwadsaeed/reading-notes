# Express REST API

## Review, Research, and Discussion  
Name 3 real world use cases where you’d want to change the request with custom middleware.  
- invalid info from user
- error handling 
- for authentication  
True or false: The route handler is middleware? 
- true  
In what ways can a middleware function end the process and send data to the browser?  
- using the next() method.
- by throwing errors.  
At what point in the request lifecycle can you “inject” middleware?  
- in the express request method as the second argument between the route and the request handler.  
What can cause express to error with “Request headers sent twice, cannot start a second response"  
- sending a request while anothe is being currently sent.  
## Document the following Vocabulary Terms
| term                    | describtion                                                                       |
| ----------------------  | ----------------------------------------------------------------------------------|
| Middleware              | a server that sends an html file as a response                                    |
| Request Object          | a light node framework that provides multiple services for the back end           |
| Response Object         | how does an application end point responds to client request                      |
| Application Middleware  | middleware on a global level. this middleware executes on all route route calls   | 
| Routing Middleware      | middleware that is used in a route that is able to modify request/response objects| 
| Test Driven Development | an apporach of writing tests to ensure the code working properly                  | 
| Behavioral Testing      |BDD is principally an idea about how software development should be managed by both business interests and technical insight|  

## Preview  
Which 3 things had you heard about previously and now have better clarity on?  
- request objects, respons object and error throwing.  
Which 3 things are you hoping to learn more about in the upcoming lecture/demo?  
- middle wares, next() mthod and TDD.  
What are you most excited about trying to implement or see how it works?  
- Tests.  
## Preparation Materials  
### Review: ES6 Classes  
Classes are a template for creating objects. They encapsulate data with code to work on that data. Classes in JS are built on prototypes but also have some syntax and semantics that are not shared with ES5 class-like semantics.  
### Using Express Routing  
Routing refers to how an application’s endpoints (URIs) respond to client requests. For an introduction to routing, see Basic routing.

You define routing using methods of the Express app object that correspond to HTTP methods; for example, app.get() to handle GET requests and app.post to handle POST requests. For a full list, see app.METHOD. You can also use app.all() to handle all HTTP methods and app.use() to specify middleware as the callback function (See Using middleware for details).

These routing methods specify a callback function (sometimes called “handler functions”) called when the application receives a request to the specified route (endpoint) and HTTP method. In other words, the application “listens” for requests that match the specified route(s) and method(s), and when it detects a match, it calls the specified callback function.  
### Express Routing  
With the inclusion of the Express 4.0 Router, we are given more flexibility than ever before in defining our routes. To recap, we can:

- Use express.Router() multiple times to define groups of routes
- Apply the express.Router() to a section of our site using app.use()
- Use route middleware to process requests
- Use route middleware to validate parameters using .param()
- Use app.route() as a shortcut to the Router to define multiple requests on a route
