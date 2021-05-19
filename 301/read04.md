# React and Forms

## controled components

- What is a ‘Controlled Component’?  
  an input element whose value is being controled in state by react
- Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.  
no. because react needs some time to update state. and not waiting gives us the chance to pass those values to other components.
- How do we target what the user is entering if we have an event handler on an input field?
the input field will have a property in the set state and the event handler will be a method.  
## ternary operator  
- Why would we use a ternary operator?  
fewere and cleaner code.
- (x == y)?console.log(true):console.log(false).