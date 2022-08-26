<img src="https://members-csforall.imgix.net/members/logos/code-fellows-logo-horizontal-2-color-black.png" width="340" height="66">  

# Code 201 Reading Notes

## Class 08 Reading Notes - (source cred: developer.mozilla.org)  

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

### HTML Forms

```
1. Why are forms so important in web development?

  - Web forms are one of the main points of interaction between a user and a web site or application. Forms allow users to enter data, which is generally sent to a web server for processing and storage (see Sending form data later in the module), or used on the client-side to immediately update the interface in some way.

2. When designing a form, what are some key things to keep in mind when it comes to user experience?

  - It's always better to step back and take the time to think about your form. Designing a quick mockup will help you to define the right set of data you want to ask your user to enter. From a user experience (UX) point of view, it's important to remember that the bigger your form, the more you risk frustrating people and losing users. Keep it simple and stay focused: ask only for the data you absolutely need.

3. List 5 form elements and explain their importance.

  - <form> - defines a form
    <label> - label the input
    <input> - input field for text, email etc.
    <textarea> - a multiline text field
    <button> - submit their data

(source cred: developer.mozilla.org)  
```

### Learn JS - Introduction To Events

```
1. How would you describe events to a non-technical friend?

  - An event is a way for JS to 'listen' to a webpage for any events from the user such as a click on an area or button or even mouse movement.

2. When using the addEventListener() method, what 2 arguments will you need to provide?

  - You will need to provide the name of the event and a function to handle the event.

3. Describe the event object. Why is the target within the event object useful?

  - The event object is automatically passed to event handlers to provide extra features and information. The target property of the event object is always a reference to the element the event occurred upon.

4. What is the difference between event bubbling and event capturing?

  - Event bubbling and capture are terms that describe phases in how the browser handles events targeted at nested elements.
  - In the capturing phase:
      * The browser checks to see if the element's outer-most ancestor (<html>) has a click event handler registered on it for the capturing phase, and runs it if so. Then it moves on to the next element inside <html> and does the same thing, then the next one, and so on until it reaches the direct parent of the element that was actually clicked.
  - In the bubbling phase, the exact opposite of the capturing phase occurs:
      - The browser checks to see if the direct parent of the clicked element has a click event handler registered on it for the bubbling phase, and runs it if so. Then it moves on to the next immediate ancestor element and does the same thing, then the next one, and so on until it reaches the <html> element.

(source cred: developer.mozilla.org)  
```
## Things I Want to Know More About

- The DOM and its role in web pages.
- JavaScript Object Literals
- JS Constructors
- Prototypes and Inheritance
- **LOOPS**. (for loops)
- Variables, **Functions**, Operators in JS
- JS syntax and structure
- Arrays, Conditionals, Expressions and Operators
- CSS Box Modeling
- CSS Selectors
