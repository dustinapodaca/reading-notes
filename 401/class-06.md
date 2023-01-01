<img src="https://members-csforall.imgix.net/members/logos/code-fellows-logo-horizontal-2-color-black.png" width="340" height="66">  

# Code 401 Reading Notes

## Class 06 Reading Notes

### Securing Passwords

```
1. Explain to a non-technical friend how you would safely hash and store a password.
   - To safely hash and store a password, you would first apply a one-way hashing function to the password. This creates a hash value that is a fixed-size, encrypted representation of the password, which cannot be easily reversed to obtain the original password. You would then store the hash value in a secure database, rather than the actual password. When a user tries to log in, you would re-apply the same hashing function to the password they enter, and compare the resulting hash value to the one stored in the database. If they match, the user is authenticated.
2. What is Bcrypt?
   - Bcrypt is a password hashing function designed to be computationally expensive to execute, in order to make it more difficult for attackers to crack hashed passwords.
3. Why might you use something like Bcrypt?
   - You might use something like Bcrypt to protect the security of user passwords by making it more difficult for attackers to crack them.

```

### Basic Authentication

```
1. What is Basic Authentication?
   - Basic Authentication is a simple HTTP authentication scheme that involves sending a user's credentials (e.g. username and password) in an HTTP header with each request to a server.
2. What properties are necessary in the header of a Basic Auth request?
   - The properties necessary in the header of a Basic Auth request are: `Authorization`, `username`, and `password`.
3. How are username:password in Basic Auth encoded?
   - In Basic Auth, the `username:password` combination is encoded in base64.

```

### OWASP Auth Cheat Sheet

```
1. Define the authentication process to a non-technical recruiter.
   - The authentication process is the process of verifying the identity of a user or device, typically by requiring them to provide some form of credentials (e.g. a username and password).
2. How should your error messaging respond (both HTTP and HTML)? Why?
   - Your error messaging should be clear and concise, and should not reveal any sensitive information (e.g. the actual reason for the error). In HTML, you should use appropriate status codes (e.g. 401 for authentication failures) and include any necessary error messages in the response body. This helps to prevent attackers from gaining unauthorized access or information, and helps to maintain the security of the system.
3. Bookmark this link also and consider OWASP fundamentals any time you interact with authentication. Applications developed with security in mind from inception have fewer vulnerabilities throughout their lifecycle.

```
