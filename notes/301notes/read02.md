# Reading class 2

## React Lifecycle

1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
+ the render happens first
2. What is the very first thing to happen in the lifecycle of React?
+ The mounting of a component being created then inserted into the DOM
3. Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
+ Constructor, render, componentDidMount, React Updates, componentWillUnmount. 
4. What does componentDidMount do? 
+ It is a method that is invoked after a component is mounted to let any other components or network requests know it is now safe to do so.

## React State vs Props

1. What types of things can you pass in the props?
+ Primitive Data types, JavaScript objects, React elements, and Functions.
2. What is the big difference between props and state?
+ Props is passed from a parent componenet and must be passed down, but a compoenent's state is owned and managed by the componenet itself and requires no one-direction flow
+ state is mutable, which can be changed via the useState function, unlike props which are read-only.
3. When do we re-render our application?
+ we can change state via the setState method.
+ we can change props and resend it via the parentcompoentn.
+ force the rerender with a useState hook or the proper method, forceUpdate().
4. What are some examples of things that we could store in state?
+ component state? we can store user input, visbility status, data from the server, counter or timer values.

References : 

+ https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093
+ https://www.youtube.com/watch?v=IYvD9oBCuJI
