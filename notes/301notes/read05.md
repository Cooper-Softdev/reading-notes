# Reading

## React Docs - Thinking in React

1. What is the single responsibility principle and how does it apply to components?
+ A concept for managing software for maintainability. In React it's used to accomplish that each component will handle one task so the code stays readable and managable.
2. What does it mean to build a ‘static’ version of your application?
+ A static application would be a version that have no interactivity, so props will get passed but no input will be retrieved from the user.
3. Once you have a static application, what do you need to add?
+ Determine what if anything is a state, or should be a state and allow the user to interact with it.
4. What are the three questions you can ask to determine if something is state?
+ Does the thing change over time or remain unchanged?
+ Is it passed from a parent via props?
+ Can it be computed based on existing state of the app itself or props in the component?
5. How can you identify where state needs to live?
+ Identify every component that renders based on that state.
+ Find a common owner component higher in their shared heirarchy.
+ If none of the previous, make the component yourself in an appropriate spot.

## Higher-Order Functions

1. What is a “higher-order function”?
+ A higher-order function is a function that operatores on other functions. It can take one or more functions as arguments which we call "callback functions". It can also return a function in addition to this.
2. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?
+ The greaterThan function second line is returning an arrow function that did not previously exist.
5. Explain how either map or reduce operates, with regards to higher-order functions.
+ the map method will take a function as an argument, take the pieces of data from an array and insert those into the function that was given to it as an argument and then put that result into a brand new array.
