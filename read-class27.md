Reading: `useState()` Hook
==========================

Reading
-------

[Introducing Hooks](https://reactjs.org/docs/hooks-intro.html#motivation)

1. What was the motivation for introducing Hooks?
    We want to present an API that makes it more likely for code to stay on the optimizable path. To solve these problems, Hooks let you use more of React's features without classes. Conceptually, React components have always been closer to functions.

2. What changes are important regarding implementing Hooks versus Component Classes?
    The major difference between Hooks and class-based state is that hooks are used inside of the functional component. One thing to keep in mind is that never call hooks inside of a any logic, it should always be on the top level! useState() is a hook that allows you to play with state in functional components in react.

3. Hooks allow you to reuse stateful logic without changing **\_\_****\_ \_\_**\_\_\_\_\_.
your component hierarchy. This makes it easy to share Hooks among many components or with the community.

[hooks api](https://reactjs.org/docs/hooks-overview.html)

1. Name two rules imposed by React Hook usage.
   * Don't call Hooks inside loops, conditions, or nested functions. ...
   * Don't call Hooks from regular JavaScript functions. ...
   * You can skip to the next page explaining how to write your own Hooks now. ...
   * This is why Hooks must be called on the top level of our components.

2. How would you identify a custom Hook and why might you create one?
    Custom Hooks are a convention that naturally follows from the design of Hooks, rather than a React feature.

[the state hook](https://reactjs.org/docs/hooks-state.html)

1. What is a Hook?
    React Hooks are simple JavaScript functions that we can use to isolate the reusable part from a functional component. Hooks can be stateful and can manage side-effects. React provides a bunch of standard in-built hooks: useState : To manage states. Returns a stateful value and an updater function to update it.

2. When would I use the `useState` Hook?
    The useState Hook can be used to keep track of strings, numbers, booleans, arrays, objects, and any combination of these! We could create multiple state Hooks to track individual values.
    
3. If you were to add React state to a function component by declaring a state variable:
    1. What does calling `useState` do?
        The useState Hook can be used to keep track of strings, numbers, booleans, arrays, objects, and any combination of these! We could create multiple state Hooks to track individual values.

    2. What do we pass to `useState` as an argument?
        The only argument to the useState() Hook is the initial state. Unlike with classes, the state doesn't have to be an object. We can keep a number or a string if that's all we need. In our example, we just want a number for how many times the user clicked, so pass 0 as initial state for our variable.
    
    3. What does `useState` return?
        useState accepts an initial state and returns two values: The current state. A function that updates the state.

Bookmark and Review
-------------------

[hooks api reference](https://reactjs.org/docs/hooks-reference.html)