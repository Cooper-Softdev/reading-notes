## Reading

### Java Basics

1. What does “strong typed” mean?
- Strong typed means the types in the programming language must be strictly declared before naming and assigning a value. So to add a number that's typed as a STR you must first convert it to an INT before adding it to another number typed as an INT.
2. What are the primitive data types?
- Byte
- Short
- Int
- Long
- Float
- Double
- Boolean
- Char

### XKCD: Compiling

1. Explain to a non-technical friend the difference in how compilation works in Java and JavaScript.
- Java code gets compiled into Bytecode by the Java Virtual Machine, which is then converted into machine code when it gets ran. JavaScript is interpreted line by line by the engine like V8 in Chrome or SpiderMonkey in Firefox, this doesn't allow checking for syntax errors unless you're using a linter during production.
2. Does code complining mean that it works correctly?
- No, it just means there are no syntax errors within the code, but it does not ensure there are no logical errors written by the programmer.

### Reading Java Documentation

1. How many keywords does Java have?
- Depending on which version it could be around 50 or so, JDK 8 is 50 keywords.
2. How do you print words to the console in Java?
- system.out.println("Hello World");

### Would you like to know more?

- I got a decent explaination from GPT about bytecode and how it runs anywhere the JVM can run, but I couldn't get it to explain JavaScript interpreter in any meaningful way. It seems it's just sent to the browser in the same syntax that the programmer wrote it in, and then the browser converts it all the way down to machine code... that can't be right. That seems like it would be slow.
