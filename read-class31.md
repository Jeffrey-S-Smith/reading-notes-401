Reading: Context API
====================

Reading
-------

[Context API](https://reactjs.org/docs/context.html)

1. What can React Context provide your app?
    The React Context API is a way for a React app to effectively produce global variables that can be passed around. This is the alternative to "prop drilling" or moving props from grandparent to child to parent, and so on. Context is also touted as an easier, lighter approach to state management using Redux.

2. Why might we use Context?
    Context is primarily used when some data needs to be accessible by many components at different nesting levels. Apply it sparingly because it makes component reuse more difficult. If you only want to avoid passing some props through many levels, component composition is often a simpler solution than context.

3. Why should we use it sparingly?
    Libraries such as Redux-form which has excellent integration with React + Redux. So Redux needs to be integrated to use redux-form. Middlewares need to be written as custom code. A bit harder to debug.

[Awesome React Context links](https://github.com/diegohaz/awesome-react-context)

1. Consume content from (at least) two of the Awesome React Context links. Share your take-away from each:
    1. Takeaway 1:
    2. Takeaway 2: