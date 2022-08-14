# Code 201 Reading Notes

## Class 01 Reading Notes
> Why this topic matters? - It is important to have a base understanding of how the internet works. HTML, CSS, and JS are the code files from which websites are primarily built. Understanding the roles that each play is essential to becoming a programmer or web developer. 
>  - **HTML** - creates the structure i.e. the backbone.
>     1. HTML is the markup language that we use to structure and give meaning to our web content, for example defining paragraphs, headings, and data tables, or embedding images and videos in the page.
>  - **CSS** - stylizes the website or makes it look good.
>  
>     2. CSS is a language of style rules that we use to apply styling to our HTML content, for example setting background colors and fonts, and laying out our content in multiple columns.
>  - **JavaScript** - increases interactivity; handles more complex functions and features and enhances site functionality.
>  
>     3. JavaScript is a scripting language that enables you to create dynamically updating content, control multimedia, animate images, and pretty much everything else. (Okay, not everything, but it is amazing what you can achieve with a few lines of JavaScript code.)
>  
---

### Notes - (source: developer.mozilla.org)
- **Clients** are the typical web user's internet-connected devices (for example, your computer connected to your Wi-Fi, or your phone connected to your mobile network) and web-accessing software available on those devices (usually a web browser like Firefox or Chrome).
- **Servers** are computers that store webpages, sites, or apps. When a client device wants to access a webpage, a copy of the webpage is downloaded from the server onto the client machine to be displayed in the user's web browser.
- **HTTP: Hypertext Transfer Protocol** is an application protocol that defines a language for clients and servers to speak to each other. This is like the language you use to order your goods.

  1. The browser goes to the DNS server, and finds the real address of the server that the website lives on (you find the address of the shop).
  2. The browser sends an HTTP request message to the server, asking it to send a copy of the website to the client (you go to the shop and order your goods). This message, and all other data sent between the client and the server, is sent across your internet connection using TCP/IP.
  3. If the server approves the client's request, the server sends the client a "200 OK" message, which means "Of course you can look at that website! Here it is", and then starts sending the website's files to the browser as a series of small chunks called data packets (the shop gives you your goods, and you bring them back to your house).
  4. The browser assembles the small chunks into a complete web page and displays it to you (the goods arrive at your door — new shiny stuff, awesome!).

- **Parsing:** Parsing is the process of breaking down code into individual chunks of code, verifying that all necessary inputs are included in the code, and acting on the instructions dictated by the code.

- In the context of the Web, parsing most commonly happens when a web browser receives the files that comprise a website. Every web browser is equipped with a rendering engine that converts the files into the web page you see in your browser. The rendering engine contains several parsers – the part of the program that parses code prior to rendering the web page. There is a different parser for every language. At a minimum, any modern browser can parse HTML, CSS, and JavaScript.

- When browsers send requests to servers for HTML files, those HTML files often contain `<link>` elements referencing external CSS stylesheets and `<script>` elements referencing external JavaScript scripts. It's important to know the order in which those files are parsed by the browser as the browser loads the page:

  1. The browser parses the HTML file first, and that leads to the browser recognizing any `<link>` element references to external CSS stylesheets and any `<script>`-element references to scripts.
  2. As the browser parses the HTML, it sends requests back to the server for any CSS files it has found from `<link>` elements, and any JavaScript files it has found from `<script>` elements, and from those, then parses the CSS and JavaScript.
  3. The browser generates an in-memory DOM tree from the parsed HTML, generates an in-memory CSSOM structure from the parsed CSS, and compiles and executes the parsed JavaScript.
  4. As the browser builds the DOM tree and applies the styles from the CSSOM tree and executes the JavaScript, a visual representation of the page is painted to the screen, and the user sees the page content and can begin to interact with it.

- The **`<link>`** HTML element specifies relationships between the current document and an external resource. This element is most commonly used to link to stylesheets

- The **`<script>`** HTML element is used to embed executable code or data; this is typically used to embed or refer to JavaScript code.
  
### JavaScript is a programming language that allows you to implement complex things on web pages. Every time a web page does more than just sit there and display static information for you to look at—displaying timely content updates, interactive maps, animated 2D/3D graphics, scrolling video jukeboxes, or more—you can bet that JavaScript is probably involved.

- Application Programming Interfaces (APIs) are ready-made sets of code building blocks that allow a developer to implement programs that would otherwise be hard or impossible to implement.

- Browser APIs are built into your web browser, and are able to expose data from the surrounding computer environment, or do useful complex things. For example:
  
    - The DOM (Document Object Model) API allows you to manipulate HTML and CSS, creating, removing and changing HTML, dynamically applying new styles to your page, etc. Every time you see a popup window appear on a page, or some new content displayed (as we saw above in our simple demo) for example, that's the DOM in action.
    - The Geolocation API retrieves geographical information. This is how Google Maps is able to find your location and plot it on a map.
    - The Canvas and WebGL APIs allow you to create animated 2D and 3D graphics. People are doing some amazing things using these web technologies — see Chrome Experiments and webglsamples.
    - Audio and Video APIs like HTMLMediaElement and WebRTC allow you to do really interesting things with multimedia, such as play audio and video right in a web page, or grab video from your web camera and display it on someone else's computer (try our simple Snapshot demo to get the idea).
  

