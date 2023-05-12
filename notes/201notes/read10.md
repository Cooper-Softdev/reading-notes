# Reading 10

### This is important because I've been ruining code since day one. Nobody can destroy an index.HTML like me. Challenge me.

## Troubleshooting

1. Syntax Error is an error in the way the code is written that disallows it to run properly. A logical error is an error that, while the program runs, produces erroneous results that are not correct or not intended. May be caused by adding a i-- instead of i++, oops.
2. I've mostly encountered missing semicolons, or things not placed properly in the .js file. Wish I were good enough to encounter REAL issues.
3. I'm probably going to be messing things up for awhile so being familiar with debugging tools and error codes should be really useful forever.

### JavaScript Debugger

1. 2. 3. JavaScript Debugger is a tool built into web browsers inspector. The inspector is a program that can read and understand your webpage code. Inside the Inspector you'll find things like a console.log, which will print out values to the console like when we did "hello world". This is great for logical error that are producing results but possibly wrong, and you can see which piece of code is producing the error. There are also Breakpoints which make the inspector run your code, and pause it. If there's something going wrong between 2 console.logs you can have the breakpoint execute line by line while you look at your webpage to see the error happen in realtime, as opposed to the webpage being loaded up in a fraction of a second. Call Stack will allow you to see the list of all the functions that have been called, and what order they were called in until that point. This is good for finding flow order issues. Network Tab helps debug networking issues, lost packets, not connecting to the server, when requests were made, what the response was, and how long it took. In case a part of your code is trying to execute before the information it needs from the server reaches your computer.
