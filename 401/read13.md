# Message Queues:  
## Review, Research, and DiscussionLinks to an external site.
- What does it mean that web sockets are bidirectional? Why is this useful?  
yes. being bidirectional is a communication protocal that is able to send data from client to server or from server to client reusing the established connection.  
- Does socket.io use HTTP? Why?  
Yes, the initial connection setup is done over HTTP.  
sockets are made within this connection.  
- What happens when a client emits an event?  
Event is thrown into an event pool and is triggered by any client/event that is listening for the event
listeners typically have a callback function which runs a codeblock when the event is triggered.  
- What happens when a server emits an event?  
event is sent to specific subs, all clients, or both.  
triggers a callback that is assigned to the listener and runs the code.  
- What happens if a client “misses” an event?  
missed events are ignored which prevents the rest of a chain of code to run (which is bad).  
- How can we mitigate this?  
unheard events should be stored in a queue system on the server that is resumed as a client connects.  
## Document the following vocabulry:  
- Socket : a socket is an endpoint of a communication between two programs running on a network. Sockets are used to create a connection between a client program and a server program.  

- Web Socket: WebSocket is its own layer 7 protocol, similar to HTTP. WebSockets create a full-duplex connection for sending messages from client to server, or server to client at any instant. This pattern is far superior to HTTP request-response when an application requires systems to get the latest data ASAP.  

Socket.io: Socket.IO is a library that enables real-time, bidirectional and event-based communication between the browser and the server.  

Client: A client is a connection on the frontend.  

Server: A system that provides services to other systems in its network.  

OSI Model: is a conceptual framework used to describe the functions of a networking system.  

TCP Model: TCP/IP model (Transmission Control Protocol/Internet Protocol) is a model with four layers which is for both modelling current Internet architecture, as well as providing a set a rules that govern all forms of transmission over a network.  

TCP: TCP (Transmission Control Protocol) is a protocol for sending information between computers. TCP guarantees* that all the information will be sent and that it will be received in order.  

User Datagram Protocol: is a communications protocol that is primarily used for establishing low-latency and loss-tolerating connections between applications on the internet. It speeds up transmissions by enabling the transfer of data before an agreement is provided by the receiving party.  

Packets: is a small segment of a larger message. Data sent over computer networks, such as the Internet, is divided into packets. These packets are then recombined by the computer or device that receives them.  

## Preparation Materials:  
#### Socket.io Chat example
- Sockets have traditionally been the solution around which most real-time chat systems are architected, providing a bi-directional communication channel between a client and a server
- The server can push messages to clients
- Whenever you write a chat message, the idea is that the server will get it and push it to all other connected clients
- Setup steps hereLinks to an external site.
#### Rooms and Namespaces
- Room is an arbitrary channel that sockets can join and leave, it can be used to broadcast events to a subset of clients
- Rooms are a server-only concept (client does not have access to the list of rooms it has joined)
- Can join to subscribe the socket to a given channel socket.join()
- Each socket in Socket.io is identified by a random unique identifier (Socket#id), each socket automatically joins a room identified by its own id
- Upon disconnection, sockets leave all the channels they were part of automatically.