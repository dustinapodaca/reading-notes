<img src="https://members-csforall.imgix.net/members/logos/code-fellows-logo-horizontal-2-color-black.png" width="340" height="66">  

# Code 201 Reading Notes

## Class 02 Reading Notes
> Why this topic matters? - It is important to continue to develop our understanding of how the internet works. HTML, CSS, and JS are the code files from which websites are primarily built. Continuing to further our understanding of the roles that each play is essential to becoming a programmer or web developer. 
>  - **HTML** - creates the structure i.e. the backbone.
>     - HTML is the markup language that we use to structure and give meaning to our web content, for example defining paragraphs, headings, and data tables, or embedding images and videos in the page.
>  - **CSS** - stylizes the website or makes it look good.
>  
>     - CSS is a language of style rules that we use to apply styling to our HTML content, for example setting background colors and fonts, and laying out our content in multiple columns.
>  - **JavaScript** - increases interactivity; handles more complex functions and features and enhances site functionality.
>  
>     - JavaScript is a scripting language that enables you to create dynamically updating content, control multimedia, animate images, and pretty much everything else. (Okay, not everything, but it is amazing what you can achieve with a few lines of JavaScript code.)
>  
---
### One of HTML's main jobs is to give text structure so that a browser can display an HTML document the way its developer intends. 

- In HTML, each paragraph has to be wrapped in a `<p>` element
- Each heading has to be wrapped in a heading `<h1> <h2> <h3>` element.
    - Preferably, you should use a single `<h1>` per page—this is the top level heading, and all others sit below this in the hierarchy.
    - Of the six heading levels available, you should aim to use no more than three per page, unless you feel it is necessary.
    - Users looking at a web page tend to scan quickly to find relevant content, often just reading the headings, to begin with. If they can't see anything useful within a few seconds, they'll likely get frustrated and go somewhere else.
    - Search engines indexing your page consider the contents of headings as important keywords for influencing the page's search rankings. Without headings, your page will perform poorly in terms of SEO (Search Engine Optimization).

### Semantics and why we need them.

- Semantic HTML refers to syntax that makes the HTML more comprehensible by better defining the different sections and layout of web pages. It makes web pages more informative and adaptable, allowing browsers and search engines to better interpret content.

- Semantics are relied on everywhere around us—we rely on previous experience to tell us what the function of an everyday object is; when we see something, we know what its function will be. So, for example, we expect a red traffic light to mean "stop," and a green traffic light to mean "go." Things can get tricky very quickly if the wrong semantics are applied.

### Nesting Lists

- It is perfectly OK to nest one list inside another one. You might want to have some sub-bullets sitting below a top-level bullet.
    - Since the last two bullets are very closely related to the one before them (they read like sub-instructions or choices that fit below that bullet), it might make sense to nest them inside their own unordered list and put that list inside the current fourth bullet. This would look like so:

```
<ol>
  <li>Remove the skin from the garlic, and chop coarsely.</li>
  <li>Remove all the seeds and stalk from the pepper, and chop coarsely.</li>
  <li>Add all the ingredients into a food processor.</li>
  <li>Process all the ingredients into a paste.
    <ul>
      <li>If you want a coarse "chunky" hummus, process it for a short time.</li>
      <li>If you want a smooth hummus, process it for a longer time.</li>
    </ul>
  </li>
</ol>
```

### Emphasis and Importance

- In HTML we use the `<em>` (emphasis) element to mark up text in *italics.*
- In HTML we use the `<strong>` (strong importance) element to mark up text in **bold.**
- The `<span>` tag is an inline container used to mark up a part of a text, or a part of a document.
    - The `<span>` tag is easily styled by CSS or manipulated with JavaScript using the class or id attribute.
    - You use it to wrap content when you want to apply CSS to it (or do something to it with JavaScript) without giving it any extra meaning. 
    -i.e. `<span style="font-size: 32px; margin: 21px 0; display: block;">Is this a top level heading?</span>`

### Other Advanced Formatting

- Description lists use a different wrapper than the other list types — `<dl>`; in addition each term is wrapped in a `<dt>` (description term) element, and each description is wrapped in a `<dd>` (description definition) element.
    - The browser default styles will display description lists with the descriptions indented somewhat from the terms.

- Inline quotations work by using the `<q>` element.
- There is a `<cite>` element, but this is meant to contain the title of the resource being quoted, e.g. the name of the book. There is no reason, however, why you couldn't link the text inside `<cite>` to the quote source in some way
    - i.e. `<p>According to the <a href="/en-US/docs/Web/HTML/Element/blockquote">`
`<cite>MDN blockquote page</cite></a>:</p>`

