Readings: Redux - Additional Topics
===================================

Reading
-------

[Redux Toolkit (RTK)](https://redux-toolkit.js.org/introduction/getting-started)

1. What concerns are addressed by Redux Toolkit?
    RTK is touted as the intended way to write modern Redux logic. More than just reducing boilerplate code, RTK aims to address other problems, such as the difficulty in creating reducers and creating a store with multiple actors. With creating string constants and endless switch cases, this can be a hassle.

2. What does `configureStore()` do?
    A friendly abstraction over the standard Redux createStore function that adds good defaults to the store setup for a better development experience.

3. How would I use `createSlice()`?
    A function that accepts an initial state, an object of reducer functions, and a "slice name", and automatically generates action creators and action types that correspond to the reducers and state.

[MobX](https://mobx.js.org/getting-started.html)

1. What is Mobx?
    s a battle tested library that makes state management simple and scalable by transparently applying functional reactive programming (TFRP).

2. How does MobX make it “impossible” to produce an inconsistent state?
    MobX, a simple, scalable, and standalone state management library, follows functional reactive programming (FRP) implementation and prevents inconsistent state by ensuring that all derivations are performed automatically.

3. How would we build a reactive user interface?

Tutorial
--------

[Tutorial](https://redux-toolkit.js.org/tutorials/intermediate-tutorial)

1. What take-away(s) did this tutorial provide?

Bookmark and Review
-------------------

[Redux Toolkit (RTK)](https://redux-toolkit.js.org/)

[HookState](https://hookstate.js.org/)