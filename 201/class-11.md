<img src="https://members-csforall.imgix.net/members/logos/code-fellows-logo-horizontal-2-color-black.png" width="340" height="66">  

# Code 201 Reading Notes

## Class 11 Reading Notes - (source cred: developer.mozilla.org)  

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

### Video and Audio Content

```
1. Explain how the ability to use video and audio on the web has evolved since the early 2000s.

  - The first influx of online videos and audio were made possible by proprietary plugin-based technologies like Flash and Silverlight. Both of these had security and accessibility issues, and are now obsolete, in favor of native HTML solutions <video> and <audio> elements and the availability of JavaScript APIs for controlling them. 

2. Describe the use of the src and controls attributes in the <video> element.

  - The src (source) attribute contains a path to the video you want to embed. You must either use the controls attribute to include the browser's own control interface, or build your interface using the appropriate JavaScript API. 

3. Why is it important to have fallback content inside the <video> element?

  - The paragraph inside the <video> tags is called fallback content — this will be displayed if the browser accessing the page doesn't support the <video> element, allowing us to provide a fallback for older browsers. 

4. Write a very short story where <audio> and <video> are characters.

  - Once upon a time there was two elements that needed to display their content. <audio> was freely able to express himself with sound while <video> was able to put pixels on the screen.
  

(source cred: developer.mozilla.org)  
```

### A Complete Guide To Grid

```
1. How does Grid layout differ from Flex?

  - Flexbox is also a very great layout tool, but its one-directional flow has different use cases. CSS Grid Layout (aka “Grid” or “CSS Grid”), is a two-dimensional grid-based layout system that, compared to any web layout system of the past, completely changes the way we design user interfaces.

2. Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.

  - Grid Container: The element on which display: grid is applied. It’s the direct parent of all the grid items. 
  - Grid Item: The children (i.e. direct descendants) of the grid container.
  - Grid Line: The dividing lines that make up the structure of the grid. They can be either vertical (“column grid lines”) or horizontal (“row grid lines”) and reside on either side of a row or column.

(source cred: css-tricks.com/snippets/css/complete-guide-grid/)
```

### Responsive Images

```
1. Besides making a site visually appealing across different screen sizes, why should developers make images responsive?

  - Responsive images helps to improve performance across different devices. 

2. Define the following <img> attributes srcset and sizes. Write an example of how they are used.

  - srcset: One or more strings separated by commas, indicating possible image sources for the user agent to use. Each string is composed of:
    - A URL to an image
    - Optionally, whitespace followed by one of: A width descriptor (a positive integer directly followed by w). The width descriptor is divided by the source size given in the sizes attribute to calculate the effective pixel density. A pixel density descriptor (a positive floating point number directly followed by x).

  - sizes: One or more strings separated by commas, indicating a set of source sizes. Each source size consists of:
    - A media condition. This must be omitted for the last item in the list.
    - A source size value.

3. How is srcset more helpful for responsive images than CSS or JavaScript?

  - When the browser starts to load a page, it starts to download (preload) any images before the main parser has started to load and interpret the page's CSS and JavaScript. That mechanism is useful in general for reducing page load times, but it is not helpful for responsive images — hence the need to implement solutions like srcset. For example, you couldn't load the <img> element, then detect the viewport width with JavaScript, and then dynamically change the source image to a smaller one if desired. By then, the original image would already have been loaded, and you would load the small image as well, which is even worse in responsive image terms.

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
