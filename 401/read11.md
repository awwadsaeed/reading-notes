# Event Driven Applications  
## Review, Research, and Discussion
- Why is access control important?
because it is a valuable security technique that can be used to regulate who or what can view or use any given resource. … Without proper access control you could leave your staff and your company wide open to problems such as data loss, theft or breach of privacy and data protection laws.

- Describe an application that would need access control.
Banking system and educational websites.

- What is a role used for?
Because it is easier to set certain permissions to a specific role then apply the role to users than setting the permissions again and again for each user.

- Why is role based access control more scalable than discretionary or mandatory access control?
Because roles can be added easily if needed.
Actions for each role can be easily modified and will be updated for all users.
Actions on routes can be changed easily since they are merely parameters in the middleware.  


## Document The Following Vocabulary Terms:  
- Authorization : Authorization is a security mechanism to determine access levels or user/client privileges related to system resources including files, services, computer programs, data and application features  
- Role Based Access Control : Role-Based Access Control (RBAC) is a security paradigm whereby users are granted access to resources based on their role in the company.  
- Capabilities : A capability is a token, ticket, or key that gives the possessor permission to access an entity or object in a computer system.  

## Preview:  
- Which 3 things had you heard about previously and now have better clarity on?
 - SQL. 
 - dbeaver
 - Auth
- Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
 - stack
 - event loop
 - javascript runtime behaviour.
- What are you most excited about trying to implement or see how it works?
 - event-driven applications.
  
## Event-Driven Programming in Node.js
Event-Driven Programming is a logical pattern that we can choose to confine our programming within to avoid issues of complexity and collision. In this article we’re going to go over how Event-Driven Programming works and how we can make the best use of it in our Node.js projects.  

Most developers are introduced to concepts of Event-Driven Programming early on in their study of programming yet they might not fully realize it until a bit later. You’ll find that the concept is rather ubiquitous. Check any major framework or software out there and odds are you’ll find evidence of Event-Driven Programming.  

For the most recognizable example of Event-Driven Programming for people at any level of programming skill, we’ll turn to our old friend The Web Browser.  

Every time you interact with a webpage through it’s user interface, an event is happening. When you click a button a click event is triggered. When you press a key a keydown event is triggered. These events have associated functions that, when triggered, are executed to make a change to the user interface in some way.  