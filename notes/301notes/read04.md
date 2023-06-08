# Reading

## React Docs - Forms
https://reactjs.org/docs/forms.html

1. What is a ‘Controlled Component’?
  + A controlled component is a React specific component that has its value controlled by React itself, and not the element it is contained within, like vanilla HTML and JS.
2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
  + The state should be updated as soon as the form response has been submitted. This will update immediately so anything requesting something from the DOM doesn't run into an error of data that should be there not being there, and the user gets to see that what they're doing is actually working.
3. How do we target what the user is entering if we have an event handler on an input field?
  + We would target the event handler itself, but it will have assigned a name to the event.target.value that was passed from the event itself.

## Ternary Operator
https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff

1. Why would we use a ternary operator?
  + A ternary is a shorter way of writing a regular conditional expression like an if/else statement.
2. x === y ? console.log(true) : console.log(false);
