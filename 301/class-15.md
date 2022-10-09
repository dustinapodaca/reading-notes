<img src="https://members-csforall.imgix.net/members/logos/code-fellows-logo-horizontal-2-color-black.png" width="340" height="66">  

# Code 301 Reading Notes

## Class 15 Reading Notes

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

## What is OAuth

```
1. What is OAuth?

  - OAuth is an open standard for access delegation, commonly used as a way for Internet users to grant websites or applications access to their information on other websites but without giving them the passwords.

2. Give an example of what using OAuth would look like.

  - The "Sign in with Google" button.

3. How does OAuth work? What are the steps that it takes to authenticate the user?

  - The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity.
  - The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.
  - The first site gives this token and secret to the initiating user’s client software.
  - The client’s software presents the request token and secret to their authorization provider (which may or may not be the second site).
  - If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the transaction to the second site.
  - The user approves (or their software silently approves) a particular transaction type at the first website.
  - The user is given an approved access token (notice it’s no longer a request token).
  - The user gives the approved access token to the first website.
  - The first website gives the access token to the second website as proof of authentication on behalf of the user.
  - The second website lets the first website access their site on behalf of the user.
  - The user sees a successfully completed transaction occurring

4. What is OpenID?

  - OpenID is about authentication: as a commenter on StackOverflow pithily put it, "OpenID is for humans logging into machines, OAuth is for machines logging into machines on behalf of humans."

```

## Authorization and Authentication Flows

```
1. What is the difference between authorization and authentication?

  - Authentication confirms that users are who they say they are. Authorization gives those users permission to access a resource.

2. What is Authorization Code Flow?

  - The authorization code flow is used to obtain both access tokens and refresh tokens and is optimized for confidential clients. The web application exchanges an Authorization Code for a token.

3. What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

  - The PKCE-enhanced Authorization Code Flow introduces a secret created by the calling application that can be verified by the authorization server; this secret is called the Code Verifier. The authorization server creates a transformed value of this secret called the Code Challenge and sends this value over HTTPS to the application. When the application makes a request to the token endpoint, it must pass the Code Verifier. The authorization server will re-create the Code Challenge and ensure that it matches the value it created originally.

4. What is Implicit Flow with Form Post?

  - The implicit flow with form post is used to obtain access tokens (it does not support the issuance of refresh tokens) and is optimized for public clients known to operate a particular redirection URI. This flow is defined in OpenID Connect.

5. What is Client Credentials Flow?

  - The client credentials flow is used for machine-to-machine applications where the client is requesting access to the protected resources under its control, or those of another resource owner that have been previously arranged with the authorization server (the method of which is beyond the scope of this specification).

6. What is Device Authorization Flow?

  - The device authorization flow is used to obtain an access token by presenting device code and user code to the resource owner. The device code is short-lived and is used to identify this authentication attempt. The user code is intended for display on the device so that the user can easily identify the device. The end-user then interacts with the authorization server to approve the device code.

7. What is Resource Owner Password Flow?

  - The resource owner password credentials flow is suitable in cases where the resource owner has a trust relationship with the client, such as the device operating system or a highly privileged application. The authorization server should take special care when enabling this grant type and only allow it when other flows are not viable.

```

## Things I Want to Know More About

- OAuth for SPA's
- CRUD
- NoSQL & SQL Databases
- Node JS
- REST APIs
- Higher Order Functions
- Ternary Operators
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