- Third party APIs are not built into the browser by default, and you generally have to grab their code and information from somewhere on the Web. For example:
  - The Twitter API allows you to do things like displaying your latest tweets on your website.
  - The Google Maps API and OpenStreetMap API allows you to embed custom maps into your website, and other such functionality.
  
- **Variables** are containers that store values. You start by declaring a variable with the let keyword, followed by the name you give to the variable:
  - i.e. `let myVariable;`
  - A semicolon at the end of a line indicates where a statement ends. It is only required when you need to separate statements on a single line. However, some people believe it's good practice to have semicolons at the end of each statement.

## Note that variables may hold values that have different data types:

### String 
- This is a sequence of text known as a string. To signify that the value is a string, enclose it in single quote marks.
  - `let myVariable = 'Bob';`
### Number
- This is a number. Numbers don't have quotes around them.
  - `let myVariable = 10;`   
### Boolean
- This is a True/False value. The words `true` and `false` are special keywords that don't need quote marks.
  - `let myVariable = true;` 
### Array
- This is a structure that allows you to store multiple values in a single reference.	
  - `let myVariable = [1,'Bob','Steve',10];`
Refer to each member of the array like this:
`myVariable[0]`, `myVariable[1]`, etc.
### Object
- This can be anything. Everything in JavaScript is an object and can be stored in a variable. Keep this in mind as you learn.	
  - `let myVariable = document.querySelector('h1');`

---  
```
1. Compose a short poem describing how HTTP sends data between computers.
  
  An HTTP Haiku
  - Browser help me find
    Per your request, here you go
    A copy to view
 
 or
 
  - Browser find my site
    Per your request, a copy
    Displayed just for you
    
2. Describe how HTML, CSS, and JS files are “parsed” in the browser.
  
  - The browser parses the HTML file first and locates any link or script elements. 
    From there requests are sent back to the server for the CSS and JavaScript files and parses those next. 
    The browser then generates an in-memory DOM tree and applies the styles from the CSSOM tree and executes 
    the JavaScript where a visual representation of the page appears on the screen.
  
3. How can you find images to add to a Website?
  
  - One can always go to Google Images and search for a suitable image. You can then copy the image URL
    and save it for future use. 
  
4. How do you create a String vs a Number in JavaScript?
  
  - A string variable is created with single "" marks around the value that you are signifying as a string. 
    i.e let myVariable = 'Dustin'; It is a sequnce of text where signifying a Number variable you do not 
    enclose in quotes. i.e let myVariable = 10;
  
5. What is a Variable and why are they important in JavaScript?
  
    - A varibale is a container for storing data (data types). Variables are necessary to do anything interesting 
      in programming. If values couldn't change, then you couldn't do anything dynamic.
      
 (source cred: developer.mozilla.org)     
```
---
### HTML (Hypertext Markup Language) is a markup language that tells web browsers how to structure the web pages you visit. HTML consists of a series of elements, which you use to enclose, wrap, or mark up different parts of content to make it appear or act in a certain way. The enclosing tags can make content into a hyperlink to connect to another page, italicize words, and so on. 

#### - An **element** is a part of a webpage. In XML and HTML, an element may contain a data item or a chunk of text or an image, or perhaps nothing. A typical element includes an opening tag with some attributes, enclosed text content, and a closing tag.

- Elements can be placed within other elements. This is called **nesting.**
  - i.e. `<p>My cat is <strong>very</strong> grumpy.</p>`
- **Block vs. Inline**
  - Block-level elements form a visible block on a page. A block-level element appears on a new line following the content that precedes it. Any content that follows a block-level element also appears on a new line. Block-level elements are usually structural elements on the page. For example, a block-level element might represent headings, paragraphs, lists, navigation menus, or footers.
  - i.e `<p>fourth</p><p>fifth</p><p>sixth</p>`
  - Inline elements are contained within block-level elements, and surround only small parts of the document's content (not entire paragraphs or groupings of content). An inline element will not cause a new line to appear in the document. It is typically used with text, for example an `<a>` element creates a hyperlink, and elements such as `<em>` or `<strong>`create emphasis. 
  - i.e. `<em>first</em><em>second</em><em>third</em>`

#### - Attributes contain extra information about the element that won't appear in the content.
- i.e. `<p class="editor-note">My cat is very grumpy</p>`

- An **attribute** should have:
  - A space between it and the element name. (For an element with more than one attribute, the attributes should be separated by spaces too.)
  - The attribute name, followed by an equal sign.
  - An attribute value, wrapped with opening and closing quote marks.

