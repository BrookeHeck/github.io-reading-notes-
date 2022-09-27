# Bearer Authorization

## Intro to JWT
1. What is a JSON Web Token (JWT)?
- JSON web tokens are a compact way of securely sending information between parties as a JSON object. The information is digitally signed using a secret or key depending on the encryption algorithm.

2. When should we use JSON Web Tokens?
- Authorization - instead of logging with every request, a client can provide a JWT instead
- Information exchange - digital signatures help insure that the content is from who the person claims to be and make sure that the content hasn't been tampered with.

3. Claims are expected in which structural component of a JWT?
- The payload

## Are JWTs secure
1. If I get a JWT and I can decode the payload, how can we call that secure?
- If I get a JWT I can't decode it, but If I know the secret that that was used to create the JWT hash, then I can recreate that hash and check to see if the message is legit.

2. If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.
- Both the sender and the receiver must know the secret that it used to encrypt the message.

3. Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.
- I don't completely understand hashing math and algorithms, but the way it was explained to me is like a simple math equation. If you have x + y = 36, and we say that x is the content, y is the secret, and the JWT is the encrypted hash, you can't get 36 without knowing what x and y are. If I know the secret and the payload, then I can get the answer.

## JWTs Explained
1. Why use JWT?
- Open standard for securely transfer information between parties. It is digitally signed with a secret or key so it can be trusted.

2. JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.
- It is easy and fast to send via URL, POST request, and HTTP header.
- It contains the information and avoids querying the database more than once

3. What are the three components (the structure) of a JWT signature?
- Header, Payload, Signature

## Things I want to learn more about

### Links
[Intro to JWT](https://jwt.io/introduction/)

[Are JWTs Secure?](https://stackoverflow.com/questions/27301557/if-you-can-decode-jwt-how-are-they-secure)

[JWTs Explained](https://www.youtube.com/watch?v=926mknSW9Lo)

[npm jsonwebtoken docs](https://www.npmjs.com/package/jsonwebtoken)
