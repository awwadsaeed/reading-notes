# useState() Hook
## Review, Research, and Discussion  
**How does React differ from vanilla JS/HTML/CSS?**  
- With React, we write HTML using JavaScript. We rely on the power of JavaScript to generate HTML that depends on some data, rather than enhancing HTML to make it work with that data. Enhancing HTML is what other JavaScript frameworks usually do.  
- Vanilla JS is nothing but plain JS without any external libraries or frameworks. Using this we can build powerful and cross-platform applications.  
- React is a Javascript library used for building user interfaces. It allows us to make complex UIs from isolated pieces of code called “components”.  
- In Vanilla JS, the code becomes very difficult to maintain if the application is large because in such cases the UI needs to be updated regularly.  
**What is the primary difference between a function component and a class component?**  
- A functional component is just a plain JavaScript function that accepts props as an argument and returns a React element. A class component requires you to extend from React. Component and create a render function which returns a React element. There is no render method used in functional components.  
## Document the following Vocabulary Terms  
- Functional Components: are basic JavaScript functions, these are typically arrow functions but can also be created with the regular function keyword (the best practice). Sometimes referred to as “dumb” or “stateless” components as they simply accept data and display them in some form; that is they are mainly responsible for rendering UI.  
- Children / Child Components: children allow you to pass components as data to other components, just like any other prop you use. The special thing about children is that React provides support through its ReactElement API and JSX. XML children translate perfectly to React children.  
## Preparation Materials  
**Making Sense of React Hooks**  
there are cases where react class components cant be simplified into smaller components and that will result in:  
- Huge components that are hard to refactor and test.   
- Duplicated logic between different components and lifecycle methods.  
- Complex patterns like render props and higher-order components.  
and react Hooks solve these problems.  
**Using the State Hook**  
A Hook is a special function that lets you “hook into” React features. For example, useState is a Hook that lets you add React state to function components.  
  


