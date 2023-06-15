# Reading

## Functional Programming Concepts

What is functional programming?
+ That didn't help too much so here's a dictionary definition... Functional programming is a programming paradigm that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data. It emphasizes the application of functions, in contrast to the imperative programming style, which emphasizes changes in state.
What is a pure function and how do we know if something is a pure function?
+ a pure function is a function that will return a value soley dependent upon its input values, with no observable side effects. We know if it's pure function if the same input gives the same output, and the function doesn't produce side effects, by not altering state outside of its scope like global or shared variables.
What are the benefits of a pure function?
+ They are easier ot think about and debug since they don't change the state of anything outside of its own scope.
+ Easy to test because they don't require setting up a state... whatever that means.
+ They can be "memoized" to improve performance, like storing the results of a computationally expensive function call and then reusing them when the same inputs occur again.
+ Pure functions are often reusable and flexible. 
What is immutability?
+ Immutability, means tha tonce a data structure or a variable is created, it cannot be changed. If the immutable object needs to be altered in some way, you need to make a new version of that object.
What is Referential transparency?
+ Referential transparents is a pure functional property that says a function can be replaced by its resulting value without altering the program's behavior. Which ensures that the function consistently produces the same output for the same input.

## Node JS Tutorial for Beginners #6 - Modules and require()

What is a module?
+ Node.js modules are a separate piece of code that is logically organized and is able to be used in other parts of the codebase. This is done in an effort to increase modularity and organization.
What does the word ‘require’ do?
+ Require is a Node.js function that is used to import modules into a file. Like importing bootstrap into React App, it allows us to use bootstrappy things.
How do we bring another module into the file the we are working in?
+ `const myModule = require('./myModule');`
What do we have to do to make a module available?
+ It must be exported from its containing file where it is defined.

## Things to know more about

1. I'm sure we're going to do more test creation... creating a state for a test? Sounds almost like rebuilding part of an app... I sure hope that's not complicated!
