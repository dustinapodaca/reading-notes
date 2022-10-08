<img src="https://members-csforall.imgix.net/members/logos/code-fellows-logo-horizontal-2-color-black.png" width="340" height="66">  

# Code 301 Reading Notes

## Class 05 Reading Notes

> Why this topic matters? - It is important to have a deeper understanding of how the internet works. HTML, CSS, and JS are the code files from which websites are primarily built. Understanding the roles that each play is essential to becoming a programmer or web developer. One can build upon those basics by learning other frameworks and libraies such as React.js to further implement more dymanic user interfaces for an overall better experience.
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

## React Docs - Thinking in React

```
1. What is the single responsibility principle and how does it apply to components?
  
    - The single responsibility principle states that a component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller sub-components.

2. What does it mean to build a ‘static’ version of your application?

    - A static version of an application is one that has no interactivity. It is built with components that only render data that is passed in as props. It is a good way to build the basic structure of an application before adding interactivity.

3. Once you have a static application, what do you need to add?

    - Once you have a static application, you need to add interactivity. This is done by adding state to the components.

4. What are the three questions you can ask to determine if something is state?

    - Is it passed in from a parent via props? If so, it probably isn’t state.
    - Does it remain unchanged over time? If so, it probably isn’t state.
    - Can you compute it based on any other state or props in your component? If so, it isn’t state.

5. How can you identify where state needs to live?

    - Identify every component that renders something based on that state.
    - Find a common owner component (a single component above all the components that need the state in the hierarchy).
    - Either the common owner or another component higher up in the hierarchy should own the state.
    - If you can’t find a component where it makes sense to own the state, create a new component simply for holding the state and add it somewhere in the hierarchy above the common owner component.
```

## Higher-Order Functions

```
1. What is a “higher-order function”?

  - A higher-order function is a function that either takes one or more functions as arguments, or returns a function as its result.

2. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

  - Line 2 is returning a function m that evaluates the value of n compared to m and returns true if m is greater than the value of n.

3. Explain how either map or reduce operates, with regards to higher-order functions.

  - Map and reduce are both higher-order functions. Map takes an array and a function as arguments and returns a new array. Reduce takes an array, a function, and an initial value as arguments and returns a single value.

```

## Things I Want to Know More About

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
