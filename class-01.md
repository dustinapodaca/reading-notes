# Code 201 Reading Notes

## Class 01 Reading Notes
---

### Notes
- **Clients** are the typical web user's internet-connected devices (for example, your computer connected to your Wi-Fi, or your phone connected to your mobile network) and web-accessing software available on those devices (usually a web browser like Firefox or Chrome).
- **Servers** are computers that store webpages, sites, or apps. When a client device wants to access a webpage, a copy of the webpage is downloaded from the server onto the client machine to be displayed in the user's web browser.
- **HTTP: Hypertext Transfer Protocol** is an application protocol that defines a language for clients and servers to speak to each other. This is like the language you use to order your goods.

  1. The browser goes to the DNS server, and finds the real address of the server that the website lives on (you find the address of the shop).
  2. The browser sends an HTTP request message to the server, asking it to send a copy of the website to the client (you go to the shop and order your goods). This message, and all other data sent between the client and the server, is sent across your internet connection using TCP/IP.
  3. If the server approves the client's request, the server sends the client a "200 OK" message, which means "Of course you can look at that website! Here it is", and then starts sending the website's files to the browser as a series of small chunks called data packets (the shop gives you your goods, and you bring them back to your house).
  4. The browser assembles the small chunks into a complete web page and displays it to you (the goods arrive at your door — new shiny stuff, awesome!).

- **Parsing:** Parsing is the process of breaking down code into individual chunks of code, verifying that all necessary inputs are included in the code, and acting on the instructions dictated by the code.

- In the context of the Web, parsing most commonly happens when a web browser receives the files that comprise a website. Every web browser is equipped with a rendering engine that converts the files into the web page you see in your browser. The rendering engine contains several parsers – the part of the program that parses code prior to rendering the web page. There is a different parser for every language. At a minimum, any modern browser can parse HTML, CSS, and JavaScript.

- When browsers send requests to servers for HTML files, those HTML files often contain <link> elements referencing external CSS stylesheets and <script> elements referencing external JavaScript scripts. It's important to know the order in which those files are parsed by the browser as the browser loads the page:

  - The browser parses the HTML file first, and that leads to the browser recognizing any <link>-element references to external CSS stylesheets and any <script>-element references to scripts.
  - As the browser parses the HTML, it sends requests back to the server for any CSS files it has found from <link> elements, and any JavaScript files it has found from <script> elements, and from those, then parses the CSS and JavaScript.
  - The browser generates an in-memory DOM tree from the parsed HTML, generates an in-memory CSSOM structure from the parsed CSS, and compiles and executes the parsed JavaScript.
  - As the browser builds the DOM tree and applies the styles from the CSSOM tree and executes the JavaScript, a visual representation of the page is painted to the screen, and the user sees the page content and can begin to interact with it.

- The **<link>** HTML element specifies relationships between the current document and an external resource. This element is most commonly used to link to stylesheets

- The **<script>** HTML element is used to embed executable code or data; this is typically used to embed or refer to JavaScript code.
  
```
1. Compose a short poem describing how HTTP sends data between computers.
  - 
2. Describe how HTML, CSS, and JS files are “parsed” in the browser.
3. How can you find images to add to a Website?
4. How do you create a String vs a Number in JavaScript?
5. What is a Variable and why are they important in JavaScript?

```
---
