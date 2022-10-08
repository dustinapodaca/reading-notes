<img src="https://members-csforall.imgix.net/members/logos/code-fellows-logo-horizontal-2-color-black.png" width="340" height="66">  

# Code 301 Reading Notes

## Class 02 Reading Notes

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

## React Lifecycle

```
1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

  - Based off the diagram, render comes before componentDidMount.

2. What is the very first thing to happen in the lifecycle of React? 

  - The mounting phase is the very first thing to happen in the lifecylce of React. Constructor, static getDerivedStateFromProps, render, componentDidMount, and UNSAFE_componentWillMount all occur in this order during mounting.

3. Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates.

  - constructor
  - render
  - componentDidMount
  - React Updates
  - componentWillUnmount

4. What does componentDidMount do?

  - This method is invoked immediately after a component is mounted. If you need to load anything using a network request or initialize the DOM, it should go here. This method is a good place to set up any subscriptions. If you do that, don’t forget to unsubscribe in componentWillUnmount().

```

## React State Vs Props

```
1. What types of things can you pass in the props?

  - Props are arguments passed into React components. Props are passed to components via HTML attributes. Props are read-only, which means that data coming from the parent should not be changed by child components.


2. What is the big difference between props and state?

  - Props are passed into the component (similar to function parameters) whereas state is managed within the component (similar to variables declared within a function).

3. When do we re-render our application?

  - When the state of a component changes, the component re-renders.

4. What are some examples of things that we could store in state?

  - State is a special type of prop that is used to store data that is used to update the UI. State is a special type of prop that is used to store data that is used to update the UI. State is a special type of prop that is used to store data that is used to update the UI.

```

## Things I Want to Know More About

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
