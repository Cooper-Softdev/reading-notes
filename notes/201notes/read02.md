# Reading Class 02

## Getting Started

0. Understanding how the web works on a depper level is important for this module because have a strong foundational knowledge of what we're manipulating inside of our website and how it interacts with the web will ensure we don't fall behind and are able to connect different concepts together into a cohesive understanding.

1. Semantics are important for SEO, search engines look at specific places within the HTML and if you're page isn't formatted IAW industry standard you'r page will fall down in the search results. Another reason is screen readers for visually impared users. The ability to navigate a webpage for them is dependent on the HTML elements within the page being written semantically correct.

2. There are 6 levels of ```<h>``` in HTML. Starting with ```<h1>```, and ending with ```<h6>```.

3. ```<sub>``` and ```<sup>``` elements are good for showing things like chemical formulas like H<sup>2</sup>O, as an example. Superscript for the top little number and sub for the tiny bottom number.

4. You must include the ```<title>``` for the ```<abbr>``` element to expand fully. Inline is probably easiest. ```<abbr title=Mozilla Developer Center?>```.

## Lurnin' see ess ess

1. CSS can be applied via Internal CSS, written into the head of the HTML document outside of the body element. Or it can be contained in-line within the body of the HTML document within the elements themselves. Lastly and most used is external, a link to the css document path is written in the HTML document which the browser follows to get the css information.

2. Avoiding inline styles helps to ensure we don't spend forever debugging why a certain element is not taking a rule we've written into our external css document. It also helps with ease of readability of the HTML document itself and with css Specificity tiers so we don't mix inline and external rules together and cause poor inheritance of our rules.

3. Reviewing the block below.

```
    h2 {
     color: black;
     padding: 5px;
   }
```
+ ```type``` is representing the selector. h2 is the selctor and it's specificity is ```<type>``` which is just below `class`.
+ The declaration components are ```color: black;``` and ```padding: 5px;```, the property, color or padding added with a value is called a declaration.
+  ```color``` and ```padding``` by themselves are the properties, which must be assigned a value to be declared.

## Learn JS

1. Datetypes enclosed in single quotes are ```strings```.
2. 4 types of JS operators are ```*```, ```-```, ```=```, and ```/```.
3. A real world issue is doing math, you can use functions to take numbers as an input and then use a function to calculate them and return the value.

### Conditionals

1. An if statement checks an expression and if it evaluates to `TRUE`, the block will execute.
2. What is the use of an `else if` in a condition? If the expression does not evaluate to `true` ie, `false` then the `else if` will invoke a different option that the block may execute.
3. Types of comparison operators are things like `==`, `===`, `!`, and `!==`.
4. `&&` is the 'logical AND' operator, it will check if 2 different expressions evaluate to  `true` respectively before it can execute. Conversely the 'logical OR' operator will return `false` only if 2 of the expressions evaluate to `false` each, if any combination involves one being `true` the operator will return `true`.

## Things I want to know more about.

Functions are hard, kinda.