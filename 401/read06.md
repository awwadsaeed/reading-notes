# Authentication 
## Review, Research, and Discussion  
- singlton : is a class that only allowes the instantiation of one instance.
- it can be used by checking if there an instance of the class already instantiated and if it is it will return the already instantiated one.
- dont know yet.

## Document the following Vocabulary Terms:  
- Router Middleware: a middleware that takes the original request, and forward it to a sub handler according to the path.  
- Singleton Pattern: singleton pattern is a software design pattern that restricts the instantiation of a class to one "single" instance  
- CRUD: is an acronym for the four basic types of SQL commands: Create , Read , Update , Delete the rest methods that matches them are: POST,GET,PUT,DELETE respectivly.  
- Mock Testing: Mock testing is an approach to unit testing that lets you make assertions about how the code under test is interacting with other system modules.  
## preview
- Which 3 things had you heard about previously and now have better clarity on?
    - Mock Testing
    - Singleton Pattern
    - CRUD
- Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
    - authintication
    - authorization 
    - security
- What are you most excited about trying to implement or see how it works?
    - Singleton Patterns 
    - Dynamic Modules.

### Basic Auth:  
In the context of an HTTP transaction, basic access authentication is a method for an HTTP user agent (e.g. a web browser) to provide a user name and password when making a request. In basic HTTP authentication, a request contains a header field in the form of Authorization: Basic credentials, where credentials is the Base64 encoding of ID and password joined by a single colon : .  
### Bcrypt Hashing Function  
Bcrypt is an adaptive hash function based on the Blowfish symmetric block cipher cryptographic algorithm and introduces a work factor (also known as security factor), which allows you to determine how expensive the hash function will be.  
### bcrypt  
A library to help you hash passwords. bcrypt module uses node-gyp to build and install, you’ll need a stable version of node to use bcrypt.

