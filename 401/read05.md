# Linked Lists
## what are linked lists:  
A Linked List is a sequence of Nodes that are connected/linked to each other. The most defining feature of a Linked List is that each Node references the next Node in the link.
so each node has two main parts(in case of singly linked lists). data and a refrence to the next node.  

## types of linked lists:  
- doubly linked lists: those contain an addetional refrence that points to the previous node.  
- singly linked lists: those contain only one refrence that points to the next node in sequence.

## diferences between linked lists and arrays:  
- arrays are stored in contigious block of data whereas linked lists nodes can be stored seperatly.
- arrays can be faster in finding particular elements inside it whereas linked lists needs time to find a particular element.  
- linked lists are faster in adding and deleting nodes and array are slower in deleting one of its elements.

## the BigO:  
the bigO or the big order notation focuses on how fast our code run in relation to the input when the input reaches infinity.  
it concerns itself with 2 main parts which are:
- the time complexity: which means how many times does the cpu run a specific algorithm.
- the space complecity: how much do we store in our memory in during that algorithm.