# Reading

## Understanding the JavaScript Call Stack

1. What is a ‘call’?
    + In JavaScript, a 'call' refers to the invocation of a function. When a function is called, it is added to the call stack and executed.
2. How many ‘calls’ can happen at once?
    + The JavaScript call stack operates in a single-threaded manner, which means that only one function can be executed at a time. Therefore,    only one call can happen at once.
3. What does LIFO mean?
    + LIFO stands for "Last-In, First-Out." In the context of the call stack, it means that the last function added to the stack is the first one to be executed and removed from the stack. It follows the principle of stacking elements on top of each other and removing them from the top.
4. Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
    + <function firstFunction(){
  throw new Error('Stack Trace Error');
}

function secondFunction(){
  firstFunction();
}

function thirdFunction(){
  secondFunction();
}

thirdFunction();>

5. What causes a Stack Overflow?
    + A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.


## JavaScript error messages

1. What is a ‘reference error’?
   + A 'reference error' occurs when trying to access a variable or function that has not been declared or is out of scope.

2. What is a ‘syntax error’?
   + A 'syntax error' occurs when the JavaScript code violates the language's syntax rules. It means that the code is not written correctly and cannot be parsed or interpreted by the JavaScript engine.

3. What is a ‘range error’?
   + A 'range error' occurs when a numeric value is not within the valid range of values.

4. What is a ‘type error’?
   + A 'type error' occurs when a value is not of the expected type.

5. What is a breakpoint?
   + A 'breakpoint' is a specific point in the code where the execution is paused during debugging. It allows developers to inspect the program's state, variables, and step through the code line by line to analyze and identify issues.

6. What does the word ‘debugger’ do in your code?
   + The 'debugger' statement is a tool used for debugging in JavaScript. It allows developers to inspect variables, step through the code, and analyze the program's state at that specific moment.

## Things to know more about

    + Is this why ghandi went crazy in civ? Or was that a myth?
