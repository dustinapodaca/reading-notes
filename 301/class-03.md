<img src="https://members-csforall.imgix.net/members/logos/code-fellows-logo-horizontal-2-color-black.png" width="340" height="66">  

# Code 301 Reading Notes

## Class 03 Reading Notes

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

## React Docs - Lists & Keys

```
1. What does .map() return?

 - .map() returns a new array with the results of calling a provided function on every element in the calling array.

2. If I want to loop through an array and display each value in JSX, how do I do that in React?

- You can loop through an array and display each value in JSX by using the map() function.

3. Each list item needs a unique ____.

- Each list item needs a unique key.

4. What is the purpose of a key?

- The purpose of a key is to give the elements a stable identity inside of a key value pair.

```

## The Spread Operator

```
1. What Is The Spread Operator?

  - The spread operator is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.

2. List 4 things that the spread operator can do.

  - The spread operator can add items to arrays, combine arrays or objects, and spread an array out into a function’s arguments.

3. Give an example of using the spread operator to combine two arrays.

  - const array1 = [1, 2, 3];
    const array2 = [4, 5, 6];
    const array3 = [...array1, ...array2];

4. Give an example of using the spread operator to add a new item to an array.

  - const array1 = [1, 2, 3];
    const array2 = [...array1, 4, 5, 6];

5. Give an example of using the spread operator to combine two objects into one.

  - const obj1 = { foo: 'bar', x: 42 };
    const obj2 = { foo: 'baz', y: 13 };
    const clonedObj = { ...obj1 };
    const mergedObj = { ...obj1, ...obj2 };

```

## How to Pass Functions Between Components

```
1. In the video, what is the first step that the developer does to pass functions between components?

  - The first step that the developer does to pass functions between components is to create a function in the parent component.

2. In your own words, what does the increment function do?

  - The increment function increments the count by 1.

3. How can you pass a method from a parent component into a child component?

  - You can pass a method from a parent component into a child component by passing it as a prop.

4. How does the child component invoke a method that was passed to it from a parent component?

  - The child component invokes a method that was passed to it from a parent component by using the props keyword.

```

## Things I Want to Know More About

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
