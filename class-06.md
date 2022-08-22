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
### JavaScript Object Basics

```
1. How would you describe an object to a non-technical friend you grew up with?

  - An object is simply a collection of data stored inside of one area (variable).

2. What are some advantages to creating object literals?

  - It is very common to create an object using an object literal when you want to transfer a series of structured, related data items in some manner, for example sending a request to the server to be put into a database. Sending a single object is much more efficient than sending several items individually, and it is easier to work with than an array, when you want to identify individual items by name

3. How do objects differ from arrays?

  - Instead of using an index number to select an item, you are using the name associated with each member's value and they map strings to values in the same way that arrays map numbers to values.

4. Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.

  -  Dot notation is generally preferred over bracket notation because it is more succinct and easier to read. However there are some cases where you have to use brackets. For example, if an object property name is defined at runtime then you can't use dot notation to access the value, but you can pass the name as a variable inside brackets.

5. Evaluate the code below. What does the term this refer to and what is the advantage to using this?

  -  In the code below 'this' is being referred to as the dog itself. The 'this' keyword refers to the current object the code is being written inside and if you create more than one, this enables you to use the same method definition for every object you create.


(source cred: developer.mozilla.org)  
```
### Introduction to the DOM
```
1. What is the DOM?

  - The Document Object Model (DOM) is a programming interface for web documents. It represents the page so that programs can change the document structure, style, and content. The DOM represents the document as nodes and objects; that way, programming languages can interact with the page.



2. Briefly describe the relationship between the DOM and JavaScript.

  - The DOM is not a programming language, but without it, the JavaScript language wouldn't have any model or notion of web pages, HTML documents, SVG documents, and their component parts. The document as a whole, the head, tables within the document, table headers, text within the table cells, and all other elements in a document are parts of the document object model for that document. They can all be accessed and manipulated using the DOM and a scripting language like JavaScript.


(source cred: developer.mozilla.org)  
```

## Things I Want to Know More About

- CSS Selectors
- The DOM and its role in web pages. 
- JavaScript Object Literals
- **LOOPS**. (for loops)
- Variables, **Functions**, Operators in JS
- JS syntax and structure
- Arrays, Conditionals, Expressions and Operators
- CSS box modeling
