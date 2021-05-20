#  Putting it all together
- How would you break a mock into a component heirarchy?  
every copmonent should follow the single responsibility principle.
- What is the single responsibility principle and how does it apply to components?  
a component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.
- What does it mean to build a ‘static’ version of your application?  
it meanst to build a version that takes your data model and renders the UI but has no interactivity.
- Once you have a static application, what do you need to add?  
interactivity
- What are the three questions you can ask to determine if something is state?  
 they are:  
  Is it passed in from a parent via props?  
 Does it remain unchanged over time?  
 Can you compute it based on any other state or props in your component?  
- How can you identify where state needs to live?
Identify every component that renders something based on that state and Find a common owner component which will propably be the state owner and if not then a higher component would own the state.