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
- Each heading has to be wrapped in a heading `<h1>`` <h2>`` <h3>` element.
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
    - i.e. `25<sup>th</sup>` is <p>25<sup>th</sup></p>
    - i.e. `C<sub>8</sub>H<sub>10</sub>N<sub>4</sub>O<sub>2</sub>` is <p>C<sub>8</sub>H<sub>10</sub>N<sub>4</sub>O<sub>2</sub></p>

#### Misc.

- `<code>`: For marking up generic pieces of computer code.
- `<pre>`: For retaining whitespace (generally code blocks) — if you use indentation or excess whitespace inside your text, browsers will ignore it and you will not see it on your rendered page. If you wrap the text in `<pre>``</pre>` tags however, your whitespace will be rendered identically to how you see it in your text editor.
- `<var>`: For specifically marking up variable names.
- `<kbd>`: For marking up keyboard (and other types of) input entered into the computer.
- `<samp>`: For marking up the output of a computer program.

```
What are ways we can apply CSS to our HTML?
Why should we avoid using inline styles?
Review the block of code below and answer the following questions:
What is representing the selector?
Which components are the CSS declarations?
Which components are considered properties?
```
```
What data type is a sequence of text enclosed in single quote marks?
List 4 types of JavaScript operators.
Describe a real world Problem you could solve with a Function.
```
```
An if statement checks a __ and if it evaluates to ___, then the code block will execute.
What is the use of an else if?
List 3 different types of comparison operators.
What is the difference between the logical operator && and ||?
```