Reading: Component Lifecycle / `useEffect` Hook
===============================================

Reading
-------

[effects hook](https://reactjs.org/docs/hooks-effect.html)

1. What purpose does `useEffect` serve in a function component compared to its counterpart(s) in class components?
    The useEffect helps to perform side effects in functional components; that is, any function that you need to run after updating the DOM. It replaces some events by running a function whenever one or more variables change. It takes two arguments: a function and an optional array.

2. When using the useEffect Hook:
    1. What does `useEffect` do?
        you tell React that your component needs to do something after render.
    2. Why is `useEffect` called inside a component?
        Why is useEffect called inside a component? Placing useEffect inside the component lets us access the count state variable (or any props) right from the effect. We don't need a special API to read it — it's already in the function scope.

    3. Why is `useEffect` called inside a component?
        Why is useEffect called inside a component? Placing useEffect inside the component lets us access the count state variable (or any props) right from the effect. We don't need a special API to read it — it's already in the function scope.

3. Explain the importance of properly implementing effects with Cleanup
    saves applications from unwanted behaviors like memory leaks by cleaning up effects.