# Reading 09

I'm assuming we are adding in some forms to let users input data. So EventListeners are pretty vital to that.

## HTML Forms 

1. Forms are important for interacting with users like collecting data, or allowing them to control a user interface.
2. We can add headings to our forms, so users can see exactly what needs to be done to complete a form, sighted and non-sighted. As well as adding in labels for both types of users to be able to understand inputs.

## JS Events

1. How would you describe events? Events are bits of a webpage that are waiting for some sort of interaction from the user, things it can listen for are mouse clicks, keyboard presses, submit buttons being clicked, and more.
Once the event is triggered a piece of code will run, like changing from lightmode to darkmode.
2. The 2 arguments that event listeners need are the string 'click' and a function to call in response to the string. Makes sense, you're listening for something, you should have something to do when you hear the thing you're listening for.
3. An event object is an object that is created when an event occurs. It contains metadata on the event itself. Things like, type of event, which element it happened on, position of the mouse on the viewport, and some more fancy stuff. The target within the event object is useful for letting the event handler function know which element had the interaction. Instead of making a ton of event listeners we can make one and then iterate them for each button with a different piece of code which is decided by the target.
4. Event bubbling takes the event and starts from the target element in the innermost section and propagates outwards into parent elements. Like bubbling over a pot of spaghetti or something I guess. Event capturing does the opposite, the event starts at the root element and gets progressively more into the nested elements until it reaches the innermost child element. false is bubbling, which is the default. and true is event capturing.