- Another example of an element is `<a>`. This stands for anchor. An anchor can make the text it encloses into a hyperlink. Anchors can take a number of attributes, but several are as follows:

  - `href`: This attribute's value specifies the web address for the link. For example: `href="https://www.mozilla.org/".`
  - `title`: The title attribute specifies extra information about the link, such as a description of the page that is being linked to. For example, `title="The Mozilla homepage"`. This appears as a tooltip when a cursor hovers over the element.
  - `target`: The target attribute specifies the browsing context used to display the link. For example, `target="_blank"` will display the link in a new tab. If you want to display the linked content in the current tab, just omit this attribute.
  - i.e. `<p>A link to <a href="https://aresseecurity.co" title="Ares Security Homepage" target="_blank">Ares Security</a>.</p>`









---
```  
  
1. What is an HTML attribute?

  - An HTML attribute are special words that define additional characteristics or properties of the HTML element.
    They generally contain extra information that won't appear in the content.
  
2. Describe the Anatomy of an HTMl element.

  - The anatomy of an HTML element is broken up into three characteristics; the opening tag, the content, and 
    the closing tag.
    - The opening tag consists of the name of the element wrapped in opening and closing angle brackets.
    - The content is simply that; the content of the element such as paragraph text or an image link etc.
    - The closing tag is the same as the opening tag except for a forward slash before the element name and marks
      where the element ends.
  
3. What is the Difference between <article> and <section> element tags?
  
  - <article> encloses a block of related content that makes sense on its own without the rest of the page.
  - <section> is similar to <article>, but it is more for grouping together a single part of the page that constitutes 
    one single piece of functionality or a theme- therefore, defines a section in a document.
  
4. What Elements does a “typical” website include?

  - <header> <nav> <main> <article> <section> <div> <aside> <footer> <body> <title> <p> <ul> <ol> <h1> <br> etc.
  
5. How does metadata influence Search Engine Optimization?
  
  - Specifying a description that includes keywords relating to the content of your page is useful as it has the 
    potential to make your page appear higher in relevant searches performed in search engines.
    
6. How is the <meta> HTML tag used when specifying metadata?
  
  - The <meta> element is used to specify metadata and typically many <meta> elements include "name" and "content"
    attributes. Name specifies the type of meta element it is; what type of information it contains and content 
    specifies the actual meta content.

(source cred: developer.mozilla.org)    
```
---

### When starting with a web project, many people focus on the technical side. Of course you must be familiar with the technique of your craft, but what really matters is what you want to accomplish. Yes, it seems obvious, but too many projects fail not from a lack of technical know-how, but from lack of goals and vision.

- What exactly do I want to accomplish?
- How will a website help me reach my goals?
- What needs to be done, and in what order, to reach my goals?

```
1. What is the first step to designing a Website?

  - The first step when designing any website is to first define what you want to accomplish. 
  
2. What is the most important question to answer when designing a Website?

  - One must answer what they intend to accomplish, and what needs to be done and in what order to reach their goals.
    What you intend to accomplish is most important as it is the driving force behind everything else. One should 
    generally list all of the goals that they wish to acheive. 

(source cred: developer.mozilla.org)    
```
---

### In programming, Semantics refers to the meaning of a piece of code — for example "what effect does running that line of JavaScript have?", or "what purpose or role does that HTML element have" (rather than "what does it look like?".)

- In HTML, for example, the `<h1>` element is a semantic element, which gives the text it wraps around the role (or meaning) of "a top level heading on your page."
  - `<h1>This is a top level heading</h1>`
- On the other hand, you could make any element look like a top level heading. Consider the following:
  - `<span style="font-size: 32px; margin: 21px 0;">Is this a top level heading?</span>`
- This will render it to look like a top level heading, but it has no semantic value, so it will not get any extra benefits as described above. It is therefore a good idea to use the right HTML element for the right job.


```
1. Why should you use an <h1> element over a <span> element to display a top level heading?

  - One should use an <h1> element over a <span> element as the <h1> is a semantic element and will therefore
    give the text it wraps around a role or meaning. For example the <h1> tag is utilized in SEO optimazation where
    search engines will consider its contents as important keywords to influence the page's search rankings

2. What are the benefits of using semantic tags in our HTML?

  - SEO optimization for page rankings, finding blocks of code is easier than multiple <div>, screen readers
    can use it as a signpost to help disabled users navigate, helps suggest to the dev what type of data will be 
    populated, etc.

(source cred: developer.mozilla.org)    
```
---
```
1. Describe 2 things that require JavaScript in the Browser?

- 

2. How can you add JavaScript to an HTML document?

- 

(source cred: developer.mozilla.org)    
```
## Things I Want to Know More About

- Variables, Functions, Operators in JS
- Memorize HTML syntax, elements, and attributes
- Structuring metadata for SEO optimization with Google Search Engine
- Version Control and git
- JS syntax and structure
