<img src="https://members-csforall.imgix.net/members/logos/code-fellows-logo-horizontal-2-color-black.png" width="340" height="66">  

# Code 401 Reading Notes

## Class 07 Reading Notes

### Intro to JWT

```
1. What is a JSON Web Token (JWT)?
   - A JSON Web Token (JWT) is a JSON object that is used to securely transmit information between parties. It can be signed using a secret or public/private key pair, and can be verified using the corresponding secret or key.
2. When should we use JSON Web Tokens?
   - JSON Web Tokens should be used when there is a need to transmit information securely between two parties, and the information being transmitted is not sensitive enough to warrant the use of a more secure protocol.
3. Claims are expected in which structural component of a JWT?
   - Claims are expected in the second structural component of a JWT, which is the payload.

```

### Are JWTs Secure?

```
1. If I get a JWT and I can decode the payload, how can we call that secure?
   - A JWT can still be considered secure even if the payload can be decoded, as long as the signature of the JWT has not been tampered with. The signature is created using a secret known only to the issuer of the JWT and the recipient, and is used to verify the authenticity of the JWT.
2. If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.
   - If sending a JWT, both the sender and the receiver must know the secret used to create the signature. The secret is appended to the signature in order to verify the authenticity of the JWT.
3. Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.
   - To send and receive concatenated content and secret securely, the sender would create a signature using a secret known only to the sender and the recipient. The signature would be created by concatenating the content and the secret, and applying a one-way hashing function to the result. The sender would then transmit the concatenated content and the signature to the recipient, who would use the same secret to verify the authenticity of the transmitted data. If the recipient is able to successfully verify the signature, they can be confident that the transmitted data has not been tampered with and is authentic.

```

### JWTs Explained

```
1. Why use JWT?
   - JWTs are used to securely transmit information between parties. They can be signed using a secret or public/private key pair, and can be verified using the corresponding secret or key.
2. JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.
   - JWTs are compact and self-contained because they contain all the information needed to transmit data securely in a single, small string. This makes them easy to transmit and useful for storing data on the client side, such as in a cookie or local storage.
3. What are the three components (the structure) of a JWT signature?
   - The three components of a JWT signature are the header, the payload, and the signature. The header typically consists of information about how the JWT is encoded. The payload contains the claims, or statements about an entity (typically, the user) and additional data. The signature is used to verify that the sender of the JWT is who it claims to be and to ensure that the message wasn't changed along the way.

```
