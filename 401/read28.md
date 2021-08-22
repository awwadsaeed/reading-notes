# Redux - Combined Reducers
## Review, Research, and Discussion  
- **Why choose Redux instead of the Context API for global state?**
Context API is great for small applications where state changes are minimal but Redux is better for large applications where there are many changes to state. Redux also offer time-travel and single source of truth for state.  
To manage huge applications with complex state management, in a large scale application, Redux is a better way to control state.  
In a large scale application, Redux is a better way to control state.  
- **What is the purpose of a reducer?**  
The reducer takes a state and an action and returns a new state  
- **What does an action contain?**  
Object literals that tell the reducer what is being done to the app, and any data required for the update.  
- **Why do we need to copy the state in a reducer?**  
Reducers are not allowed to modify the existing state, instead they must make immutable updates by copying the existing state and making changes to the copied values.  
## Document the following Vocabulary Terms  
- immutable state: This allows the state to only change when absolutely necessary to make React apps perform as well as possible.  

- time travel in redux: This is a feature of redux dev tools that allows you to see every state that a page has been in.  

- action creator: Actions send data from your application to your store, and are the only source of information for the store. An action creator is a function that creates an action.  

- reducer: Reducers tell the application how to change state in response to an action.  

- dispatch: This is the name of the function you use to send actions to the store.  
## Preperation material  
combineReducers:  
helper function turns an object whose values are different reducing functions into a single reducing function you can pass to createStore . The resulting reducer calls every child reducer, and gathers their results into a single state object  

As your app grows more complex, you’ll want to split your reducing function into separate functions, each managing independent parts of the state  

The combineReducers helper function turns an object whose values are different reducing functions into a single reducing function you can pass to createStore  

The resulting reducer calls every child reducer, and gathers their results into a single state object. The state produced by combineReducers() namespaces the states of each reducer under their keys as passed to combineReducers()  