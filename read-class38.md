Readings: Redux - Asynchronous Actions
======================================

Reading
-------

[async actions](https://redux.js.org/advanced/asyncactions)

1. Why use Redux middleware?
    Redux Middleware allows you to intercept every action sent to the reducer so you can make changes to the action or cancel the action. Middleware helps you with logging, error reporting, making asynchronous requests, and a whole lot more.

2. Consider the Redux Async Data Flow Diagram. Describe the flow in your own words.
  
* The state, the source of truth that drives our app;
* The view, a declarative description of the UI based on the current state
* The actions, the events that occur in the app based on user input, and trigger updates in the state

3. How are we accommodating async in our Redux app?
  update the state by calling the root reducer function

[thunk middleware](https://github.com/reduxjs/redux-thunk)

1. Why would you need `redux-thunk` middleware?
  Redux Thunk is middleware that allows you to return functions, rather than just actions, within Redux. This allows for delayed actions, including working with promises. One of the main use cases for this middleware is for handling actions that might not be synchronous, for example, using axios to send a GET request.
2. Redux Thunk middleware allows you to write action creators that return a function instead of an action.

3. Describe how any return value from the inner thunk function will be made available.