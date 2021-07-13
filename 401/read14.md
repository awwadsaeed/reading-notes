# Event Driven Architecture
## Review, Research, and Discussion  
- What’s the difference between a FIFO and a standard queue?  
FIFO queue provides first in first out ordering and messages are delivered exactly once. It supports 300 transactions per second.  
Standard queue supports best effort ordering, at least one delivery and nearly unlimited throughput.  
- How can the server be assured a message was properly received?  
a console.log will do.  
- What classic design pattern is best represented by event driven programming?  
observer pattern  
- How do you test an event driven system?  
checking the message queue.  
### Document the following Vocabulary Terms  
FIFO Queue: A FIFO queue is a queue that operates on the first-in, first-out principle, hence the name. This is also referred to as the first-come, first-served principle.  
Pub/Sub: is an asynchronous messaging service that decouples services that produce events from services.   
- Which 3 things had you heard about previously and now have better clarity on?  
socet io,message queue.  
- Which 3 things are you hoping to learn more about in the upcoming lecture/demo?  
socket io,fifo and standard queue.  
- What are you most excited about trying to implement or see how it works?  
socket io.  
## preparation material:  
- QS does not push messages to the consumers, instead, consumers have to poll the queue, and as soon as one of them receives a message, the message is out of the queue and no other consumer can access it. This polling inevitably introduces a certain latent delay in message delivery.
- SNS pushes the messages to all its subscribers as soon as it receives it, hence there is no latency and you can easily add subscribers down the line.
- SQS is mainly used to decouple applications or integrate applications.
- SNS is used to broadcast messages and it’s up to the receivers how they interpret and process those messages.