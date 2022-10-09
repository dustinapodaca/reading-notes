<img src="https://members-csforall.imgix.net/members/logos/code-fellows-logo-horizontal-2-color-black.png" width="340" height="66">  

# Code 301 Reading Notes

## Class 12 Reading Notes

> Why this topic matters? - It is important to have a deeper understanding of how the internet works. HTML, CSS, and JS are the code files from which websites are primarily built. Understanding the roles that each play is essential to becoming a programmer or web developer. One can build upon those basics by learning other frameworks and libraries such as React.js to further implement more dynamic user interfaces for an overall better experience.
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

## Status Codes Based On REST Methods

```
1. In your own words, describe what each group of status code represents:

  - 100’s = These are informational status codes. They indicate that the request was received and the process is continuing.
  - 200’s = These are success codes. They indicate that the request was successfully received, understood, and accepted.
  - 300’s = These are redirection codes. They indicate that further action needs to be taken in order to complete the request.
  - 400’s = These are client error codes. They indicate that the request contains bad syntax or cannot be fulfilled.
  - 500’s = These are server error codes. They indicate that the server failed to fulfill an apparently valid request.

2. What is a status code 202?

  - A status code 202 indicates that the request has been accepted for processing, but the processing has not been completed.

3. What is a status code 308?

  - A status code 308 indicates that the resource is now permanently located at another URI, specified by the Location: HTTP Response header.

4. What code would you use if an update didn’t return data to a client?

  - A status code 204 would be used if an update didn’t return data to a client.

5. What code would you use if a resource used to exist but no longer does?

  - A status code 410 would be used if a resource used to exist but no longer does.

6. What is the ‘Forbidden’ status code?
  
  - A status code 403 indicates that the server understood the request but refuses to authorize it.

```

## Build A REST API With Node.js, Express, & MongoDB - Quick - First 20 minutes

```
1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?

  - We need to pull our MongoDB database string out of our server and put it into our .env so that we can hide our database string from the public.

2. What is middleware?

  - Middleware is software that provides common services and capabilities to applications outside of what's offered by the operating system.

3. What does app.use(express.json()) do?

  - app.use(express.json()) parses incoming requests with JSON payloads and is based on body-parser.

4. What does the /:id mean in a route?

  - The /:id means that the route is expecting an id to be passed in the URL.

5. What is the difference between PUT and PATCH?

  - The difference between PUT and PATCH is that PUT is used to update a resource and PATCH is used to partially update a resource.

6. How do you make a default value in a schema?

  - You make a default value in a schema by using the default property.

7. What does a 500 error status code mean?

  - A 500 error status code means that the server has encountered a situation it doesn't know how to handle.

8. What is the difference between a status 200 and a status 201?

  - The difference between a status 200 and a status 201 is that a status 200 means that the request has succeeded and a status 201 means that a request has succeeded and has led to the creation of a resource.

```