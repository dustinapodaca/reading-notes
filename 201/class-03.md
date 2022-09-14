<img src="https://members-csforall.imgix.net/members/logos/code-fellows-logo-horizontal-2-color-black.png" width="340" height="66">  

# Code 201 Reading Notes

## Class 03 Reading Notes - (source cred: developer.mozilla.org)  

> Why this topic matters? - It is important to continue to develop our understanding of how the internet works. HTML, CSS, and JS are the code files from which websites are primarily built. Continuing to further our understanding of the roles that each play is essential to becoming a programmer or web developer.
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
```
When should you use an unordered list in your HTML document?

    - The <ul> element is for grouping a collection of items that do not have a numerical ordering, and their order in the list is meaningless.

How do you change the bullet style of unordered list items?

    - The bullet style is not defined in the HTML description of the page, but in its associated CSS, using the list-style-type property.

When should you use an ordered list vs an unorder list in your HTML document?

    - Typically, ordered list items display with a preceding marker, such as a number or letter. Use the <ol> when the order is needing to be meaningful.

Describe two ways you can change the numbers on list items provided by an ordered list?

    - You can use <ol type="i"> to utilize roman numeral type or simply use <ol> for a generic numbered starting from 1. You can also use a start attribute <ol start="4"> to start the list at a different number than 1.


(source cred: developer.mozilla.org) 
```
### The Box Model

- Everything in CSS has a box around it, and understanding these boxes is key to being able to create more complex layouts with CSS, or to align items with other items.

- In CSS we broadly have two types of boxes — **block boxes** and **inline boxes**. The type refers to how the box behaves in terms of page flow and in relation to other boxes on the page. Boxes have an *inner display type* and an *outer display type*.


```
Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?

    - The Box Model:
        - Once upon a time there was a border box that was under attack. "Margin" added protection and fortified the outer layer of the box while "Padding" added a buffer zone to the inside. Nobody was going to get in without a fight. All the while the contents were at peace and rested safely within.

    - The End.

List and describe the four parts of an HTML elements box as referred to by the box model.

    - Content box: The area where your content is displayed; size it using properties like inline-size and block-size or width and height.
    - Padding box: The padding sits around the content as white space; size it using padding and related properties.
    - Border box: The border box wraps the content and any padding; size it using border and related properties.
    - Margin box: The margin is the outermost layer, wrapping the content, padding, and border as whitespace between this box and other elements; size it using margin and related properties.

(source cred: developer.mozilla.org) 
```
### Arrays

- Arrays present a neat way of storing a list of data items under a single variable name.
  - Arrays are generally described as "list-like objects"; they are basically single objects that contain multiple values stored in a list. 
  - Array objects can be stored in variables and dealt with in much the same way as any other type of value, the difference being that we can access each value inside the list individually, and do super useful and efficient things with the list, like loop through it and do the same thing to every value.

1. Arrays consist of square brackets and items that are separated by commas.
    - `const shopping = ['bread', 'milk', 'cheese', 'hummus', 'noodles'];`
    - `console.log(shopping);`

2. In the above example, each item is a string, but in an array we can store various data types — strings, numbers, objects, and even other arrays. We can also mix data types in a single array — we do not have to limit ourselves to storing only numbers in one array, and in another only strings.
    - `const sequence = [1, 1, 2, 3, 5, 8, 13];`
    - `const random = ['tree', 795, [0, 1, 2]];`

### Expressions and Operators

- At a high level, an **expression** is a valid unit of code that resolves to a value. There are two types of expressions: those that have side effects (such as assigning values) and those that purely *evaluate*.

- The expression `x = 7` is an example of the first type. This expression uses the `=` operator to assign the value seven to the variable `x`. The expression itself evaluates to `7`.

- The expression `3 + 4` is an example of the second type. This expression uses the `+` operator to add `3` and `4` together and produces a value, `7`. However, if it's not eventually part of a bigger construct (for example, a variable declaration like `const z = 3 + 4`), its result will be immediately discarded — this is usually a programmer mistake because the evaluation doesn't produce any effects.

```
What data types can you store inside of an Array?

    - In an array one can store various data types — strings, numbers, objects, and even other arrays. One can also mix data types in a single array.

Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?

    - It is not a valid JS array. One can create a multidimensional array but the chaining of square brackets is done improperly. (incorrect original answer)

    - It is a valid JS array. It is a multidimensional array that store 3 arrays. You can access the values by brackets and index. people [1][2] etc.

List five shorthand operators for assignment in javascript and describe what they do.

    - The simple assignment operator (=) is used to assign a value to a variable.
    - The addition assignment operator (+=) adds the value of the right operand to a variable and assigns the result to the variable.
    - The subtraction assignment operator (-=) subtracts the value of the right operand from a variable and assigns the result to the variable.
    - The multiplication assignment operator (*=) multiplies a variable by the value of the right operand and assigns the result to the variable.
    - The division assignment operator (/=) divides a variable by the value of the right operand and assigns the result to the variable.

Read the code below and evaluate the last expression and explain what the result would be and why.

    - The result would be 10 as you are adding 10 to a false boolean and then adding that by a string 'dog'.
        - (10 + false) + 'dog'
        - false = 0; true = 1 in binary. 0 is the 'falsy' value
        - '10dog' => false is 0 and 10 gets converted to a string and attached to dog. Easier to turn 10 to a string than dog to a number. '10dog'

Describe a real world example of when a conditional statement should be used in a JavaScript program.

    -  Imagine a child being asked for help with a chore by their mother or father. The parent might say "Hey sweetheart! If you help me by going and doing the shopping, I'll give you some extra allowance so you can afford that toy you wanted."  It'd be up to us to provide a mechanism for the parent to set the shoppingDone variable to true if the child did the shopping.

    let shoppingDone = false;
    let childsAllowance;

    if (shoppingDone === true) {
        childsAllowance = 10;
    } else {
         childsAllowance = 5;
    }

Give an example of when a Loop is useful in JavaScript.

    - A loop is useful in JS when one is needing to go through a lot of information multiple times. Most of the time when you use a loop, you will have a collection of items and want to do something with every item. It would be a lot of code and very tiring to have to write code to go through a collection one by one as opposed to a loop thats sole purpose is doing the same thing over and over again with much less code.


(source cred: developer.mozilla.org) 
```

## Things I Want to Know More About

- Variables, Functions, Operators in JS
- Memorize HTML syntax, elements, and attributes.
- JS syntax and structure
- Arrays, Conditionals, Expressions and Operators.
- CSS box modeling.