-Another fairly common element you'll meet when looking around the Web is `<abbr>`— this is used to wrap around an abbreviation or acronym. When including either, provide a full expansion of the term in plain text on first use, along with the `<abbr>` to mark up the abbreviation.
    - If providing the expansion in addition to the abbreviation makes little sense, and the abbreviation or acronym is a fairly shortened term, provide the full expansion of the term as the value of `title` attribute:
    - i.e. `<p>I think <abbr title="Reverend">Rev.</abbr> Green did it in the kitchen with the chainsaw.</p>`

- You will occasionally need to use superscript and subscript when marking up items like dates, chemical formulae, and mathematical equations so they have the correct meaning. The `<sup>` and `<sub>` elements handle this job.
    - i.e. `25<sup>th</sup>` is 25<sup>th</sup>
    - i.e. `C<sub>8</sub>H<sub>10</sub>N<sub>4</sub>O<sub>2</sub>` is C<sub>8</sub>H<sub>10</sub>N<sub>4</sub>O<sub>2</sub>

#### Misc.

- `<code>`: For marking up generic pieces of computer code.
- `<pre>`: For retaining whitespace (generally code blocks) — if you use indentation or excess whitespace inside your text, browsers will ignore it and you will not see it on your rendered page. If you wrap the text in `<pre>``</pre>` tags however, your whitespace will be rendered identically to how you see it in your text editor.
- `<var>`: For specifically marking up variable names.
- `<kbd>`: For marking up keyboard (and other types of) input entered into the computer.
- `<samp>`: For marking up the output of a computer program.

```
Why is it important to use semantic elements in our HTML?

    - Semantic HTML refers to syntax that makes the HTML more comprehensible by better defining the different sections and layout of web pages. It makes web pages more informative and adaptable, allowing browsers and search engines to better interpret content.

How many levels of headings are there in HTML?

    - There are 6 levels of heading elements starting with <h1> to <h6>

What are some uses for the <sup> and <sub> elements?

    - Superscript and subscript elements are important when needing to mark up items like dates and/or mathematical or chemical equations so they have the correct meaning. 

When using the <abbr> element, what attribute must be added to provide the full expansion of the term?

    - The title attribute should be added in addition to the element to provide the full expansion of the term.

```

### Applying CSS to HTML

- **External Stylesheet**
    - An external stylesheet contains CSS in a separate file with a .css extension. This is the most common and useful method of bringing CSS to a document. You can link a single CSS file to multiple web pages, styling all of them with the same CSS stylesheet.
    - You reference an external CSS stylesheet from an HTML `<link>` element.
    - i.e: `<link rel="stylesheet" href="styles.css">`

- The `href` attribute of the `<link>` element needs to reference a file on your file system. In the example above, the CSS file is in the same folder as the HTML document, but you could place it somewhere else and adjust the path.
    - i.e: `<link rel="stylesheet" href="styles/style.css">` *Inside a subdirectory called styles inside the current directory*

- **Internal Stylesheet**
    - An internal stylesheet resides within an HTML document. To create an internal stylesheet, you place CSS inside a `<style>` element contained inside the HTML `<head>`.
```    
<head>
    <meta charset="utf-8">
    <title>My CSS experiment</title>
    <style>
      h1 {
        color: blue;
        background-color: yellow;
        border: 1px solid black;
      }

      p {
        color: red;
      }
    </style>
  </head>
```
    - In some circumstances, internal stylesheets can be useful. For example, perhaps you're working with a content management system where you are blocked from modifying external CSS files.
    - But for sites with more than one page, an internal stylesheet becomes a less efficient way of working. To apply uniform CSS styling to multiple pages using internal stylesheets, you must have an internal stylesheet in every web page that will use the styling. 
    - The efficiency penalty carries over to site maintenance too. With CSS in internal stylesheets, there is the risk that even one simple styling change may require edits to multiple web pages.

- **Inline Styles**
    - Inline styles are CSS declarations that affect a single HTML element, contained within a style attribute. 
    - The implementation of an inline style in an HTML document might look like this:
    - i.e: `<h1 style="color: blue;background-color: yellow;border: 1px solid black;">Hello World!</h1>`

- Avoid using CSS in this way, when possible. It is the opposite of a best practice. 
    1. First, it is the least efficient implementation of CSS for maintenance.
    2. Second, inline CSS also mixes (CSS) presentational code with HTML and content, making everything more difficult to read and understand. Separating code and content makes maintenance easier for all who work on the website.

### Selectors

- Each CSS rule starts with a selector — or a list of selectors — in order to tell the browser which element or elements the rules should apply to.

- You may encounter scenarios where two selectors select the same HTML element.

- The CSS language has rules to control which selector is stronger in the event of a conflict. These rules are called **cascade** and **specificity.**

- Declarations that appear later in the stylesheet replace conflicting styles that appear earlier in the stylesheet. This is the **cascade** rule.

