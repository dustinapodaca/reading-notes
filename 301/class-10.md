<img src="https://members-csforall.imgix.net/members/logos/code-fellows-logo-horizontal-2-color-black.png" width="340" height="66">  

# Code 301 Reading Notes

## Class 10 Reading Notes

> Why this topic matters? - It is important to have a deeper understanding of how the internet works. HTML, CSS, and JS are the code files from which websites are primarily built. Understanding the roles that each play is essential to becoming a programmer or web developer. One can build upon those basics by learning other frameworks and libraries such as React.js to further implement more dynamic user interfaces for an overall better experience.
>
> - **HTML** - creates the structure i.e. the backbone.
>   - HTML is the markup language that we use to structure and give meaning to our web content, for example defining paragraphs, headings, and data tables, or embedding images and videos in the page.
> - **CSS** - stylizes the website or makes it look good.
>  
>   - CSS is a language of style rules that we use to apply styling to our HTML content, for example setting background colors and fonts, and laying out our content in multiple columns.
> - **JavaScript** - increases interactivity; handles more complex functions and features and enhances site functionality.
>  
>   - JavaScript is a scripting language that enables you to create dynamically updating content, control multimedia, animate images, and pretty much everything else. (Okay, not everything, but it is amazing what you can achieve with a few lines of JavaScript code.)
>  
---

## Understanding the JavaScript Call Stack

```
1. What is a ‘call’?

  - A call is a function invocation (call) expression.

2. How many ‘calls’ can happen at once?

  - One call can happen at a time.

3. What does LIFO mean?

  - LIFO means Last In, First Out.
4. Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

  - function firstFunction() {
  -   console.log("Hello from firstFunction");
  - };
  - function secondFunction() {
  -   firstFunction();
  -   console.log("Hello from secondFunction");
  - };
  - function thirdFunction() {
  -   secondFunction();
  -   console.log("Hello from thirdFunction");
  - };
  - thirdFunction();

5. What causes a Stack Overflow?

  - A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point.

```

## JavaScript Error Messages

```
1. What is a ‘reference error’?

  - A reference error is when you try to use a variable that is not yet declared.

2. What is a ‘syntax error’?

  - A syntax error is when you have something that cannot be parsed in terms of syntax.

3. What is a ‘range error’?

  - A range error is when you try to manipulate an object with some kind of length and give it an invalid length.

4. What is a ‘type error’?

  - A type error is when the types (number, string, etc.) you are trying to use or access are incompatible.

5. What is a breakpoint?

  - A breakpoint is a point in your code where you can pause execution and inspect the values that are stored in your variables.

6. What does the word ‘debugger’ do in your code?

  - The debugger keyword stops the execution of your code, and calls (if available) the debugging function. This has the same function as setting a breakpoint in the debugger.

```

## Things I Want to Know More About

- Node JS
- REST APIs
- Higher Order Functions
- Ternary Operators
- State and Props
- React and ReactDOM
- ES6 Classes and Constructors
- CSS3 Animations and Transitions
- The DOM and its role in web pages.
- JavaScript Object Literals
- JS Constructor Functions
- Event Listeners
- Prototypes and Inheritance
- **LOOPS**. (for loops)
- Variables, **Functions**, Operators in JS
- JS syntax and structure
- Arrays, Conditionals, Expressions and Operators
- CSS Box Modeling
- CSS Selectors
- If / Else Statements
