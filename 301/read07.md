# REST
- Who is Roy Fielding?  
the guy who made HTTP.
- Why don’t the techniques that we use today work well when we need to be able to talk to all of the machines in the world?  
Because they weren’t designed to be used like that, most of the techniques developers after Fielding used to get computers to talk to each other didn’t have those requirements. You just needed to talk to a small group of machines.
- What is the HTTP protocol that Fielding and his friends created?  
HTTP is the protocol used to transfer data over the web , it is all about applying verbs to nouns. For instance, when you go to a web page, the browser does an HTTP GET on the URL you typed in and back comes a web page
- What does a GET do?  
Each of the systems would retrieve information from each other using a simple HTTP GET.
- What does a POST do?  
If one system needs to add something to another system, it would use an HTTP verb of POST.
- What does PUT do?  
If a system wants to replace something in another system, it uses an HTTP verb of PUT.
- What does PATCH do?  
some minor update in another system with the uses of an HTTP verb of PATCH.