- **Class** selector is rated as being more specific than the element selector, as in having more **specificity** than the element selector, so it cancels the other conflicting style declaration
    - i.e: the code shows that the `.special` class selector will override `<p>` in the below line of code.
    - `<p class="special">What color am I?</p>`
    
```
.special {
  color: red;
}

p {
  color: blue;
}
```
- At its most basic level, CSS consists of two components:
    - **Properties**: These are human-readable identifiers that indicate which stylistic features you want to modify. For example, font-size, width, background-color.
    - **Values**: Each property is assigned a value. This value indicates how to style the property.

- When a property is paired with a value, this pairing is called a **CSS declaration.** CSS declarations are found within CSS Declaration Blocks.
    - Setting CSS properties to specific values is the primary way of defining layout and styling for a document. The CSS engine calculates which declarations apply to every single element of a page.

```
What are ways we can apply CSS to our HTML?

    - There are three methods of applying CSS to a document: an external stylesheet, with an internal stylesheet, and with inline styles.

Why should we avoid using inline styles?

    - It is the least effecient for any requried maintenance and inline CSS also mixes (CSS) presentational code with HTML and content, making everything more difficult to read and understand. 

Review the block of code below and answer the following questions:

    What is representing the selector?
        - h2

    Which components are the CSS declarations?
        - color: black;
        - padding: 5px;

    Which components are considered properties?
        - color:
        - padding:

```
### Operators
- An `operator` is a mathematical symbol that produces a result based on two values (or variables).

#### Addition
- Add two numbers together or combine two strings.	
    - i.e. `6 + 9;` `'Hello ' + 'world!';`

#### Subtraction, Multiplication, Division
- These do what you'd expect them to do in basic math.	
    - i.e. `9 - 3;` `8 * 2;` `9 / 3;`

#### Assignment
- As you've seen already: this assigns a value to a variable.
    - i.e. `let myVariable = 'Bob';`

#### Strict equality	
- This performs a test to see if two values are equal. It returns a `true`/`false` (Boolean) result.
    - `let myVariable = 3;`
    - `myVariable === 4;`

#### Not, Does-not-equal
- This returns the logically opposite value of what it precedes. It turns a `true` into a `false`, etc.. When it is used alongside the Equality operator, the negation operator tests whether two values are not equal.
    - For "Not", the basic expression is true, but the comparison returns false because we negate it:
    - `let myVariable = 3;`
    - `!(myVariable === 3);`

    - "Does-not-equal" gives basically the same result with different syntax. Here we are testing "is myVariable NOT equal to 3". This returns false because myVariable IS equal to 3:
    - `let myVariable = 3;`
    - `myVariable !== 3;`

### Conditionals
- Conditionals are code structures used to test if an expression returns true or not. A very common form of conditionals is the if...else statement. 
```
let iceCream = 'chocolate';
if (iceCream === 'chocolate') {
  alert('Yay, I love chocolate ice cream!');
} else {
  alert('Awwww, but chocolate is my favorite…');
}
```
- The expression inside the `if ()` is the test. This uses the strict equality operator (as described above) to compare the variable `iceCream` with the string `chocolate` to see if the two are equal. If this comparison returns `true`, the first block of code runs. If the comparison is not true, the second block of code—after the `else` statement—runs instead.

### Functions
- Functions are a way of packaging functionality that you wish to reuse. It's possible to define a body of code as a function that executes when you call the function name in your code. This is a good alternative to repeatedly writing the same code.
    - `let myVariable = document.querySelector('h1');`
    - `alert('hello!');`
    - These functions, `document.querySelector` and `alert`, are built into the browser.

- If you see something which looks like a variable name, but it's followed by parentheses— `()` —it is likely a function. 
- Functions often take *arguments*: bits of data they need to do their job. Arguments go inside the parentheses, separated by commas if there is more than one argument.
    - For example, the `alert()` function makes a pop-up box appear inside the browser window, but we need to give it a string as an argument to tell the function what message to display.

- You can also define your own functions.
- In the next example, we create a simple function which takes two numbers as arguments and multiplies them:
```
function multiply(num1,num2) {
  let result = num1 * num2;
  return result;
}
```
- You can then test `multiply(4, 7);` or `multiply(0.5, 3);` etc. later in the code or console.

```
What data type is a sequence of text enclosed in single quote marks?

    - A string. A value enclosed in single quote marks signifies a string.

List 4 types of JavaScript operators.

    - +, -. *, /, =, ===, !, !==, etc.

Describe a real world Problem you could solve with a Function.

    - In the real world you could use a function- much like in my Lab 1- that would take a person's weight, height, and age, and determine the recommended amount of water they would need to drink on a daily basis. You could also use a function to solve complex financial or business problems.

```
```
An if statement checks a __ and if it evaluates to ___, then the code block will execute.
What is the use of an else if?
List 3 different types of comparison operators.
What is the difference between the logical operator && and ||?
```